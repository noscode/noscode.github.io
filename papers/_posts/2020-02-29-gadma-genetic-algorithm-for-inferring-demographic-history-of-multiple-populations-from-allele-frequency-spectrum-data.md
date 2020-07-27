---
layout: post
title: "GADMA: Genetic algorithm for inferring demographic history of multiple populations from allele frequency spectrum data"
author: Ekaterina Noskova
---

<a class="btn btn-outline-success" href="https://academic.oup.com/gigascience/article/9/3/giaa005/5768731"> PDF </a>
<a class="btn btn-outline-success" href="https://github.com/ctlab/GADMA"> Code </a>

### Abstract
**Background**

The demographic history of any population is imprinted in the genomes of the individuals that make up the population. One of the most popular and convenient representations of genetic information is the allele frequency spectrum (AFS), the distribution of allele frequencies in populations. The joint AFS is commonly used to reconstruct the demographic history of multiple populations, and several methods based on diffusion approximation (e.g., ∂a∂i) and ordinary differential equations (e.g., moments) have been developed and applied for demographic inference. These methods provide an opportunity to simulate AFS under a variety of researcher-specified demographic models and to estimate the best model and associated parameters using likelihood-based local optimizations. However, there are no known algorithms to perform global searches of demographic models with a given AFS.

**Results**

Here, we introduce a new method that implements a global search using a genetic algorithm for the automatic and unsupervised inference of demographic history from joint AFS data. Our method is implemented in the software GADMA (Genetic Algorithm for Demographic Model Analysis, https://github.com/ctlab/GADMA).

**Conclusions**

We demonstrate the performance of GADMA by applying it to sequence data from humans and non-model organisms and show that it is able to automatically infer a demographic model close to or even better than the one that was previously obtained manually. Moreover, GADMA is able to infer multiple demographic models at different local optima close to the global one, providing a larger set of possible scenarios to further explore demographic history.
