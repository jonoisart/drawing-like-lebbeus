# Drawing like Lebbeus Woods

A 12-week self-directed studio course in Lebbeus Woods's drawing method: ten modules plus a capstone, each with drills, a test, an output and links to his works in museum collections.

Single static page, no build step. Open `index.html` locally or deploy the folder as-is.

## Features

- One sheet per module, linkable by hash: `#overview`, `#kit`, `#rhythm`, `#m1` to `#m10`, `#capstone`, `#rubric`, `#reading`, `#sources`
- Canvas figures: ruled hyperbolic paraboloid (M1), hatching value scales (M2), seeded line-field generator (M9)
- Rhino 8 Python script for a printed line-field underlay (M9)
- Self-scoring rubric, capstone checklist, per-module progress (stored in `localStorage`, per browser)
- Light and dark themes

## Deploy (Cloudflare Pages)

```zsh
npx wrangler pages deploy . --project-name=drawing-like-lebbeus
```

Or connect this repo in the Cloudflare dashboard: framework preset `None`, build command empty, output directory `/`. `_headers` sets security headers and a 5-minute HTML cache.

## Images and copyright

The site reproduces none of Woods's drawings. Every example links to the museum or publication that holds it (SFMOMA, MoMA, Cooper Hewitt, Whitney, Getty, M+). His work remains under the copyright of his estate; the MIT license covers only this repo's code and text.

## Sources

Listed on the `#sources` sheet. Facts checked October 2026.

## License

[MIT](LICENSE)
