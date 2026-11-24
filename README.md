# PPOTN Sandbox (NON-PRODUCTION)

**This is a TEST copy of the PPOTN site — it is NOT the real ppotn.com.**

League members can use this sandbox to run test games, click around, and try the
pending Upload Results approval flow with zero risk to the real site or its data.

- Real site: https://ppotn.com (repo: `Robrasta/ppotn-dashboard`)
- This sandbox: repo `Robrasta/ppotn-sandbox`, served by GitHub Pages once enabled
  in Settings -> Pages (branch `main`, folder `/ (root)`).

## How it was seeded

- Site files copied from production `ppotn-dashboard` main @ 84a093fc (Nov 24, 2026 go-live).
- `data/manual_games.json` and `data/season.json` are COPIES as of Nov 24, 2026, kept only
  so the sandbox looks real. They are this repo's own test data: edits, test games, and the
  build workflow (`scripts/build.py`) here can never touch production data.
- No `CNAME` file: this repo does not claim the ppotn.com domain.
- The entry passphrase gate is the same mechanism (and same passphrase) as the real site.
- Binary files (photos in `photos/`, sound clips and chip images in `assets/`, docs in
  `docs/`) could not be copied through the connector and are not in this repo yet, so the
  photo gallery and champion sound clips will not load here until they are added
  (e.g. by uploading them through the GitHub web UI).

The red "TEST / SANDBOX" badge in the corner of the landing page marks this copy.
