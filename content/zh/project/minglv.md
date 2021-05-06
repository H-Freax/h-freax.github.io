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
担任项目总负责
项目描述：基于大数据和人工智能技术的法律平台，服务于法律从业人员及咨询方，该平台可提供文书、律师、律所、法条的搜索服务，法务相关舆情热点推荐服务，文书智能纠错服务，为法律从业者提供法务舆情预警服务，可提供咨询者法务智能问答服务，法律相关文章推荐服务，涉及舆情分析模型、智能文本纠错模型、以及法务智能问答系统。
负责部分：前期进行调研及功能分块，主要参与项目中的算法设计。
在舆情分析模型中，采用python编写爬虫爬取主流新闻网站上的新闻，进行将文本结构化存入Elasticsearch中，采用CNN进行舆情分类，选取其中与法律知识相关性强的部分文本进行进一步舆情可视化、整合智能问答系统中的提问数据进行舆情预警，用于法务知识的推荐以及相关舆情热点推荐。
在智能文本纠错模型中，主要应用于文书纠错，故基于统计与特征进行纠错，采用了首先进行预处理去除噪声，进而完成分词、词性标注，采用前向序列搜索算法进行优化，以及基于聚类的方法进行向量压缩，采用Add-k平滑算法进行数据平滑处理，基于多音字、同音字等情况建立混淆集进行排序，进行错误纠正，以计算结果中得分最高者作为正确修改，以此达到查错纠错的目的。
在法务智能问答服务中，主要分为案件类型分类模块、基于相似度匹配的基本问题问答模块，案件类型分类模块中通过提问的问题进行分类，从而给出相关文书、律师、律所、法条的推荐，基本问答模块基于已有的20w问答数据集进行问题的短文本相似度匹配，从而实现基本问题智能问答。
完成情况：完成了基本功能的分块化实现，算法的优化。
