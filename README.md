# [![Imgur](http://i.imgur.com/FHjshUv.png)](https://github.com/webcaetano/jinx)

[Jinx](https://github.com/webcaetano/jinx) module for handle error and submit to browser console

## Instalation

```
npm install jinx-error-catcher
```

## Usage 
```javascript
require('jinx-error-catcher')(); // that's all
// all errors will display on browser console

// or with options

require('jinx-error-catcher')({
	deepDir:2, 
	maxStack:3 
});
```

## Options

#### deepDir
show up to 3 parents folder Like (/home/www/main.as).
- Default: 2

#### maxStack
show 3 stacks of root error 
- Default: 3

---------------------------------

The MIT [License](https://raw.githubusercontent.com/webcaetano/jinx-error-catcher/master/LICENSE.md)
