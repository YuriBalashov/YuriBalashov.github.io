# yuribalashov.github.io

Personal website of Yuri Balashov, built with [Jekyll](https://jekyllrb.com/) and the built-in `minima` theme, hosted on GitHub Pages.

## How this site works

- Every `.md` file in the root is a page. The menu is defined by `header_pages` in `_config.yml`.
- Pages are plain Markdown with a small "front matter" block (the part between `---` lines) at the top

## Common tasks (all via the GitHub web interface)

- **Edit a page:** open the `.md` file → click the pencil icon → edit → "Commit changes".
- **Add a news item:** edit `index.md`, add a bullet under "News".
- **Add a publication:** edit `publications.md`, add a bullet.
- **Upload your CV:** go to the `assets/pdf/` folder → "Add file" → "Upload files" → upload your PDF named `balashov-cv.pdf`.
- **Add a photo:** go to the `assets/` folder → upload a square-ish photo named `photo.jpg` (it is referenced in `index.md`). If you skip this, just delete the `<img ...>` line at the top of `index.md`.
- **Add a new page:** "Add file" → "Create new file" → name it e.g. `projects.md`, copy the front-matter block from another page, then add `- projects.md` to `header_pages` in `_config.yml`.
