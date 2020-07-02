---
title: "Group-wise automatic mesh-based analysis of cortical thickness"
date: 2011-01-01
publishDate: 2020-07-02T21:36:10.933594Z
authors: ["Clement Vachet", "Heather Cody Hazlett", "Marc Niethammer", "Ipek Oguz", "Joshua E. Cates", "Ross T. Whitaker", "Joseph Piven", "Martin Styner"]
publication_types: ["1"]
abstract: "The analysis of neuroimaging data from pediatric populations presents several challenges. There are normal variations in brain shape from infancy to adulthood and normal developmental changes related to tissue maturation. Measurement of cortical thickness is one important way to analyze such developmental tissue changes. We developed a novel framework that allows group-wise automatic mesh-based analysis of cortical thickness. Our approach is divided into four main parts. First an individual pre-processing pipeline is applied on each subject to create genus-zero inflated white matter cortical surfaces with cortical thickness measurements. The second part performs an entropy-based group-wise shape correspondence on these meshes using a particle system, which establishes a trade-off between an even sampling of the cortical surfaces and the similarity of corresponding points across the population using sulcal depth information and spatial proximity. A novel automatic initial particle sampling is performed using a matched 98-lobe parcellation map prior to a particle-splitting phase. Third, corresponding re-sampled surfaces are computed with interpolated cortical thickness measurements, which are finally analyzed via a statistical vertex-wise analysis module. This framework consists of a pipeline of automated 3D Slicer compatible modules. It has been tested on a small pediatric dataset and incorporated in an open-source C++ based high-level module called GAMBIT. GAMBIT's setup allows efficient batch processing, grid computing and quality control. The current research focuses on the use of an average template for correspondence and surface re-sampling, as well as thorough validation of the framework and its application to clinical pediatric studies."
featured: false
publication: "*Medical Imaging 2011: Image Processing, Lake Buena Vista, Florida, USA, February 14-16, 2011*"
url_pdf: "https://doi.org/10.1117/12.878300"
doi: "10.1117/12.878300"
---

