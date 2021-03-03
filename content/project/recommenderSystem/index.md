---
title: Recommender System
summary: A recommender System on the Netflix dataset.
tags:
- 2
- Machine Learning
- Python
- Data Cleaning
date: "2020-12-18T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Recommender systems have taken more and more place in our lives. In this project, we implemented one following the Netflix Prize solution, by using ensemble methods of different algorithms. 
Our best model had 1.020 RMSE score on AICrowd platform where we ranked 8th over 100 teams.
The data consisted of ratings of 10,000 users for 1,000 different movies. All ratings were integer values between 1 and 5 stars, 1 being the lowest grade and 5 being the best. No additional information was available on the users or movies. 
The training data set contained 1,176,952 out of 10,000,000 ratings with 88.23\% sparsity. The rest of the ratings had to be predicted by our recommender system.

This project involved a lot of data cleaning. It was challenging because of the competition. It wasn't sufficient to build a model that worked, we needed to optimize it constantly. 
Hence, we had to read papers and understand techniques that could lead to the best solution! 
