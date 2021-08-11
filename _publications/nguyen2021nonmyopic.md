---
title: "Nonmyopic Multifidelity Active Search"
collection: publications
permalink: /publication/nguyen2021nonmyopic
excerpt: 'We extend the active search problem to the multifidelity setting in which multiple oracles may be queried simultaneously at different costs and accuracies.'
date: 2021-07-18
venue: 'International Conference on Machine Learning'
citation: 'Quan Nguyen, Arghavan Modiri, and Roman Garnett. Nonmyopic Multifidelity Active Search. <i> International Conference on Machine Learning (ICML)</i>, 2021.'
---
Active search is a learning paradigm where we seek to identify as many members of a rare, valuable class as possible given a labeling budget.
Previous work on active search has assumed access to a faithful (and expensive) oracle reporting experimental results.
However, some settings offer access to cheaper surrogates such as computational simulation that may aid in the search.
We propose a model of <i>multifidelity</i> active search, as well as a novel, computationally efficient policy for this setting that is motivated by state-of-the-art classical policies.
Our policy is nonmyopic and budget aware, allowing for a dynamic tradeoff between
exploration and exploitation.
We evaluate the performance of our solution on real-world datasets and demonstrate significantly better performance than natural benchmarks.

[Download paper here](http://proceedings.mlr.press/v139/nguyen21f.html)
