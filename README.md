# Hover-on.css ![npm](https://img.shields.io/npm/v/hover-on.svg)  ![npm bundle size](https://img.shields.io/bundlephobia/min/hover-on.svg)
Bootrap button supported, pure css animation
 
`hover-on.css` has creative animations and transitions for your projects. It's great to make your buttons look awesome.


![Hover gif](https://github.com/knowankit/hoveron/blob/fix/file_structure/hover-gif.gif)



## Installation
### Install via npm:

`$ npm install hover-on`

### SCSS

You can also import `hover-on.scss` in your main scss file.
```scss
@import '~hover-on/source/sass/hover-on.scss';
```

## Usage
To use hover-on.css in your website, just add the stylesheet into your document's `<head>`, add the appropriate class to the button. That's it! You've got a animated button. Cool!

```html
<head>
    <link rel="stylesheet" href="hover-on.css">
</head>
```

Import the `scss` file in your main sass file.

```scss
@import "~hover-on/hover-on.css";
```

or use a CDN version by [jsDelivr](https://cdn.jsdelivr.net/npm/hover-on/hover-on.css)

```html
<head>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/hover-on/hover-on.css">
</head>
```

## Animations

| Class Name       |                    |                 |
| --------------   |:-----------------: | --------------: |
| `both-line`      | `bottom-line`      | `top-line`      |
| `fill-left`      | `fill-right`       | `fill-top`      |
| `fill-bottom`    | `fill-both`        | `fill-both2`    |
| `fill-skew-left` | `fill-skew-right`  | `shine`         |
| `grow`           | `shrink`           | `pulse`         |
| `pulse-grow`     | `pulse-shrink`     | `push`          |
| `pop`            | `bounce-in`        | `bounce-out`    |
| `rotate`         | `rotate-grow`      | `float`         |
| `sink`           | `bob`              | `hang`          | 
| `skew`           | `wobble-skew`      | `forward`       | 
| `backward`       | `shadow`           |                 | 

For example:

```html
<button class="btn fill-bottom-warning">Warning</button>
```
In the above example `btn` is from bootstrap classes and `fill-bottom-warning` is from the hover-on.

**Important!** It's necessary to suffix the class name with bootstrap color name like `fill-both-primary`. You don't need to add any suffix in the 2d animation class which are `pop`, `push`, `float` etc.
## Demo

[Click here](https://hover.knowankit.com/)
