# ThoughtfullyRups

**Little Things Worth Knowing by Rups**: a personal blog by Rupa for notes, ideas and useful finds, written down to share.

The site is built with [Jekyll](https://jekyllrb.com/) and published with GitHub Pages.

## What's here

The site files live at the root of this repository (the original upload is also kept in `rupa-blog.zip`):

| Path | What it does |
|---|---|
| `_config.yml` | Site title, tagline, author, and `baseurl` (`/ThoughtfullyRups`) |
| `_layouts/default.html` | Shared page frame: header, navigation (Home · Posts · About), footer |
| `_layouts/post.html` | Layout for a single post: date, tags, title and body |
| `_posts/` | Blog posts as Markdown files named `YYYY-MM-DD-title.md` |
| `index.html` | Home page showing the 5 latest posts |
| `posts.html` | Archive of all posts, grouped by year |
| `about.md` | About page |
| `assets/style.css` | Site styling (Fraunces + Inter fonts, warm cream palette) |
| `HOW-TO-POST.md` | Step-by-step guide to writing and publishing posts |

## Publishing the site

1. In **Settings → Pages**, choose **Deploy from a branch**, branch **main**, folder **/ (root)**.
2. After a minute or two the site will be live at
   **https://rupalidkulkarni.github.io/ThoughtfullyRups/**

## Writing a post

Add a new file to `_posts/` named with the date and a short title, for example `2026-11-25-my-favourite-recipes.md`, starting with:

```markdown
---
title: "My favourite recipes"
tags: [food]
---

Write your post here.
```

Commit it, and the post appears on the site about a minute later. See `HOW-TO-POST.md` for a formatting cheat sheet.

## Previewing locally (optional)

```bash
gem install bundler jekyll
jekyll serve
```

Then open http://localhost:4000/ThoughtfullyRups/.
