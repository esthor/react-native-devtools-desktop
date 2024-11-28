# React Native DevTools Desktop

This is a PoC for getting a native desktop debugger experience for the new React Native DevTools utilizing Tauri (Rust-lang).

On a personal note, I prefer a standalone app vs. a full web browser for debugging mobile apps. 🤷

## Dev setup

- [Rust](https://www.rust-lang.org/learn/get-started) - `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`
- [Tauri cli](https://crates.io/crates/tauri-cli) - `cargo install tauri-cli`
- [Node](https://nodejs.org/en/download/package-manager) - pick your prefered install scripts
- [pnpm](https://pnpm.io/installation) - Yell at me if you don't like this and we can change to npm or yarn.

Run the dev build: `pnpm tauri dev`

## Build

Run `pnpm tauri build`

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
