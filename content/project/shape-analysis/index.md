---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Shape Analysis"
summary: "Analysis approaches to quantify shape differences."
authors: []
tags: ["shape"]
categories: []
date: 2020-07-09T18:18:57-10:00

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

url_code: ""
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

Statistical shape analysis is a key technology in medical image analysis to understand distributions of shapes within a subject group, differences between groups, or differences between a group and an individual subject. Just as for the analysis of time-varying data, a good shape representation is important. We have investigated shape representations that either do not require establishing spatial correspondences (i.e., spectral approaches ({{<cite "reuter09">}}) which are invariant to isometric transformations -  transformations that do not cause local stretching or compression) or only require an initial global alignment, thereby sidestepping the potentially challenging estimation of local correspondences. We have also developed approaches based on object-oriented data analysis, specifically, making use of orderings on shape ({{<cite "hong14">}}{{<cite "hong15">}}). By forming such orderings, rank-order statistical methods can be generalized to shapes (such as the median, percentiles, the interquartile range, outliers). Some of our shape analysis approaches make use of topology, either to define shape features ({{<cite "reuter09">}}) or for the entire shape analysis framework ({{<cite "hofer17">}}). See [here]({{<ref "/tags/shape/">}}) for a more complete overview of our shape analysis work.

{{<putbib "dblp-journalsmia-hong-dmkskpsdzn-14" "hong14">}}
{{<putbib "dblp-journalsmia-hong-gnb-15" "hong15">}}
{{<putbib "dblp-journalscad-reuter-wsn-09" "reuter09">}}
{{<putbib "dblp-confipmi-hofer-knhtu-17" "hofer17">}}





