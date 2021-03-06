## GridCalc

Grid Calc is a dynamic SASS grid layout framework that allows you infinite scope to define the number of grid columns you require. It also allows you to specify your gutter width as a pixel value.

See <a href="https://codepen.io/Rueb/pen/qyeVWZ">demo</a> on Codepen.

You will need to compile the SASS before using it on your project. See <a href="https://sass-lang.com/install">this link</a> for more info on compiling SASS. There is an example of a compiled version of this framework based on a traditional 12 column layout included in this this repo.

### Usage

Set the total columns and gutter width based on your needs and Grid Calc will take care of the rest.

``` scss
$cols: 120;
$gutter: 20px;  //  must be a pixel value
```

For the template to function correctly the column class numbers must be factors of the ``` $cols ```  variable and and their sum must match it's total.

In the example below the  ``` $cols ``` variable is set at the default 120 columns. The column classes for each row add up to the same total of 120 creating the desired 3 and 4 column layouts.

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
Most conventional CSS grid frameworks use the traditional 12 column layout. To use Grid Calc in this way simply change the ``` $cols ```  variable to 12 and you're on your way. HTML example below:

``` html
<div class="row">
    <div class="cl-4"></div>
    <div class="cl-4"></div>
    <div class="cl-2"></div>
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

### Licence

Open source under the MIT License.

```

   |\          .(' *) ' .
   | \        ' .*)SASS .'*
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
