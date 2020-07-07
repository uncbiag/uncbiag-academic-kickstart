---
title: "Networks for Joint Affine and Non-Parametric Image Registration"
date: 2019-01-01
publishDate: 2020-07-07T22:54:11.028046Z
authors: ["Zhengyang Shen", "Xu Han", "Zhenlin Xu", "Marc Niethammer"]
publication_types: ["1"]
abstract: "We introduce an end-to-end deep-learning framework for 3D medical image registration. In contrast to existing approaches, our framework combines two registration methods: an affine registration and a vector momentum-parameterized stationary velocity field (vSVF) model. Specifically, it consists of three stages. In the first stage, a multi-step affine network predicts affine transform parameters. In the second stage, we use a U-Net-like network to generate a momentum, from which a velocity field can be computed via smoothing. Finally, in the third stage, we employ a self-iterable map-based vSVF component to provide a non-parametric refinement based on the current estimate of the transformation map. Once the model is trained, a registration is completed in one forward pass. To evaluate the performance, we conducted longitudinal and cross-subject experiments on 3D magnetic resonance images (MRI) of the knee of the Osteoarthritis Initiative (OAI) dataset. Results show that our framework achieves comparable performance to state-of-the-art medical image registration approaches, but it is much faster, with a better control of transformation regularity including the ability to produce approximately symmetric transformations, and combining affine as well as non-parametric registration."
featured: false
publication: "*IEEE Conference on Computer Vision and Pattern Recognition, CVPR 2019, Long Beach, CA, USA, June 16-20, 2019*"
tags: ["registration", "deep learning", "knee", "SVF", "CVPR"]
url_pdf: "http://openaccess.thecvf.com/content_CVPR_2019/html/Shen_Networks_for_Joint_Affine_and_Non-Parametric_Image_Registration_CVPR_2019_paper.html"
doi: "10.1109/CVPR.2019.00435"
---

