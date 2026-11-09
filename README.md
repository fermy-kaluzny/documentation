# documentation

Static legal documents of FERMY KALUZNY SP. Z O.O., published with GitHub Pages.

Live site: <https://fermy-kaluzny.github.io/documentation/>

| Page | File |
| --- | --- |
| Index | `index.html` |
| Privacy Policy | `privacy.html` |
| User Agreement | `terms.html` |

Styling is shared via `styles.css`; every page carries the same top bar linking
the documents. The documents link to each other by their absolute GitHub Pages
URLs, so keep those in sync if the repository is renamed or moved.

## Deployment

`.github/workflows/deploy-pages.yml` publishes the repository root to GitHub
Pages on every push to `main` (and on manual `workflow_dispatch`).

Pages must use GitHub Actions as its source: **Settings → Pages → Build and
deployment → Source: GitHub Actions**.

## Local preview

```sh
python3 -m http.server 8000
# open http://localhost:8000/
```
