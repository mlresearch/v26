---
title: Stumping along a Summary for Exploration & Exploitation Challenge 2011
abstract: 'The  \emph{Pascal Exploration & Exploitation challenge 2011} seeks to evaluate
  algorithms for the online website content selection problem. This article presents
  the solution we used to achieve second place in this challenge and some side-experiments
  we performed. The methods we evaluated are all structured in three layers. The first
  layer provides an online summary of the data stream for continuous and nominal data.
  Continuous data are handled using an online quantile summary. Nominal data are summarized
  with a hash-based counting structure. With these techniques, we managed to build
  an accurate stream summary with a small memory footprint. The second layer uses
  the summary to build predictors. We exploited several kinds of trees from simple
  decision stumps to deep multivariate ones. For the last layer, we explored several
  combination strategies: online bagging, exponential weighting, linear ranker, and
  simple averaging.'
pdf: "./salperwyck12a/salperwyck12a.pdf"
layout: inproceedings
key: salperwyck12a
month: 0
firstpage: 86
lastpage: 97
origpdf: http://jmlr.org/proceedings/papers/v26/salperwyck12a/salperwyck12a.pdf
sections: 
authors:
- given: Christophe
  family: Salperwyck
- given: Tanguy
  family: Urvoy
---
