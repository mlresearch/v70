---
title: Device Placement Optimization with Reinforcement Learning
booktitle: Proceedings of the 34th International Conference on Machine Learning
year: '2017'
volume: '70'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v70/mirhoseini17a/mirhoseini17a.pdf
url: http://proceedings.mlr.press/v70/mirhoseini17a.html
abstract: The past few years have witnessed a growth in size and computational requirements
  for training and inference with neural networks. Currently, a common approach to
  address these requirements is to use a heterogeneous distributed environment with
  a mixture of hardware devices such as CPUs and GPUs. Importantly, the decision of
  placing parts of the neural models on devices is often made by human experts based
  on simple heuristics and intuitions. In this paper, we propose a method which learns
  to optimize device placement for TensorFlow computational graphs. Key to our method
  is the use of a sequence-to-sequence model to predict which subsets of operations
  in a TensorFlow graph should run on which of the available devices. The execution
  time of the predicted placements is then used as the reward signal to optimize the
  parameters of the sequence-to-sequence model. Our main result is that on Inception-V3
  for ImageNet classification, and on RNN LSTM, for language modeling and neural machine
  translation, our model finds non-trivial device placements that outperform hand-crafted
  heuristics and traditional algo-rithmic methods.
layout: inproceedings
id: mirhoseini17a
tex_title: Device Placement Optimization with Reinforcement Learning
firstpage: 2430
lastpage: 2439
page: 2430-2439
order: 2430
cycles: false
editor:
- given: Doina
  family: Precup
- given: Yee Whye
  family: Teh
author:
- given: Azalia
  family: Mirhoseini
- given: Hieu
  family: Pham
- given: Quoc V.
  family: Le
- given: Benoit
  family: Steiner
- given: Rasmus
  family: Larsen
- given: Yuefeng
  family: Zhou
- given: Naveen
  family: Kumar
- given: Mohammad
  family: Norouzi
- given: Samy
  family: Bengio
- given: Jeff
  family: Dean
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
