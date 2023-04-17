---
permalink: /index.html
---

[Website (Git Pages)](https://chrisnajman.github.io/grid-flexbox-page-layouts)

# Grid and Flexbox Page Layouts

## Description

Three-row template for laying out header, main and footer.

The result is the same whether `grid` or `flexbox` is used (but `grid` uses less code).

- `header`: fits content,
- `main`: takes up the remaining space,
- `footer`: fits content, always sits at the bottom of the page.

## CSS

- `grid` / `flexbox` used for page layout.
- `100dvh` (with `100vh` as fallback) set on `.main-layout` for 100% page height.
  - (Avoids setting 100% height on `html, body` which can cause problems on mobile.)

## Testing

- Tested on:
  - Windows 10
    - Chrome
    - Firefox
    - Microsoft Edge
