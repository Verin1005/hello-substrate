## cargo install 安装指定版本

### --version 指定

```
cargo install cargo-contract --version 2.0.0-alpha.1
```

### --branch 指定

```
cargo install cargo-contract --git https://github.com/paritytech/cargo-contract.git --branch=master --force --locked
```

### --tag 指定

```
cargo install cargo-contract --git https://github.com/paritytech/cargo-contract.git --tag v2.0.0-alpha.3 --force --locked
```

### --path 指定

```
cargo install --path .
```
