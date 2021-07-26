---
title: "Adversarial Data Augmentation via Deformation Statistics"
date: 2020-01-01
publishDate: 2021-07-26T17:36:31.229503Z
authors: ["Sahin Olut", "Zhengyang Shen", "Zhenlin Xu", "Samuel Gerber", "Marc Niethammer"]
publication_types: ["1"]
abstract: "Deep learning models have been successful in computer vision and medical image analysis. However, training these models frequently requires large labeled image sets whose creation is often very time and labor intensive, for example, in the context of 3D segmentations. Approaches capable of training deep segmentation networks with a limited number of labeled samples are therefore highly desirable. Data augmentation or semi-supervised approaches are commonly used to cope with limited labeled training data. However, the augmentation strategies for many existing approaches are either hand-engineered or require computationally demanding searches. To that end, we explore an augmentation strategy which builds statistical deformation models from unlabeled data via principal component analysis and uses the resulting statistical deformation space to augment the labeled training samples. Specifically, we obtain transformations via deep registration models. This allows for an intuitive control over plausible deformation magnitudes via the statistical model and, if combined with an appropriate deformation model, yields spatially regular transformations. To optimally augment a dataset we use an adversarial strategy integrated into our statistical deformation model. We demonstrate the effectiveness of our approach for the segmentation of knee cartilage from 3D magnetic resonance images. We show favorable performance to state-of-the-art augmentation approaches."
featured: false
publication: "*Computer Vision - ECCV 2020 - 16th European Conference, Glasgow, UK, August 23-28, 2020, Proceedings, Part XXIX*"
tags: ["ECCV", "registration", "segmentation", "knee", "statistics", "deep learning"]
url_pdf: "https://doi.org/10.1007/978-3-030-58526-6_38"
doi: "10.1007/978-3-030-58526-6_38"
---

