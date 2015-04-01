## buffer-chunks

Split buffer into chunks

## Installation

```
npm install buffer-chunks
```

## Usage

```js
var list = chunks(new Buffer('aaaaazzzzzbbbbb'), 5);

// ->

[ <Buffer 61 61 61 61 61>,
  <Buffer 7a 7a 7a 7a 7a>,
  <Buffer 62 62 62 62 62> ]
```

## License

MIT
