# @x12i/ebooks-core usage example

**Deprecated npm package:** Renamed: use @x12i/docify-* (platform) and @x12i/memorix-docs instead. See https://github.com/x12i/memorix-mono-repo

This example documents the pinned historical release. Follow the replacement guidance above for new integrations.

Schemas and helpers for x12i ebook libraries (catalog, use-cases, manifests).

This consuming application demonstrates **validate incoming json and report contract errors** using the published npm package, pinned to `1.0.0`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

## When to use the package

- Validate a product ebook catalog and manifest.
- Share book and use-case schemas between the exporter and reader.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/ebooks-core)

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.
