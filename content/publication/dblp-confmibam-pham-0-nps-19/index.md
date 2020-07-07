---
title: "Multiseg pipeline: automatic tissue segmentation of brain MR images with subject-specific atlases"
date: 2019-01-01
publishDate: 2020-07-07T23:41:09.583813Z
authors: ["Kevin Pham", "Xiao Yang", "Marc Niethammer", "Juan-Carlos Prieto", "Martin Styner"]
publication_types: ["1"]
abstract: "Automated segmentation and labeling of individual brain anatomical regions is challenging due to individual structural variability. Although, atlas-based segmentation has shown its potential for both tissue and structure segmentation, the inherent natural variability as well as disease-related changes in MR appearance is often inappropriately represented by a single atlas image. In order to have a more accurate representation, several atlases may be used for the segmentation task in a given neuroimaging study. In this paper, we present the MultisegPipeline, it uses multiple atlases that have been visually inspected and capture the expected variability in a neonatal population. The MultisegPipeline transfers the labeled regions from each atlas to the target image using deformable registration (ANTs or QuickSilver is available for this task). Additionally, the set of labels are merged using a label fusion technique that reduces the errors produced by the registration. The final output is a single label map that combines the results produced by all atlases into a consensus solution. In our study, the MultisegPipeline is used to segment brain MR images from 31 infants, a leave-one-out strategy was used to test our framework. The average dice score coefficient was 0.89."
featured: false
publication: "*Medical Imaging 2019: Biomedical Applications in Molecular, Structural, and Functional Imaging, San Diego, California, United States, 16-21 February 2019*"
url_pdf: "https://doi.org/10.1117/12.2513237"
doi: "10.1117/12.2513237"
---

