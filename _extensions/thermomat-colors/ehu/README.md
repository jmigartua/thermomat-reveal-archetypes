# Thermomat Brand Pack — v0.1.2 (colors folded into brand)

What you get:
- Brand YAML files with an extended `color.palette` (coral, mint, periwinkle, chartreuse, lavender, green, tag-gray).
- Auto-loaded CSS utilities for inline coloring:
  - class-based: `[text]{.coral}`
  - attribute-based (optional not included here; class API is shortest).
- Fonts CSS auto-included for EHU variants.

## Install
Unzip so `_extensions/thermomat/ehu/` sits at your project root.

## Use
Select a skin and render—no extra CSS includes needed:
```yaml
brand: thermomat/ehu/02-es      # or 02-eu, 01-posit-style, 00-standard
```
Then in your content:
```markdown
This is [coral]{.coral}, a [chip]{.chip .bg-periwinkle}, and a [highlight]{.hl-chartreuse}.
```
