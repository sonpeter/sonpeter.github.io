---
title: "Structured Dropout Variational Inference for Bayesian Neural Networks"
category: articles
permalink: "/articles/vsd/"
venue: "Advances in Neural Information Processing Systems (NeurIPS)"
date: 15-01-2022
link: https://arxiv.org/abs/2102.07927
---

<b>Son Nguyen</b>, Duong Nguyen, Khai Nguyen, Nhat Ho, Khoat Than, Hung Bui

Abstract: Approximate inference in deep Bayesian networks exhibits a dilemma of how to yield high fidelity posterior approximations while maintaining computational efficiency and scalability. We tackle this challenge by introducing a novel variational structured approximation inspired by the Bayesian interpretation of Dropout regularization. Concretely, we focus on the inflexibility of the factorized structure in Dropout posterior and then propose an improved method called Variational Structured Dropout (VSD). VSD employs an orthogonal transformation to learn a structured representation on the variational noise and consequently induces statistical dependencies in the approximate posterior. Theoretically, VSD successfully addresses the pathologies of previous Variational Dropout methods and thus offers a standard Bayesian justification. We further show that VSD induces an adaptive regularization term with several desirable properties which contribute to better generalization. Finally, we conduct extensive experiments on standard benchmarks to demonstrate the effectiveness of VSD over state-of-the-art variational methods on predictive accuracy, uncertainty estimation, and out-of-distribution detection.
