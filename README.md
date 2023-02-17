# @trouni/eslint-config

Project forked from (@antfu/eslint-config)[https://github.com/antfu/eslint-config]

[![npm](https://img.shields.io/npm/v/@trouni/eslint-config)](https://npmjs.com/package/@trouni/eslint-config)

## Usage

### Install

```bash
pnpm add -D eslint @trouni/eslint-config
```

### Config `.eslintrc`

```json
{
  "extends": [
    "@trouni"
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
