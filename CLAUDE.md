# Claude Instructions — yixinhuang48.github.io

Personal academic website for Yixin Huang. Plain HTML/CSS/JS, no build step, deployed via GitHub Pages.

## Key files

- `index.html` — single-page site with sections: About, Projects, Visitors, Blog, Announcements, Contact
- `style.css` — primary stylesheet (use this for new styles)
- `styles.css` — secondary stylesheet (legacy, avoid adding to it)
- `script.js` — nav toggle and scroll behavior
- `blog/` — individual blog post HTML files
- `yixin_resume.pdf` — current resume

## Style conventions

- Font: Space Grotesk (body), JetBrains Mono (code/accents)
- Colors: defined as CSS variables in `style.css` — always use variables, never hardcode hex values
- Blog links are styled pink; use the `.blog-link` class
- Key phrases in blog posts use `<strong>` or a highlight span — check existing posts for the pattern
- Keep cards consistent: blog cards use `.blog-card`, announcement cards use `.announcement-card`

## Content rules

- Do not add placeholder or "Coming soon" cards — only add real content
- Announcements mirror blog posts: whenever a blog post is added, add a matching announcement card
- Resume updates: replace `yixin_resume.pdf` only, do not rename the file (links throughout the page reference it)
- Keep the `<title>` and `<meta name="description">` in `index.html` in sync with actual current role/focus

## Git

- Commit directly to `main` — no branching needed for this personal site
- Commit messages should be short and descriptive (e.g. "Add blog post on inference stacks")
- History has been squashed; keep commits clean going forward
