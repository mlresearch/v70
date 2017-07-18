---
title: Learned Optimizers that Scale and Generalize
booktitle: Proceedings of the 34th International Conference on Machine Learning
year: '2017'
volume: '70'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v70/wichrowska17a/wichrowska17a.pdf
url: http://proceedings.mlr.press/v70/wichrowska17.html
abstract: Learning to learn has emerged as an important direction for achieving artificial
  intelligence. Two of the primary barriers to its adoption are an inability to scale
  to larger problems and a limited ability to generalize to new tasks. We introduce
  a learned gradient descent optimizer that generalizes well to new tasks, and which
  has significantly reduced memory and computation overhead. We achieve this by introducing
  a novel hierarchical RNN architecture, with minimal per-parameter overhead, augmented
  with additional architectural features that mirror the known structure of optimization
  tasks. We also develop a meta-training ensemble of small, diverse, optimization
  tasks capturing common properties of loss landscapes. The optimizer learns to outperform
  RMSProp/ADAM on problems in this corpus. More importantly, it performs comparably
  or better when applied to small convolutional neural networks, despite seeing no
  neural networks in its meta-training set. Finally, it generalizes to train Inception
  V3 and ResNet V2 architectures on the ImageNet dataset for thousands of steps, optimization
  problems that are of a vastly different scale than those it was trained on.
layout: inproceedings
id: wichrowska17a
tex_title: Learned Optimizers that Scale and Generalize
firstpage: 3751
lastpage: 3760
page: 3751-3760
order: 3751
cycles: false
editor:
- given: Doina
  family: Precup
- given: Yee Whye
  family: Teh
author:
- given: Olga
  family: Wichrowska
- given: Niru
  family: Maheswaranathan
- given: Matthew W.
  family: Hoffman
- given: Sergio Gómez
  family: Colmenarejo
- given: Misha
  family: Denil
- given: Nando
  family: Freitas
- given: Jascha
  family: Sohl-Dickstein
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
  link: http://proceedings.mlr.press/v70/wichrowska17a/wichrowska17a-supp.zip
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
