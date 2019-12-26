---
layout: post
categories: posts
title: Dimensionality reduction, categorized
tags: [video, unsupervised learning, python]
date-string: DECEMBER 26, 2019
---
The Canadian mathematician Leland McInnes ([@leland_mcinnes](https://twitter.com/leland_mcinnes?lang=en)), who's known for his work on designing and popularizing the use of UMAP [^1] for dimensionality reduction of single cell data, gave an insightful rundown of the key approaches of dimensionality reduction---finding matrix factorization or neighbor graphs---illustrated by the various algorithms which often feature mesmerizing names. In the talk, he mentioned the nice booklet by Udell et al [^2] on low-rank modelling of high-dimensional data, which is also very worth reading.
<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/9iol3Lk6kyU" frameborder="0" allowfullscreen></iframe>
</center>

[^1]: UMAP stands for *uniform manifold approximation and projection* and has been described [here](https://arxiv.org/abs/1802.03426) with example in a [Nature Biotechnology publication](https://www.nature.com/articles/nbt.4314) and implemented in the Python package [scanpy](https://scanpy.readthedocs.io/en/stable/).

[^2]: M. Udell, C. Horn, R. Zadeh and S. Boyd, Generalized Low Rank Models, Foundations and Trends in Machine Learning 9, 1–118 (2016). [link](https://stanford.edu/~boyd/papers/pdf/glrm.pdf) from a co-author and [link](https://arxiv.org/abs/1410.0342) from arXiv.