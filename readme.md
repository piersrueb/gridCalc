## Grid Calc Sass
Standard SASS grid layout template that allows you define the number of grid columns you require and specify your gutter width as a pixel value.

### Usage

Simply setup you columns and make sure their class numbers add up to the col total defined in your SASS variables. The default is 12.

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
    <div class="column-4"></div>
    <div class="column-4"></div>
    <div class="column-4"></div>
</div>

```
Set the gutter width and column number based on your needs.

``` scss
$cols: 12;
$gutter: 12px;
```
See demo <a href="https://codepen.io/Rueb/pen/qyeVWZ">here</a>.
