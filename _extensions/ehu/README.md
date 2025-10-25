# Thermomat Brand Pack — Patched (v0.1.1)

This patch fixes validation errors in brand YAML files:

- `typography.link` must be **singular** (not `links`).
- `typography.base` **does not** support `color`; base text inherits `color.foreground`.

Docs:
- Brand typography attributes and supported fields. See: https://posit-dev.github.io/brand-yml/brand/typography.html
- Quarto brand reference. See: https://quarto.org/docs/reference/metadata/brand.html

## Using EHU fonts in nested folders

Load `styles/ehu-fonts-mixed.css` and place your files under:

```
_extensions/thermomat/ehu/fonts/EHU_Sans/
_extensions/thermomat/ehu/fonts/EHU_Serif/
```

Project-level example:

```yaml
brand: thermomat/ehu/02-es
format:
  revealjs:
    css: thermomat/ehu/styles/ehu-fonts-mixed.css
```

Per-document example:

```yaml
---
brand: thermomat/ehu/02-eu
format:
  revealjs:
    css: thermomat/ehu/styles/ehu-fonts-mixed.css
---
```
