# hermestheme

HERMES theme picture overview — brand-kit visual reference for USAREUR-AF Operational Data Team.

Live: https://usareur-af-odt.github.io/hermestheme/

Standalone single-page snapshot of the HERMES dark theme (void / cyan / pink / coral / plum / acid-green) used by HERMES Workshop modules and the HERMES splash custom widget. Shows core palette, surface stack, type ramp, in-situ components, and all four HERMES variants (canon / light / mono / toxic).

Source token file: `dist/hermes.css` (generated from `tokens/themes/hermes.json` in the main brand-kit repo by `scripts/build-tokens.ts`).

## Local preview

```bash
xdg-open index.html
```

Or serve over HTTP:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/
```

## Updating

This is a published snapshot, not the canonical source. Edits flow:

1. Update tokens in `~/projects/odt/brand-kit/tokens/themes/hermes.json`
2. Regenerate with `npx tsx scripts/build-tokens.ts`
3. Copy the refreshed `dist/hermes.css` here, push, GitHub Pages redeploys.
