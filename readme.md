## Grid Calc Sass

Standard SASS grid layout template that allows you define the number of grid columns you require. It also allows you to specify your gutter width as a pixel value.

#### Usage

For the template to function correctly the column class numbers must be factors of the ``` $cols ```  variable and and their sum must match it's total. The default is 12, examples below.

``` html

<div class="row">
    <div class="column-5"></div>
    <div class="column-5"></div>
    <div class="column-2"></div>
</div>

<div class="row">
    <div class="column-6"></div>
    <div class="column-3"></div>
    <div class="column-2"></div>
    <div class="column-1"></div>
</div>

<div class="row">
    <div class="column-4"></div>
    <div class="column-3"></div>
    <div class="column-2"></div>
    <div class="column-2"></div>
    <div class="column-1"></div>
</div>

```
Set the gutter width and total columns based on your needs.

``` scss
$cols: 12;
$gutter: 20px;
```
See demo <a href="https://codepen.io/Rueb/pen/qyeVWZ">here</a>.
