# lib-config-ts

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Deployment](https://github.com/vbetsch/lib-config-ts/workflows/Deployment/badge.svg)](https://github.com/vbetsch/lib-config-ts/actions?query=workflow%3ADeployment+)

This repository is a monorepo powered by [NPM Workspaces](https://docs.npmjs.com/cli/using-npm/workspaces). It allows
you to install only the specific configuration blocks you need, eliminating unnecessary dependency overhead in your
projects.

## 🧩 Structure

### Packages

| Package                                                                              | Description               | Path                                                         | Details                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|--------------------------------------------------------------------------------------|---------------------------|--------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`@vbetsch/config-eslint`](https://www.npmjs.com/package/@vbetsch/config-eslint)     | Core ESLint configuration | [src/packages/config-eslint](src/packages/config-eslint)     | [![npm package version](https://img.shields.io/npm/v/@vbetsch/config-eslint)](https://www.npmjs.com/package/@vbetsch/config-eslint) [![npm downloads number per week](https://img.shields.io/npm/dw/@vbetsch/config-eslint)](https://www.npmjs.com/package/@vbetsch/config-eslint) [![npm package install size](https://packagephobia.com/badge?p=@vbetsch/config-eslint)](https://www.npmjs.com/package/@vbetsch/config-eslint)             |
| [`@vbetsch/config-jest`](https://www.npmjs.com/package/@vbetsch/config-jest)         | Testing configuration     | [src/packages/config-jest](src/packages/config-jest)         | [![npm package version](https://img.shields.io/npm/v/@vbetsch/config-jest)](https://www.npmjs.com/package/@vbetsch/config-jest) [![npm downloads number per week](https://img.shields.io/npm/dw/@vbetsch/config-jest)](https://www.npmjs.com/package/@vbetsch/config-jest) [![npm package install size](https://packagephobia.com/badge?p=@vbetsch/config-jest)](https://www.npmjs.com/package/@vbetsch/config-jest)                         |
| [`@vbetsch/config-prettier`](https://www.npmjs.com/package/@vbetsch/config-prettier) | Formatting standards      | [src/packages/config-prettier](src/packages/config-prettier) | [![npm package version](https://img.shields.io/npm/v/@vbetsch/config-prettier)](https://www.npmjs.com/package/@vbetsch/config-prettier) [![npm downloads number per week](https://img.shields.io/npm/dw/@vbetsch/config-prettier)](https://www.npmjs.com/package/@vbetsch/config-prettier) [![npm package install size](https://packagephobia.com/badge?p=@vbetsch/config-prettier)](https://www.npmjs.com/package/@vbetsch/config-prettier) |
| [`@vbetsch/config-tsconfig`](https://www.npmjs.com/package/@vbetsch/config-tsconfig) | Compiler settings         | [src/packages/config-tsconfig](src/packages/config-tsconfig) | [![npm package version](https://img.shields.io/npm/v/@vbetsch/config-tsconfig)](https://www.npmjs.com/package/@vbetsch/config-tsconfig) [![npm downloads number per week](https://img.shields.io/npm/dw/@vbetsch/config-tsconfig)](https://www.npmjs.com/package/@vbetsch/config-tsconfig) [![npm package install size](https://packagephobia.com/badge?p=@vbetsch/config-tsconfig)](https://www.npmjs.com/package/@vbetsch/config-tsconfig) |

### Templates

The [templates](src/templates) folder provides ready-to-use configuration boilerplates for a quick project setup.

## 🏗️ Installation

It is recommended that you use Node version [lts/krypton -> v24.14.1](https://nodejs.org/en/blog/release/v24.14.1) or later.

Refer to the individual module READMEs for specific installation instructions.

```bash
# Example
npm install -D @vbetsch/config-eslint @vbetsch/config-tsconfig
```

## 🚀 Using

Check out the [vbetsch/lib-config-ts-test](https://github.com/vbetsch/lib-config-ts-test) repository for an integration example.

## 🤝 Contributing

Contributions are welcome! To get started, please ensure you have an approved issue before submitting a PR.

[© 2026 vbetsch — MIT License](LICENSE)
