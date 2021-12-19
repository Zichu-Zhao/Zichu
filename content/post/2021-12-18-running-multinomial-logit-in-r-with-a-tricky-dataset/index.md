---
title: "Running Multinomial Logit in R with a Tricky Dataset"
author: "Zichu Zhao"
date: '2021-12-18'
output: pdf_document
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
lastmod: '2021-12-18T22:32:23-08:00'
categories: []
projects: []
slug: running-multinomial-logit-in-r-with-a-tricky-dataset
subtitle: ''
summary: ''
tags: []
authors: []
---

mlogit covers most of the needs if you have a clean and balanced dataset, which has not too many missing values. But if you have a lot of missing values in your dataset, mlogit might not be the best options for the reasons in this [answer](https://stackoverflow.com/questions/56939628/handling-alternative-specific-na-values-in-mlogit)