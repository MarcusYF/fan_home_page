---
abstract: "We propose a new problem setting to study the sequential interactions
  between a recommender system and a user. Instead of assuming the user is
  omniscient, static, and explicit, as the classical practice does, we sketch a
  more realistic user behavior model, under which the user: 1) rejects
  recommendations if they are clearly worse than others; 2) updates her utility
  estimation based on rewards from her accepted recommendations; 3) withholds
  realized rewards from the system. We formulate the interactions between the
  system and such an explorative user in a $K$-armed bandit framework and study
  the problem of learning the optimal recommendation on the system side. We show
  that efficient system learning is still possible but is more difficult. In
  particular, the system can identify the best arm with probability at least
  $1−\\delta$ within $O(1/\\delta)$ interactions, and we prove this is tight.
  Our finding contrasts the result for the problem of best arm identification
  with fixed confidence, in which the best arm can be identified with
  probability $1−\\delta$ within $O(\\log(1/\\delta))$ interactions. This gap
  illustrates the inevitable cost the system has to pay when it learns from an
  explorative user's revealed preferences on its recommendations rather than
  from the realized rewards."
slides: bair
url_pdf: https://arxiv.org/abs/2110.03068
publication_types:
  - "1"
authors:
  - admin
  - Chuanhao Li
  - Denis Nekepalov
  - Hongning Wang
  - Haifeng Xu
author_notes: []
publication: AAAI'22
summary: "We propose a new perspective in studying the sequential interactions
  between a recommender system and a user. Instead of assuming the user is
  omniscient, static, and explicit, as the classical practice does, we sketch a
  more realistic user behavior model, under which the user: 1) rejects
  recommendations if they are clearly worse than others; 2) updates her utility
  estimation based on rewards from her accepted recommendations; 3) withholds
  realized rewards from the system. We formulate the interactions between the
  system and such an explorative user in a $K$-armed bandit framework and study
  the problem of learning the optimal recommendation on the system side. Our
  result illustrates the inevitable price the system has to pay when it learns
  from an explorative user's revealed preferences on its recommendations rather
  than from the realized rewards."
url_dataset: ""
url_project: ""
publication_short: To appear in *AAAI*, 2022
url_source: https://arxiv.org/abs/2110.03068
url_video: ""
title: Learning the Optimal Recommendation from Explorative Users
doi: ""
featured: true
tags: []
projects:
  - bair
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  focal_point: center
  preview_only: true
  filename: ""
date: 2021-12-05T21:56:14.075Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---
