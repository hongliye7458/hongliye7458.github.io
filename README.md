# Hongli Ye — personal website

A customized Minimal Mistakes 4.28.1 academic homepage, published with GitHub Pages.

## Update content

- `index.md`: homepage introduction
- `about.md`: biography
- `courses.md`: course notes and upload status
- `_data/seminars.yml`: seminar entries (also shown on the homepage)
- `_posts/`: original blog articles
- `assets/pdf/`: downloadable notes and CV
- `assets/css/main.scss`: colors, typography, and responsive layout
- `_includes/author-profile.html`: sidebar profile

The existing PDF and blog URLs are preserved. The original `my-photo.jpg` is an empty placeholder, so the sidebar uses a typographic monogram instead.

## Preview

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve
```

GitHub Pages builds from the existing branch configuration. No external account or paid hosting is required. Theme: https://github.com/mmistakes/minimal-mistakes (MIT).
