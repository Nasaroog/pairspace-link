# pairspace-link

A stable address for a PairSpace server that runs on a home PC behind a temporary Cloudflare tunnel.

- `index.html` (GitHub Pages) reads `current.json` and forwards the visitor to the current tunnel address.
- `current.json` is rewritten by `scripts/start-public.ps1` of the PairSpace repository every time the server starts or stops.

It contains nothing but the current public address of the site. Delete the repository to remove the link.
