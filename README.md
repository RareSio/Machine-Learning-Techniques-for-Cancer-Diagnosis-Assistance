# Master Thesis: Machine Learning for Lung Cancer Classification

## Overview
This repository contains the master thesis titled **"Machine Learning Techniques for Cancer Diagnosis Assistance"**, authored by **Babih Velázquez De Burnay** as part of the Master's program at **Universidad de A Coruña (UDC)**. The thesis explores the use of machine learning techniques for the early detection of non-small cell lung cancer (NSCLC) using RNA-Seq data from Tumor-Educated Platelets (TEPs).

---

## Abstract
Early detection of non-small cell lung cancer (NSCLC) remains a critical challenge in clinical medicine. This study leverages machine learning techniques to address this issue, utilizing RNA-Seq data from Tumor-Educated Platelets (TEPs). The research involves identifying outlier samples, selecting relevant features for cancer detection, and constructing 11 machine learning models to determine the most accurate and interpretable model.

**Keywords:** Machine Learning, Cancer, Early Diagnosis, NSCLC

---

## Table of Contents
1. [Introduction](#introduction)
2. [Data Description](#data-description)
3. [Methodology](#methodology)
   - Data Preprocessing
   - Feature Selection
   - Model Construction and Optimization
4. [Results](#results)
5. [Conclusions and Future Work](#conclusions-and-future-work)

---

## Introduction
Lung cancer is the second leading cause of death worldwide, with NSCLC accounting for approximately 13% of all new cancer diagnoses. This study focuses on using RNA-Seq data obtained from blood samples to develop non-invasive diagnostic tools based on machine learning algorithms.

---

## Data Description
The dataset used in this study is sourced from the NCBI repository (accession ID: GSE89843). It includes:
- RNA-Seq data for 4722 genes across 779 patients:
  - **402 samples** from patients with NSCLC.
  - **377 samples** from healthy individuals.
- Clinical metadata such as age, gender, and NSCLC status.

---

## Methodology

### Data Preprocessing
- **Normalization:** Adjusting RNA-Seq data to mitigate sequencing biases.
- **Outlier Detection:** Techniques such as Chebyshev's theorem and Isolation Forest were applied to identify anomalous samples.
- **Feature Selection:** Methods like Random Forest and ANOVA F-statistics were used to reduce dimensionality and improve interpretability.

### Model Construction and Optimization
A total of **11 machine learning models** were evaluated, including:
- Neural Networks
- Support Vector Machines (SVM)
- Random Forests
- Logistic Regression
- Gradient Boosting

Hyperparameter optimization was performed using `GridSearchCV`.

---

## Results
The study found that:
- Neural Networks achieved the highest predictive performance with an F1-score of **0.909**.
- Logistic Regression was selected as the final model due to its interpretability and strong predictive capabilities (F1-score: **0.880**).

---

## Conclusions and Future Work
This thesis demonstrates the potential of machine learning techniques in enhancing early cancer detection through non-invasive methods. Future work could explore integrating additional biomarkers or extending the approach to other types of cancer.

---

## Author Information
**Author:** Babih Velázquez De Burnay  
**Institution:** Universidad de A Coruña (UDC)  
**Contact:** babih.velazquez@udc.es  

**Supervisors:**  
- Alejandro Puente Castro (a.puentec@udc.es)  
- Cristian Robert Munteanu (c.munteanu@udc.es)  

