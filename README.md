# WebAssembly + Rust 初體驗

> 本篇教學參考自 [Rust and WebAssembly](https://rustwasm.github.io/docs/book/introduction.html)

## 環境設定

1. 先確認有Rust toolchain三大工具: `rustup`、`rustc`、`cargo`
2. 安裝`wasm-pack`: [Get here](https://rustwasm.github.io/wasm-pack/installer/)
3. 安裝`cargo-generate`: 方便直接從git repository抓版模<br>指令: 
```
cargo install cargo-generate
```
4. npm: 從[這裡](https://www.npmjs.com/get-npm)下載安裝，完成後執行
```
npm install npm@latest -g
```