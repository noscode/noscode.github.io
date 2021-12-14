---
layout: paper
title: "Talk: Bayesian Optimization for Demographic History Inference"
conference: "Probabilistic Techniques in Analysis"
conference_url: "https://siriusmathcenter.ru/en/program/pta"
location: Sirius, Mathematics Center, Sochi, Russia
slides: "../download/2021-12-07_Bayesian_Optimization_for_Demographic_Inference.html"
---


Abstract:

Demographic history of populations is a record of their evolutionary history that includes parameters like population size dynamics, divergence times, rates of migration and selection over time. With the rise of the next generation sequencing technologies and emergence of the abundant genome data, it has become possible to explore complex and parameter-rich demographic models.

Existing methods for inference of demographic history solve the “forward” problem. They model population statistics for a given demographic history. A researcher then has to try a number of plausible histories and choose the one for which the modeled statistics align well with the observed data. In order to take the human out of the loop we are interested in automatically solving the inverse problem that is reduced to an optimization one: find the parameters of the demographic history that maximize the likelihood of the observed data.

Bayesian optimization is one of the most popular algorithms for optimization with a limited time budget. In my talk, I will tell about the application of the Bayesian optimization method for fast inference of the demographic history parameters.
