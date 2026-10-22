# BioVault Saudi website — source of truth and change control

## Immutable business/design decisions
- Brand: approved emerald/silver BioVault mark. Do not redraw.
- Approved cinematic visual composition, Arabic/English language switch and existing interactive product experiences must remain.
- Four products: BalanceChain, Venture Sentinel, EndlessJob, Custom Software.
- Exactly **one visible film per product**, followed by its interactive experience.
- Viewer-initiated playback **with sound on**, optional mute. Never assume browsers permit audible autoplay.
- Do not make unverified customer, central-bank or regulatory approval claims. Demos use synthetic data; actual operational boundaries must be clear.

## Canonical version locations
- `site-v14/index.html` + `site-v14/assets/*.mp4`: complete V14 review site versioned in this repository. Assets must travel alongside HTML.
- `docs/V14_AUDIT.json`: reproducible file-level audit and known limitations.
- `preview/BioVault_Cinematic_V6_Offline.html`: LEGACY; do **not** deploy as the current website.
- Official deployed production `biovault-saudi-cinematic-preview.vercel.app`: preserved legacy original; do not overwrite without explicit approval.
- V14 review deployment: available via Vercel Review project's deployment URL; distinct project.

## Safe edit workflow
1. Start from `site-v14` (or later approved version), never from legacy V6.
2. Back up existing version; change only requested elements; keep every other section intact.
3. Create a new version branch or directory, update version changelog and audit.
4. Test on desktop and mobile: pages, film playback/audio/mute, switching projects, interactive flows, both languages, no horizontal overflow, network errors, accessibility and console errors.
5. Deploy to preview only. Get approval before changing official production URL.
6. Preserve rollback pointer to last tested READY deployment.

## Release checklist status
- Four MP4 assets and four stage targets: verified.
- Preview V14 built READY in Vercel; media V13 previously HTTP 200.
- CSS hidden duplicates in V14: code verified, visual test outstanding.
- Complete browser/device test: NOT YET VERIFIED.
- GitHub-to-Vercel deployment automation: NOT YET CONFIGURED.
