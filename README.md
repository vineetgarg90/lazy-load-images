# Lazy Load Background Images
Simple JQuery plugin to lazy load background images

#How to Use?

Include jQuery and Lazy load plugin before closing body tag:

```html
<script src="jquery.min.js" type="text/javascript"></script>
<script src="jquery.bglazyload.js" type="text/javascript"></script>
```

Add container's background image path in "data-bgimage" data attribute

```html
<div class="lazy" data-bgimage="img/bg.jpg" width="600" height="450" >
```
then initialise using

```html
$("div.lazy").lazyload();
```
<a href='http://vineetgarg90.github.io/lazy-load-images/'>View Demo</a>
