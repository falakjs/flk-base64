# Base64
A syntactic sugar wrapper to [atob()](https://developer.mozilla.org/en-US/docs/Web/API/WindowBase64/atob) and [btoa()](https://developer.mozilla.org/en-US/docs/Web/API/WindowBase64/btoa0).

> This is a standalone package so it works on browser, node js or Falak framework.

# Installation
`flk install flk-base64` 

OR 

`npm install flk-base64`

# Usage
### Node Js:

Import the package 

`import base64 from 'flk-base64';`

OR

`const base64 = require('flk-base64');`

### Browser
`<script src="base64.js"></script>`

> Add the path of the file in the `dist` directory. 

### Encoding

```js
// Encoding
let encodedString = base64.encode('hello world'); // SGVsbG8gd29ybGQ=

// Decoding
let decodedString = base64.decode('SGVsbG8gd29ybGQ='); // Hello world
```