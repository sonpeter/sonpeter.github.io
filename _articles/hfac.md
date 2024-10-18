---
title: "Memory-Efficient Optimization with Factorized Hamiltonian Descent"
category: articles
permalink: "/articles/hfac/"
date: 24-06-2024
link: https://arxiv.org/abs/2406.09958
---
<b>Son Nguyen</b>, Lizhang Chen, Bo Liu, Qiang Liu

Abstract: Modern deep learning heavily depends on adaptive optimizers such as Adam and its variants, which are renowned for their capacity to handle model scaling and streamline hyperparameter tuning. However, these algorithms typically experience high memory overhead caused by the accumulation of optimization states, leading to a critical challenge in training large-scale network models. In this study, we introduce a novel adaptive optimizer, H-Fac, which incorporates a memory-efficient factorization approach to address this challenge. By employing a rank-1 parameterization for both momentum and scaling parameter estimators, H-Fac reduces memory costs to a sublinear level while maintaining competitive performance across a wide range of architectures. We develop our algorithms based on principles derived from Hamiltonian dynamics, providing robust theoretical underpinnings in optimization dynamics and convergence guarantees. These optimization algorithms are designed to be both straightforward and adaptable, facilitating easy implementation in diverse settings.

