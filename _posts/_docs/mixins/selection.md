---
type: mixin
name: selection
caniuse: http://caniuse.com/#search=selection
mozdev: https://developer.mozilla.org/en-US/docs/Web/CSS/::selection
source: https://github.com/bcinarli/caffeine/blob/master/lib/mixins/_text.scss#L152
params: $content...
---
The `::selection` CSS pseudo-element applies rules to the portion of a document that has been highlighted (e.g., selected with the mouse or another pointing device) by the user. Only a small part of text related properties supports. You can change the following properties in selections; `color`, `background-color`, `cursor`, `outline`, `text-decoration`, `text-emphasis-color` and `text-shadow`.

``` {.language-scss}
@include selection("color: white; background: turquoise;");
```