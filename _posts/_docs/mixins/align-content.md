---
type: mixin
name: align-content
params: $content
---
Outputs align-content code with defined prefixes. Internet Explorer and Safari are not supporting this feature yet even with vendor prefix.

```{.language-scss}
.box {
  @include align-content('center');
}
```
