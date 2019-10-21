<p align="center">
  <img src="docs/assets/slate.svg" width="128" alt="Slate Logo"/>
</p>

# Slate
Dynamic DOM manipulation at the speed of JavaScript.

## Overview
`Slate` efficiently renders templates to DOM and efficiently updates the DOM with new values.

`Slate` works natively with JavaScript via template literals, bringing the power of JavaScript to HTML templates.

```javascript
import { html, append } from 'slate';

const sayHello = (name) => html`<div>Hello ${name}!</div>`;
// This appends <div>Hello World!</div> to the document body
append(sayHello('World'),  document.body);
```
