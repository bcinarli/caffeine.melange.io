---
type: mixin
name: disable-text-select
caniuse: http://caniuse.com/#search=user-select
mozdev: https://developer.mozilla.org/en-US/docs/Web/CSS/user-select
source: https://github.com/bcinarli/caffeine/blob/master/lib/mixins/_text.scss#L130
params: null
---
It is useful for mobil applications. Prevents text selection when swipe or double click. According to current development status, all browsers need vendor prefixing.

``` {.language-scss}
.button {
    @include disable-text-select();
}
```