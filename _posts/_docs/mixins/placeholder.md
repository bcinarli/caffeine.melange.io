---
type: mixin
name: placeholder
mozdev: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input#attr-placeholder
source: https://github.com/bcinarli/caffeine/blob/master/lib/mixins/_placeholder.scss#L12
params: $self
---
Styles input elements' placeholder. If the $self params is true, styles applied to class itself, otherwise, styles applied to the child elements

``` {.language-scss}
.text-field {
    @include placeholder() {
        color: #333;
        font-style: italic;
    };
}
```