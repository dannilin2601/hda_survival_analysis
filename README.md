# Heterogeneous Domain Adaptation Survival Analysis with Partially Observed Outcomes via Dictionary Learning and MMD Alignment

## About This Project

This repository contains the implementation of the paper entitled **Heterogeneous Domain Adaptation (HDA) for Survival Analysis with Partially Observed Outcomes  via Dictionary Learning and MMD Alignment**.

The goal of this project is to improve **time-to-event prediction in data-scarce clinical settings (target domain)**, where survival outcomes (event indicators and time-to-event) may be partially missing. The framework leverages **external datasets (source domains)** to enhance prediction performance on the **target dataset**, even when source and target data differ in feature dimensionality and covariate distributions.

The proposed framework integrates three main components:

- **Dictionary Learning** to construct a shared latent representation between heterogeneous source and target feature spaces.
- **Maximum Mean Discrepancy (MMD)** to align the statistical distributions of source and target domains.
- **Cox Proportional Hazards modeling** to learn survival risk from the aligned latent representation.

By combining these components, the model leverages **heterogeneous external datasets and partially labeled target data** to improve target survival discrimination performance.

This repository provides:

- Implementation of the **HDA-CoxPH framework**
- **Jupyter notebooks for simulation experiments**
- **Jupyter notebooks for TCGA dataset experiments**

The notebooks are designed to be easily uploaded and executed on **Kaggle**, enabling users to reproduce the experiments in a cloud-based environment without requiring local computational resources.