---
type: mixin
name: align-content
params: $content
caniuse: http://caniuse.com/#search=flex
mozdev: https://developer.mozilla.org/en-US/docs/Web/CSS/align-content
source: https://github.com/bcinarli/caffeine/blob/master/lib/mixins/css3/_flex.scss#L115
---
Outputs align-content code with defined prefixes. Internet Explorer and Safari are not supporting this feature yet even with vendor prefix.

```{.language-scss}
.box {
  @include align-content('center');
}
```
