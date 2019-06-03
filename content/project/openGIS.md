+++
# Date this page was created.
date = 2018-05-05T00:00:00

# Project title.
title = "openGIS"

# Project summary to display on homepage.
summary = "Multiple `R` packages for using data about St. Louis and curated spatial data"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "oldmaps.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["GIS", "open-science", "software", "urban"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/oldmaps-wide.jpg"
caption = "Image credit: Andrew Neel on [Unsplash](https://unsplash.com/photos/1-29wyvvLJA)"

+++

The [SLU Data Science Seminar](https://slu-dss.github.io), which Chris is a founding co-organizer of, is the host of Chris's [openGIS project](https://slu-openGIS.github.io). The project is a collaborative effort with SLU students to curate and host GIS data about the St. Louis area in an accessible manner. We also maintain several `R` packages that contain tools for working with spatial data that orginiates locally as well as more general `R` tools for working with spatial data.

## Data
The openGIS project is focused on providing easy access to spatial data about the City of St. Louis. We are currently working on producing demographic estimates for 2010 and 2016 at a variety of local extents, including precincts, wards, and neighborhoods, and have released data on other local social phenomena as well.

## Software

### Released R Packages

<i class="fa fa-cog" aria-hidden="true"></i>  `areal`
<br> <span class="talk-metadata">workflow for areal weighted interpolation in `R`</span>
<br> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://slu-openGIS.github.io/areal/" target = "_blank"> Website </a> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/slu-openGIS/areal" target = "_blank"> GitHub </a> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://cran.r-project.org/package=areal" target = "_blank"> CRAN </a>

<i class="fa fa-cog" aria-hidden="true"></i>  `qualmap`
<br> <span class="talk-metadata">tidy, opinionated approach to digitizing semi-structured qualitative GIS data</span>
<br> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://slu-openGIS.github.io/qualmap/" target = "_blank"> Website </a> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/slu-openGIS/qualmap" target = "_blank"> GitHub </a> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://cran.r-project.org/package=qualmap" target = "_blank"> CRAN </a>

### Internal R Packages

<i class="fa fa-cog" aria-hidden="true"></i>  `brownLTDB`
<br> <span class="talk-metadata">quick access to tidy versions of the [Brown Longitudinal Census Database](https://s4.ad.brown.edu/projects/diversity/researcher/ltdb.htm) data releases; not public</span>

<i class="fa fa-cog" aria-hidden="true"></i>  `cityHealth`
<br> <span class="talk-metadata">quick access to tidy versions of the CDC's [500 Cities Project](https://www.cdc.gov/500cities/) data releases</span>
<br> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/slu-openGIS/cityHealth" target = "_blank"> GitHub </a>

### R Packages in Progress

<i class="fa fa-cog" aria-hidden="true"></i>  `compstatr`
<br> <span class="talk-metadata">tools for validating and managing St. Louis Metropolitan Police Department data</span>
<br> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/slu-openGIS/compstatr" target = "_blank"> GitHub </a>

<i class="fa fa-cog" aria-hidden="true"></i>  `gateway`
<br> <span class="talk-metadata">tools for working with georeferenced data for the city of St. Louis</span>
<br> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/slu-openGIS/gateway" target = "_blank"> GitHub </a>

<i class="fa fa-cog" aria-hidden="true"></i>  `postmastr`
<br> <span class="talk-metadata">tools for working with georeferenced data for the city of St. Louis</span>
<br> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/chris-prener/postmastr" target = "_blank"> GitHub </a>

<i class="fa fa-cog" aria-hidden="true"></i>  `stlcsb`
<br> <span class="talk-metadata">tools for validating and managing data from the City of St. Louis's Citizens Service Bureau</span>
<br> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/slu-openGIS/stlcsb" target = "_blank"> GitHub </a>

<i class="fa fa-cog" aria-hidden="true"></i>  `stldata`
<br> <span class="talk-metadata">data for teaching GIS, spatial statistics, and data science that I use in my [geoscience course](/courses/introgis/)</span>
<br> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/slu-openGIS/stldata" target = "_blank"> GitHub </a>
