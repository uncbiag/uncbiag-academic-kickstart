---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Local Temperatutre Scaling"
summary: ""
authors: ["Marc Niethammer"]
tags: ["deep learning", "probability calibration"]
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

url_code: "https://github.com/uncbiag/LTS"
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
Deep segmentation networks typically create their outputs via a softmax. Hence, the assignment appears to be probabilistic. However, it has been shown in literatute that interpreting these softmax outputs as label probabilities is not reliable and that they tend to be overly confident. A simple approach to counteract this phenomenon for classification problems is to use Temperature Scaling which rescales the inputs to the softmax via a global temperatute constant so that the resulting outputs are consistent with the empirically observed labeling performance, i.e., the softmax output become calibrated probabilites. Our Local Temperature Scaling approach extends this principle to image segmentation. In particular, it allows for localized probability calibrations.

The Local Temperature Scaling repository can be found here:
https://github.com/uncbiag/LTS

