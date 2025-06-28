# lazycargo

> A fast, minimal TUI for exploring and managing Rust projects using Cargo — inspired by lazygit.


---

## ✨ Features

- 📦 View crate metadata, targets, dependencies, and features
- 🧪 Run and monitor `cargo build`, `test`, and `check` from the UI
- 🔍 Explore your project's structure in a keyboard-driven interface
- ⚡ Lightning-fast and powered entirely by Rust
- 🧰 Designed to feel like `lazygit`, but made for Rust devs

---

## 🧱 Installation

```bash
cargo install lazycargo
````

> Requires Rust 1.70+ (stable)

---

## 🚀 Usage

```bash
lazycargo
```

* Arrow keys / `h`, `j`, `k`, `l` — navigate panels
* `b` — run `cargo build`
* `t` — run `cargo test`
* `c` — run `cargo check`
* `q` — quit

---

## 🛠️ Roadmap

* [ ] Feature flag toggling
* [ ] Workspace/project navigation
* [ ] Dependency version check (`cargo outdated`)
* [ ] Inline error view / diagnostics
* [ ] Git integration (optional)


## 🤝 Credits

* Inspired by [lazygit](https://github.com/jesseduffield/lazygit) by Jesse Duffield
* Built with [ratatui](https://github.com/tui-rs-revival/ratatui), and [cargo\_metadata](https://crates.io/crates/cargo_metadata)

---

## 📄 License

MIT License © 2025 YourName

