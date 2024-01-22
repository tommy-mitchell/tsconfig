# @tommy-mitchell/tsconfig

Personal TypeScript config.

## Install

```sh
npm install --save-dev @tommy-mitchell/tsconfig
```

<details>
<summary>Other Package Managers</summary>

```sh
yarn add --dev @tommy-mitchell/tsconfig
```
</details>

## Usage

```json5
{
  "extends": "@tommy-mitchell/tsconfig",
  "compilerOptions": {
    "outDir": "dist",
  },
}
```

If using with a bundler, set the following options to prevent type resolution issues:

```json5
{
  "compilerOptions": {
    "declaration": false,
    "noEmit": false,
  },
}
```
