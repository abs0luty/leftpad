<p align="center">
<img width="30%" src="./logo.png" />
</p>

# `leftpad-str` crate.

Obviously the best crate for the Rust programming language. The crate serves the only goal of implementing `leftpad` function:

```rs
pub fn leftpad(input: &str, width: usize, padding_char: char) -> String;
```

# Examples

```rs
assert_eq!(leftpad("hello", 8, '*'), "***hello");
assert_eq!(leftpad("rust", 6, ' '), "  rust");
```
