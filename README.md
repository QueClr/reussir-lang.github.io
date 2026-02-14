# reussir-lang.github.io

Technical website for Reussir.

## Local development

```bash
trunk serve --address 127.0.0.1 --port 8080
```

## GitHub Pages deployment

This repo uses `.github/workflows/pages.yml` to:

1. build the site with Trunk (`trunk build --release`)
2. upload `dist/` as Pages artifact
3. deploy via `actions/deploy-pages`

For organization root site hosting, the repository name must be:

`reussir-lang.github.io`
