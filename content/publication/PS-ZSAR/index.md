---
abstract: >+
  The goal of zero-shot action recognition (ZSAR) is to classify action classes
  which were not previously seen during training. Traditionally, this is
  achieved by training a network to map, or regress, visual inputs to a semantic
  space where a nearest neighbor classifier is used to select the closest target
  class. We argue that this approach is sub-optimal due to the use of nearest
  neighbor on static semantic space and is ineffective when faced with
  multi-label videos - where two semantically distinct co-occurring action
  categories cannot be predicted with high confidence. To overcome these
  limitations, we propose a ZSAR framework which does not rely on nearest
  neighbor classification, but rather consists of a pairwise scoring function.
  Given a video and a set of action classes, our method predicts a set of
  confidence scores for each class independently. This allows for the prediction
  of several semantically distinct classes within one video input. Our
  evaluations show that our method not only achieves strong performance on three
  single-label action classification datasets (UCF-101, HMDB, and RareAct), but
  also outperforms previous ZSAR approaches on a challenging multi-label dataset
  (AVA) and a real-world surprise activity detection dataset (MEVA).

slides: example
url_pdf: http://arxiv.org/pdf/1512.04133v1
publication_types:
  - "2"
authors:
  - Alec Kerrigan
  - Kevin Duarte
  - Yogesh Rawat
  - Mubarak Shah
author_notes:
  - Equal contribution
  - Equal contribution
publication: Advances in Neural Information Processing Systems 34
summary: ""
url_dataset: ""
url_project: ""
publication_short: NeurIPS 2021
url_source: ""
url_video: ""
title: Reformulating Zero-shot Action Recognition for Multi-label Actions
doi: ""
featured: true
tags:
  - Source Themes
projects: []
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"
  focal_point: center
  preview_only: false
  filename: architecture3-1-.png
date: 2022-04-07T01:31:48.151Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: https://github.com/wowchemy/wowchemy-hugo-themes
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
