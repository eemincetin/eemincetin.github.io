# eemincetin.github.io
infpgawetrust

## Add a new post

Create a markdown file in `_posts` named: `YYYY-MM-DD-title-with-dashes.md`

Front matter template:
```
---
layout: post
title: "Your Title"
date: YYYY-MM-DD HH:MM:SS +0000
categories: category1 category2
---

Write content here.
```

Example:
`_posts/2025-08-23-my-new-post.md`

Then rebuild locally:
```bash
bundle exec jekyll serve
```

Commit & push so GitHub Pages deploys.
