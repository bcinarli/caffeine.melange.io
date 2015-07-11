--
type: function
name: rem-to-pixel
params: $font-size
--
Converts rem unit to pixel unit. If given number has units in pixels return number. Otherwise converts number according to base font size. _requires_ previously defined `$base-font-size` variable for conversions. 

``` {.language-scss}
$base-font-size: 16px;
...
rem-to-px(2rem); // returns 32px
rem-to-px(20px); // returns 20px
...
