---
type: mixin
name: box-shadow
caniuse: http://caniuse.com/#search=box-shadow
mozdev: https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow
source: https://github.com/bcinarli/caffeine/blob/master/lib/mixins/css3/_box-shadow.scss#L14
params: $content...
---
Box-shadow is mostly available in all modern browser. If not edge case, you can use the standart box-shadow definition.

``` {.language-scss}
@include box-shadow(1px 1px 1px rgba(0, 0, 0, .3));
```