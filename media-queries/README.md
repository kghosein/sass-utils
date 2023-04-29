# Media Queries in SASS

`_break_points.scss` shows a maintainable way of writing and using media queries in SASS and lets you define: 

- a map of `break-points` with a `default` so you can apply (default) values dynamically
- a `@mixin` to declare any kind of media query and
- a second `@mixin` to use that kind of media query

## How to use?
In order to use a `@mixin` from `_break_points.scss` you would do,

***_use_media.scss***
```
@use "./break_points";

@include break_points.max-desktop {
    // styles
}
```