---
title: 下一代低延迟拥塞控制
summary: 从 BBR 平稳过渡到 CUBIC
tags:
- network_protocols
date: "2020-06-05"

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
Advised by [Prof. Ben Leong](https://www.comp.nus.edu.sg/~bleong/)

- Our results suggest that CUBIC is currently the dominant TCP variant on the Internet, and it is deployed on about 36% of the websites in the Alexa Top 20,000 list. While BBR and its variant BBR G1.1 are currently in second place with a 22% share by website count, their present share of total Internet traffic volume is estimated to be larger than 40%. (*The Great Internet TCP Congestion Control Census*)
    - see talk: https://youtu.be/oImBLTue6So
- We have seen in recent times the emergence of a large number of low-latency TCP variants to address the poor latency performance of traditional loss-based TCP variants like CUBIC. But they will cause performance degradation to competing CUBIC flows (*Towards A Low-Latency Future Internet*)
