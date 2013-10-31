TipTop
======

Stupidly simple jQuery tooltips. No fuss. Doesn't support HTML or fixed position tooltips.

Usage
-----

Include the scripts and styles in your HTML head:

```html
<link rel="stylesheet" href="tiptop.css" type="text/css" />

<script src="//ajax.googleapis.com/ajax/libs/jquery/1.10.1/jquery.min.js"></script>
<script src="tiptop.js"></script>
```

Then simply add a title to any element you want to add TipTop to:

```html
<a href="#alink" class="help" title="This is the tooltip content">A Link</a>
```

Then simply hook up TipTop:

```html
<script>
$(document).ready(function(){
	$('.help').tipTop();
});
</script>
```

Advanced
--------

TipTop has two settings:

* `offsetVertical` - Vertical offset in px (defaults to 10)
* `offsetHorizontal` - Horizontal offset in px (defaults to 10)

Browser Compat
--------------

TipTop works in all modern browsers (Chrome, Firefox, Safari, Opera) and probably in IE8+.

Credits
-------

TipTop was created by [Gilbert Pellegrom](http://gilbert.pellegrom.me) from [Dev7studios](http://dev7studios.com). Released under the MIT license.
