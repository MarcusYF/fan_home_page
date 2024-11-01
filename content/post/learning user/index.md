---
title: Learning from a Learning User for Optimal Recommendations
subtitle: "Fan Yao, Chuanhao Li, Denis Nekepalov, Hongning Wang, Haifeng Xu"
date: 2021-12-13T00:00:00Z
summary: We formalize a model to capture the ``learning user'' effect in recommendation systems and design learning algorithm to tackle the challenges brought by the non-stationary feedback from a learning user.
draft: false
featured: false
authors:
  - admin
lastmod: 2020-12-13T00:00:00Z
tags:
  - Academic
categories:
  - poster
  - ""
projects: []
image:
  caption: ""
  focal_point: ""
  placement: 2
  preview_only: false
---





## Abstract

In real-world recommendation problems, especially those with a formidably large item
space, users have to gradually learn to estimate the utility of any fresh recommendations
from their experience about previously consumed items. This in turn affects their interaction dynamics with the system and can invalidate previous algorithms built on the omniscient user assumption. In this paper, we formalize a model to capture such “learning users”
and design an efficient system-side learning solution, coined Noise-Robust Active Ellipsoid
Search (RAES), to confront the challenges brought by the non-stationary feedback from
such a learning user. Interestingly, we prove that the regret of RAES deteriorates gracefully
as the convergence rate of user learning becomes worse, until reaching linear regret when
the user’s learning fails to converge. Experiments on synthetic datasets demonstrate the
strength of RAES for such a contemporaneous system-user learning problem. Our study
provides a novel perspective on modeling the feedback loop in recommendation problems.



