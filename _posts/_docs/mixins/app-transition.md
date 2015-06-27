---
type: mixin
name: app-transition
---
Adds a default transition properties to element with predefined `$base-duration` and `$base-easing` parameters in settings.

``` {.language-scss}
.box {
    @include app-transition();
}
```