---
type: mixin
name: prefixer
params: $property, $value, $vendors: webkit moz
---
Adds prefixed version of a property according to listed vendors

``` {.language-scss}
.box {
    @include prefixer(box-shadow, 1px 1px rgba(0, 0, 0, .3));
}

.another-box {
    @include prefixer(box-shadow, 1px 1px rgba(0, 0, 0, .3), moz);
}
```