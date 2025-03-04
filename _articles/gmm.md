---
title: "Reducing Catastrophic Forgetting in Neural Networks via Gaussian Mixture Approximation"
category: articles
permalink: "/articles/gmm/"
venue: "Pacific-Asia Conference on Knowledge Discovery and Data Mining (PAKDD)"
date: 16-05-2020
link: https://dl.acm.org/doi/10.1007/978-3-031-05933-9_9
---

Hoang Phan, Anh Phan Tuan, <b>Son Nguyen</b>, Ngo Van Linh, Khoat Than

Our paper studies the continual learning (CL) problems in which data comes in sequence and the trained models are expected to be capable of utilizing existing knowledge to solve new tasks without losing performance on previous ones. This also poses a central difficulty in the field of CL, termed as Catastrophic Forgetting (CF). In an attempt to address this problem, Bayesian methods provide a powerful principle, focusing on the inference scheme to estimate the importance of weights. Variational inference (VI), one of the most widely used methods within this vein, approximates the intractable posterior by a factorized distribution, thus offering computational efficiency. Notwithstanding many state-of-the-art performances in practice, this simple assumption about the posterior distribution typically limits the model capacity to some extent. In this paper, we introduce a novel approach to mitigate forgetting in the Bayesian approach via enriching the posterior distribution with mixture models, which intuitively promotes neural networks to acquire knowledge from multiple tasks at a time. Moreover, in order to reduce the model’s complexity growth when the number of components increases, we propose a solution that conducts low-rank decomposition on the variance of each component based on neural matrix factorization. Extensive experiments show that our method yields significant improvements compared to prior works on different benchmarks
