<div align="center">
    <h1>
        <img src="./static/icon.png" width="18" height="18" alt="" />
        Snake
    </h1>
    <a href="https://git.exst.fun/snake">
        <img src="https://img.shields.io/github/stars/eexsty/snake?colorA=1e1e28&colorB=1187c9&style=for-the-badge&logo=github" alt="GitHub" />
    </a>
    <a href="https://git.exst.fun/snake/actions/workflows/rust.yml">
        <img src="https://img.shields.io/github/workflow/status/eexsty/snake/Rust%20CI%20with%20Cargo?colorA=1e1e28&colorB=1187c9&label=Rust&style=for-the-badge&logo=rust" alt="GitHub Actions" />
    </a>
    <br/>
    <strong>A reimplementation of the classic snake game written in Rust, with desktop and web support via WebAssembly.</strong>
</div>


## Table of contents

1. [🎨 Color Palette](#-color-palette)
2. [🚴 Prerequisites](#-prerequisites)
3. [🏠 Building](#-building)
4. [🔗 Attribution](#-attribution)


## 🎨 Color Palette

<table>
    <tr>
        <th>⚪</th>
        <th>Label</th>
        <th>Hex</th>
    </tr>
    <tr>
        <td><img src="https://readme-swatches.vercel.app/3ba481?style=circle" alt="" /></td>
        <td>Ocean Green</td>
        <td><code>#3ba481</code></td>
    </tr>
    <tr>
        <td><img src="https://readme-swatches.vercel.app/6ab798?style=circle" alt="" /></td>
        <td>Silver Tree</td>
        <td><code>#6ab798</code></td>
    </tr>
    <tr>
        <td><img src="https://readme-swatches.vercel.app/fbefa3?style=circle" alt="" /></td>
        <td>Texas</td>
        <td><code>#fbefa3</code></td>
    </tr>
    <tr>
        <td><img src="https://readme-swatches.vercel.app/cafe81?style=circle" alt="" /></td>
        <td>Mindaro</td>
        <td><code>#cafe81</code></td>
    </tr>
    <tr>
        <td><img src="https://readme-swatches.vercel.app/7ac88b?style=circle" alt="" /></td>
        <td>De York</td>
        <td><code>#7ac88b</code></td>
    </tr>
</table>


## 🚴 Prerequisites

* [Git][git]
* [Latest build of Rust Nightly][rustup]
* * `rustup target install wasm32-unknown-unknown`
* * `cargo install -f cargo-binutils` ![](./readme/windows-blue.svg)
* * `rustup component add llvm-tools-preview` ![](./readme/windows-blue.svg)
* [`rui314/mold`][mold] ![](./readme/ubuntu-blue.svg)
* [`michaeleisel/zld`][zld] ![](./readme/apple-blue.svg)
* [Trunk][trunk]


## 🏠 Building

* `cargo build --release` ![](./readme/desktop-blue.svg)
* `trunk build --release` ![](./readme/web-blue.svg)


## 🔗 Attribution

1. [`tabler-icons.io`](https://tabler-icons.io) for their icons used in this markdown file.


[git]: https://git-scm.com/
[rustup]: https://rustup.rs
[trunk]: https://trunkrs.dev
[mold]: https://github.com/rui314/mold
[zld]: https://github.com/michaeleisel/zld