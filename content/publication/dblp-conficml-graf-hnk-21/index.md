---
title: "Dissecting Supervised Constrastive Learning"
date: 2021-01-01
publishDate: 2021-07-26T17:36:31.224316Z
authors: ["Florian Graf", "Christoph D. Hofer", "Marc Niethammer", "Roland Kwitt"]
publication_types: ["1"]
abstract: "Minimizing cross-entropy over the softmax scores of a linear map composed with a high-capacity encoder is arguably the most popular choice for training neural networks on supervised learning tasks. However, recent works show that one can directly optimize the encoder instead, to obtain equally (or even more) discriminative representations via a supervised variant of a contrastive objective. In this work, we address the question whether there are fundamental differences in the sought-for representation geometry in the output space of the encoder at minimal loss. Specifically, we prove, under mild assumptions, that both losses attain their minimum once the representations of each class collapse to the vertices of a regular simplex, inscribed in a hypersphere. We provide empirical evidence that this configuration is attained in practice and that reaching a close-to-optimal state typically indicates good generalization performance. Yet, the two losses show remarkably different optimization behavior. The number of iterations required to perfectly fit to data scales superlinearly with the amount of randomly flipped labels for the supervised contrastive loss. This is in contrast to the approximately linear scaling previously reported for networks trained with cross-entropy."
featured: false
publication: "*Proceedings of the 38th International Conference on Machine Learning, ICML 2021, 18-24 July 2021, Virtual Event*"
tags: ["deep learning", "contrastive learning", "ICML"]
url_pdf: "http://proceedings.mlr.press/v139/graf21a.html"
---

