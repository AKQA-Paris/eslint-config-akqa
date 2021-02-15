# Basic installation

## Install npm dependencies

```bash
npm i --save-dev eslint @akqa/eslint-config-akqa eslint-config-prettier eslint-plugin-import eslint-plugin-prettier eslint-plugin-react prettier
```

## Add to your eslint config

Create .eslintrc to the root folder

```json
{
  "extends": ["config-akqa"]
}
```

# React installation

## Install npm dependencies

```bash
npm i --save-dev eslint @akqa/eslint-config-akqa eslint-config-prettier eslint-config-react-app eslint-plugin-import eslint-plugin-prettier eslint-plugin-react prettier
```

## Add to your eslint config

Create .eslintrc to the root folder

```json
{
  "extends": ["config-akqa", "config-akqa/react"]
}
```
