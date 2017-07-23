---
title: Scalable Multi-Class Gaussian Process Classification using Expectation Propagation
booktitle: Proceedings of the 34th International Conference on Machine Learning
year: '2017'
volume: '70'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v70/villacampa-calvo17a/villacampa-calvo17a.pdf
url: http://proceedings.mlr.press/v70/villacampa-calvo17a.html
abstract: This paper describes an expectation propagation (EP) method for multi-class
  classification with Gaussian processes that scales well to very large datasets.
  In such a method the estimate of the log-marginal-likelihood involves a sum across
  the data instances. This enables efficient training using stochastic gradients and
  mini-batches. When this type of training is used, the computational cost does not
  depend on the number of data instances N. Furthermore, extra assumptions in the
  approximate inference process make the memory cost independent of N. The consequence
  is that the proposed EP method can be used on datasets with millions of instances.
  We compare empirically this method with alternative approaches that approximate
  the required computations using variational inference. The results show that it
  performs similar or even better than these techniques, which sometimes give significantly
  worse predictive distributions in terms of the test log-likelihood. Besides this,
  the training process of the proposed approach also seems to converge in a smaller
  number of iterations.
layout: inproceedings
id: villacampa-calvo17a
tex_title: Scalable Multi-Class {G}aussian Process Classification using Expectation
  Propagation
bibtex_author: Carlos Villacampa-Calvo and Daniel Hern{\'a}ndez-Lobato
firstpage: 3550
lastpage: 3559
page: 3550-3559
order: 3550
cycles: false
editor:
- given: Doina
  family: Precup
- given: Yee Whye
  family: Teh
author:
- given: Carlos
  family: Villacampa-Calvo
- given: Daniel
  family: Hernández-Lobato
date: 2017-07-17
container-title: Proceedings of the 34th International Conference on Machine Learning
genre: inproceedings
issued:
  date-parts:
  - 2017
  - 7
  - 17
extras:
- label: Supplementary ZIP
  link: http://proceedings.mlr.press/v70/villacampa-calvo17a/villacampa-calvo17a-supp.zip
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
