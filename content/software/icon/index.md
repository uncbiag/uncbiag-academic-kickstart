---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "ICON"
summary: ""
authors: ["Marc Niethammer"]
tags: ["registration", "deep learning"]
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

url_code: "https://github.com/uncbiag/ICON"
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
ICON (Inverse COnsistent RegistratioN) is a non-parametric deep learning registration approach which relies only on inverse consistency for regularity. As the regularization neither involves explicit smoothing or a penality on spatial derivatives no affine pre-registration is required. Hence, ICON is largely parameter free. It also support ITK images as well as ITK transforms so is easy to use. We currently provide a pre-trained ICON registration network for the DESS magnetic resonance knee images of the Osteoarthritis Initiative. 

The ICON repository can be found here:
https://github.com/uncbiag/ICON


