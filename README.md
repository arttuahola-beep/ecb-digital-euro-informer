# The ECB Digital Euro Informer

One key takeaway on the ECB digital euro, every weekday.

Takeaways are written by bot Lagarde. Not legal advice.

`posts/YYYY-MM-DD/post.md` is the source of truth. `scripts/build_site.py` regenerates the HTML and `posts/posts.json` from those files.

Weekday posts start on Monday 5 October 2026. Until the first `post.md` is added, the homepage and archive say so. That note is not a takeaway. Lagarde’s first real post becomes the first takeaway.

## Daily update

1. Add `posts/YYYY-MM-DD/post.md` with front matter and a body:

```markdown
---
date: YYYY-MM-DD
lens: Banks
headline: Headline of the takeaway
source: ""
---

Body of the takeaway, in markdown.
```

`lens` is the audience. Use one of:

- Banks
- Payment service providers
- Corporate treasurers

Leave `source` as `""` when there is no source. The body may use paragraphs, **bold**, *italic*, and [links](https://example.com).

2. Rebuild:

```bash
python3 scripts/build_site.py
```

3. Commit the new `post.md` and the generated files: `index.html`, `archive/index.html`, `posts/YYYY-MM-DD/index.html`, and `posts/posts.json`.

The first real takeaway is Monday 5 October 2026. Add `posts/2026-10-05/post.md`, run the build, and commit those files. The empty-state note then leaves the homepage and the archive.

Links are relative so the site works at `https://arttuahola-beep.github.io/ecb-digital-euro-informer/`.

## GitHub Pages

The site is published from the `main` branch, folder `/` (repository root). `.nojekyll` is included so GitHub Pages serves the generated HTML as static files.
