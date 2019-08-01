+++
title = "An R Package for Correcting Continuous Water Quality Monitoring Data for Drift"
date = 2019-06-18T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["A Shaughnessy", "CG Prener", "L Hasenmuller"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In *Enviornmental Monitoring & Assessment*"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Continuous water quality monitoring instruments are used to understand the chemical and physical behaviors of aquatic environments over time. However, the data generated from these instruments are susceptible to inaccuracies due to drift that can occur between site visits. While there are several software packages available to correct drift in water quality data, these packages are often proprietary, expensive, and/or do not offer the user control over the data corrections. This paper describes driftR, an R package that corrects drift in water quality data. driftR implements either one- or two-point variable data corrections based on the number of standards used to calibrate the sensor of interest, then linearly interpolates the correction over the period of interest. This program gives control to users to correct each parameter in a way that is ideal for their unique stu- dies and offers a free, reproducible method for drift correction."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = ["driftR"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["ecology", "R", "open-science", "software"]

# Links (optional).
url_pdf = "https://link.springer.com/article/10.1007/s10661-019-7586-x"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = "driftR"
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "Website", url = "https://shaughnessyar.github.io/driftR/"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "headers/stream-wide.jpg"
caption = "Image credit: Caleb George on [Unsplash](https://unsplash.com/photos/zZzKLzKP24o)"

+++