---
title: "Towards Stability of Parameter-free Optimization"
collection: publications
permalink: /publication/paper-4
excerpt: 'Authors: Yijiang Pang, Shuyang Yu, Bao Hoang, Jiayu Zhou.'
date: 2024-01-01
venue: 'arXiv'
paperurl: 'https://arxiv.org/pdf/2405.04376'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Hyperparameter tuning, particularly the selection of an appropriate learning rate in adaptive gradient training methods, remains a challenge. To tackle this challenge, in this paper, we propose a novel parameter-free optimizer, AdamG (Adam with the golden step size), designed to automatically adapt to diverse optimization problems without manual tuning. The core technique underlying AdamG is our golden step size derived for the AdaGrad-Norm algorithm, which is expected to help AdaGrad-Norm preserve the tuning-free convergence and approximate the optimal step size in expectation w.r.t. various optimization scenarios. To better evaluate tuning-free performance, we propose a novel evaluation criterion, stability, to comprehensively assess the efficacy of parameter-free optimizers in addition to classical performance criteria. Empirical results demonstrate that compared with other parameter-free baselines, AdamG achieves superior performance, which is consistently on par with Adam using a manually tuned learning rate across various optimization tasks.