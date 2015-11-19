# observable-to-promise [![Build Status](https://travis-ci.org/sindresorhus/observable-to-promise.svg?branch=master)](https://travis-ci.org/sindresorhus/observable-to-promise)

> Convert an [Observable](https://github.com/zenparsing/es-observable) to a Promise

Other values are just passed through.


## Install

```
$ npm install --save observable-to-promise
```


## Usage

```js
const observableToPromise = require('observable-to-promise');

observableToPromise(Observable.of(1, 2)).then(() => {
	console.log('done');
});
```


## Related

- [is-observable](https://github.com/sindresorhus/is-observable) - Check if a value is an Observable


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
