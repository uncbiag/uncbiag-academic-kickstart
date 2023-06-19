---
title: "iSegFormer: Interactive Segmentation via Transformers with Application to 3D Knee MR Images"
date: 2022-01-01
publishDate: 2023-06-19T20:19:09.347322Z
authors: ["Qin Liu", "Zhenlin Xu", "Yining Jiao", "Marc Niethammer"]
publication_types: ["1"]
abstract: "Interactive image segmentation has been widely applied to obtain high-quality voxel-level labels for medical images. The recent success of Transformers on various vision tasks has paved the road for developing Transformer-based interactive image segmentation approaches. However, these approaches remain unexplored and, in particular, have not been developed for 3D medical image segmentation. To fill this research gap, we investigate Transformer-based interactive image segmentation and its application to 3D medical images. This is a nontrivial task due to two main challenges: 1) limited memory for computationally inefficient Transformers and 2) limited labels for 3D medical images. To tackle the first challenge, we propose iSegFormer, a memory-efficient Transformer that combines a Swin Transformer with a lightweight multilayer perceptron (MLP) decoder. To address the second challenge, we pretrain iSegFormer on large amount of unlabeled datasets and then finetune it with only a limited number of segmented 2D slices. We further propagate the 2D segmentations obtained by iSegFormer to unsegmented slices in 3D images using a pre-existing segmentation propagation model pretrained on videos. We evaluate iSegFormer on the public OAI-ZIB dataset for interactive knee cartilage segmentation. Evaluation results show that iSegFormer outperforms its convolutional neural network (CNN) counterparts on interactive 2D knee cartilage segmentation, with competitive computational efficiency. When propagating the 2D interactive segmentations of 5 slices to other unprocessed slices within the same 3D volume, we achieve 82.2% Dice score for 3D knee cartilage segmentation. Code is available at https://github.com/uncbiag/iSegFormer."
featured: false
publication: "*Medical Image Computing and Computer Assisted Intervention - MICCAI 2022 - 25th International Conference, Singapore, September 18-22, 2022, Proceedings, Part V*"
tags: ["MICCAI", "deep learning", "segmentation", "interactive"]
url_pdf: "https://drive.google.com/file/d/1CwtA_P7m1cwTI1YLRGOEc3LM7oXiJO5m"
doi: "10.1007/978-3-031-16443-9_45"
---

