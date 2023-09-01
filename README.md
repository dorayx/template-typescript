# _opinionated_ TypeScript Template

Since I like to create minimal viable products from time to time, having a personal boilerplate for TypeScript projects can boost efficiency,
and so I've created this repo as a starting point for my future projects.

## Tooling

**Package Manager**

- [Yarn](https://yarnpkg.com/) _(v3)_
  - Doc: [Zero-installs](https://www.npmjs.com/package/vite-tsconfig-paths)

**Compiler & Bundler**

- [TypeScript](https://www.typescriptlang.org/) _(v5)_
- [Vite](https://vitejs.dev/) _(v4)_
  - Plugin: [vite-tsconfig-paths](https://www.npmjs.com/package/vite-tsconfig-paths)
  - Plugin: [vite-plugin-dts](https://www.npmjs.com/package/vite-plugin-dts)

**Testing**

- [Vitest](https://vitest.dev/)
  - Convention: Unit tests for user cases are stored in the `tests/units` directory.
  - Convention: Unit tests for individual functions are placed alongside their respective implementations ([In-source testing](https://vitest.dev/guide/in-source.html))
  - Convention: The file `tests/setup.ts` is executed before each test file
  - Convention: The `tests/tsconfig.json` file configures TypeScript for testing

**Linters**

- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [Commitlint](https://commitlint.js.org/#/)
- [Husky](https://typicode.github.io/husky/#/)
- [LintStaged](https://github.com/okonet/lint-staged)

**Code Generator**

- [Plop](https://plopjs.com/)
