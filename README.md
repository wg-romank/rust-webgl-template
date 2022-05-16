# Rust WebGL Template

A template for `cargo-generate` utility (see https://github.com/cargo-generate/cargo-generate for more info)

To use this template run following command

```bash
 cargo generate --git https://github.com/wg-romank/rust-webgl-template
 ```

 Currently it only has one parameter, which is `project-name`. Specified project name will be used both for the crate name as well as for generated `.js` package to be bundled with `wasm-pack`.

 The template assumes you went through installation guide from Rust WebAssembly book (https://rustwasm.github.io/book/), installation of `wasm-pack`, `webpack` and other auxillary tools is not covered here.

 This template will setup a `cdlyb` crate as well as some bootstraping html/js code to quickly get started developing WebGL applications. It will use a minimal set of dependencies such as `web-sys`, `js-sys` and `wasm-bindgen`.