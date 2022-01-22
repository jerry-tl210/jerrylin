---
title: Predicting House Prices in South Korea
summary: Implementation of machine learning algorithms in predictive analytics.
tags:
- Other
date: "2020-12-10T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image: 
  caption: A scatterplot with house size on x-axis and price on y-axis
  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: "example.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

In this project, we try to reliably predict the housing price based on the information of the house and its neighborhood as well as what factors
has the more substantial influences on the decision of the price. To do so we would perform a linear regression on the dataset. We would designate
the feature SalePrice to be our target variable and all the features that describe the house sold (which is all the rest of the features save for YrSold
and MonthSold ). This is a regressional analysis because the target variable is, for all intents and purposes, continuous, and weights of a linear
regression model shines light on the importance of the features.

