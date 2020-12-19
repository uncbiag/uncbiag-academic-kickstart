---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Robust and generalizable visual representation learning via random convolutions
subtitle: ''
summary: ''
authors:
- Zhenlin Xu
- Deyi Liu
- Junlin Yang
- Colin Raffel
- Marc Niethammer
tags:
- '"deep learning"'
- '"representation learning"'
- '"robustness"'
- '"domain generalization"'
- '"neural networks"'
- '"data augmentation"'
categories: []
date: '2020-01-01'
lastmod: 2020-12-19T05:17:47-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-12-19T10:17:47.758165Z'
publication_types:
- '1'
abstract: While successful for various computer vision tasks, deep neural networks
  have shown to be vulnerable to texture style shifts and small perturbations to which
  humans are robust. In this work, we show that the robustness of neural networks
  can be greatly improved through the use of random convolutions as data augmentation.
  Random convolutions are approximately shape-preserving and may distort local textures.
  Intuitively, randomized convolutions create an infinite number of new domains with
  similar global shapes but random local texture. Therefore, we explore using outputs
  of multi-scale random convolutions as new images or mixing them with the original
  images during training. When applying a network trained with our approach to unseen
  domains, our method consistently improves the performance on domain generalization
  benchmarks and is scalable to ImageNet. In particular, in the challenging scenario
  of generalizing to the sketch domain in PACS and to ImageNet-Sketch, our method
  outperforms state-of-art methods by a large margin. More interestingly, our method
  can benefit downstream tasks by providing a more robust pretrained visual representation.
publication: ''
url_pdf: https://arxiv.org/abs/2007.13003
---
