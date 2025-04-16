---
# Title of post
title: '{{ replace .File.ContentBaseName `-` ` ` | title }}'

# Summary of post
summary: Embed videos, podcasts, code, LaTeX math, and even test students!

# Date of post
date: 2023-10-24

# Schedule page to be published on this date
publishDate: {{ .Date }}

# Draft
draft: true

# Enable math?
math: true

# Author usernames from `content/authors/`, e.g. `admin` or `your-username`
authors:
  - admin

# Tags (keywords) to help organize your content
tags:
  - tags

# Featured image settings
# Add `featured.jpg` or `featured.png` in the same folder as this pages folder
image:
    caption: 'Image credit: [**Source Name**](https://example.com)'
    focal_point: ""
    preview_only: false
---

# {{ replace .File.ContentBaseName `-` ` ` | title }}
- You can add the post's **full text** or **supplementary notes** here.  
- You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
- You can also use [Hugo shortcodes](https://gohugo.io/content-management/shortcodes/)