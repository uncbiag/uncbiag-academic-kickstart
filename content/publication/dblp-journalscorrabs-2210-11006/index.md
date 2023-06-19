---
title: "SimpleClick: Interactive Image Segmentation with Simple Vision Transformers"
date: 2022-01-01
publishDate: 2023-06-19T20:19:09.350142Z
authors: ["Qin Liu", "Zhenlin Xu", "Gedas Bertasius", "Marc Niethammer"]
publication_types: ["2"]
abstract: "Click-based interactive image segmentation aims at extracting objects with a limited user clicking. A hierarchical backbone is the de-facto architecture for current methods. Recently, the plain, non-hierarchical Vision Transformer (ViT) has emerged as a competitive backbone for dense prediction tasks. This design allows the original ViT to be a foundation model that can be finetuned for downstream tasks without redesigning a hierarchical backbone for pretraining. Although this design is simple and has been proven effective, it has not yet been explored for interactive image segmentation. To fill this gap, we propose SimpleClick, the first interactive segmentation method that leverages a plain backbone. Based on the plain backbone, we introduce a symmetric patch embedding layer that encodes clicks into the backbone with minor modifications to the backbone itself. With the plain backbone pretrained as a masked autoencoder (MAE), SimpleClick achieves state-of-theart performance. Remarkably, our method achieves 4.15 NoC@90 on SBD, improving 21.8% over the previous best result. Extensive evaluation on medical images demonstrates the generalizability of our method. We further develop an extremely tiny ViT backbone for SimpleClick and provide a detailed computational analysis, highlighting its suitability as a practical annotation tool."
featured: false
publication: "*CoRR*"
tags: ["deep learning", "segmentation", "interactive"]
url_pdf: "https://doi.org/10.48550/arXiv.2210.11006"
doi: "10.48550/arXiv.2210.11006"
---

