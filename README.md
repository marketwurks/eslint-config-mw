# ESLint Config

ESLint configuration used for TypeScript projects.

## Install

```
$ yarn add --dev eslint-config-mw
```

## Usage

Modify `eslintConfig` in `package.json` as follows.

### TypeScript

```json
{
  "name": "cool-node-server",
  "eslintConfig": {
    "extends": "mw"
  }
}
```

### TypeScript + React

```json
{
  "name": "awesome-react-website",
  "eslintConfig": {
    "extends": "mw/react"
  }
}
```

### TypeScript + React Native

```json
{
  "name": "amazing-native-app",
  "eslintConfig": {
    "extends": "mw/react-native"
  }
}
```
