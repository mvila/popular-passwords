# popular-passwords [![npm version](https://img.shields.io/npm/v/popular-passwords.svg)](https://www.npmjs.com/package/popular-passwords)

List of popular passwords with at least 8 characters.

Data source: [zxcvbn](https://github.com/dropbox/zxcvbn).

## Installation

```
npm install --save popular-passwords
```

## Usage

```javascript
var passwords = require('popular-passwords');

console.log(passwords.indexOf('passw0rd') !== -1); // => true
```

## License

MIT
