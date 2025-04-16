---
# The title of the subject being taught
title: Learn '{{ replace .File.ContentBaseName `-` ` ` | title }}'

# A short summary shown in listings.
summary: |
    Summary here.

# Date of post
date: {{ .Date }}

# Date the event page is published. Default to now.
publishDate: {{ .Date }}

type: docs
math: false

# Optional tags for categorization or filtering.
tags:
  - JavaScript

# Event image settings.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: ""    # Options: Smart, Center, TopLeft, BottomRight, etc.
---

# {{ replace .File.ContentBaseName `-` ` ` | title }}
- You can add the Education's **full text** or **supplementary notes** here.  
- You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
- You can also use [Hugo shortcodes](https://gohugo.io/content-management/shortcodes/)


## Test students

Provide a simple yet fun self-assessment by revealing the solutions to challenges with the `spoiler` shortcode:

```markdown
{{</* spoiler text="👉 Click to view the solution" */>}}
You found me!
{{</* /spoiler */>}}
```

renders as

{{< spoiler text="👉 Click to view the solution" >}} You found me 🎉 {{< /spoiler >}}