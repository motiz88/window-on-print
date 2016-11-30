# window-on-print

**Reliably detect when the user prints.** A better solution for [`beforeprint`](https://developer.mozilla.org/en-US/docs/Web/API/WindowEventHandlers/onbeforeprint)/[`afterprint`](https://developer.mozilla.org/en-US/docs/Web/API/WindowEventHandlers/onafterprint).

[![npm version](https://img.shields.io/npm/v/window-on-print.svg)](https://www.npmjs.com/package/window-on-print)
![ISC-licensed](https://img.shields.io/github/license/derhuerst/window-on-print.svg)


## Installing

Use the bundle from `dist/window-on-print.min.js` or install using [npm](https://www.npmjs.com).

```shell
npm install window-on-print
```


## Usage

```js
const onPrint = require('window-on-print')

onPrint.before(window, () => {
	console.info('user is going to print')
})
onPrint.after(window, () => {
	console.info('user is has printed or aborted')
})
```


## Contributing

If you **have a question**, **found a bug** or want to **propose a feature**, have a look at [the issues page](https://github.com/derhuerst/window-on-print/issues).