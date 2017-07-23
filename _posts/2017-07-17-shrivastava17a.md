---
title: Optimal Densification for Fast and Accurate Minwise Hashing
booktitle: Proceedings of the 34th International Conference on Machine Learning
year: '2017'
volume: '70'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v70/shrivastava17a/shrivastava17a.pdf
url: http://proceedings.mlr.press/v70/shrivastava17a.html
abstract: Minwise hashing is a fundamental and one of the most successful hashing
  algorithm in the literature. Recent advances based on the idea of densification
  (Shrivastava \& Li, 2014) have shown that it is possible to compute $k$ minwise
  hashes, of a vector with $d$ nonzeros, in mere $(d + k)$ computations, a significant
  improvement over the classical $O(dk)$. These advances have led to an algorithmic
  improvement in the query complexity of traditional indexing algorithms based on
  minwise hashing. Unfortunately, the variance of the current densification techniques
  is unnecessarily high, which leads to significantly poor accuracy compared to vanilla
  minwise hashing, especially when the data is sparse. In this paper, we provide a
  novel densification scheme which relies on carefully tailored 2-universal hashes.
  We show that the proposed scheme is variance-optimal, and without losing the runtime
  efficiency, it is significantly more accurate than existing densification techniques.
  As a result, we obtain a significantly efficient hashing scheme which has the same
  variance and collision probability as minwise hashing. Experimental evaluations
  on real sparse and high-dimensional datasets validate our claims. We believe that
  given the significant advantages, our method will replace minwise hashing implementations
  in practice.
layout: inproceedings
id: shrivastava17a
tex_title: Optimal Densification for Fast and Accurate Minwise Hashing
firstpage: 3154
lastpage: 3163
page: 3154-3163
order: 3154
cycles: false
editor:
- given: Doina
  family: Precup
- given: Yee Whye
  family: Teh
author:
- given: Anshumali
  family: Shrivastava
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
  link: http://proceedings.mlr.press/v70/shrivastava17a/shrivastava17a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
