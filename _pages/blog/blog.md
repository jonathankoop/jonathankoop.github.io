---
layout: single-toc-on-top
classes: wide
permalink: /blog/
title: "Blog Posts"
toc_label: "List of Posts"
toc: true
sidebar:
  nav: "blog"
---

## REMs as Poisson Regressions

In this article, I explain how to rewrite Relational Event Models into Poisson regression models. Following the rationale of [Vieira, Leenders and Mulder (2024)](https://doi.org/10.1007/s42001-024-00290-7), a simple data set and model is used to illustrate, how this can be done in R. Estimates and standard errors are lastly compared to those from the `remstimate` package. [**Read more**](/blog/rem-to-poisson/)

## Multicollinearity in REMs

This post explores the extent to which multicollinearity can be observed in Relational Event History (REH) data generated through the specification of a single non-zero effect. To this end, correlation coefficients between endogenous statistics for directed networks in the `remstats` package are calculated. One step further, Variance Inflation Factors (VIFs) are computed. [**Read more**](/blog/collinearity-rem/)