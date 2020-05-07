# @CatsMiaow/tsconfig

## Install

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
  "include": [
    "src/**/*"
  ],
  "exclude": [
    "node_modules"
  ]
}
```
