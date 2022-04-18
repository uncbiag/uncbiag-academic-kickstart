---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "OAI Analysis 2"
summary: ""
authors: ["Marc Niethammer"]
tags: ["registration", "segmentation", "deep learning"]
categories: []
date: 2022-04-18T07:05:00-10:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/uncbiag/OAI_analysis_2"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

This software contains open-source analysis approaches for the Osteoarthritis Initiative (OAI) magnetic resonance image (MRI) data. The analysis code is largely written in Python with the help of ITK and VTK for data I/O and mesh processing as well as PyTorch for the deep learning approaches for segmentation and registration. 

The following functionality is currently supported:

1. **Deep Learning Segmentation**: Automatic cartilage segmentation (femoral and tibial cartilage) using a 3D UNet.
2. **Cartilage thickness**: Extraction of femoral and tibial cartilage meshes and measuring of cartilage thickness based on a closest-point thickness estimation.
3. **Deep Learning Atlas Registration**: Registration of the carilage meshes with associated cartilage thickness to a knee atlas space via a deep registration network.
4. **2D Thickness Mapping**: Mapping of the thickness maps to a common 2D atlas space which provides full spatial correspondence. This is achieved via unrolling (based on a cylindrical coordinate system) for the femoral cartilage and a planar projection for the tibial cartilage.
5. **Statistical Analysis**: [Longitudinal statistical analysis approaches will be added shortly]

The OAI Analysis 2 repository can be found here:
https://github.com/uncbiag/OAI_analysis_2

