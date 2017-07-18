---
title: Learning to Discover Sparse Graphical Models
booktitle: Proceedings of the 34th International Conference on Machine Learning
year: '2017'
volume: '70'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v70/belilovsky17a/belilovsky17a.pdf
url: http://proceedings.mlr.press/v70/belilovsky17.html
abstract: 'We consider structure discovery of undirected graphical models from observational
  data. Inferring likely structures from few examples is a complex task often requiring
  the formulation of priors and sophisticated inference procedures. Popular methods
  rely on estimating a penalized maximum likelihood of the precision matrix. However,
  in these approaches structure recovery is an indirect consequence of the data-fit
  term, the penalty can be difficult to adapt for domain-specific knowledge, and the
  inference is computationally demanding. By contrast, it may be easier to generate
  training samples of data that arise from graphs with the desired structure properties.
  We propose here to leverage this latter source of information as training data to
  learn a function, parametrized by a neural network, that maps empirical covariance
  matrices to estimated graph structures. Learning this function brings two benefits:
  it implicitly models the desired structure or sparsity properties to form suitable
  priors, and it can be tailored to the specific problem of edge structure discovery,
  rather than maximizing data likelihood. Applying this framework, we find our learnable
  graph-discovery method trained on synthetic data generalizes well: identifying relevant
  edges in both synthetic and real data, completely unknown at training time. We find
  that on genetics, brain imaging, and simulation data we obtain performance generally
  superior to analytical methods.'
layout: inproceedings
id: belilovsky17a
tex_title: Learning to Discover Sparse Graphical Models
firstpage: 440
lastpage: 448
page: 440-448
order: 440
cycles: false
editor:
- given: Doina
  family: Precup
- given: Yee Whye
  family: Teh
author:
- given: Eugene
  family: Belilovsky
- given: Kyle
  family: Kastner
- given: Gael
  family: Varoquaux
- given: Matthew B.
  family: Blaschko
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
  link: http://proceedings.mlr.press/v70/belilovsky17a/belilovsky17a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
