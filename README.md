# Branch Pilot — documentation

Source of https://docs.branchpilot.ai, built and hosted by [Mintlify](https://mintlify.com). Every push to `main` deploys.

- `docs.json` — site configuration (navigation, languages, theme).
- `en/` and `fr/` — guides in English (source of truth) and French.
- `openapi.yaml` — the API specification; endpoint pages are generated from it.

```bash
npm i -g mint
mint dev        # http://localhost:3000
mint validate   # strict build check
```
