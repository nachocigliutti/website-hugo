---
title: Adversarial Method of Moments
summary: We study the performance of GAN in models based on moment conditions, and characterize it's finite sample properties.
tags:
  - Econometrics
  - Machine Learning
date: '2022-07-01'

# Optional external URL for project (replaces project detail page).
external_link: ''

# image:
#   caption: Photo by Nacho Cigliutti using Dalle 2
#   focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
# url_code: ''
url_pdf: 'uploads/AMM_draft.pdf'
url_slides: 'uploads/AMM_slides.pdf'
# url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

We introduce Adversarial Method of Moments (AMM), for models defined with moment conditions. The estimator is asymptotically equivalent to optimallyweighted 2–step GMM, but outperforms the GMM estimator in finite samples. We show this both in theory and in simulations. In our theoretical results, we exploit the relationship between AMM and GEL estimators to show, using stochastic expansions, that AMM has smaller bias than optimally–weighted GMM. In our simulation experiments, we consider different models, including estimation of variance as in Altonji and Segal (1996) and a dynamic panel data model. We compare the estimator’s performance to other commonly–used procedures in the literature, and find that AMM outperforms in cases where other estimators fail. In the appendix, we extend AMM to simulation–based settings, with an application to the estimation of DSGE models by matching IRF.