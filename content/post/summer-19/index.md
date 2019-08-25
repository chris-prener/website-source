---
title: 'Summer 2019 Updates'
subtitle: 'New publications, software, media coverage, and resources'
summary: A quick roundup of activity from the past few months! 
authors:
- admin
tags:
- academics
categories:
- Academics
date: "2019-08-24T00:00:00Z"
lastmod: "2019-08-24T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 2
  caption: 'Image credit: [Thomas Dils](https://unsplash.com/@tdils?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/photos/rHr_jtgTHH4)'
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

# Set captions for image gallery.
#gallery_item:
#- album: gallery
#  caption: Default
#  image: theme-default.png
---

On Monday, we'll be starting another school year here at [Saint Louis University](https://www.slu.edu) with the [largest first year class ever](https://www.slu.edu/news/2019/august/record-freshman-class.php). With the end of summer officially upon us, I wanted to take a moment to recap my summer. Academia isn't always sunshine and daisies, and I'm learning that it is important to celebrate whenever you have the opportunity!

That said, this summer was not all work - we moved after selling our house in Shaw this spring, and spent a few weeks road tripping Western New York (to see my parents) and to the North Country to see my in-laws. It is always good stop at St. Lawrence's bookstore (me and my wife's alma mater) on our way to Plattsburgh, and I also spent some time over in Rumney rock climbing with a bunch of SLU alumni who I'm lucky enough to still be so close with.

Despite the fun, this summer was mostly work, though, so without further adieu...

### Teaching
With such a large first year class, I was asked to switch from my typical mix of [Intro to Sociology](https://slu-soc1120.github.io) with a diversity and health emphasis and [statistics](https://slu-soc5050.github.io) to two sections of Intro to Sociology. This means that my statistics materials won't be updated this year, which is a bit of a shame because I had wanted to refresh the website and move towards live coding and away from lecture slides with that course. 

However, I'm thrilled to be teaching nearly 70 of our incoming first year students (along with 30 of their upper-class colleagues) in my Intro to Sociology sections. I've updated my [syllabus](https://slu-soc1120.github.io/syllabus/) for the course and launched a new [course website](https://slu-soc1120.github.io). 

I'm also trying something new this semester that I am super excited about - course docs. I've been engaging in this practice with my research methods courses for two years now, using the `blogdown` package to create simple course websites where I can share additional resources. With Intro, I'm planning to replicate this, focusing on linking to additional information people, events, and stories that I bring up in class. 

For me, this is an important exercise in supporting students who haven't been exposed to some of the material in the course before that I assume familiarity with. Breaking down barriers to [assumed knowledge](https://www.gse.harvard.edu/news/uk/19/04/real-advice-first-gens) is particularly important for first generation students, and I'm excited to be adding this resource to my class. My first lecture's docs are [already live](https://slu-soc1120.github.io/docs/lecture-01/).

### Research and Writing
One the research end, it has been a busy summer - I've had two open science papers published in the [*Journal of Open Source Software*](https://joss.theoj.org/papers/10.21105/joss.01221) (with graduating senior Charlie Revord) and [*Enviornmental Monitoring & Assessment*](https://link.springer.com/article/10.1007/s10661-019-7586-x) (with SLU alumni Andrew Schaughnessy, now a doctoral student at Penn State, and our colleague Elizabeth Hasenmueller). 

I also recieved an R&R on an essay that I'm really excited about, which recaps the path dependency through certain cities have become paradigmatic in urban sociology. I argue that pursuing a geographic selection of cities that is *broader* (with particular attention needed on the American south and southwest), and contextually *deeper* (by thinking of cities as having their own individual literatures), is one way to address the multiple recurrent criticisms of the field.

Two other papers from my work with colleagues at Northeastern University on [literacy and mental health](/project/literacy/) went out for peer review this summer, and we made progress on a pair of new manuscripts that pair our United States and Australian samples for the first time.

Speaking of progress on manuscripts, time was spent this summer revising our [pre-print](https://osf.io/preprints/socarxiv/2wext/) on [St. Louis's street barriers](https://chris-prener.github.io/barriers/) and are re-fitting our models using Poisson models. The same models are planned for a paper on arson rates in the City of St. Louis, and I'm planning to share pre-prints of both these updated papers this fall.

Finally, my recently graduate student Charlie Revord and I have been working on revising his fascinating senior thesis, which used sentiment analysis to document patterns in stigmatization and trivialization of obsessive compulsive disorder on Twitter. 
### Software
Two new packages were shipped this summer. The first, [`biscale`](https://slu-opengis.github.io/biscale/index.html), provides a workflow for creating bi-variate choropleth maps in `R`. It builds upon some [previous work](https://timogrossenbacher.ch/2019/04/bivariate-maps-with-ggplot2-and-sf/) done by two co-authors on the package, Timo Grossenbacher and Angelo Zehr. I've been receiving bi-variate maps on Twitter all summer, from as far afield as Washington State, Ontario, England, and Latvia. 

The second package that was shipped this summer, [`censusx`](https://slu-opengis.github.io/censusxy/), is a joint effort with my rising SLU Senior Branson Fox. Our package provides reasonably fast, efficient access to the U.S. Census Bureau's nationwide address geocoder. Branson and I will be building this functionality into our `gateway` package, which includes a completely open source composite geocoder for the City of St. Louis, this fall.

In addition, an updated version of [`areal`](https://slu-opengis.github.io/areal/) (again with my recently graduate student Charlie Revord) was published as well as an update to [`compstatr`](https://slu-opengis.github.io/compstatr/), which now has the ability to scrape monthly crime tables directly from the City of St. Louis's website.

### Service
Summer is typically a time when some of the service requirements for academics fall away for a few months, but I'm deep in the planning for [useR! 2020](https://twitter.com/useR2020stl), which we're bringing to St. Louis in July 2020. I was one of five team members who got to attend useR! 2019 in Toulouse, France, and it was easily the best academic conference I've ever been too. Planning is going well (well, as well as can be expected!) and we're almost ready to share some of the first big announcements with the world.

I also took some time this summer to revise the syllabus and policies for the Departmental Honors Thesis in Sociology, a research opportunity that I coordinate for the Sociology program. We just graduated our first two students who completed (very successfully!) theses, and the policy updates incorporate a lot of lessons we learned along the way. I also converted our policies into an FAQ that is meant to be a guide for our faculty and students.

Finally, we're continuing to make progress on some initial research steps for the [St. Louis Vacancy Initiative](https://www.stlvacancy.com), a very important group of activists, lawyers, community development professionals, and some stray academics who are trying to address [our city's sky high vacancy rate](https://www.tandfonline.com/doi/full/10.1080/07352166.2018.1474079).

### Media
Finally, I got a nice shoutout in the St. Louis Post-Dispatch [in June](https://www.stltoday.com/news/local/columns/tony-messenger/messenger-connecting-the-dots-between-dead-kids-closing-the-workhouse/article_f3a32654-7c01-5fc1-a5b6-55e9ed2a3654.html). Tony won a Pulitzer this year for his critically important coverage of debter prison practices in Missouri, and its great to see him digging into the pediatric homicide rate in St. Louis, which is heartbreakingly high.
