---
title: "Infinite Dropout for training Bayesian models from data streams"
category: articles
permalink: "/articles/IDROPOUT/"
venue: "IEEE International Conference on Big Data (Big Data) 2019"
link: https://ieeexplore.ieee.org/document/9005544
---

[comment]: <> (<a href="https://ieeexplore.ieee.org/document/9005544">Arxiv</a>.)
<b>Son Nguyen</b>, Tung Nguyen, Linh Ngo, Khoat Than

Abstract: The ability to continuously train Bayesian models in streaming environments is highly important in the era of big data. However, it has to face the famous stability-plasticity dilemma and the problem of noisy and sparse data. We propose a novel and easy-to-implement framework, called Infinite Dropout (iDropout), to address these challenges. iDropout has an easy mechanism to balance between old and new information, which allows models to trade off stability against plasticity. Thanks to the ability to reduce overfitting and the ensemble property of Dropout, our framework obtains better generalization, thus effectively handles undesirable effects of noise and sparsity. Further, iDropout is able to adapt quickly to abnormal changes in data streams. We theoretically analyze the equivalence of Dropout in iDropout to a regularizer, well applied to a much larger context than what was known before. Extensive experiments show that iDropout significantly outperforms the state-of-the-art baselines.
