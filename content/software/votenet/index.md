---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "VoteNet"
summary: ""
authors: ["Marc Niethammer"]
tags: ["deep learning", "segmentation", "registration"]
categories: []
date: 2020-07-03T07:05:00-10:00

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

url_code: "https://github.com/uncbiag/VoteNet-Family"
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

VoteNet is a deep-learning-based label fusion strategy for multi-atlas segmentation (MAS) which locally selects a set of reliable atlases whose labels are then fused via plurality voting. By selecting a good initial atlas set MAS with VoteNet significantly outperforms a number of other label fusion strategies as well as a direct deep-learning (DL) segmentation approach. VoteNet makes use of a fast DL registration approach.

The VoteNet repository, which contains the code for VoteNet, VoteNet+, and VoteNet++ can be found here:
https://github.com/uncbiag/VoteNet-Family

