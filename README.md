# The VerseNet — theversenet.com

A living map of relational intelligence: the concepts, people, experiments and artefacts of the field, and how they relate.

Live at https://theversenet.com/ — served by GitHub Pages from this repository (`main` / root), DNS at Cloudflare, HTTPS enforced.

Static site — no build step. `index.html` + `support.js` (runtime) + `style.css` and the self-hosted fonts beside it (verse-ality brand) + `lexicon-data.json` (parsed from TheNovacene/verse-al-lexicon).

## Updating the site

Edit, commit and push to `main`; Pages redeploys within a minute or two. The `CNAME` file holds the custom domain and must stay.

Three places describe the field and should agree:

- the map data in `index.html` (`NODES`, `EDGES` and the lists of surfaces)
- the `<noscript>` block in `index.html`, which is what crawlers without JavaScript see
- `llms.txt`, the welcome for AI agents

## Updating the lexicon

`lexicon-data.json` is generated from the entries in TheNovacene/verse-al-lexicon. When the lexicon grows, regenerate it in the design project and re-commit.

## Podcast

`podcast.xml` is the feed for *The Novacene: Deep Dives*, with `podcast-cover.jpg` as its artwork. Add an episode by adding an `<item>` to the feed.

Provenance: human-directed model collaboration. Held by Kirstin Stevens. Not generated alone.
