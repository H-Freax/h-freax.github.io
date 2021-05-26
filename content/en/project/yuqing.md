---
title: Public opinion analysis project based on Wenzhou News Network
summary: Public opinion analysis based on Wenzhou News Network
tags:
- public_opinion
date: "2019-01-01"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Acting as the project leader, independently developed and completed.

- Use python to write a crawler to crawl 100w+ news content of Wenzhou news network to deposit in ElasticSearch
- Based on tornado as the server, realize the sentiment analysis of news content based on sentiment dictionary
- Structured for a single piece of news, to realize the news content mapping
- TextRank4ZH is used to extract news topic words, and charts are used to show news topic hotness tracking
- Visualization of news content clustering by the word cloud
- Combine with maps to display news heat map for a certain time
