# String-Break

[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![npm download][download-image]][download-url]

![](./example/screenshot.gif)

## Install

```shell
npm install string-break --save
```

## Usage

```js
const stringBreak = require('string-break');
const str = '远处海港传来阵阵船笛 我一直飘零到被你拣起 如今望著反映窗户玻璃 有个我陌生又熟悉';

let lines = stringBreak(str, 30);
```

## License

MIT.

[npm-image]: https://img.shields.io/npm/v/string-break.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/string-break
[travis-image]: https://img.shields.io/travis/keenwon/string-break.svg?style=flat-square
[travis-url]: https://travis-ci.org/keenwon/string-break
[download-image]: https://img.shields.io/npm/dm/string-break.svg?style=flat-square
[download-url]: https://npmjs.org/package/string-break