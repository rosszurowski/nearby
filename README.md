# Nearby

Finds elements in an array that are within a given distance threshold.

This is useful for generating random numbers that don't collide, or have ample distance between them.

## Usage

```js

var nearby = require('nearby')
var near = nearby(5)

var arr = [1, 5, 10, 25, 40, 42]

near(arr, 12) // true
near(arr, 19) // false
```

## License

MIT