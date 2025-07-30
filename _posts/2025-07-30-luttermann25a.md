---
abstract: Lifted probabilistic inference exploits symmetries in a probabilistic model
  to allow for tractable probabilistic inference with respect to domain sizes of logical
  variables. We found that the current state-of-the-art algorithm to construct a lifted
  representation in form of a parametric factor graph misses symmetries between factors
  that are exchangeable but scaled differently, thereby leading to a less compact
  representation. In this paper, we propose a generalisation of the advanced colour
  passing (ACP) algorithm, which is the state of the art to construct a parametric
  factor graph. Our proposed algorithm allows for potentials of factors to be scaled
  arbitrarily and efficiently detects more symmetries than the original ACP algorithm.
  By detecting strictly more symmetries than ACP, our algorithm significantly reduces
  online query times for probabilistic inference when the resulting model is applied,
  which we also confirm in our experiments.
openreview: KhQdqsnRc0
section: Poster Presentations
software: https://github.com/StatisticalRelationalAI/AlphaAdvancedColourPassing
title: 'Lifted Model Construction Without Normalisation: A Vectorised Approach to
  Exploit Symmetries in Factor Graphs'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: luttermann25a
month: 0
tex_title: 'Lifted Model Construction Without Normalisation: A Vectorised Approach
  to Exploit Symmetries in Factor Graphs'
firstpage: '46:1'
lastpage: '46:17'
page: 46:1-46:17
order: 46
cycles: false
bibtex_author: Luttermann, Malte and M{\"o}ller, Ralf and Gehrke, Marcel
author:
- given: Malte
  family: Luttermann
- given: Ralf
  family: Möller
- given: Marcel
  family: Gehrke
date: 2025-07-30
address:
container-title: Proceedings of the Third Learning on Graphs Conference
volume: '269'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 7
  - 30
pdf: https://raw.githubusercontent.com/mlresearch/v269/main/assets/luttermann25a/luttermann25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
