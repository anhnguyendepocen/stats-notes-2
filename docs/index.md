--- 
title: "Some notes on Statistics and Data Analytics"
author: "Desmond Ong"
date: "Draft Dated: 2019-12-13"
site: bookdown::bookdown_site
output: 
  bookdown::gitbook:
    lib_dir: assets
    split_by: section
    config:
      toolbar:
        position: static
      toc:
        before: |
          <li><a href="./">My Statistics Notes</a></li>
        after: |
          <li><a href="https://github.com/rstudio/bookdown" target="blank">Published with bookdown</a></li>
documentclass: book
bibliography: [stats-references.bib]
biblio-style: apalike
link-citations: yes
github-repo: desmond-ong/stats-notes
description: "A collection of statistics notes useful for data analytics."
---

# Preface {-}

This is a collection of notes on statistics and data analytics that I am compiling, primarily to supplement a course that I teach at the National University of Singapore (BT1101: Introduction to Business Analytics), which is a statistics course in R targeted at first-year undergraduate students and aspiring data scientists / researchers. 


I hope to cover quite broadly several important and useful statistical concepts (e.g. regression, simulations), as well as discuss issues like data visualization best practices. If I have time, I would like to transition to teaching statistics in a more Bayesian tradition.


As some background, I am a computational cognitive psychologist, with a little bit of training in econometrics, so I tend to favor regression and simulation approaches, and my examples may default to examples common in the social sciences.


This is a work in progress that is inspired by Russ Poldrack's Psych10 book here: http://statsthinking21.org/. This set of notes is hosted on [GitHub](https://github.com/desmond-ong/stats-notes) and built using [Bookdown](https://github.com/rstudio/bookdown).


Feedback can be sent to dco (at) comp.nus.edu.sg.


## Outline of notes {-}

- [In Progress] Getting Started - R, RStudio, R Markdown. 
    a. Coding Best Practices. 
    b. Analysis Best Practices.
- [In Progress] Introduction
- [In Progress] Descriptive Statistics - Mean / Median / Mode, Types of Variables
- [In Progress] Handling Data
- [In Progress] Data Visualization
- The Linear Model
    a. Linear Regression
    b. Logistic Regression
    c. Interactions
    d. Model Selection
    e. Mixed-effects linear models
- [In Progress] Data Mining
- [In Progress] Simulations
    a. Monte Carlo Simulations
    b. The Bootstrap
- Optimization
    a. Linear Optimization
    b. Integer-valued Optimization

...