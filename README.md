# riemke.css

A simple CSS framework for an easy start of new HTML pages.

![Screenshot of an example](/examples/1.png?raw=true "example")

It's not a competitor to other "big" CSS frameworks, and it's not desigend to be a competitor. It has neither special features nor does everything better. But if you find it useful for your project and helps you further - feel free to use it.

## Using riemke.css

Copy the dist folder to your project and include the CSS in the HTML document. riemke.css uses the Open Sans Font, the Source Code Pro Font and Remix Icons. Please have also a glimpse into the licenses of these items (see license file).

```html
<link rel="stylesheet" href="dist/riemke.css" />
```

## Structuring the HTML-Page

riemke.css assumes that you use the following structure in you document body.

```html
<body>
  <nav></nav>
  <main></main>
  <footer></footer>
</body>
```

You use the framework by adding the desired style classes to your element.

## Create a Menu

Use `<nav>` with an unordered list. The active menu items gets the active class.

```html
<nav>
  <ul>
    <li><a href="#" class="active">Home</a></li>
    <li><a href="#">Products</a></li>
    <li><a href="#">Services</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Imprint</a></li>
  </ul>
</nav>
```

## Create a Drop-Down Menu

```html
<nav>
  <ul>
    <li><a href="#" class="active">Home</a></li>
    <li>
      <a href="#">Products</a>
      <ul class="drop">
        <a href="#" class="active">Bananas</a>
        <a href="#" class="active">Strawberries</a>
        <a href="#" class="active">Apples</a>
      </ul>
    </li>

    <li>
      <a href="#">Services</a>
      <ul class="drop">
        <a href="#" class="active">Thinking</a>
        <a href="#" class="active">Making</a>
        <a href="#" class="active">Talking</a>
      </ul>
    </li>
    <li><a href="#">About</a></li>
    <li><a href="#">Imprint</a></li>
  </ul>
</nav>
```

## Responsive Menus

The only the simple menu is responsive.

## Styling Forms

Forms are automatically styled.

## Alert Boxes

```html
<div class="box info">Info!</div>
<div class="box success">Success</div>
<div class="box alert shadow">Alarm!</div>
<div class="box question shadow">Question!</div>
```

## Margins

Add margins with the margin class.

```html
<div class="m-10">margin 10</div>
<div class="mt-20">margin top 20</div>
```

## Paddings

Add paddings with the padding class.

```html
<div class="p-10">padding 10</div>
<div class="pt-20">padding top 20</div>
```

## Shadow and Rounded Corners

```html
<div class="shadow">Shadow!</div>
<div class="rounded">Rounded!</div>
```

## Avatar Image

Creates round avatar image.

```html
<img src="https://img.riemke.dev/200/200" class="img-avatar shadow" />
```

## Set Colors

Sets color and/or background-color. Choose from red, green, blue, yellow, pink, orange, purple.

```html
<div class="bgcolor-red">red background</div>
<div class="bgcolor-green color-white">green background,white text</div>
```

## Flex & Float

Classes for flex & float are also included.

```html
<div class="float-root">
  <div class="float-left"></div>
  <div class="float-left"></div>
</div>
```

```html
<div class="flex-row">
  <div class="w-100 h-100 bgcolor-red"></div>
  <div class="w-100 h-100 bgcolor-green"></div>
</div>
```
