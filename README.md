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
5. 接上網頁: 在根目錄下指令:
```
npm init wasm-app www
```
取得`create-wasm-app`作為版模

## 編譯&執行

在根目錄下指令:
```
wasm-pack build
```
以生成`.wasm`、`.ts`、`.js`三檔案
