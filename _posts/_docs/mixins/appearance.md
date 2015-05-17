---
type: mixin
name: appearance
caniuse: http://caniuse.com/#search=appearance
mozdev: https://developer.mozilla.org/en-US/docs/Web/CSS/-moz-appearance
source: https://github.com/bcinarli/caffeine/blob/master/lib/mixins/_appearance.scss#L21
params: $name, $file, $weight, $style
---
This is an unofficial feature and not included in the spec. Aside from Internet Explorer, all browsers need their vendor prexing. However for the Internet Explorer, -webkit-appearance with value none is supported on IE11 Mobile for phones with "Windows Phone 8.1 Update", and in EdgeHTML.dll

``` {.language-scss}
@include appearance(none);
@include appearance(listbox);
```
