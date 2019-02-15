# General Sass Styles

[Twitter](https://twitter.com/sudoawesome) | [Medium](https://medium.com/@sudoawesome)

General Sass Style Library

* [Columns](/styles/columns.scss)
* [Flex](/styles/flex.scss)
* [Position](/styles/position.scss)
* [Content-Width](/styles/content.scss)

## Columns

```html
<div class="xl-col-1-4 lg-col-1-4 md-col-1-4 sm-col-1-2 xs-col-1-1">
  { content }
</div>

<div class="col-1-1">
  { content }
</div>
```

## Flex

Usage: flex($flex-direction, $flex-wrap, $justify-content, $align-items)

```scss
@include flex(row,wrap,flex-start,center);
```

## Position

Usage: position($position, $top, $right, $bottom, $left)

```scss
@include position(absolute,0,0,null,null);
```

## Content-Width

Usage: content-width($width)

```scss
@include content-width(900px);
```
