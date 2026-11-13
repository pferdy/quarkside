# quarkside

Quarks are elementary particles. Ideas for composing social benefits. QUARKSIDEas

Static blog built with Jekyll, hosted free on GitHub Pages.

## Structure

- `_posts/` — 245 posts imported from lenand.wordpress.com (2010–2015), dates, categories, and tags preserved
- `_layouts/` — page templates (default, post, page)
- `index.html` — home page, all posts listed newest first
- `tags.html` — tag index at /tags/
- `about.md` — the About page
- `assets/css/main.css` — styling
- `_config.yml` — site configuration, including `baseurl: /quarkside`

## Enable the site

1. Push all files to the main branch of this repository (replace the README or keep it, the `exclude` setting stops Jekyll rendering it).
2. Repository Settings → Pages → Source: Deploy from a branch → Branch: main, folder / (root).
3. The site goes live at https://pferdy.github.io/quarkside/

## Custom domain

Add a `CNAME` file containing `quarkside.co.uk`, then set a CNAME record for quarkside.co.uk pointing at pferdy.github.io at the domain registrar, and set the custom domain in the repository Pages settings. Remove `baseurl: /quarkside` from `_config.yml` once the domain is attached.

## Images

Posts reference images still hosted at lenand.wordpress.com. If that WordPress site is ever deleted, download its media library (Tools → Export includes the media URL list) and store copies under `assets/images/`, then update the image paths in the posts.

## Writing a new post

Create a file in `_posts/` named `YYYY-MM-DD-your-title.md` with this header:

    ---
    title: "Your title"
    layout: post
    categories: [Governance]
    tags: [Tag1, Tag2]
    ---

    Your text here.
