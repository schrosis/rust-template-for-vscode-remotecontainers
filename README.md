# rust-template-for-vscode-remotecontainers

[![CI](https://github.com/schrosis/rust-template-for-vscode-remotecontainers/actions/workflows/ci.yml/badge.svg)](https://github.com/schrosis/rust-template-for-vscode-remotecontainers/actions/workflows/ci.yml)

Rust template development environment using VSCode's RemoteContainers

## Requirements

- [Docker](https://www.docker.com/)
- [Visual Studio Code](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)
- [Remote - Containers(VSCode extension)](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

## Usage

Run `Remote-containers: Reopen in Container` from the command palette ( `⌘` + `⇧` + `P` ).
And if you see "Dev Container: Rust Template" in the bottom left corner, you're good to go!

## The following are installed.

- Docker image
    - rust:1.66-buster
- CLI tools
    - git
    - cargo-edit
    - cargo-watch
- VSCode extensions
    - [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=matklad.rust-analyzer)
    - [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb)
    - [Better TOML](https://marketplace.visualstudio.com/items?itemName=bungcip.better-toml)
    - [crates](https://marketplace.visualstudio.com/items?itemName=serayuzgur.crates)
    - [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

