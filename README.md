bootstrap-tab-ajax
==================

Gives bootstrap-tab ajax capabilities as a jQuery plugin

Minimum required html markup:

```html
<div>
	<ul id="index-tabs" class="nav nav-tabs">
		<li><a href="/your_url_1" data-toggle="tab">Tab Header 1</a></li>
		<li><a href="/your_url_2" data-toggle="tab">Tab Header 2</a></li>
	</ul>
</div>
```

And finally initialize the plugin

```javascript
$(document).ready(function () {
	$("#index-tabs").ajaxTab();
});
```