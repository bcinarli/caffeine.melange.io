--
type: function
name: remove-unit
params: $number
--
Removes the unit of any given number. Useful for calculating conversions between different sizes e.g. px to rem conversionsion.

``` {.language-scss}
...
   $unitless: remove-unit(16px); // returns 16
...
```