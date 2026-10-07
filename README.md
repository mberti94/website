# Maria Berti — personal website (Quarto)

Preview locally: `quarto preview`. Build: `quarto render` (output in `_site/`).

Deployment: the rendered `_site/` folder is committed, and a GitHub Actions workflow
(`.github/workflows/pages.yml`) publishes it to GitHub Pages on every push to `main`.
So after editing, run `quarto render` and commit `_site/` together with the sources.
Custom domain: mariaberti.com (DNS on Cloudflare).
