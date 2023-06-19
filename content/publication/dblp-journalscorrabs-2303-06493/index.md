---
title: "Exploring Cycle Consistency Learning in Interactive Volume Segmentation"
date: 2023-01-01
publishDate: 2023-06-19T20:19:09.338202Z
authors: ["Qin Liu", "Meng Zheng", "Benjamin Planche", "Zhongpai Gao", "Terrence Chen", "Marc Niethammer", "Ziyan Wu"]
publication_types: ["2"]
abstract: "Interactive volume segmentation can be approached via two decoupled modules: interaction-to-segmentation and segmentation propagation. Given a medical volume, a user first segments a slice (or several slices) via the interaction module and then propagates the segmentation(s) to the remaining slices. The user may repeat this process multiple times until a sufficiently high volume segmentation quality is achieved. However, due to the lack of human correction during propagation, segmentation errors are prone to accumulate in the intermediate slices and may lead to sub-optimal performance. To alleviate this issue, we propose a simple yet effective cycle consistency loss that regularizes an intermediate segmentation by referencing the accurate segmentation in the starting slice. To this end, we introduce a backward segmentation path that propagates the intermediate segmentation back to the starting slice using the same propagation network. With cycle consistency training, the propagation network is better regularized than in standard forward-only training approaches. Evaluation results on challenging benchmarks such as AbdomenCT-1k and OAI-ZIB demonstrate the effectiveness of our method. To the best of our knowledge, we are the first to explore cycle consistency learning in interactive volume segmentation."
featured: false
publication: "*CoRR*"
tags: ["deep learning", "segmentation", "interactive"]
url_pdf: "https://doi.org/10.48550/arXiv.2303.06493"
doi: "10.48550/arXiv.2303.06493"
---

