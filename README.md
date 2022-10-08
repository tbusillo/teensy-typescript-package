# WIP - teensy typescript package

[![.github/workflows/test.yml](https://github.com/tbusillo/teensy-typescript-package/actions/workflows/test.yml/badge.svg)](https://github.com/tbusillo/teensy-typescript-package/actions/workflows/test.yml)

A teensy tiny TypeScript package template, built to make getting started with TypeScript projects a little less painful. 

## Features

- [TypeScript](https://www.typescriptlang.org/) right from the start
- Bundling using [Rollup](https://github.com/rollup/rollup) and [unbuild](https://github.com/unjs/unbuild) with native supports for `ESM/CJS` packages
- Unit testing using `jest` / `ts-jest`
- [ESLint](https://github.com/eslint/eslint), [prettier](https://github.com/prettier/prettier), and git hooks with [Husky](https://github.com/typicode/husky)
- CI/CD workflows using [Github Actions](https://docs.github.com/en/actions) 
- Extendable configurations (e.g., tsconfig) perfect for use in monorepos
-

## Installation

```bash
git clone git@github.com:tbusillo/teensy-typescript-package.git

```

```diff-bash
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```

## Getting Started

```bash

# clone the template via Github.com or...
git clone git@github.com:tbusillo/teensy-typescript-package.git

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

# Clean /dist cache
pnpm clean

```

## Contributing / Issues

## License

MIT License

Copyright (c) 2022 Tom
