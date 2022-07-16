# TerraLab ESLint config

## What's included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- Import Helper plugin;
- Prettier;

## Setup

1. Install the dependencies
```
npm i -D eslint terralab-eslint-config
```
or
```
yarn add -D eslint terralab-eslint-config
```


2. Create a `.eslintrc.json` file extending the config:
```
{
  "extends": "terralab-eslint-config/react"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.