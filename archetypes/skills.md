---
# Title of post
title: '{{ replace .File.ContentBaseName `-` ` ` | title }}'

# Date of post
date: {{ .Date }}

# Schedule page to be published on this date
publishDate: {{ .Date }}

# Optional: URL relating to the skill
external_link: https://example.com

# Tags (keywords) to help organize your content
tags:
  - tags
---

## '{{ replace .File.ContentBaseName `-` ` ` | title }}'

Write a short section here about the skill. 

- You can add the skill's **full text** or **supplementary notes** here.  
- You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
- You can also use [Hugo shortcodes](https://gohugo.io/content-management/shortcodes/)
