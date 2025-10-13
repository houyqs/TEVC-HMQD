# Evolutionary Heterogeneous Multitasking for Quality Diversity Optimization

## Abstract

Quality Diversity (QD) algorithms generate high-performance, behaviorally diverse solutions for complex optimization problems, but are typically limited to single tasks (with only one fitness function). Recent studies have used QD algorithms to simultaneously address multiple tasks with similar structures or the same parameterization within a single archive. Such multitasking attempts are limited by strict task parameterizations, the inability to handle different task dimensionalities, and limited transfer capabilities in non-linear behavior spaces, rendering it unsuitable for more general multitasking scenarios. 

To bridge this gap, this study proposes a heterogeneous multitasking framework for QD optimization (HMQD), where each task possesses an independent archive (feature space) and allows significant differences in fitness functions and feature spaces between tasks, focusing on finding suitable methods for transferring knowledge across multiple QD archives. HMQD utilizes generative models (in particular, variational auto-encoders) to capture the distribution of elite solutions and apply adaptive transfer methods for efficient heterogeneous multi-task optimization across different QD archives. We apply the HMQD framework to various QD algorithms and conduct extensive experiments on benchmarks, manipulators, and hexapod robot problems, confirming that HMQD outperforms single-task QD optimizers.

---

*Published in: IEEE Transactions on Evolutionary Computation*

📄 The paper is available at .
