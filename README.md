# codename-zodiac

> Zodiac Signs names parser for [Codename](https://github.com/khaosdoctor/Codename) (Standalone)

## Usage

Install the package using either `npm install codename-zodiac --save` or `yarn add codename-zodiac`.

Require it and use the function `parse`:

```js
const zodiac = require('codename-zodiac')

console.log(zodiac.parse('2.1.4').codenameText) // V2.1.4 - Taurus
```

For more information about the API, see [Codename](https://github.com/khaosdoctor/Codename) project, this parser only abstracts the `parse` function, returning an instance of the original Codename parser