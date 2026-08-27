<div align="center">

# PostCSS-Go

**High-performance PostCSS-compatible CSS processor in Go**


[Website](https://postcss-go.github.io/) · [Documentation](https://postcss-go.github.io/) · [Main Repository](https://github.com/postcss-go/postcss-go)

</div>

---

## About

[PostCSS-Go](https://github.com/postcss-go/postcss-go) is a Go port of the core [PostCSS](https://github.com/postcss/postcss) architecture. It provides CSS parsing, AST transformation, processing, stringifying, and source map support — with Node.js packages for seamless integration into existing toolchains.

> **Experimental:** `postcss-go` is not production-ready. APIs and behavior may change.

## Goals

- **Performance** — Be faster than PostCSS for common parse, transform, and stringify workloads.
- **Compatibility** — Stay compatible with the existing PostCSS ecosystem, including plugins and surrounding tooling.
- **Portability** — Ship as a native Go library and as browser WASM via `@postcss-go/core/wasm`.

## Packages

| Package | Role | Link |
| --- | --- | --- |
| [`@postcss-go/core`](https://www.npmjs.com/package/@postcss-go/core) | Node.js / TypeScript API and browser WASM | [![npm weekly downloads](https://img.shields.io/npm/dw/@postcss-go/core.svg)](https://www.npmjs.com/package/@postcss-go/core) |
| [`@postcss-go/webpack-loader`](https://www.npmjs.com/package/@postcss-go/webpack-loader) | Webpack 5 adapter without a `postcss-loader` dependency | [![npm weekly downloads](https://img.shields.io/npm/dw/@postcss-go/webpack-loader.svg)](https://www.npmjs.com/package/@postcss-go/webpack-loader) |
| [`@postcss-go/vite-loader`](https://www.npmjs.com/package/@postcss-go/vite-loader) | Vite plugin without a PostCSS dependency | [![npm weekly downloads](https://img.shields.io/npm/dw/@postcss-go/vite-loader.svg)](https://www.npmjs.com/package/@postcss-go/vite-loader) |

## Acknowledgements

PostCSS-Go is an independent Go port of [PostCSS](https://github.com/postcss/postcss) by [Andrey Sitnik](https://github.com/ai), and is **not affiliated with or endorsed by** the PostCSS project.

## Contact

Questions, feedback, or collaboration ideas? Open an [issue](https://github.com/postcss-go/postcss-go/issues) or reach out at [eryue0220@gmail.com](mailto:eryue0220@gmail.com).
