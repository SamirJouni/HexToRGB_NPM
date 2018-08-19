# hex_a-to-rgb

## How To Use:

### First require the package:

```
$ const convertColor = require("hex_a-to-rgba");
```

### Then call the function with a value:

```
convertColor ('');   // Will return an error message

convertColor ('#000000');   / will return rgb(0,0,0)

convertColor ('( 255,255,255,.5)') / will return #ffffff80

```