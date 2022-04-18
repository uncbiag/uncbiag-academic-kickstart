---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Pediatric Airway Atlas"
summary: ""
authors: ["Marc Niethammer"]
tags: ["registration", "segmentation", "atlas", "pediatric", "deep learning"]
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

url_code: "https://github.com/uncbiag/pediatric_airway_atlas"
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
The project aims to provide an analytical for measuring the normality of children's airways. We build an age-based atlas on multiple CT images of normal subjects. First, we use a segmentation model to extract the airway. Then, the cross-sectional areas over the airway's length are computed, and we use them as the main feature for the analysis. Having normal subjects, we can construct the weighted percentiles of cross-sectional areas, and the extreme percentiles (5%, 95%) can serve as proper anomaly detection boundaries.

The Pediatric Airway Atlas repository can be found here:
https://github.com/uncbiag/pediatric_airway_atlas


