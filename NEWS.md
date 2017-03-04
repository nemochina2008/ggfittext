# v0.2

## Major changes
- `geom_shrink_text` and `geom_fill_text` replaced with single `geom_fit_text`
  with `fill_text` option. (The old geoms still work, but as wrappers for
  `geom_fit_text`).
- Add support for discrete axes with new `discrete.height` and `discrete.width`
  options.

## Bug fixes
- Font sizes now correctly and consistently represented as point sizes.

# v0.1
First release!