---
layout: paper
title: "Bayesian optimization for demographic inference"
author: Ekaterina Noskova, Viacheslav Borovitskiy
journal: "G3 Genes|Genomes|Genetics"
journal_url: "https://doi.org/10.1093/g3journal/jkad080"
pdf: "https://academic.oup.com/g3journal/article-pdf/13/7/jkad080/50819663/jkad080.pdf"
code: "https://github.com/ctlab/GADMA"
---

### Abstract

Inference of demographic histories of species and populations is one of the central problems in population genetics. It is usually stated as an optimization problem: find a model’s parameters that maximize a certain log-likelihood. This log-likelihood is often expensive to evaluate in terms of time and hardware resources, critically more so for larger population counts. Although genetic algorithm-based solution has proven efficient for demographic inference in the past, it struggles to deal with log-likelihoods in the setting of more than three populations. Different tools are therefore needed to handle such scenarios. We introduce a new optimization pipeline for demographic inference with time consuming log-likelihood evaluations. It is based on Bayesian optimization, a prominent technique for optimizing expensive black box functions. Comparing to the existing widely used genetic algorithm solution, we demonstrate new pipeline’s superiority in the limited time budget setting with four and five populations, when using the log-likelihoods provided by the *moments* tool.
