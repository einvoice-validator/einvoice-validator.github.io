# einvoice-validator.github.io

The website of [einvoice-validator](https://github.com/einvoice-validator/einvoice-validator): https://einvoice-validator.github.io/

**[Website](https://einvoice-validator.github.io/)** · [Repository](https://github.com/einvoice-validator/einvoice-validator) · [Issues and roadmap](https://github.com/einvoice-validator/einvoice-validator/issues) · [Build and test](https://einvoice-validator.github.io/docs.html)

Plain HTML and CSS, no build step, no JavaScript, no external fonts or trackers: `index.html` (the one-pager), `docs.html` (building and testing), `style.css` (light and dark themes, following the system setting), `favicon.svg`. GitHub Pages serves `main` as is (`.nojekyll`: no Jekyll processing).

`scripts/privacy-guard.sh` and `.githooks/` check every commit and push of this public repository for private references; enable the hooks after cloning with `git config core.hooksPath .githooks`. CI runs the same check (`.github/workflows/privacy.yml`).

MIT licensed, see [LICENSE](LICENSE).
