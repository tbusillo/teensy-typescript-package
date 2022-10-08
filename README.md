# WIP - teensy typescript package
[![.github/workflows/test.yml](https://github.com/tbusillo/teensy-typescript-package/actions/workflows/test.yml/badge.svg)](https://github.com/tbusillo/teensy-typescript-package/actions/workflows/test.yml)

A teensy tiny TypeScript package template, built to make developing with TypeScript within the JS ecosystem a little less painful. 
## Features
- `TypeScript` right from the start
- Bundling using `Rollup` and `unbuild` with native supports for `ESM/CJS` packages
- Unit testing using `jest` / `ts-jest`
- `ESLint`, `prettier`, and customer `pre-commit` hooks pre-configured
- `GH Actions` - Simple CI/CD workflow example 
- Perfect start for use within monorepos
- Prebuild commands with support for building/caching dependencies on Netlify
## Getting Started

```bash

# clone the template via Github.com or...
git clone <repository url>

# install dependencies
pnpm install

# stub /dist - great for use with playgrounds/monorepos
pnpm dev

# Run tests
pnpm test

# Lint / format
pnpm lint

# Run with nodemon (reload on file change) and transpile with TSC
pnpm start

# Build package
pnpm build

```


## License
MIT License

Copyright (c) 2022 Tom