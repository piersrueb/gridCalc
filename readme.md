## Grid Calc Sass

Your standard SASS grid template that allows you define your gutter width as a pixel value.

### Usage

Simply setup you columns and make sure their class numbers add up to the col total defined in your SASS variables.

``` html

<div class="row">
    <div class="column-2"></div>
    <div class="column-10"></div>
</div>

<div class="row">
    <div class="column-3"></div>
    <div class="column-9"></div>
</div>

<div class="row">
    <div class="column-3"></div>
    <div class="column-3"></div>
    <div class="column-3"></div>
    <div class="column-3"></div>
</div>

```
Set the gutter width and column number based on your needs.

``` scss
$gutter: 12px;
$cols: 12;
```
