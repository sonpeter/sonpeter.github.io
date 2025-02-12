---
title: "Improving Adaptive Moment Optimization via Preconditioner Diagonalization"
category: articles
permalink: "/articles/adadiag/"
date: 01-10-2024
link: https://arxiv.org/abs/2502.07488
---
<b>Son Nguyen</b>, Bo Liu, Lizhang Chen, Qiang Liu

Abstract: Modern adaptive optimization methods, such as Adam and its variants, have emerged as the most widely used tools in deep learning over recent years. These algorithms offer automatic mechanisms for dynamically adjusting the update step based on estimates of gradient statistics. Compared to traditional algorithms like Stochastic Gradient Descent, these adaptive methods are typically more robust to model scale and hyperparameter tuning. However, the gradient statistics employed by these methods often do not leverage sufficient gradient covariance information, leading to suboptimal updates in certain directions of the parameter space and potentially slower convergence. In this work, we keep track of such covariance statistics in the form of a structured preconditioner matrix. Unlike other works, our approach does not apply direct approximations to estimate this matrix. We instead implement an invertible transformation that maps the preconditioner matrix into a new space where it becomes approximately diagonal. This enables a diagonal approximation of the preconditioner matrix in the transformed space, offering several computational advantages. Empirical results show that our approach can substantially enhance the convergence speed of the modern adaptive optimizers. Notably, for large language models like LLaMA, we can achieve a speedup of 2x compared to the baseline Adam. Additionally, our method can be integrated with memory-efficient optimizers like Adafactor to manage computational overhead.

