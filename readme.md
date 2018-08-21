## Grid Calc Sass

SASS grid layout framework that allows you infinite scope to define the number of grid columns you require. It also allows you to specify your gutter width as a pixel value.

See demo <a href="https://codepen.io/Rueb/pen/qyeVWZ">here</a>.

### Usage

Set the gutter width and total columns based on your needs.

``` scss
$cols: 120;
$gutter: 20px;
```

For the template to function correctly the column class numbers must be factors of the ``` $cols ```  variable and and their sum must match it's total. The default is 120, HTML examples below:

``` html
<div class="row">
    <div class="cl-55"></div>
    <div class="cl-45"></div>
    <div class="cl-20"></div>
</div>

<div class="row">
    <div class="cl-45"></div>
    <div class="cl-30"></div>
    <div class="cl-30"></div>
    <div class="cl-15"></div>
</div>

```
Most conventional CSS grid frameworks use the traditional 12 column layout. To use gridCalc in this way simply change the ``` $cols ```  variable to 12 and you're on your way. HTML examples below:

``` html
<div class="row">
    <div class="cl-4"></div>
    <div class="cl-4"></div>
    <div class="cl-4"></div>
</div>

<div class="row">
    <div class="cl-5"></div>
    <div class="cl-5"></div>
    <div class="cl-2"></div>
</div>

```

### Mobile

Mobile classes can be added to modify the layout on smaller screens. In the example below a single row of 4 elements will change to two rows of two elements when the screen width drops below the value specified in the media query.

``` html

<div class="row">
    <div class="cl-30 cl-sm-60"></div>
    <div class="cl-30 cl-sm-60"></div>
    <div class="cl-30 cl-sm-60"></div>
    <div class="cl-30 cl-sm-60"></div>
</div>

```

Computer magick.

```

   |\          .(' *) ' .
   | \        ' .*) .'*
   |(*\      .*(// .*) .
   |___\       // (. '*
   ((("'\     // '  * .
   ((c'7')   /\)
   ((((^))  /  \
 .-')))(((-'   /
    (((()) __/'
     )))( |
      (()
       ))

```
