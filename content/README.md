# Markdown content copies

This folder holds Markdown reference and editing copies of the homepage and essays. The published website uses the HTML files in the repository root and in `writing/`.

There is no Markdown-to-HTML conversion script or workflow in this repository. Editing a file here does not update its corresponding public page automatically. These copies can differ from the published HTML, including image references; treat the HTML as the source of truth for what visitors see.

## Where to make website edits

- Homepage: edit `index.html` in the repository root; `content/homepage.md` is its Markdown copy.
- Essays: edit `writing/<slug>/index.html`; a corresponding Markdown copy, when present, is in `content/articles/`. Use its frontmatter `slug` to identify the published page, rather than its numbered filename.
- Writing index: edit `writing.html` in the repository root.
- Links page: edit `links.html` in the repository root.
- Styling: edit `style.css` in the repository root.

When changing homepage or essay text, update the corresponding Markdown copy as well if one exists. If drafting in Markdown first, apply the finished changes to the HTML before publishing. Do not assume every published essay has a Markdown copy.

GitHub Pages publishes from the root of the `main` branch. Commit and push the HTML changes to update the website.
