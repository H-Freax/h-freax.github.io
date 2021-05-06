---
title: 基于lending club的数据分析实战项目
summary: 基于lending club的数据分析
tags:
- open_source
date: "2021-04-27"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
url_code: "https://github.com/H-Freax/lendingclub_analyse"
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
该项目为独立完成的个人开源项目

- 项目描述：该项目基于lending club数据集，通过对使用机器学习以及深度学习的方法，探索如何提高预测是否给予贷款的准确率。

- 负责部分：独立完成。该项目基于lending club数据集，采用lightgbm作为baseline，预测是否给出贷款。基于CatBoostEncoder、聚类、指数性区划分以及业务逻辑分析，分析出了四组衍生变量用于提升效果，随后采用多种机器学习方法进行预测，通过投票融合及Stacking的堆叠与混合进行集成，将准确率提高了0.2%，随后采用DNN方法，尝试使用SGD和Adam优化器进行模型训练进行了准确度的优化，效果仍欠佳，采用Tabnet进行尝试，效果欠佳，使用Stacking堆叠集成机器学习方法与DNN方法后准确度上升了0.3%

- 完成情况：已开源
