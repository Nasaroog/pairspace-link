# pairspace-link

A stable address for PairSpace.

- `index.html` (GitHub Pages) reads `current.json` and forwards the visitor to the current server address.
- `current.json` currently points at the Render deployment (`https://pairspace-gaqp.onrender.com`). It used to be rewritten by `scripts/start-public.ps1` of the PairSpace repository (home PC behind a temporary Cloudflare tunnel); running that script again would overwrite it.

It contains nothing but the public address of the site. Delete the repository to remove the link.
