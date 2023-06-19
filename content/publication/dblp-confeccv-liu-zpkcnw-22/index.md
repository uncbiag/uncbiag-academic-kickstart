---
title: "PseudoClick: Interactive Image Segmentation with Click Imitation"
date: 2022-01-01
publishDate: 2023-06-19T20:19:09.346785Z
authors: ["Qin Liu", "Meng Zheng", "Benjamin Planche", "Srikrishna Karanam", "Terrence Chen", "Marc Niethammer", "Ziyan Wu"]
publication_types: ["1"]
abstract: "The goal of click-based interactive image segmentation is to obtain precise object segmentation masks with limited user interaction, i.e., by a minimal number of user clicks. Existing methods require users to provide all the clicks: by first inspecting the segmentation mask and then providing points on mislabeled regions, iteratively. We ask the question: can our model directly predict where to click, so as to further reduce the user interaction cost? To this end, we propose PseudoClick, a generic framework that enables existing segmentation networks to propose candidate next clicks. These automatically generated clicks, termed pseudo clicks in this work, serve as an imitation of human clicks to refine the segmentation mask. We build PseudoClick on existing segmentation backbones and show how the click prediction mechanism leads to improved performance. We evaluate PseudoClick on 10 public datasets from different domains and modalities, showing that our model not only outperforms existing approaches but also demonstrates strong generalization capability in cross-domain evaluation. We obtain new state-of-theart results on several popular benchmarks, e.g., on the Pascal dataset, our model significantly outperforms existing state-of-the-art by reducing 12.4% number of clicks to achieve 85% IoU."
featured: false
publication: "*Computer Vision - ECCV 2022 - 17th European Conference, Tel Aviv, Israel, October 23-27, 2022, Proceedings, Part VI*"
url_pdf: "https://arxiv.org/pdf/2207.05282.pdf"
doi: "10.1007/978-3-031-20068-7_42"
---

