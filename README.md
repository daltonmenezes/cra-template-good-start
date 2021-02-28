
<p align="center"><a hrf="#"><img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg" alt="react logo" width="40%" /></a></p>

<h1 align="center">cra-template-good-start</h1>
<p align="center">A <strong>Create React App</strong> good starting point template to init a configured app with typescript, sass, eslint, prettier and more 💅</p>

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
- [Sneak-peek](#sneak-peek)
  - [Files and folders](#files-and-folders)
  - [Tsx code style](#tsx-code-style)
  - [Sass style](#sass-style)
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

To use this template, add `--template good-start` when creating a new app with **create-react-app**.

> **Note:** if you are using **Windows** make sure to add the equality symbol between --template and good-start. example: **--template=good-start**

For example:
```bash
npx create-react-app my-app --template good-start

# OR

yarn create react-app my-app --template good-start
```
Then:
```bash
cd my-app
```

## Sneak-peek

### Files and folders
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
### Tsx code style
```tsx
import Hello from 'components/Hello'

function App() {
  return (
    <section className="containers">
      <Hello />
    </section>
  )
}

export default App
```

### Sass style
```sass
@import 'reset'
@import 'colors'

.containers
  display: flex
  flex-flow: column wrap
  align-items: center
  justify-content: center
  padding: 0 2rem
  background-color: $black
```

## License
[MIT © Dalton Menezes](https://github.com/daltonmenezes/cra-template-good-start/blob/main/LICENSE)
