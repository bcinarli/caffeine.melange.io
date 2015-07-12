---
type: mixin
name: align-self
params: $content
caniuse: http://caniuse.com/#search=flex
mozdev: https://developer.mozilla.org/en-US/docs/Web/CSS/align-self
source: https://github.com/bcinarli/caffeine/blob/master/lib/mixins/css3/_flex.scss#L146
---
Outputs align-self code with defined prefixes. Safari is not supporting this feature yet even with vendor prefix.

```{.language-scss}
.box {
  @include align-self('center');
}
```
