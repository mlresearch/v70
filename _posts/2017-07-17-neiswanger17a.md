---
title: Post-Inference Prior Swapping
booktitle: Proceedings of the 34th International Conference on Machine Learning
year: '2017'
volume: '70'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v70/neiswanger17a/neiswanger17a.pdf
url: http://proceedings.mlr.press/v70/neiswanger17a.html
abstract: 'While Bayesian methods are praised for their ability to incorporate useful
  prior knowledge, in practice, convenient priors that allow for computationally cheap
  or tractable inference are commonly used. In this paper, we investigate the following
  question: for a given model, is it possible to compute an inference result with
  any convenient false prior, and afterwards, given any target prior of interest,
  quickly transform this result into the target posterior? A potential solution is
  to use importance sampling (IS). However, we demonstrate that IS will fail for many
  choices of the target prior, depending on its parametric form and similarity to
  the false prior. Instead, we propose prior swapping, a method that leverages the
  pre-inferred false posterior to efficiently generate accurate posterior samples
  under arbitrary target priors. Prior swapping lets us apply less-costly inference
  algorithms to certain models, and incorporate new or updated prior information “post-inference”.
  We give theoretical guarantees about our method, and demonstrate it empirically
  on a number of models and priors.'
layout: inproceedings
id: neiswanger17a
tex_title: Post-Inference Prior Swapping
bibtex_author: Willie Neiswanger and Eric Xing
firstpage: 2594
lastpage: 2602
page: 2594-2602
order: 2594
cycles: false
editor:
- given: Doina
  family: Precup
- given: Yee Whye
  family: Teh
author:
- given: Willie
  family: Neiswanger
- given: Eric
  family: Xing
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
  link: http://proceedings.mlr.press/v70/neiswanger17a/neiswanger17a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
