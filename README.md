<h1 align="center"><code>clean-ms.js</code></h1>

<p align="center">Convert ms to human-readable format</p>

## ⚙️ Installation

```terminal
npm i clean-ms
```

## 📖 Usage

#### • Import

```js
// ES6
import cleanMs from "clean-ms";

// commonjs
const cleanMs = require("clean-ms");
```

#### • Examples

```js
console.log(cleanMs(60000));     // output: 1m
console.log(cleanMs(3600000));   // output: 1h
console.log(cleanMs(86400000));  // output: 1d
console.log(cleanMs(123456789)); // output: 1d 10h 17m 36s
```

---

[Support me on Patreon](https://www.patreon.com/axorax) — 
[Check out my socials](https://github.com/axorax/socials)