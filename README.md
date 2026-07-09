# synaps-community

Synaps — community WASM vulnerability-detection modules for the [Hugin](https://hugin.nu) scanner.

Modules are fetched and installed with `hugin scanner install <name>` / `hugin scanner update`.
Each module runs sandboxed via Wasmtime with fuel limits and memory caps.

## Writing a module

Use the `hugin-scanner-guest` SDK. A module implements the `Context` trait and compiles to
`wasm32-unknown-unknown`. See the guest SDK docs at [hugin.nu/docs](https://hugin.nu/docs).

## Links

- [hugin.nu](https://hugin.nu) — Hugin website
- [HuginCyber/Hugin](https://github.com/HuginCyber/Hugin) — main community hub (issues, discussions, releases)
- [X / Twitter](https://x.com/HuginCyber) — @HuginCyber
- [LinkedIn](https://www.linkedin.com/company/hugin-cyber) — Hugin Cyber

## License

MIT. Modules remain the property of their authors.
