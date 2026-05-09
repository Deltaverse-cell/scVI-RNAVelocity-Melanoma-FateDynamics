## Overview

This repository contains the computational framework and reproducible analysis pipeline accompanying the study:

**“scVI- and RNA Velocity–Integrated Fate Dynamics Reveal Latent Stability Architecture in Melanoma Therapy Resistance.”**

Author: Pranshu Bharadwaj

The framework integrates variational latent manifold learning, RNA velocity dynamics, absorbing Markov fate inference, entropy-based terminal-state detection, perturbation-response modelling, and probabilistic stability analysis to reconstruct long-term cellular fate organization from single-cell transcriptomic data.

The study investigates how resistant melanoma populations exhibit increased dynamical persistence and reduced perturbation-induced fate redistribution within the transcriptomic state landscape.

---

# Features

- scVI latent manifold learning
- scANVI semi-supervised latent modelling
- RNA velocity dynamics using scVelo
- Absorbing Markov fate inference
- Entropy-based terminal-state identification
- Diffusion-derived transition modelling
- Velocity-informed nonequilibrium dynamics
- Perturbation-response modelling
- KL-divergence fate stability analysis
- Statistical comparison of resistant and sensitive populations
- Reproducible computational pipeline
- Docker-compatible execution environment

---

# Dataset

The single-cell RNA sequencing dataset analysed in this study is publicly available through the NCBI Gene Expression Omnibus (GEO):

**Dataset:** GSE72056

Original study:

Tirosh, I. et al.  
*Dissecting the multicellular ecosystem of metastatic melanoma by single-cell RNA-seq.*  
Science (2016).

GEO access link:

https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE72056

Raw sequencing data were processed using the preprocessing and latent modelling pipeline described in this study.
All computational scripts, preprocessing workflows, latent-space modelling pipelines, transition operators, perturbation-analysis modules, precomputed result arrays, and figures are publicly available through this repository.
This repository is distributed under the MIT License.
---
