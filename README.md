# vite-jest

First-class Vite integration for Jest.

Still work-in-progress, here are some working examples:

- [Vue 3 + `type: "module"` in `package.json`](./examples/vue-app-type-module/)
- [Vue 3 + `type: "commonjs"` or no `type` field in `package.json`](./examples/vue-app-type-commonjs/)
  - Beware that all source and unit test JavaScript files should be named with the `.mjs` extension in this case.
- [Vue 3 + TypeScript](./examples/vue-app-ts/)
- [React](./examples/react-app-type-module/)

Usage:

1. Add `preset: 'vite-jest'` to your Jest config.
2. Replace the `jest` CLI with `vite-jest`.

See [./packages/vite-jest/README.md](./packages/vite-jest/README.md) for more implementation details.
