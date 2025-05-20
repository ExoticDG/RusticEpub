# Tauri + Yew

This template should help get you started developing with Tauri and Yew.

## Recommended IDE Setup

[VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer).


## Dev Setup

* Setup WASM target

  ```bash
  rustup target add wasm32-unknown-unknown
  ```

* Install trunk

  ```bash
  cargo install --locked trunk
  ```

* Install nodejs (for tailwind support)

In order to run, this example requires a working [nodejs](https://nodejs.org/en/download) installation that includes npx.


* Run

  ```bash
  trunk serve
  ```

## Deploy

Use a web server to serve the files from trunk release.

```bash
trunk build --release
```
