# @CatsMiaow/tsconfig

Shared TypeScript configurations for projects

## Configuration

`Installing a package` on [Configuring npm for use with GitHub Packages](https://docs.github.com/en/packages/using-github-packages-with-your-projects-ecosystem/configuring-npm-for-use-with-github-packages#installing-a-package)

## Installation

```sh
npm i -D @catsmiaow/tsconfig
```

## Usage

`tsconfig.json`

```json
{
  "extends": "@catsmiaow/tsconfig",
  "compilerOptions": {
    "outDir": "dist",
    "noUnusedParameters": false
  },
  "include": ["src/**/*"],
  "exclude": ["node_modules"]
}
```
