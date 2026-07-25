# The VerseNet — theversenet.com

A living map of relational intelligence. Built to replace the previous theversenet.com site.

Static site — no build step. `index.html` + `support.js` (runtime) + `style.css`/`fonts/` (verse-ality brand) + `lexicon-data.json` (parsed from TheNovacene/verse-al-lexicon).

## Deploy

1. Create the repo: github.com/new → owner **TheNovacene**, name `versenet-site`, public.
2. Push these files to `main` (or drag-drop upload them on github.com in "uploading an existing file").
3. **Cloudflare Pages**: dash.cloudflare.com → Workers & Pages → Create → Pages → Connect to Git → pick `versenet-site` → no build command, output dir `/` → Deploy.
4. Once the domain moves to Cloudflare: Pages project → Custom domains → add `theversenet.com` (and `www`).

(GitHub Pages works too: repo Settings → Pages → deploy from `main` / root.)

## Updating the lexicon

`lexicon-data.json` is generated from the entries in TheNovacene/verse-al-lexicon. When the lexicon grows, regenerate it in the design project and re-commit.

Provenance: human-directed model collaboration. Held by Kirstin Stevens. Not generated alone.
