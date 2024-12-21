# vue-select-user-ui

Originally from [This Challenge Is Great Practice For Any Web Developer
Interview (Using Vue)](https://www.youtube.com/watch?v=bGtDimebyoA).

Key takeaways:

- importing an image as `import WebDevImg from './assets/web-developer.png'` and
  then using it in `<script>` as `img: WebDevImg` and in `<template>` as `<img
:src="img"`.
- passing `disabled` directly in the component `<BaseButton
:disabled="!isRoleSelected" />` (which gets automatically added to the root
  element of the template) without the need for a prop.

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) to make the TypeScript language service aware of `.vue` types.

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
yarn
```

### Compile and Hot-Reload for Development

```sh
yarn dev
```

### Type-Check, Compile and Minify for Production

```sh
yarn build
```

### Lint with [ESLint](https://eslint.org/)

```sh
yarn lint
```
