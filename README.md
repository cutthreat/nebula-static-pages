# Nebula Static Pages

Public static export of the currently built NEBULA pages and review surfaces.

## Entry points

- `index.html` - page index
- `home.html` - home page
- `psychic-reading-new.html` - product page
- `tarot-reading-new.html` - product page
- `palm-reading-new.html` - product page
- `phone-psychic-new.html` - product page
- `cheap-psychic-new.html` - product page

The package is intended for public preview via GitHub Pages.

## Local quality gate

Run the deterministic PR gate locally with:

```powershell
pwsh -NoProfile -ExecutionPolicy Bypass -File .github\scripts\quality-gate.ps1 -Phase all
```

## GitHub review flow

- Deterministic merge protection stays on `quality-gate`.
- Included Codex review can be requested on a PR with `@codex review`.
