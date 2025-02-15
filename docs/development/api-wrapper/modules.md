---
title: Modules
description: 🧩 Modules exposed via Spicetify object.
---

Spicetify exposes some modules via `Spicetify` object.

You can access them by typing `Spicetify.<module name>` in the DevTools console, inside your extension, or `window.top.Spicetify.<module name>` if you're developing an app inside an `iframe`.

Utilizing these modules can help you create more powerful extensions without having to include the whole module in your extension.

```js
Spicetify.React
```

For usage of these modules, please refer to their official documentation.

### React

[React](https://reactjs.org/) is a JavaScript library for building user interfaces. It is used by Spotify to build their UI.

```js
Spicetify.React
```

### ReactDOM

[ReactDOM](https://reactjs.org/docs/react-dom.html) is a package that provides DOM-specific methods that can be used at the top level of your app and as an escape hatch to get outside of the React model if you need to. It is used by Spotify to render React components to the DOM.

```js
Spicetify.ReactDOM
```

### Tippy.js

[Tippy.js](https://atomiks.github.io/tippyjs/) is a highly customizable tooltip and popover library powered by Popper.

```js
Spicetify.Tippy
```

### Mousetrap

[Mousetrap](https://craig.is/killing/mice) is a simple library for handling keyboard shortcuts in Javascript.

```js
Spicetify.Mousetrap
```
