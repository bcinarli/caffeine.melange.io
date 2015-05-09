---
type: mixin
name: font-icon
caniuse: http://caniuse.com/#search=font-face
mozdev: https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face
source: https://github.com/bcinarli/caffeine/blob/master/lib/mixins/_text.scss#L65
params: `$name`, `$file`
---
Outputs an icon font definition with supporting class attribute selectors. For preventing font misuse for the element, the class selector applied to `:before` pseudo element instead of the element itself.

```SCSS {.language-scss}
@include font-icon('myicons', 'myicons');
```