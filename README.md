# @sinchang/eslint-config

[![npm](https://img.shields.io/npm/v/@sinchang/eslint-config)](https://npmjs.com/package/@sinchang/eslint-config)

## Usage

### Install

```bash
pnpm add -D eslint @sinchang/eslint-config
```

### Config `.eslintrc`

```json
{
  "extends": [
    "@sinchang"
  ]
}
```

### Config `.eslintignore`

```txt
dist
public
```

### Add script for package.json

For example:

```json
{
  "scripts": {
    "lint": "eslint \"**/*.{vue,ts,js}\""
  }
}
```

### Config VSCode auto fix

Create `.vscode/settings.json`

```json
{
  "prettier.enable": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  }
}
```
