+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = ""

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "New Publication"
  content = "My R package `areal`, which implements a reproducible workflow for areal weighted interpolation, has been updated on CRAN and a related paper has recently been published in the *Journal of Open Source Software*. This is a joint effort with recent SLU graduate Charlie Revord."
  align = "left"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#777"  # An HTML color value.
  # overlay_img = "headers/bubbles-wide.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Details"
  cta_url = "#"
  cta_icon_pack = "fas"
  cta_icon = "info-circle"

[[item]]
  title = "New Publication"
  content = "An article detailing the contributions of an R package I help develop and maintain, `driftR`, has recently been published in *Environmental Monitoring & Assessment*. This is a join project with SLU graduate Andrew Shaughnessy and colleague Elizabeth Hasenmueller, PhD."
  align = "right"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = ""  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  cta_label = "Details"
  cta_url = "#"
  cta_icon_pack = "fas"
  cta_icon = "info-circle"

[[item]]
  title = "New Package"
  content = "Branson Fox, a SLU senior, and I have recently released a new package `censusxy` for batch geocoding street addresses using the nationwide U.S. Census Bureau geocoding service. The package offers a free, reproducible alternative to commerical geocoders and GIS software."
  align = "left"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = ""  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
  
  cta_label = "Details"
  cta_url = "#"
  cta_icon_pack = "fas"
  cta_icon = "info-circle"
+++
