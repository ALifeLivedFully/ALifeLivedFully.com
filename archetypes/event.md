---
# The title of the event/talk.
title: '{{ replace .File.ContentBaseName `-` ` ` | title }}'

# The name of the event or conference.
event: ""

# Optional: URL to the event's official page.
event_url: ""

# Location name or venue.
location: 

# Full address for event location (used for maps or details).
address:
  street: ""
  city: ""
  region: ""
  postcode: ''
  country: ""

# A short summary shown in listings.
summary: |
    Summary here.

# A more detailed description used in the full page.
abstract: |
    More detailed description here.

# Start date and time of the event. `.Date` uses the date from `hugo new`.
date: {{ .Date }}

# End date and time of the event. Can be left blank or commented out.
date_end: ''

# Is the event an all-day event? Set to true or false.
all_day: false

# Date the event page is published. Default to now.
publishDate: {{ .Date }}

# List of authors — use matching folder names in `content/authors/`.
authors:
  - admin

# Optional tags for categorization or filtering.
tags: []

# Feature this talk on home or other key pages.
featured: false

# Event image settings.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: ""    # Options: Smart, Center, TopLeft, BottomRight, etc.

# Optional social or external links.
# Uncomment and customize as needed.
# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/yourhandle

# Optional links to related resources.
url_code: ""       # Link to source code repo (e.g., GitHub).
url_pdf: ""        # Link to PDF version of presentation.
url_slides: ""     # Link to slides (e.g., on SlideShare).
url_video: ""      # Link to a video (e.g., YouTube or Vimeo).

# Use this to link to internal Markdown slide deck (omit file extension).
# E.g. `slides: "example-slides"` references `content/slides/example-slides.md`.
slides: ""

# Link this talk to one or more internal projects by folder or filename (no extension).
projects: [""]
---

# {{ replace .File.ContentBaseName `-` ` ` | title }}
- You can add the publication's **full text** or **supplementary notes** here.  
- You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
- You can also use [Hugo shortcodes](https://gohugo.io/content-management/shortcodes/)
