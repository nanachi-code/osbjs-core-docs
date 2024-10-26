# Getting started

## Overview

::: warning
osbjs is still in alpha.
:::

osbjs is a osu! storyboard library designed to create complex storyboards while staying close to the original .osb scripting language, making it easy to pick up for beginners. It also let you create reusable and nestable components.

## Installation

You need to install [Node.js](https://nodejs.org/en/) for local development.

::: code-group

```sh [npm]
$ npm i @osbjs/core@alpha
```

```sh [pnpm]
$ pnpm add @osbjs/core@alpha
```

```sh [yarn]
$ yarn add @osbjs/core@alpha
```

:::

If you want to use osbjs in the browser, you can use this cdn:

::: code-group

```html [umd]
<script src="https://cdn.jsdelivr.net/npm/@osbjs/core@1.0.0-alpha.4/dist/index.umd.js"></script>
```

```html [esm]
<script type="module">
  import osbjs from 'https://cdn.jsdelivr.net/npm/@osbjs/core@1.0.0-alpha.4/dist/index.mjs'
</script>
```

:::
