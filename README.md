# Of Course It Went Wrong (GitHub Pages starter)

This is a GitHub Pages / Jekyll starter for publishing chapters as you write them.

## Structure

- `index.md` landing page
- `categories.md` category index (auto-generated from chapter metadata)
- `chapters.md` full chapter list
- `_chapters/` chapter content (Markdown), published at `/chapters/<slug>/`
- `_layouts/` templates

## Add a new chapter

1. Copy `_chapters/000-chapter-template.md`
2. Rename it, e.g. `_chapters/002-fear-masquerades-as-prudence.md`
3. Update the front matter at the top:
   - `title`
   - `slug`
   - `category`
   - `order` (used for sorting)
   - `status` (draft/revised/final)
   - `date`

## Publish on GitHub Pages

1. Create a new repo on GitHub (public is simplest)
2. Upload these files
3. Repo Settings -> Pages
4. Build and deployment:
   - Source: Deploy from a branch
   - Branch: `main` (or `master`), folder `/ (root)`

GitHub Pages will build Jekyll automatically.

## Optional: run locally

You need Ruby installed.

```bash
bundle install
bundle exec jekyll serve
```

Then open: http://127.0.0.1:4000
