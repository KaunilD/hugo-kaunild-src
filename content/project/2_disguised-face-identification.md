+++
# Date this page was created.
date = "2016-01-01"

# Project title.
title = "Disguised Face Identification."

# Project summary to display on homepage.
summary = "Identifying disguised faces using facial key points."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "disguise_detection.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["deep-learning", "python"]

# Does the project detail page use math formatting?
math = false

+++

As a Software Engineer at iSenses Inc. I was responsible for developing a machine learning pipeline for Disguised Face Identification.
After thorough research, a two-stage pipeline was formulated. In the first stage a learned SegNet CNN classifier extracted 14 key feature points from an image. Using these key points facial region is localized. In the second stage, the facial region is classified into disguised or normal classes using an SVM classifier. My research and the resulting pipeline was then implemented on an FPGA board and materialized into a product.

{{< vimeo 248132629 >}}
