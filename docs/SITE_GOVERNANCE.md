# BioVault Saudi website — canonical production and governance

## Approved publishing architecture (2026-10-23)
- **Live company domain:** https://biovaultsa.com (also www).
- **Hosting platform:** GitHub Pages in repository `alsultanqa/biovault-saudi-website`, branch `gh-pages`, folder `/(root)`.
- **GitHub Pages custom-domain file:** `gh-pages/CNAME`, contents exactly `biovaultsa.com`.
- **Canonical editable source:** `main/site-v14/index.html` plus `main/site-v14/assets/`.
- **Current published source:** `gh-pages/index.html` plus `gh-pages/assets/`.
- These copies must remain in sync. Until automation is configured and tested, update *both* branches for every approved public release. GitHub Pages consumes `gh-pages`, **not** the `main` copy.
- Vercel is legacy only and should not be used for this domain or future user-approved releases. Do not reconfigure the DNS or alter email MX/TXT records unnecessarily.

## Non-negotiable content and experience decisions
- Keep the approved emerald/silver BioVault branding and cinematic design; never replace logo or visual identity.
- Preserve the first solution-selection menu **exactly as approved**.
- Four current solutions: BalanceChain, Venture Sentinel, EndlessJob, Custom Software; add more via the existing approved selector as business evolves.
- Inside each project: user-controlled Previous, Next, Replay, and Explore All controls. **No automatic jump to the next project**.
- Exactly one visible film per project, followed by its interactive experience.
- User-triggered video plays with sound, with a visible mute option; browsers may block unrequested audible autoplay.
- Keep the 30-second company brand film and source assets alongside the page.
- Public inboxes: `info@biovaultsa.com` and `partners@biovaultsa.com`.
- Public footer: © BioVault Software Solutions; all rights reserved in English and Arabic.
- Do not label the public website PRIVATE CONCEPT, PRIVATE PREVIEW, or similar.
- Synthetic/fictional showcase disclosures are required; no unsupported claims of real customer integration or regulatory approval.

## Verification protocol
1. Review the exact current `main/site-v14/` content before editing.
2. Protect all unrelated UI, email links, videos, language switch and interactive demos.
3. Confirm updated HTML and required assets in both `main/site-v14/` and `gh-pages/`; preserve CNAME.
4. Verify rendered website and controls on both desktop and mobile when capable; don't claim browser tests if not done.
5. Check Pages deployment and domain availability where the integration permits it. State honestly when end-to-end public-site verification cannot be completed.
6. Keep a rollback point using Git commits. Public branch production changes need explicit approval.

## Historic records
- `docs/V14_AUDIT.json` is a file-level audit made before current domain launch.
- `preview/BioVault_Cinematic_V6_Offline.html` is a legacy prototype; never deploy.
- Prior Vercel launch records are historical, **not** current infrastructure instructions.
