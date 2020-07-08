---
title: "DeepAtlas: Joint Semi-supervised Learning of Image Registration and Segmentation"
date: 2019-01-01
publishDate: 2020-07-08T19:44:31.459627Z
authors: ["Zhenlin Xu", "Marc Niethammer"]
publication_types: ["1"]
abstract: "Deep convolutional neural networks (CNNs) are state-of-theart for semantic image segmentation, but typically require many labeled training samples. Obtaining 3D segmentations of medical images for supervised training is difficult and labor intensive. Motivated by classical approaches for joint segmentation and registration we therefore propose a deep learning framework that jointly learns networks for image registration and image segmentation. In contrast to previous work on deep unsupervised image registration, which showed the benefit of weak supervision via image segmentations, our approach can use existing segmentations when available and computes them via the segmentation network otherwise, thereby providing the same registration benefit. Conversely, segmentation network training benefits from the registration, which essentially provides a realistic form of data augmentation. Experiments on knee and brain 3D magnetic resonance (MR) images show that our approach achieves large simultaneous improvements of segmentation and registration accuracy (over independently trained networks) and allows training high-quality models with very limited training data. Specifically, in a one-shot-scenario (with only one manually labeled image) our approach increases Dice scores (%) over an unsupervised registration network by 2.7 and 1.8 on the knee and brain images respectively."
featured: false
publication: "*Medical Image Computing and Computer Assisted Intervention - MICCAI 2019 - 22nd International Conference, Shenzhen, China, October 13-17, 2019, Proceedings, Part II*"
tags: ["knee", "brain", "registration", "segmentation", "deep learning", "MICCAI"]
url_pdf: "https://drive.google.com/file/d/10NhXJNETZ0-tqoiwBDaHUEj5yRkg__94"
doi: "10.1007/978-3-030-32245-8_47"
---

