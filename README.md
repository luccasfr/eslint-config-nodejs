# @luccasfr/eslint-config-nodejs

This package provides an ESLint configuration for NodeJS projects using TypeScript and Prettier. It includes a set of rules and plugins to ensure code quality and consistency.

## Installation

To install the package, run the following command:

```sh
npm install --save-dev @luccasfr/eslint-config-nodejs
```

Install all peer-dependencies:

```sh
npm install --save-dev @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint-config-prettier eslint-plugin-prettier eslint-plugin-unicorn
```

ESLint are not included in the install script, as it is assumed you are already using NodeJS with Typescript, ESLint and Prettier.

# Usage

To use this ESLint configuration in your project, extend it in your .eslintrc file:

```json
{
  "extends": ["@luccasfr/eslint-config-nodejs"],
  "rules": {
    // ...
  }
}
```

# Plugins

- @typescript-eslint

# Extends

- prettier/recommended
- prettier
- eslint:recommended
- plugin:unicorn/recommended

# Peer Dependencies

Make sure to install the following peer dependencies:

- @typescript-eslint/eslint-plugin: >=7.9.0
- @typescript-eslint/parser: >=7.9.0
- eslint: >=8.57.0
- eslint-config-prettier: >=9.1.0
- eslint-plugin-prettier: >=5.1.3
- eslint-plugin-unicorn: >=55.0.0
- prettier: >=3.2.5

# Author

Lucas Ferreira - lucas.ferreira@jerasoft.inf.br

# License

This project is licensed under the ISC License.
