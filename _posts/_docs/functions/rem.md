--
type: function
name: rem
params: $font-size
--
Converts pixel units to rem unit. If given number has units in rem, returns number. Otherwise converts number according to base font size. _requires_ previously defined `$base-font-size` variable for conversions. 

``` {.language-scss}
$base-font-size: 16px;
...
rem(32px); // returns 2rem
rem(1.25rem); // returns 1.25rem
...
```
