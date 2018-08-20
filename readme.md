## Grid Calc Sass
Standard SASS grid layout template that allows you define the number of grid columns you require. I also allows you to specify your gutter width as a pixel value.

### Usage

For the template to function correctly the column class numbers must be factors of the ``` $cols ```  variable and and their sum must match it's total. The default is 12, example below.

``` html

<div class="row">
    <div class="column-5"></div>
    <div class="column-5"></div>
    <div class="column-2"></div>
</div>

```
Set the gutter width and column number based on your needs.

``` scss
$cols: 12;
$gutter: 12px;
```
See demo <a href="https://codepen.io/Rueb/pen/qyeVWZ">here</a>.
