# alu_web_development

Web development projects for the ALU curriculum.

## html_basic

Basic HTML structure, semantic tags, and page composition.

| File | Description |
| --- | --- |
| `base_index.html` | Minimal valid HTML5 skeleton (DOCTYPE, head, title, meta charset, body) |
| `index.html` | Homepage: headings, paragraphs, a clickable image, header/main/footer layout |
| `tweets.html` | Tweets page: embedded tweet, cross-links, same header/main/footer layout |

### Structure

Both `index.html` and `tweets.html` share a common layout:

- `<header>` — site navigation (`<ul>`/`<li>` links to every page)
- `<main>` — `<article>` (page content) followed by `<aside>` (placeholder for comments)
- `<footer>` — attribution line

## css_basic

Styling the html_basic pages with CSS: a reset/foundation stylesheet
(`base.css`), a Flexbox-based page layout, responsive behavior on
smaller screens, and custom visual styling.

| File | Description |
| --- | --- |
| `base.css` | Reset and foundational styles (box-sizing, fonts, links, lists) |
| `styles.css` | Flexbox layout (header/main/footer, article 2/3 + aside 1/3), responsive rule for `.works_on_smartphone`, and custom colors/typography |
| `index.html` | Homepage, now linked to both stylesheets, viewport meta tag added, `works_on_smartphone` class on `<body>` |
| `tweets.html` | Tweets page, linked to both stylesheets |
