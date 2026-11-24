# How to use your site

## 1. Put it online (one time, about 10 minutes, free)

1. Make a free account at **github.com** (if you don't have one).
2. Click **+** (top right) → **New repository**.
   Name it **`yourusername.github.io`** (use your real GitHub username). Make it **Public**. Click **Create repository**.
3. On the new page, click **"uploading an existing file"**. Drag in **everything inside** the `rupa-blog` folder
   (the folders `_layouts`, `_posts`, `assets` and the files too). Click **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, branch **main**, folder **/ (root)**. Save.
5. Wait 1–2 minutes, then visit **https://yourusername.github.io**. That's your site!

## 2. Write a new post (from any browser, even your phone)

1. Open your repository on github.com and click the **`_posts`** folder.
2. Click **Add file → Create new file**.
3. Name the file with **today's date + a short title**, ending in `.md`, like:
   `2026-11-25-my-favourite-recipes.md`
4. Paste this at the top, then write below it:

```
---
title: "My favourite recipes"
tags: [food]
---

Write your post here. Leave a blank line between paragraphs.
```

5. Click **Commit changes**. About a minute later the post is on your site.

## Formatting cheat sheet

| You type | You get |
|---|---|
| `**bold**` | **bold** |
| `*italic*` | *italic* |
| `## A heading` | a section heading |
| `- item` | a bullet point |
| `[link text](https://example.com)` | a link |
| `> a quote` | a quote block |

**Pictures:** upload the image into the `assets` folder, then write `![description](/assets/photo.jpg)`.

## Changing things
- **Site name / tagline:** edit `_config.yml`.
- **About page:** edit `about.md`.
- **Edit or delete a post:** open it in `_posts`, click the pencil (edit) or the "…" menu (delete).
