---
title: Parallel and Distributed Thompson Sampling for Large-scale Accelerated Exploration
  of Chemical Space
booktitle: Proceedings of the 34th International Conference on Machine Learning
year: '2017'
volume: '70'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v70/hernandez-lobato17a/hernandez-lobato17a.pdf
url: http://proceedings.mlr.press/v70/hernandez-lobato17a.html
abstract: Chemical space is so large that brute force searches for new interesting
  molecules are infeasible. High-throughput virtual screening via computer cluster
  simulations can speed up the discovery process by collecting very large amounts
  of data in parallel, e.g., up to hundreds or thousands of parallel measurements.
  Bayesian optimization (BO) can produce additional acceleration by sequentially identifying
  the most useful simulations or experiments to be performed next. However, current
  BO methods cannot scale to the large numbers of parallel measurements and the massive
  libraries of molecules currently used in high-throughput screening. Here, we propose
  a scalable solution based on a parallel and distributed implementation of Thompson
  sampling (PDTS). We show that, in small scale problems, PDTS performs similarly
  as parallel expected improvement (EI), a batch version of the most widely used BO
  heuristic. Additionally, in settings where parallel EI does not scale, PDTS outperforms
  other scalable baselines such as a greedy search, $\epsilon$-greedy approaches and
  a random search method. These results show that PDTS is a successful solution for
  large-scale parallel BO.
layout: inproceedings
id: hernandez-lobato17a
tex_title: Parallel and Distributed Thompson Sampling for Large-scale Accelerated
  Exploration of Chemical Space
bibtex_author: Jos{\'e} Miguel Hern{\'a}ndez-Lobato and James Requeima and Edward
  O. Pyzer-Knapp and Al{\'a}n Aspuru-Guzik
firstpage: 1470
lastpage: 1479
page: 1470-1479
order: 1470
cycles: false
editor:
- given: Doina
  family: Precup
- given: Yee Whye
  family: Teh
author:
- given: José Miguel
  family: Hernández-Lobato
- given: James
  family: Requeima
- given: Edward O.
  family: Pyzer-Knapp
- given: Alán
  family: Aspuru-Guzik
date: 2017-07-17
container-title: Proceedings of the 34th International Conference on Machine Learning
genre: inproceedings
issued:
  date-parts:
  - 2017
  - 7
  - 17
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
