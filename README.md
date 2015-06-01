
# form2obj

[![NPM version][npm-image]][npm-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]


Convert a form to JSON.

```html
<form>
  <input type="text" name="name" value="jon"></input>
</form>
```

```js
var toObject = require('form2obj')
var form = document.querySelector('form')
var object = toObject(form);

// object.name === 'jon'
```

[gitter-image]: https://badges.gitter.im/i5ting/form2obj.png
[gitter-url]: https://gitter.im/i5ting/form2obj
[npm-image]: https://img.shields.io/npm/v/form2obj.svg?style=flat-square
[npm-url]: https://npmjs.org/package/form2obj
[github-tag]: http://img.shields.io/github/tag/i5ting/form2obj.svg?style=flat-square
[github-url]: https://github.com/i5ting/form2obj/tags
[license-image]: http://img.shields.io/npm/l/form2obj.svg?style=flat-square
[license-url]: LICENSE
[downloads-image]: http://img.shields.io/npm/dm/form2obj.svg?style=flat-square
[downloads-url]: https://npmjs.org/package/form2obj
 