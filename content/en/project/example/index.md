---
title: ShortPath
summary: Searching for the shortest path - Application to image reduction and R package creation.
tags:
  - R
date: '2022-01-22T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by Wiki
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: View code
    url: https://github.com/BOUGHANMIChaima/Short-Path/tree/main
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

ShortPath is an R package for determining the shortest path on a graph from a source vertex using two algorithms: the Bellman-Ford algorithm and the Dijkstra algorithm.

In particular, this package can be used to determine the shortest path on a graph within the unit square, whose starting vertex has coordinates (0,0) and whose ending vertex has coordinates (1,1).

An example of the application of these algorithms is seam carving. This is an image resizing algorithm developed by Shai AVIDAN and Ariel SHAMIR, which resizes the image by removing so-called low-energy pixel paths.
The package includes several functions.

See the full description by clicking the link above.