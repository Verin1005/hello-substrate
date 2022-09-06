- 复制一个 pallet (pallets/template/ -> pallets/example/)
- 修改根目录 cargo.toml 新增 pallets/example

```
[workspace]
members = [
  "pallets/example",
]
```

- 修改 pallets/example/cargo.toml

```
[package]
name = "pallet-example"
```

- 替换 pallets/example/src/mock.rs
- 替换 pallets/example/src/tests.rs

```
pallet_template -> pallet_example
Template -> Example
```

- 修改 runtime/cargo.toml

```
[dependencies]
pallet-example = { version = "1.0.0", default-features = false, path = "../pallets/example" }

std = [
  "pallet-example/std",
]

runtime-benchmarks = [
  "pallet-example/runtime-benchmarks",
]

try-runtime = [
  "pallet-example/try-runtime",
]
```

- 修改 runtime/src/lib.rs

```
1. 导入 pallet
pub use pallet_kitties;

2. construct_runtime! 上方加入
impl pallet_example::Config for Runtime {
	type Event = Event;
}

3. construct_runtime 内配置 pallet
construct_runtime!({
  // local
  Example: pallet_example,
});

4. benchmarks
define_benchmarks!(
  [pallet_example, Example]
);
```
