<div align="center">

# 🪄 Open SASS Kit

[![Crates.io](https://img.shields.io/crates/v/opensass)](https://crates.io/crates/opensass)
[![Downloads](https://img.shields.io/crates/d/opensass)](https://crates.io/crates/opensass)
![License](https://img.shields.io/crates/l/opensass)
[![Made with Rust](https://img.shields.io/badge/Made%20with-Rust-1f425f.svg?logo=rust)](https://www.rust-lang.org/)
[![Rust Version](https://img.shields.io/badge/Rust-1.86%2B-blue.svg)](https://www.rust-lang.org)
[![Maintained](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/wiseaidev)

[![Join the Open SASS Discord](https://dcbadge.limes.pink/api/server/b5JbvHW5nv)](https://discord.gg/b5JbvHW5nv)

![logo](https://raw.githubusercontent.com/wiseaidev/wiseaidev/refs/heads/main/assets/crabby-banner.png)

</div>

## 📜 Introduction

**Open SASS Kit** is a modular toolkit for building fast, modern, and framework-agnostic web applications. Launching a new project or improving an existing one? Open SASS gives you the tools to scale with composable components, powerful CLI tooling, and full freedom from CSS framework lock-in.

## 🎯 Why Use Open SASS?

1. **🎨 CSS-Framework Agnostic**: Works seamlessly with Tailwind, Bootstrap, Bulma, etc, or just plain CSS.
1. **🧩 Modular Components**: Import only what you need. No bloat, just the essentials.
1. **🔁 Reusable & Composable**: Write once, use everywhere across projects.
1. **⚙️ CLI Tooling**: Scaffold projects in seconds with our [Open SASS CLI](https://github.com/opensass/cli).
1. **🌐 WASM-Ready**: Built for modern Rust + WebAssembly stacks like Yew, Dioxus, and Leptos.

## 📦 Installation

Install the CLI globally using Cargo:

```sh
cargo install opensass
```

Then import a new component:

```sh
os add accordion-rs yew
```

> 💡 The CLI will automatically generate file structures and integrate styles where needed.

## 🔌 Use with Any Stack

Open SASS components are fully decoupled from specific CSS frameworks. Compatible with:

- [TailwindCSS](https://v3.tailwindcss.com/)
- [Bootstrap](https://getbootstrap.com/docs/5.3/)
- [Bulma](https://bulma.io/)
- [Foundation](https://get.foundation/)
- Plain CSS
- etc

Your stack. Your rules. No dependencies or vendor lock-in.

## 🧪 WASM Framework Compatibility

All components are designed to work with popular WebAssembly-based frontend frameworks:

- [Yew](https://yew.rs)
- [Dioxus](https://dioxuslabs.com)
- [Leptos](https://leptos.dev)

Integration guides available in the [`components`](./components.md) page.

## 🤝 Contributing

We welcome all contributions! Help us improve Open SASS by submitting:

1. Bug reports.
1. Feature suggestions.
1. Code contributions.

To contribute:

1. Fork the repo.
1. Create a new branch (`feature/my-awesome-feature`).
1. Submit a pull request.

## 📜 License

Open SASS is released under the [MIT License](LICENSE). Free for personal and commercial use.

## 🙌 Final Thoughts

Open SASS is crafted by developers, for developers, built to be the **universal, unopinionated toolkit** for modern web projects. From vanilla CSS to the latest WASM frameworks, Open SASS lets you move fast and build confidently.

> Stop re-inventing the wheel. Start shipping faster ⚡
