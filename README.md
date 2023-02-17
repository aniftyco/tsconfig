# @aniftyco/tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for NiftyCo projects.

## Install

```sh
npm install --save-dev @aniftyco/tsconfig
```

_This config requires TypeScript 4.7 or later._

## Usage

`tsconfig.json`

```json
{
  "extends": "@aniftyco/tsconfig",
  "compilerOptions": {
    "outDir": "dist"
  }
}
```

When you are targeting a higher version of Node.js, check the relevant ECMAScript version and add it as `target`:

```json
{
  "extends": "@aniftyco/tsconfig",
  "compilerOptions": {
    "outDir": "dist",
    "target": "ES2021"
  }
}
```
