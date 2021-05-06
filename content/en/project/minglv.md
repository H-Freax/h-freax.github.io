---
title: 明律
summary: 基于大数据和人工智能技术的法律平台
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

- Project Description: A legal platform based on big data and artificial intelligence technology, serving legal practitioners and consultants, which can provide search services for documents, lawyers, law firms, and law articles, recommendation services for legal-related public opinion hotspots, intelligent error correction services for documents, early warning services for legal practitioners on legal public opinion, intelligent Q&A services for consultants on legal affairs, recommendation services for legal-related articles, involving public opinion analysis model, intelligent text error correction model, and legal intelligent question and answer system.

- Responsible part: Preliminary research and functional chunking, mainly involved in algorithm design in the project.
  - In the public opinion analysis model, we use python to write crawlers to crawl news from mainstream news websites, structure the text into Elasticsearch, use CNN to classify public opinion, select some texts with strong relevance to legal knowledge for further public opinion visualization, integrate the question data from the intelligent Q&A system for public opinion warning, and use it for the recommendation of legal knowledge. and the recommendation of relevant public opinion hotspots.
  - In the intelligent text error correction model, mainly applied to error correction of documents, the model is based on statistics and features for error correction, firstly pre-processing to remove noise, then completing word separation and lexical annotation, using forward sequence search algorithm for optimization, and vector compression based on clustering method, using Add-k smoothing algorithm for data smoothing, creating confusion set based on polyphonic words, homophones and other cases Sorting is performed, error correction is carried out, and the one with the highest score in the calculation result is used as the correct modification, so as to achieve the purpose of error checking and correction.
  - In the legal intelligent Q&A service, it is mainly divided into the case type classification module and the basic question Q&A module based on similarity matching. The case type classification module classifies the questions asked to give recommendations of relevant documents, lawyers, law firms and law articles, and the basic Q&A module performs short text similarity matching of questions based on the existing 20w Q&A dataset to realize intelligent Q&A of basic questions. The basic question and answer module is based on the existing 20w question and answer data set for short text similarity matching, thus realizing intelligent question and answer for basic questions.

- Completion: Completed the chunked implementation of basic functions and optimization of algorithms.
