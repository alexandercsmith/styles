# General SCSS Styles

[Twitter](https://twitter.com/hackerbrief) | [Medium](https://medium.com/@hackerbrief)

General SCSS Style Library

* [Angles](/styles/angles.scss)
* [Columns](/styles/columns.scss)
* [Content-Width](/styles/content.scss)
* [Flex](/styles/flex.scss)
* [Media Queries](/styles/media.scss)
* [Position](/styles/position.scss)

## Angles

```html
<div class="angle-top-left">{ content }</div>

<div class="angle-top-right">{ content }</div>

<div class="angle-bottom-left">{ content }</div>

<div class="angle-bottom-right">{ content }</div>
```

## Columns

```html
<div class="xl-col-1-4 lg-col-1-4 md-col-1-4 sm-col-1-2 xs-col-1-1">
  { content }
</div>

<div class="col-1-1">
  { content }
</div>

<div class="xl-col-1-4 lg-col-1-4 md-col-1-4 hide-on-sm xs-col-1-1">
  { content }
</div>

<div class="xl-col-1-1 lg-col-1-1 hide-at-md">
  { content }
</div>

<div class="xl-col-1-1 lg-col-1-1 show-at-lg">
  { content }
</div>

<div class="only-on-xs">
  { content }
</div>
```

## Content-Width

Usage: content-width($width)

```scss
@include content-width(900px);
```

## Flex

Usage: flex($flex-direction, $flex-wrap, $justify-content, $align-items)

```scss
@include flex(row,wrap,flex-start,center);
```

## Media Queries

* EDITING

Usage: min($width) | max($width) | min-max($min, $max)

```scss
@include min(500px) { color: blue; }

@include max(800px) { color: red; }

@include min-max(500px, 800px) { color: yellow; }
```

## Position

Usage: position($position, $top, $right, $bottom, $left)

```scss
@include position(absolute,0,0,null,null);
```
