# css-lists

Functional CSS for lists

## Filesize

| File | Size |
|------|------|
| `dist/lists.css` | 2841 bytes |
| `dist/lists.min.css` | 2125 bytes (355 Gzipped) |

## Install

```sh
npm install css-lists
```

## Usage

### Import

```css
@import "css-lists";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-lists/dist/lists.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-lists/dist/lists.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.disc` | `list-style-type: disc;` |
| `.circle` | `list-style-type: circle;` |
| `.square` | `list-style-type: square;` |
| `.decimal` | `list-style-type: decimal;` |
| `.leading-zero` | `list-style-type: decimal-leading-zero;` |
| `.lower-roman` | `list-style-type: lower-roman;` |
| `.upper-roman` | `list-style-type: upper-roman;` |
| `.lower-greek` | `list-style-type: lower-greek;` |
| `.lower-latin` | `list-style-type: lower-latin;` |
| `.upper-latin` | `list-style-type: upper-latin;` |
| `.lower-alpha` | `list-style-type: lower-alpha;` |
| `.upper-alpha` | `list-style-type: upper-alpha;` |
| `.list` | `list-style-type: none;` |
| `.disc-s` | `list-style-type: disc;` |
| `.circle-s` | `list-style-type: circle;` |
| `.square-s` | `list-style-type: square;` |
| `.decimal-s` | `list-style-type: decimal;` |
| `.leading-zero-s` | `list-style-type: decimal-leading-zero;` |
| `.lower-roman-s` | `list-style-type: lower-roman;` |
| `.upper-roman-s` | `list-style-type: upper-roman;` |
| `.lower-greek-s` | `list-style-type: lower-greek;` |
| `.lower-latin-s` | `list-style-type: lower-latin;` |
| `.upper-latin-s` | `list-style-type: upper-latin;` |
| `.lower-alpha-s` | `list-style-type: lower-alpha;` |
| `.upper-alpha-s` | `list-style-type: upper-alpha;` |
| `.list-s` | `list-style-type: none;` |
| `.disc-m` | `list-style-type: disc;` |
| `.circle-m` | `list-style-type: circle;` |
| `.square-m` | `list-style-type: square;` |
| `.decimal-m` | `list-style-type: decimal;` |
| `.leading-zero-m` | `list-style-type: decimal-leading-zero;` |
| `.lower-roman-m` | `list-style-type: lower-roman;` |
| `.upper-roman-m` | `list-style-type: upper-roman;` |
| `.lower-greek-m` | `list-style-type: lower-greek;` |
| `.lower-latin-m` | `list-style-type: lower-latin;` |
| `.upper-latin-m` | `list-style-type: upper-latin;` |
| `.lower-alpha-m` | `list-style-type: lower-alpha;` |
| `.upper-alpha-m` | `list-style-type: upper-alpha;` |
| `.list-m` | `list-style-type: none;` |
| `.disc-l` | `list-style-type: disc;` |
| `.circle-l` | `list-style-type: circle;` |
| `.square-l` | `list-style-type: square;` |
| `.decimal-l` | `list-style-type: decimal;` |
| `.leading-zero-l` | `list-style-type: decimal-leading-zero;` |
| `.lower-roman-l` | `list-style-type: lower-roman;` |
| `.upper-roman-l` | `list-style-type: upper-roman;` |
| `.lower-greek-l` | `list-style-type: lower-greek;` |
| `.lower-latin-l` | `list-style-type: lower-latin;` |
| `.upper-latin-l` | `list-style-type: upper-latin;` |
| `.lower-alpha-l` | `list-style-type: lower-alpha;` |
| `.upper-alpha-l` | `list-style-type: upper-alpha;` |
| `.list-l` | `list-style-type: none;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.disc-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/lists.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/lists.css` — formatted
- `dist/lists.min.css` — minified

## License

MIT
