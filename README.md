# Translate3d
#### Super-smooth CSS3 translate3d for jQuery

Translate3d is a plugin for to help you do CSS translate3d in jQuery.

Usage
-----
Just include [jquery.translate3d.js] after jQuery. Requires jQuery 1.2+.

``` html
<script src='jquery.js'></script>
<script src='jquery.translate3d.js'></script>
```

It is also available via [npm].

    $ npm install --save translate3d

[npm]: http://npmjs.org/package/translate3d
[jquery.translate3d.js]: https://github.com/hueyhe/translate3d


Animating - `$.fn.translate3d`
-----------------------------
``` javascript
$("#example").translate3d({
  x: 100,
  y: 0,
  z: 0
}, 400, 'ease', function() {
	/* ... */
});
```