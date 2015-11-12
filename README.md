# millify
Human-readable large numbers for Node.js v4+

### Installation
```
npm i --save millify
```

### Usage
#### `millify(@number, @decimal)`

First parameter is the number, second parameter is the desired decimal places (default: 1).

```
const millify = require('millify')

millify(2500)
// 2.5K

millify(1250000, 3)
// 1.25M

millify(2000000000)
// 2B
```

