# bevy-game

bevy game

## 使用 bevy 游戏引擎写游戏

环境搭建

1. 在 `cargo.toml` 中加上

```toml
[dependencies]
bevy = { version = "0.5.0", features = ["dynamic"] }
```

2. LLD linker
   mac 需要安装 xcode
   `brew install michaeleisel/zld/zld`

3. 使用 rust nightly
   `rustup toolchain install nightly`
   `rustup override set nightly`
