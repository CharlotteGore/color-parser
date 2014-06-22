
# color-parser

  CSS color string parser, forked from component/color-parser

## Installation

Browserify/NPM

```sh
    $ npm install --save gm-color-parser
```

```js
  var parse = require('gm-color-parser');
```

Component

```sh
    $ component install charlottegore/color-parser
```

```js
  var parse = require('color-parser');
```

### Example

```js
var parse = require('color-parser');

parse('#fc0')
// => { r: 255, g: 204, b: 0, a: 1 }

parse('#ffcc00')
// => { r: 255, g: 204, b: 0, a: 1 }

parse('rgb(255, 204, 0)')
// => { r: 255, g: 204, b: 0, a: 1 }

parse('rgba(255, 204, 0, 1)')
// => { r: 255, g: 204, b: 0, a: 1 }
```

# License

  MIT
