---
type: mixin
name: font-size
caniuse: http://caniuse.com/#search=rem
mozdev: https://developer.mozilla.org/en/docs/Web/CSS/length#rem
source: https://github.com/bcinarli/caffeine/blob/master/lib/mixins/_text.scss#L103
params: $font-size
---
For modern usage, converts and output font-size with rem units. If you need to support Internet Explorer 8, with setting `$support-for-ie8` variable to `true`, mixin also returns original __pixel__ size and with __rem__ unit.

``` {.language-scss}
p {
    @include font-size(16px);
}

.title {
    @include font-size(24px);
}
```