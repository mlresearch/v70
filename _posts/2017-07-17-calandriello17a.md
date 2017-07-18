---
title: Second-Order Kernel Online Convex Optimization with Adaptive Sketching
booktitle: Proceedings of the 34th International Conference on Machine Learning
year: '2017'
volume: '70'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v70/calandriello17a/calandriello17a.pdf
url: http://proceedings.mlr.press/v70/calandriello17.html
abstract: Kernel online convex optimization (KOCO) is a framework combining the expressiveness
  of non-parametric kernel models with the regret guarantees of online learning. First-order
  KOCO methods such as functional gradient descent require only $O(t)$ time and space
  per iteration, and, when the only information on the losses is their convexity,
  achieve a minimax optimal $O(\sqrtT)$ regret. Nonetheless, many common losses in
  kernel problems, such as squared loss, logistic loss, and squared hinge loss posses
  stronger curvature that can be exploited. In this case, second-order KOCO methods
  achieve $O(\log(\mathrmDet(K)))$ regret, which we show scales as $O(deff \log T)$,
  where $deff$ is the effective dimension of the problem and is usually much smaller
  than $O(\sqrtT)$. The main drawback of second-order methods is their much higher
  $O(t^2)$ space and time complexity. In this paper, we introduce kernel online Newton
  step (KONS), a new second-order KOCO method that also achieves $O(deff\log T)$ regret.
  To address the computational complexity of second-order methods, we introduce a
  new matrix sketching algorithm for the kernel matrix $K$, and show that for a chosen
  parameter $γ≤1$ our Sketched-KONS reduces the space and time complexity by a factor
  of $γ^2$ to $O(t^2γ^2)$ space and time per iteration, while incurring only $1/γ$
  times more regret.
layout: inproceedings
id: calandriello17a
tex_title: Second-Order Kernel Online Convex Optimization with Adaptive Sketching
firstpage: 645
lastpage: 653
page: 645-653
order: 645
cycles: false
editor:
- given: Doina
  family: Precup
- given: Yee Whye
  family: Teh
author:
- given: Daniele
  family: Calandriello
- given: Alessandro
  family: Lazaric
- given: Michal
  family: Valko
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
  link: http://proceedings.mlr.press/v70/calandriello17a/calandriello17a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
