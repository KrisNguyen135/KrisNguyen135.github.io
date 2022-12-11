---
title: "Local Bayesian optimization via maximizing probability of descent"
collection: publications
permalink: /publication/nguyen2022local
excerpt: 'We tackle local Bayesian optimization for high-dimensional problems and propose a novel and principled method maximizing the probability that we will make progres.'
date: 2022-10-21
venue: 'Advances in Neural Information Processing Systems (NeurIPS)'
citation: 'Quan Nguyen, Kaiwen Wu, Jacob R. Gardner, and Roman Garnett. Local Bayesian optimization via maximizing probability of descent. <i>Advances in Neural Information Processing Systems (NeurIPS)</i>, 2022.'
---
Local optimization presents a promising approach to expensive, high-dimensional black-box optimization by sidestepping the need to globally explore the search space.
For objective functions whose gradient cannot be evaluated directly, Bayesian optimization offers one solution – we construct a probabilistic model of the objective, design a policy to learn about the gradient at the current location, and use the resulting information to navigate the objective landscape.
Previous work has realized this scheme by minimizing the variance in the estimate of the gradient, then moving in the direction of the expected gradient.
In this paper, we re-examine and refine this approach.
We demonstrate that, surprisingly, the expected value of the gradient is not always the direction maximizing the probability of descent, and in fact, these directions may be nearly orthogonal.
This observation then inspires an elegant optimization scheme seeking to maximize the probability of descent while moving in the direction of most-probable descent.
Experiments on both synthetic and real-world objectives show that our method outperforms previous realizations of this optimization scheme and is competitive against other, significantly more complicated baselines.

[Download paper here](https://arxiv.org/abs/2210.11662)
