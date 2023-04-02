TODO

- Update to CUBE terminology
- Update breakpoints function
- Change to fluid sizes and spacing
- Add my gitignore
- Include linters etc.
- Add font-weight partial and variables?
- Add my reset and any global styles

- Add functions to enable setting values from maps:

```scss
@function fs($font-size) {
  @if map.has-key($font-sizes, $font-size) {
    @return map.get($font-sizes, $font-size);
  } @else {
    @error '$font-sizes does not have that size!';
  }
}

@function size($size) {
  @if map.has-key($sizes, $size) {
    @return map.get($sizes, $size);
  } @else {
    @error '$sizes does not have that size!';
  }
}
```

- Think about using scss variables inside CSS Custom Propterties
- Update my utility and composition classes
- Check Stef Eckeles 11ty sass starter?
