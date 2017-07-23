---
title: Forward and Reverse Gradient-Based Hyperparameter Optimization
booktitle: Proceedings of the 34th International Conference on Machine Learning
year: '2017'
volume: '70'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v70/franceschi17a/franceschi17a.pdf
url: http://proceedings.mlr.press/v70/franceschi17a.html
abstract: We study two procedures (reverse-mode and forward-mode) for computing the
  gradient of the validation error with respect to the hyperparameters of any iterative
  learning algorithm such as stochastic gradient descent. These procedures mirror
  two ways of computing gradients for recurrent neural networks and have different
  trade-offs in terms of running time and space requirements. Our formulation of the
  reverse-mode procedure is linked to previous work by Maclaurin et al (2015) but
  does not require reversible dynamics. Additionally, we explore the use of constraints
  on the hyperparameters. The forward-mode procedure is suitable for real-time hyperparameter
  updates, which may significantly speedup hyperparameter optimization on large datasets.
  We present a series of experiments on image and phone classification tasks. In the
  second task, previous gradient-based approaches are prohibitive. We show that our
  real-time algorithm yields state-of-the-art results in affordable time.
layout: inproceedings
id: franceschi17a
tex_title: Forward and Reverse Gradient-Based Hyperparameter Optimization
bibtex_author: Luca Franceschi and Michele Donini and Paolo Frasconi and Massimiliano
  Pontil
firstpage: 1165
lastpage: 1173
page: 1165-1173
order: 1165
cycles: false
editor:
- given: Doina
  family: Precup
- given: Yee Whye
  family: Teh
author:
- given: Luca
  family: Franceschi
- given: Michele
  family: Donini
- given: Paolo
  family: Frasconi
- given: Massimiliano
  family: Pontil
date: 2017-07-17
container-title: Proceedings of the 34th International Conference on Machine Learning
genre: inproceedings
issued:
  date-parts:
  - 2017
  - 7
  - 17
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v70/franceschi17a/franceschi17a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
