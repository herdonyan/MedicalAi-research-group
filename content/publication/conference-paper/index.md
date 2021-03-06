---
title: Sparse Bayesian classification and feature selection for biological
  expression data with high correlations
abstract: "Classification models built on biological expression data are
  increasingly used to predict distinct disease subtypes. Selected features that
  separate sample groups can be the candidates of biomarkers, helping us to
  discover biological functions/pathways. However, three challenges are
  associated with building a robust classification and feature selection model:
  1) the number of significant biomarkers is much smaller than that of measured
  features for which the search will be exhaustive; 2) current biological
  expression data are big in both sample size and feature size which will worsen
  the scalability of any search algorithms; and 3) expression profiles of
  certain features are typically highly correlated which may prevent to
  distinguish the predominant features. Unfortunately, most of the existing
  algorithms are partially addressing part of these challenges but not as a
  whole. In this paper, we propose a unified framework to address the above
  challenges. The classification and feature selection problem is first
  formulated as a nonconvex optimisation problem. Then the problem is relaxed
  and solved iteratively by a sequence of convex optimisation procedures which
  can be distributed computed and therefore allows the efficient implementation
  on advanced infrastructures. To illustrate the competence of our method over
  others, we first analyse a randomly generated simulation dataset under various
  conditions. We then analyse a real gene expression dataset on embryonal
  tumour. Further downstream analysis, such as functional annotation and pathway
  analysis, are performed on the selected features which elucidate several
  biological findings."
slides: null
url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
publication_types:
  - "2"
authors:
  - Xian YANG
  - Wei PAN
  - Yike GUO
publication: In Public Library of Science San Francisco, CA USA
featured: false
tags: []
projects: []
summary: The simulation results show that our method can effectively select
  features with high classification accuracy. In contrast to other methods,
  correlated features can be successfully detected. A real gene expression data
  from the embryonal brain tumour study is then used to demonstrate the
  applicability of our method. In the results, we first show that the selected
  features are correlated by looking at the heatmap of correlation matrix. Then
  we compare the weights estimated from our method with p values from statistic
  test and fold changes. We find that our method can successfully identify
  up-regulated and down-regulated genes with positive and negative weights,
  respectively. Moreover, we find that most features which are statistically
  significant have non-zero weights in our model. The gene list generated by our
  method can be used to do functional analysis. We show the detected gene
  ontology terms, which are consistent with the findings in previous study. In
  conclusion, the classification and feature selection method proposed in this
  paper can effectively handle highly correlated biological expression dataset,
  in order to predict distinct disease subtypes and select candidates of
  biomarkers simultaneously.
url_dataset: "#"
url_project: ""
publication_short: In Public Library of Science San Francisco, CA USA
url_source: "#"
url_video: "#"
date: 2021-12-03T11:29:16.159Z
url_slides: ""
links:
  - name: Custom Link
    url: http://example.org
image:
  caption: ""
  focal_point: ""
  preview_only: false
publishDate: 2017-01-01T00:00:00.000Z
url_poster: "#"
url_code: "#"
doi: ""
---
https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0189541