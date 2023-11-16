# Expectation Maximization For Ensemble Structure Learning in the Presence of Latent Variables using Gaussian Mixture Models and Static Bayesian Networks


## Overview
This repository contains the research report titled "Expectation Maximization for Ensemble Structure Learning in the Presence of Latent Variables using Gaussian Mixture Models and Static Bayesian Networks". The study focuses on the challenges and methodologies of structure learning in Bayesian networks, especially in the context of latent variables. The research simulates data reflective of Alzheimer’s Disease interactions, providing valuable insights for the field.

## Report Abstract
This study explores structure learning in Bayesian networks, with an emphasis on handling latent variables. By simulating data reflective of Alzheimer’s Disease interactions, we assess different algorithms’ ability to uncover hidden patterns.
Our approach utilizes Gaussian Mixture Models and statistical measures such as the Bayesian Information Criterion
to direct our search for the most accurate model structure. We tested several algorithms, like Tabu search and Bayesian Model Averaging, on datasets of 2000 and 6000 samples. The results reveal that a hybrid approach, on average, was the most successful in approximating the true model, as indicated by low Kullback-Leibler divergence values. Our work highlights the effectiveness of such interpretable methods in tracking the dependency structure between complex variable relationships, even when some of the data is not directly observable.

## Key Contributions
Exploration of structure learning in Bayesian networks with a focus on handling latent variables.
Utilization of Gaussian Mixture Models and statistical measures like the Bayesian Information Criterion.
Detailed analysis of algorithms like Tabu search and Bayesian Model Averaging.
Application of these methods to datasets simulating Alzheimer’s Disease interactions.


## Research Methodology
Our investigation is aimed at learning model structures M from a dataset D, which is generated from a ground truth model M∗. The models learned are evaluated against M∗ using Kullback-Leibler (KL) divergence with evidence Va from the dataset, to facilitate knowledge discovery about the underlying structure of our AD problem. It is crucial that all models M are learned while preserving the state space of the generated dataset D to ensure the precision of our joint probability-based KL divergence comparison.

## Ground Truth Model
[Ground Truth AD-Influence.pdf](https://github.com/Lindelani-3/latent-influence-tracker/files/13382759/Ground.Truth.AD-Influence.pdf)

Figure 1: Graphical representation of the ground truth model used in the study.

## Results
[Summarize the key results of your study, highlighting any significant findings or conclusions.]

Key Figures and Tables
Figure/Table Title
Figure/Table Description


## Conclusions
[Provide a brief conclusion of your research, summarizing the outcomes and any potential impact on the field.]
