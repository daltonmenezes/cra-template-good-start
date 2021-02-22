<p align="center"><a hrf="#"><img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg" alt="react logo" width="40%" /></a></p>

<h1 align="center">cra-template-good-start</h1>
<p align="center">A good starting point template to init a configured React app with typescript, eslint, prettier and more 💅</p>

<p align="center">
  <!-- Patreon -->
  <a href="https://www.patreon.com/daltonmenezes">
    <img alt="patreon url" src="https://img.shields.io/badge/support%20on-patreon-1C1E26?style=for-the-badge&labelColor=1C1E26&color=0084ff">
  </a>

  <!-- npm version -->
  <a href="https://www.npmjs.com/package/cra-template-good-start">
    <img alt="npm version" src="https://img.shields.io/npm/v/cra-template-good-start.svg?style=for-the-badge&labelColor=1C1E26&color=0084ff">
  </a>

  <!-- downloads -->
  <a href="https://www.npmjs.com/package/cra-template-good-start">
    <img alt="npm version" src="https://img.shields.io/npm/dm/cra-template-good-start.svg?style=for-the-badge&labelColor=1C1E26&color=0084ff">
  </a>
</p>

## Table of Contents
- [Features](#features)
- [Usage](#usage)
- [Structure](#structure)
- [License](#license)

## Features
- ⚡ typescript
- ⚡ eslint
- ⚡ prettier
- ⚡ editor config
- ⚡ sass
- ⚡ css reset
- ⚡ absolute imports

## Usage

To use this template, add `--template cra-template-good-start` when creating a new app with **create-react-app**.

For example:
```bash
npx create-react-app my-app --template cra-template-good-start

# OR

yarn create react-app my-app --template cra-template-good-start
```
Then:
```bash
cd my-app
```

## Structure
```bash
.
├── .editorconfig
├── .gitignore
├── .prettierrc
├── README.md
├── package.json
├── node_modules
├── public
│   └── index.html
├── src
│   ├── App.tsx
│   ├── components
│   │   └── Hello
│   │       ├── index.tsx
│   │       └── styles.module.sass
│   ├── index.tsx
│   ├── react-app-env.d.ts
│   └── styles
│       ├── colors.sass
│       ├── global.sass
│       └── reset.sass
├── tsconfig.json
└── yarn.lock
```

## License
[MIT © Dalton Menezes](https://github.com/daltonmenezes/cra-template-good-start/blob/main/LICENSE)
