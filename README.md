# Stock Analyser Blueprint Site

This repository includes a static site for the institutional-grade AI stock predictor blueprint.

## Access locally

From the repository root, run:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Then open:

- `http://127.0.0.1:8000/`

## Access on GitHub Pages

This repo now includes:

- `docs/index.html` (GitHub Pages entrypoint)
- `docs/styles.css`
- `docs/INSTITUTIONAL_AI_STOCK_PREDICTOR_BLUEPRINT.md`
- `.github/workflows/deploy-pages.yml` (deploys `docs/` to Pages on pushes to `main`)

After merging to `main`, enable **Settings → Pages → Build and deployment → GitHub Actions**.

Your URL will typically be:

- `https://<username>.github.io/<repository>/`

## If you still see 404

- Confirm the branch with site files is merged to `main`.
- Confirm Pages source is set to **GitHub Actions**.
- Wait 1–3 minutes for first deployment to finish.
- Check the **Actions** tab for workflow failures.

## Files in repository root

- `index.html` — local/static entry page.
- `styles.css` — local/static styling.
- `INSTITUTIONAL_AI_STOCK_PREDICTOR_BLUEPRINT.md` — full technical blueprint.
