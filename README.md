# Mapping with Kids

The website for Mapping with Kids courses, built with
[MkDocs](https://www.mkdocs.org/) and the
[Material](https://squidfunk.github.io/mkdocs-material/) theme.

**Live site:** https://soniadas123.github.io/mapping-with-kids/

The site describes the courses. The teaching materials (tutorials, slides and
data) are kept in a separate private repository.

## What's here

- `mkdocs.yml`: site settings and the navigation menu.
- `docs/index.md`: the home page.
- `docs/courses/`: one page per course.
- `docs/activities/`: one page per single-session activity.
- `docs/images/`: pictures used on the pages.
- `docs/stylesheets/extra.css`: small style tweaks.

## Build and preview

Use the `mapping_kids` conda env (`pip install mkdocs-material` once).

```
conda activate mapping_kids
mkdocs serve
```

Open http://127.0.0.1:8000/mapping-with-kids/ to preview. The page reloads
when you save a file.

## Publish

```
mkdocs gh-deploy
```

This builds the site and pushes it to the `gh-pages` branch, which GitHub Pages
serves.
