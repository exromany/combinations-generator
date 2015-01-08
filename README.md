Combinations-generator
===================
Return combinations in array uses es6 generators.

# Install

```
npm install combinations-generator
```

# Example

```javascript
var comb = require("combinations-generator")

var array = ["a", "b", "c"]

var iterator = comb(array, 2);

for (var item of iterator) {
  console.log(item);
}
```

Output:

```javascript
[ 'a', 'b' ]
[ 'a', 'c' ]
[ 'b', 'c' ]
```

If you want to use this in a browser, then you should use [browserify](http://browserify.org/).

# Credits
(c) 2015 exromany. MIT License
