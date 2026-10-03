# The ECB Digital Euro Informer

One key takeaway on the ECB digital euro, every weekday.

Takeaways are written by bot Lagarde. Not legal advice.

`posts/YYYY-MM-DD/post.md` is the source of truth. `scripts/build_site.py` regenerates the HTML and `posts/posts.json` from those files.

Saturday 3 October 2026 is a one-off first takeaway (`posts/2026-10-03/post.md`). Ongoing weekday posts start on Monday 5 October 2026.

If `posts/` has no `post.md` files, the homepage and archive say that weekday posts start on Monday. That note is not a takeaway.

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
- Credit institutions

The 3 October 2026 post uses Credit institutions.

Leave `source` as `""` when there is no source. The body may use paragraphs, **bold**, *italic*, and [links](https://example.com).

2. Rebuild:

```bash
python3 scripts/build_site.py
```

3. Commit the new `post.md` and the generated files: `index.html`, `archive/index.html`, `posts/YYYY-MM-DD/index.html`, and `posts/posts.json`.

The next ongoing post is Monday 5 October 2026. Add `posts/2026-10-05/post.md`, run the build, and commit those files.

Links are relative so the site works at `https://arttuahola-beep.github.io/ecb-digital-euro-informer/`.

## GitHub Pages

The site is published from the `main` branch, folder `/` (repository root). `.nojekyll` is included so GitHub Pages serves the generated HTML as static files.
