# Fonts in SASS

`_fonts.scss` shows a maintainable way of writing and using font families along with font weights in SASS and lets you define: 

- a map of fonts with weights
- a `@mixin` to use the fonts map and apply properties

## How to use?
In order to use font `@mixin` from `_fonts.scss` you would do,

***_use_fonts.scss***
```
@use "./fonts";

@include fonts.font-poppins(500) // 500 is weight
```