---
title: Ming Law
summary: A legal platform based on big data and artificial intelligence technology to serve legal practitioners and consultants
tags:
- nlp_program
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
Act as the overall project manager

- Project Description: A legal platform based on big data and artificial intelligence technology to serve legal practitioners and consultants. The platform can provide search services for documents, lawyers, law firms, and law articles, recommendation services for legal-related opinion hotspots, intelligent error correction services for records, legal opinion warning services for legal practitioners, legal intelligent Q&A services for consultants, and recommendation services for legal-related articles.
- Responsible part: responsible for the preparation of public opinion analysis model, intelligent text error correction model, and legal affairs intelligent Q&A model.
  - Public opinion analysis model: crawl news from mainstream news websites, pre-process and structured into Elasticsearch, use CNN for classification with accuracy over 93%, select texts with solid relevance to legal knowledge and integrate Echart for visualization, integrate question data from intelligent Q&A system for public opinion early warning, the model is used for recommendation of legal expertise and related public opinion Hotspot recommendation.
  - Intelligent text error correction model: mainly applied to error correction of documents, this model is based on statistics and features for error correction, first pre-processing to remove noise, establishing N-gram model, using forward sequence search algorithm for optimization, using the method of clustering for vector compression, using Add-k smoothing algorithm for data smoothing, showing confusion set for sorting based on polyphonic words, homophones, etc., with The highest score in the calculation result is taken as the correct modification, to achieve the purpose of error detection and correction, and the model is evaluated in an extensive legal literature database.
  - Legal intelligent Q & A service: mainly divided into case type classification module and essential question Q & A module based on similarity matching. The case type classification module classifies questions by asking questions to give recommendations of relevant instruments, lawyers, law firms, and law articles, and the essential Q & A module performs short text similarity matching of questions based on the existing 20W Q & A dataset to realize intelligent Q & A of basic questions.
