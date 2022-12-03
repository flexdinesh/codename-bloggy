---
title: "Prism.js syntax highlighting for code blocks"
description: "Code blocks are syntax highlighted using Prism.js"
date: "2022-11-03"
---

Syntax highlighting is done using [Prism.js](https://github.com/PrismJS/prism) with the default [nord theme](https://github.com/PrismJS/prism-themes/blob/master/themes/prism-nord.css). You can customise to whichever theme you want from the [plenty available prism themes](https://github.com/PrismJS/prism-themes).

## HTML Code Block

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Example HTML5 Document</title>
  </head>
  <body>
    <p>Test</p>
  </body>
</html>
```

## JSX Code Block

```jsx
const Greet = () => {
  const message = `Hello World!`;
  return <div>{message}</div>;
};
```

## CSS Code Block

```css
.layout {
  display: grid;
  grid-template-columns: 5rem minmax(0, 1fr) 4rem;
}
```

...and many more - [Languages supported by Prism.js](https://prismjs.com/#supported-languages)