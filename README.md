# Heterogeneous Domain Adaptation Survival Analysis with Partially Observed Outcomes via Dictionary Learning and MMD Alignment

## About This Project

This repository contains the implementation of **Heterogeneous Domain Adaptation (HDA) for Survival Analysis with Partially Observed Outcomes**, based on the framework proposed in the accompanying research paper.

The goal of this project is to improve **time-to-event prediction in data-scarce clinical settings**, where survival outcomes (event indicators and time-to-event) may be partially missing and where **source and target datasets may differ in feature dimensionality and covariate distributions**.

The proposed framework integrates three main components:

- **Dictionary Learning** to construct a shared latent representation between heterogeneous source and target feature spaces.
- **Maximum Mean Discrepancy (MMD)** to align the statistical distributions of source and target domains.
- **Cox Proportional Hazards modeling** to learn survival risk from the aligned latent representation.

By combining these components, the model leverages **heterogeneous external datasets and partially labeled target data** to improve survival discrimination performance.

This repository provides:

- Implementation of the **HDA-CoxPH framework**
- **Jupyter notebooks for simulation experiments**
- **Jupyter notebooks for TCGA dataset experiments**
- Experimental pipelines used to reproduce the results reported in the paper

The notebooks are designed to be easily uploaded and executed on **Kaggle**, enabling users to reproduce the experiments in a cloud-based environment without requiring local computational resources.