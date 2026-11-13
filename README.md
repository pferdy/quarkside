# quarkside

Quarks combine to make matter; ideas combine to make systems.

Static blog built with Jekyll, hosted free on GitHub Pages.

## Structure

- `_posts/` — 245 posts imported from lenand.wordpress.com (2010–2015), dates, categories, and tags preserved
- `index.html` — home page, the New section: posts from 2026 onwards
- `archive.html` — the archive: compact index of the imported posts grouped by year
- `search.html` and `search.json` — client-side search over every post
- `_layouts/` — page templates (default, post, page)
- `about.md` — the About page
- `assets/css/main.css` — styling
- `_config.yml` — site configuration, including `baseurl: /quarkside`

## Enable the site

1. Push all files to the main branch of this repository.
2. Repository Settings → Pages → Source: Deploy from a branch → Branch: main, folder / (root).
3. The site goes live at https://pferdy.github.io/quarkside/

## Custom domain

Add a `CNAME` file containing `quarkside.co.uk`, then set DNS at the registrar (34SP.com) and set the custom domain in the repository Pages settings. Remove `baseurl: /quarkside` from `_config.yml` once the domain is attached.

## Images

Post images are currently referenced from lenand.wordpress.com. A full media archive exists; to self-host, upload it under `assets/images/` and update image paths in the posts.

## Writing a new post

Create a file in `_posts/` named `YYYY-MM-DD-your-title.md` with this header:

    ---
    title: "Your title"
    layout: post
    categories: [Governance]
    tags: [Tag1, Tag2]
    ---

    Your text here.

New posts dated 2026 or later appear on the home page; older posts belong to the archive.
