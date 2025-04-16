---
# Title of the publication
title: '{{ replace .File.ContentBaseName `-` ` ` | title }}'

# Author usernames from `content/authors/`, e.g. `admin` or `your-username`
authors:
    - admin

# Optional author notes (e.g., equal contribution)
author_notes:
#   - "Equal contribution"
#   - "Equal contribution"

# Date of publication
date: {{ .Date }}

# Draft
draft: true

# Schedule page to be published on this date
publishDate: {{ .Date }}

# DOI for the publication (if any)
doi: ""

# Publication type (see https://github.com/citation-style-language/schema/blob/master/schemas/styles/csl-types.rnc)
publication_types: ['']

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

# Full abstract of the publication
abstract: >
    Write abstract here.

# Optional short summary of the publication
summary: >
    Write a concise summary here (1–3 sentences).

# Tags (keywords) to help organize your content
tags: 
    - Tags

# Display this page in the Featured widget?
featured: false

# Links to various formats and resources
# Custom links example
links:
# - name: Custom Link
#   url: http://example.org
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image settings
# Add `featured.jpg` or `featured.png` in the same folder as this pages folder
image:
    caption: 'Image credit: [**Source Name**](https://example.com)'
    focal_point: ""
    preview_only: false

# Associated Projects (optional).
# E.g. `internal-project` references `content/project/internal-project/index.md`.
# Otherwise, set `projects: []`.
projects: []

# Associated slide deck (without extension), e.g., `example` matches `content/slides/example/index.md`
slides: example
---

# {{ replace .File.ContentBaseName `-` ` ` | title }}
- You can add the publication's **full text** or **supplementary notes** here.  
- You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
- You can also use [Hugo shortcodes](https://gohugo.io/content-management/shortcodes/)
