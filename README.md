# Simple plugin in Javascript Vanilla to animate scrolling when you return to the top of the page

## Demo

[Project Site](http://simplescrollup.programadorwebvalencia.com/)

## Download

```bash
npm install simplescrollup
```

or

```bash
yarn add simplescrollup
```

## Quick start

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
<a href="#up" class="simplescrollup__button simplescrollup__button--hide">Your text</a>
```

Example

```html
<html>
	<head>
	</head>
	<body>
		<!-- Your HTML content -->
		<a href="#up" class="simplescrollup__button simplescrollup__button--hide">Your text</a>
		<script src="simplescrollup.js"></script>
	</body>

</html>
```

4. Add CSS.

```css
.simplescrollup__button {
	position: fixed;
	bottom: 3rem;
	right: 3rem;
	transition: 1s all;
	z-index: 10000;
}
.simplescrollup__button--show {
	transform: translateX(0);
}
.simplescrollup__button--hide {
	transform: translateX(100px);
}
```

Example

```html
<html>
	<head>
		<style>
			.simplescrollup__button {
				position: fixed;
				bottom: 3rem;
				right: 3rem;
				transition: 1s all;
				z-index: 10000;
			}
			.simplescrollup__button--show {
				transform: translateX(0);
			}
			.simplescrollup__button--hide {
				transform: translateX(100px);
			}
		</style>
	</head>
	<body>
		<!-- Your HTML content -->
		<a href="#up" class="simplescrollup__button simplescrollup__button--hide">Your text</a>
		<script src="simplescrollup.js"></script>
	</body>

</html>
```

5. Enjoy!!

## Advance

You can control the duration and type of animation.

```html
<a href="#up" duraction="1000" height-hide="100" easing="easeInOutQuad" class="simplescrollup__button simplescrollup__button--hide">Your text</a>
```

* **duration**: Time in milliseconds that it will take to go up above the page.
* **height-hide**: Distance in pixels from top at which button will be displayed.
* **easing**: You can change the animation scroll for any of this list.
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
