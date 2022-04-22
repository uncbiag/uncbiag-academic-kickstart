+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "Software"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "software"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  [[content.filter_button]]
    name = "All"
    tag = "*"
  
  [[content.filter_button]]
    name = "Deep Learning"
    tag = "deep learning"

  [[content.filter_button]]
    name = "Image Registration"
    tag = "registration"

  [[content.filter_button]]
    name = "Image Segmentation"
    tag = "segmentation"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

We open-sourced a variety of software packages. Many of them focusing on image registration. See the detailed descriptions as tiles and quick links to the respective GitHub repositories below.

**Quick links**

<table style="width:100%">
  <tr>
    <th>Software</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><a href="https://github.com/uncbiag/Aladdin">Aladdin</td> 
    <td>Deep-learning based atlas building</td>
  </tr>
  <tr>
    <td><a href="https://github.com/uncbiag/easyreg">Easyreg</td> 
    <td>Deep-learning image registration toolbox</td>
  </tr>
  <tr>
    <td><a href="https://github.com/uncbiag/ICON">ICON</td> 
    <td>Deep-learning based inverse consistent image registration</td>
  </tr>
  <tr>
    <td><a href="https://github.com/uncbiag/LTS">LTS</td> 
    <td>Local temperature scaling</td>
  </tr>
  <tr>
    <td><a href="https://github.com/uncbiag/OAI_analysis_2">OAI Analysis 2</td> 
    <td>Image analysis tools for the Osteoarthritis Initiative image dataset</td>
  </tr>
  <tr>
    <td><a href="https://github.com/uncbiag/pediatric_airway_atlas">Pediatric Airway Atlas</td>
    <td>Software tools to build and query an atlas of the upper airway in children</td>
  </tr>
  <tr>
    <td><a href="https://github.com/uncbiag/robot">RobOT</td>
    <td>Point cloud registration</td>
  </tr>
  <tr>
    <td><a href="https://github.com/uncbiag/VoteNet-Family">VoteNet</td>
    <td>A deep learning label fusion approach for multi-atlas segmentation</td>
  </tr>
  <tr>
    <td><a href="https://github.com/uncbiag/YETI-General">YETI</td>
    <td>A deep learning approach for perfusion imaging</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
  </tr>
</table>
