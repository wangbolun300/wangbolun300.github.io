# Bolun Wang's academic homepage

Personal academic website built with Hugo and the Hugo Blox Academic CV theme.

## Structure

- `content/_index.md`: homepage biography, featured publications, recent publications, and talks.
- `content/authors/admin/_index.md`: biography, affiliations, education, and profile links.
- `content/publication/<paper>/`: one page bundle per paper, containing `index.md`, optional `cite.bib`, and a `featured` image.
- `content/event/` and `content/teaching/`: talks and courses.
- `config/_default/`: site URL, appearance, navigation, and Hugo modules.
- `assets/`, `static/`, and `layouts/`: assets, downloadable files, and template overrides.
- `.github/workflows/publish.yaml`: build and deployment to GitHub Pages on pushes to `main`.

## Preview

Install Hugo **Extended 0.136.5** (the version used by GitHub Pages) and Go, then run:

```sh
hugo server
```

For a production build:

```sh
hugo --minify
```

The generated site is in `public/`. The GitHub Pages workflow also generates the Pagefind search index; to test search locally, install Node.js and run `npx pagefind --site public` after building.

## Add a publication

Create `content/publication/<paper>/index.md` with the title, authors, publication date, venue, and links. Use `admin` for Bolun Wang to link the author profile. Set `featured: true` to include the paper in the homepage's Featured Publications section. Add `cite.bib` for the citation download and a `featured.png` or `featured.jpg` for the card image.

The isotropic initialization paper uses the journal publication date (July 9, 2026), with metadata verified against [arXiv](https://arxiv.org/abs/2506.01726) and the [publisher](https://doi.org/10.1016/j.cagd.2026.102593). Its image is Figure 1 of the paper, credited in the page metadata.

The starter blog posts and sample software projects are kept as drafts. They do not appear in a normal production build; use `hugo server --buildDrafts` when editing them.

## Chinese edition

English URLs remain unchanged; the Chinese edition is served under `/zh/`.
Translated pages use Hugo's filename convention (`index.zh.md`, `_index.zh.md`, and `experience.zh.md`), sharing images and citation files with their English page bundles. When adding or updating a paper, update both language files; official titles, abstracts, and citation metadata remain in their original language.

Language configuration lives in `config/_default/languages.yaml`. The language switch links to the corresponding translated page. Hugo generates canonical URLs, alternate language links, and a sitemap index containing both language sitemaps. The homepage also supplies bilingual Person metadata to associate 王博伦 with Bolun Wang. Search indexing remains controlled by each search engine; the sitemap can be submitted through the site owner's search-console account.
