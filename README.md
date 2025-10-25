# Reveal.js Archetypes (Quarto)

This starter provides six reusable slide layouts in a minimalist, high-contrast aesthetic (black on white, restrained grays), implemented with **pure Quarto/reveal.js** (no custom shortcodes or filters).

## Files
- `_quarto.yml` — global reveal.js options
- `styles.scss` — micro-theme (typography, colors, utility classes)
- `index.qmd` — example deck that showcases the six archetypes
- `images/` — neutral SVG placeholders; replace with your assets

## Usage
```bash
quarto preview
# or
quarto render
```

## Notes
- Sequential reveals use the native `reveal.js` **fragments**: add the class `.fragment` to any list item or block.
- Columns use Quarto's built-in `columns` container; each `column` accepts a `width` attribute.
- Image placeholders are SVGs sized to common aspect ratios; replace them with your images while keeping the same filenames or update the paths.