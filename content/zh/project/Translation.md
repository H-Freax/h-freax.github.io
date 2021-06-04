---
title: 百时美施贵宝 - 分子翻译 (Kaggle 88/874, top11\%)
summary: 将化学分子式图像转换回作为InChI文本注释的基础化学结构
tags:
- cv_program
date: "2021-04-01"

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
独立开发完成。

- 将图像转换回作为InChI文本注释的基础化学结构
- 使用Resnet101d作为编码器，Transformer作为解码器，以及Ranger 作为优化器。
- 验证集的损失率为0.8%，平均编辑距离为6，测试集的平均编辑距离为2.5。
在测试集上的平均编辑距离是2.13
