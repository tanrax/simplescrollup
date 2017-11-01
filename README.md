# Simple plugin in Javascript Vanilla to animate scrolling when you return to the top of the page

## Install

1. Download **simplescrollup.js** .

2. Link in your HTML **simplescrollup.js** .

```html
	<script src="simplescrollup.js"></script>
```

Example

```html
<html>
	<head>
	</head>
	<body>
		<!-- Your HTML content -->
		<script src="simplescrollup.js"></script>
	</body>

</html>
```

3. Add your button with this structure.


```html
<a href="#up">Your text</a>
```

Example

```html
<html>
	<head>
	</head>
	<body>
		<!-- Your HTML content -->
		<a href="#up">Your text</a>
		<script src="simplescrollup.js"></script>
	</body>

</html>
```

## Advance

You can control the duration and type of animation.

```html
<a href="#up" duraction="1000" easing="easeInOutQuad">Your text</a>
```

* **Duration**: is measured in milliseconds.
* **easing**: You can change the animation for any of this list.
	* linear
	* easeInQuad
	* easeOutQuad
	* easeInOutQuad
	* easeInCubic
	* easeOutCubic
	* easeInOutCubic
	* easeInQuart
	* easeOutQuart
	* easeInOutQuart
	* easeInQuint
	* easeOutQuint
	* easeInOutQuint