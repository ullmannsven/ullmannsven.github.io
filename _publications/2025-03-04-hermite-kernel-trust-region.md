---
title: "A trust-region framework for optimization using Hermite kernel surrogate models"
collection: publications
category: preprints
permalink: /publication/2025-hermite-kernel-trust-region
excerpt: 'A trust-region optimization method that uses Hermite kernel surrogates and the power function to reduce the number of expensive full-order model evaluations, with proven convergence to a stationary point.'
date: 2025-03-04
venue: 'Submitted'
citation: 'S. Ullmann, T. Ehring, R. Herkert, B. Haasdonk. &quot;A trust-region framework for optimization using Hermite kernel surrogate models.&quot; Submitted.'
---

In this work, we present a trust-region optimization framework that employs Hermite kernel surrogate models. The method targets optimization problems with computationally demanding objective functions, for which direct optimization is often impractical due to expensive function evaluations. To address these challenges, we leverage a trust-region strategy, where the objective function is approximated by an efficient surrogate model within a local neighborhood of the current iterate. In particular, we construct the surrogate using Hermite kernel interpolation and define the trust-region based on the so-called Power function. As mesh-free techniques, kernel-based methods are naturally suited for medium- to high-dimensional problems. Furthermore, the Hermite formulation incorporates gradient information, enabling precise gradient estimates that are crucial for many optimization algorithms. We prove that the proposed algorithm converges to a stationary point, and we demonstrate its effectiveness through numerical experiments, which illustrate the convergence behavior as well as the efficiency gains compared to direct optimization.

**Code:** [github.com/ullmannsven/A-Trust-Region-framework-for-optimization-using-Hermite-kernel-surrogate-models](https://github.com/ullmannsven/A-Trust-Region-framework-for-optimization-using-Hermite-kernel-surrogate-models)
