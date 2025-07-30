---
abstract: In recent years, graph neural networks (GNNs) have achieved great success
  in the field of graph representation learning. Although prior work has shed light
  on the expressiveness of those models (i.e., whether they can distinguish pairs
  of non-isomorphic graphs), it is still not clear what structural information is
  encoded into the node representations that are learned by those models. In this
  paper, we address this gap by studying the node representations learned by four
  standard GNN models. We find that some models produce identical representations
  for all nodes, while the representations learned by other models are linked to some
  notion of walks of specific length that start from the nodes. We establish Lipschitz
  bounds for these models with respect to the number of (normalized) walks. Additionally,
  we investigate the influence of node features on the learned representations. We
  find that if the initial representations of all nodes point in the same direction,
  the representations learned at the k-th layer of the models are also related to
  the initial features of nodes that can be reached in exactly k steps. We also apply
  our findings to understand the phenomenon of oversquashing that occurs in GNNs.
  Our theoretical analysis is validated through experiments on synthetic and real-world
  datasets.
openreview: OjHWbOsrBk
section: Poster Presentations
software: https://github.com/giannisnik/gnn-representations
title: What Do GNNs Actually Learn? Towards Understanding Their Representations
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: nikolentzos25a
month: 0
tex_title: What Do GNNs Actually Learn? Towards Understanding Their Representations
firstpage: '5:1'
lastpage: '5:21'
page: 5:1-5:21
order: 5
cycles: false
bibtex_author: Nikolentzos, Giannis and Chatzianastasis, Michail and Vazirgiannis,
  Michalis
author:
- given: Giannis
  family: Nikolentzos
- given: Michail
  family: Chatzianastasis
- given: Michalis
  family: Vazirgiannis
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
pdf: https://raw.githubusercontent.com/mlresearch/v269/main/assets/nikolentzos25a/nikolentzos25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
