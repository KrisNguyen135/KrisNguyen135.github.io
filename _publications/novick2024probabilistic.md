---
title: "Probabilistic Prediction of Material Stability: Integrating Convex Hulls into Active Learning"
collection: publications/
permalink: /publication/novick2024probabilistic
excerpt: ''
date: 2024-9-18
venue: 'Materials Horizons'
citation: 'Andrew Novick, Diana Cai, Quan Nguyen, Roman Garnett, Ryan P Adams, Eric Toberer. Probabilistic Prediction of Material Stability: Integrating Convex Hulls into Active Learning. <i>Materials Horizons</i>, 2024.'
---
Active learning is a valuable tool for efficiently exploring complex spaces, finding a variety of uses in materials science. However, the determination of convex hulls for phase diagrams does not neatly fit into traditional active learning approaches due to their global nature. Specifically, the thermodynamic stability of a material is not simply a function of its own energy, but rather requires energetic information from all other competing compositions and phases. Here we present Convex hull-aware Active Learning (CAL), a novel Bayesian algorithm that chooses experiments to minimize the uncertainty in the convex hull. CAL prioritizes compositions that are close to or on the hull, leaving significant uncertainty in other compositions that are quickly determined to be irrelevant to the convex hull. The convex hull can thus be predicted with significantly fewer observations than approaches that focus solely on energy. Intrinsic to this Bayesian approach is uncertainty quantification in both the convex hull and all subsequent predictions (e.g., stability and chemical potential). By providing increased search efficiency and uncertainty quantification, CAL can be readily incorporated into the emerging paradigm of uncertainty-based workflows for thermodynamic prediction.

[Download paper here](https://arxiv.org/pdf/2402.15582)
