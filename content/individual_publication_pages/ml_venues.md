+++
# blank widget.
widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear.

title = "Publications in Machine Learning Venues"
subtitle = ""

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"
+++

## ICML

{{<get_pubs_by_tag "ICML" 2>}}

## NeurIPS

{{<get_pubs_by_tag "NeurIPS" 2>}}

## AAAI

{{<get_pubs_by_tag "AAAI" 2>}}

## AISTATS

{{<get_pubs_by_tag "AISTATS" 2>}}

## JMLR

{{<get_pubs_by_tag "JMLR" 2>}}

