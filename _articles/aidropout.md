---
title: "Adaptive Infinite Dropout for Noisy and Sparse Data Streams"
category: articles
permalink: "/articles/aidropout/"
venue: "Machine Learning Journal"
date: 19-04-2022
link: https://link.springer.com/article/10.1007/s10994-022-06169-w
---

Ha Nguyen\*, Hoang Pham\*, **Son Nguyen**\* Linh Ngo, Khoat Than

Abstract: The ability to analyze data streams which arrive sequentially and possibly infinitely is increasingly vital in various online applications. However, data streams pose various challenges, including sparse and noisy data, and concept drifts which easily mislead a learning method. This paper develops a simple but robust framework to efficiently tackle these problems, called Adaptive Infinite Dropout (aiDropout). Our framework uses a dropout technique in a recursive Bayesian approach in order to create a flexible mechanism for balancing between old and new information. In detail, the recursive Bayesian approach imposes a constraint on the model parameters to make a regularization term between the current and previous minibatches. Then, dropout whose drop rate is autonomously learned, can adjust the constraint to new data. Thanks to the ability to reduce overfitting and the ensemble property of Dropout, our framework obtains better generalization, thus effectively handles undesirable effects of noise and sparsity. In particular, theoretical analyses expose aiDropout as a data-dependent regularization, therefore it can adapt quickly to sudden changes from data streams. Extensive experiments show that aiDropout significantly outperforms the state-of-the-art baselines on a variety of tasks such as supervised and unsupervised learning.
