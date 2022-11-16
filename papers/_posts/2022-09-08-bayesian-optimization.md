---
layout: paper
title: "Bayesian optimization for demographic inference"
author: Ekaterina Noskova, Viacheslav Borovitskiy
journal: BioRxiv
journal_url: "https://doi.org/10.1101/2022.09.06.506809"
pdf: "https://www.biorxiv.org/content/10.1101/2022.09.06.506809v1.full.pdf"
code: "https://github.com/ctlab/GADMA"
---

### Abstract

**Motivation**
Inference of demographic histories of species and populations is one of the central problems in population genetics. It is usually stated as an optimization problem: find a model’s parameters that maximize a certain log-likelihood. This log-likelihood is often expensive to evaluate in terms of time and hardware resources, critically more so for larger population counts. Although genetic algorithm based solution have proven efficient for demographic inference in the past, it struggles to deal with log-likelihoods in the setting of more than three populations. Different tools are therefore needed to handle such scenarios.

**Results**
We introduce a new specialized optimization pipeline for demographic inference with time-consuming log-likelihood evaluations. It is based on Bayesian optimization, a prominent technique for optimizing expensive black box functions. Comparing to the existing widely used genetic algorithm solution, we demonstrate new pipeline’s superiority in time limited conditions for demographic inference with four and five populations when using log-likelihoods provided by the moments tool. Moreover, we expect this behavior to generalize just as well to other expensive-to-evaluate log-likelihood functions in the field.

**Availability**
The proposed method was implemented as part of the GADMA software framework and is freely and openly available on GitHub: https://github.com/ctlab/GADMA.
