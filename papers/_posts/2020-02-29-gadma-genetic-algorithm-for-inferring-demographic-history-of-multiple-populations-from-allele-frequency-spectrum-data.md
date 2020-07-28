---
layout: paper
title: "GADMA: Genetic algorithm for inferring demographic history of multiple populations from allele frequency spectrum data"
author: Ekaterina Noskova, Vladimir Ulyantsev, Klaus-Peter Koepfli, Stephen J O’Brien, Pavel Dobrynin
journal: GigaScience
journal_url: "https://academic.oup.com/gigascience/article/9/3/giaa005/5768731"
pdf: https://watermark.silverchair.com/giaa005.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAr0wggK5BgkqhkiG9w0BBwagggKqMIICpgIBADCCAp8GCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMsIKP2bqT93A_A7M5AgEQgIICcL8YA1R3ndvEHgklAgkZyhY-qWJQZ9mctwwtGH_k9n3Sai-qL6aFaguwbXonkpLZMb0L9xRwuBUDRrYy6p1Pbn4QYtpXkVFQem2Wq1Z_7F05dFWnzwYjbVVoVL4kO-Ym_k6RJZSneldy2eoRRLUkBlAfc7dpzvEWbortYCR8-dwcVNZhdFQjvvLtfiJ54yu74egwJkap3KtfIeiMFnCu8jTN3WESK2LcIEeii9PmR-XTsCVr6xJ0Vfln6t2BfMqymzQOIih1z5KJQjUdFtv6lhv8DU3VWEzHER0KtNOdn9y7OSdNgOp36RbL2G06SLu66xRnWEx-LOZxsZc8teU8LQIXlSSXTHTrTSau8IG_CXuUj1Q5gMDpSuEN_lvq6z9e5sjxoMyHTQdN3_MZ5QXknKgBl8eTwFkJ9-MjAUPW4xrnW4bVFmtjJZozdr6ROOmtV50UXp5TE0sKgURIKWQjN82QHbPqJftlbxXjJSOxObCECyrm49l0TnWkK3NE2WmcQh4J0plHi9WTh1tXiYUMLSPwQMJSkYB6IZB3vH6z9x81nqiwOe5ORs1PuMKQC6vJu-LOHQWtvs-KRibuoO3_GCchbbmJKIjuN2E_uqmCCaXwAOHw5xPd_s_6E1dxsw3tWRhIv5Qvu3IrZI7FgDWbV_v1cTsVSz01NOdBEVWFrZUqHNZHrCMSXLBkkAzsgTHKvb_hLZLrq3UuK7cCZGC-s9wLe4LtqtSHfcNOb4FG8kEgCF6h-7A4jcmKqvD3uLpX8RJoNpuXQkNVaqK9XVhyAzCulhFxQ9GeWEuOLM7XJesnV-X0WXmMfrQUfCAeb1i0Ow
code: "https://github.com/ctlab/GADMA"
---

### Abstract
**Background**

The demographic history of any population is imprinted in the genomes of the individuals that make up the population. One of the most popular and convenient representations of genetic information is the allele frequency spectrum (AFS), the distribution of allele frequencies in populations. The joint AFS is commonly used to reconstruct the demographic history of multiple populations, and several methods based on diffusion approximation (e.g., ∂a∂i) and ordinary differential equations (e.g., moments) have been developed and applied for demographic inference. These methods provide an opportunity to simulate AFS under a variety of researcher-specified demographic models and to estimate the best model and associated parameters using likelihood-based local optimizations. However, there are no known algorithms to perform global searches of demographic models with a given AFS.

**Results**

Here, we introduce a new method that implements a global search using a genetic algorithm for the automatic and unsupervised inference of demographic history from joint AFS data. Our method is implemented in the software GADMA (Genetic Algorithm for Demographic Model Analysis, https://github.com/ctlab/GADMA).

**Conclusions**

We demonstrate the performance of GADMA by applying it to sequence data from humans and non-model organisms and show that it is able to automatically infer a demographic model close to or even better than the one that was previously obtained manually. Moreover, GADMA is able to infer multiple demographic models at different local optima close to the global one, providing a larger set of possible scenarios to further explore demographic history.
