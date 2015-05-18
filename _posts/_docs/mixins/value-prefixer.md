---
type: mixin
name: value-prefixer
params: $property, $value, $content, $vendors: webkit moz
---
Adds prefixed version of values in a property

``` {.language-scss}
.box {
    @include value-prefixer(display, flex, flex-grow, webkit);
}
```