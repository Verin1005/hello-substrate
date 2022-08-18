# 单位换算

## weight

- 10^12 weight = 1 秒
- 1_000 weight = 1 纳秒

## Balance -> u64

`let value :Option = TryInto::::try_into(balance).ok();`

## u64-> Balance

`let balance :Option<T::Balance> = value.try_into().ok();`

## BlockNumber -> u32

`let number : Option = TryInto::::try_into(block_number);`

## u32 -> BlockNumber

- `let block_number :T::BlockNumber = value.into();`
- 或者用 saturated_into() 转换

```
let number: u128 = block_number.saturated_into();
let value :u64 = balance.saturated_into();
```
