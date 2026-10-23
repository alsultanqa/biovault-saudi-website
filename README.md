# BioVault Saudi - GitHub Pages Release

This is the clean, public-facing, static BioVault Software Solutions Saudi website.

## Publishing
- Configure Settings > Pages > Source: Deploy from a branch
- Branch: gh-pages / (root)
- GitHub Pages URL before domain: https://alsultanqa.github.io/biovault-saudi-website/
- Intended domain registrar: GoDaddy; domain not purchased or assigned yet.
- There is intentionally NO CNAME file until the exact purchased domain is confirmed.
- The HTML includes robots noindex,nofollow to avoid premature indexing. Remove the tag at launch.
- HTTPS can be enforced after GitHub configures the custom-domain certificate.

## GoDaddy connection after purchase
- In GitHub Pages Settings set the purchased custom domain (choose apex or www), verify domain ownership where prompted.
- For apex root, add A records (host @) pointing to the four GitHub Pages IPv4 addresses; confirm current values against official GitHub docs.
- For www, add CNAME www -> alsultanqa.github.io (not a project path).
- Remove any conflicting GoDaddy A/CNAME records. Retain email-related MX/TXT records unchanged.
- Allow DNS and TLS issuance to propagate. Verify www/root redirect, HTTPS, film and media.

## Site source and updates
Source of truth remains main/site-v14 in biovault-saudi-website repo, currently deployed on Vercel. The clean gh-pages branch is a publication snapshot; future approved changes should sync the static site here as part of the release process. This setup does not replace or interrupt existing Vercel hosting.
