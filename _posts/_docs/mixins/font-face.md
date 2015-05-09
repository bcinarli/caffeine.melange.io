---
type: mixin
name: font-face
caniuse: http://caniuse.com/#search=font-face
mozdev: https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face
source: https://github.com/bcinarli/caffeine/blob/master/lib/mixins/_text.scss#L26
params: `$name`, `$file`, `$weight`, `$style`
---
For modern approach, woff and ttf format is supported all major browsers. If you need to support Internet Explorer 8, with setting `$support-for-ie8` variable to `true`, the eot file format also added to mixin output. You also need to provide related file formats in your fonts folder.

``` {.language-scss}
@include font-face('OpenSans', 'open-sans');
@include font-face('OpenSans', 'open-sans', 'bold', 'italic');
```

Minimum requirements are a font-name and the font-file name. `$weight` and `$style` are set to `normal` by default.