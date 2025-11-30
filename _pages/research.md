---
layout: single
title: "Research"
permalink: /research/
author_profile: true
toc: true
toc_label: "Research Areas"
toc_icon: "flask"
---

My research focuses on **addressing health disparities through large-scale analytics using secondary health data**. I work at the intersection of Bayesian statistics, causal inference, natural language processing, and multi-modal machine learning to develop methodologically rigorous approaches that can identify, measure, and address health disparities at scale.

## Dissertation Research
**Addressing Health Disparities Through Large-Scale Analytics Using Secondary Health Data**  
*Johns Hopkins University | 2021 - 2026*

My dissertation addresses the critical challenge of health disparities through three complementary aims that leverage different analytical frameworks and data modalities.

### Aim 1: Social Determinants of Health Impact on Type 2 Diabetes
**Quantifying SDoH Impact Using Self-Controlled Case Series Design**

I developed a novel analytical framework using **Continuous Self-Controlled Case Series (CSCCS)** to investigate how adverse social determinants of health affect diabetes management within individuals, eliminating time-invariant confounding.

**Key Innovation:**
- Applied CSCCS methodology to EHR data from Johns Hopkins Health System (~140,000 T2DM patients)
- Examined 7 SDoH domains aligned with SIREN framework: financial strain, food insecurity, housing instability, transportation barriers, healthcare access, social isolation, and stress
- Used symmetric exposure risk windows (30-180 days) around ICD-10-CM documented social risks
- Measured impact on HbA1c levels as diabetes severity indicator

**Impact:** Published in *JAMIA Open* (2024), providing actionable insights into cumulative burden of social risks on diabetes care.

### Aim 2: Sex Differences in Diabetes Treatment Effectiveness
**Federated Multi-Database Analysis of Second-Line Antihyperglycemic Agents**

Led comparative effectiveness research within the **LEGEND-T2DM network**, analyzing sex-specific outcomes across 10 international databases covering the U.S., U.K., Germany, and Spain.

**Methodological Approach:**
- Federated analysis across 6 administrative claims and 4 EHR databases
- Target-comparator framework comparing GLP-1 RAs, SGLT2is, DPP4is, and sulfonylureas
- Large-scale propensity score modeling with L1-regularized logistic regression
- Rigorous study diagnostics: empirical equipoise, covariate balance (SMD <0.15), statistical power (MDRR <4.0)
- Negative control outcome calibration for residual confounding

**Key Findings:**
- Cardiovascular benefits largely consistent between sexes for newer agents
- Notable sex differences in glycemic control and safety endpoints (hypoglycemia, pancreatitis, diarrhea, hypotension)
- Results highlight critical gaps in current treatment guidelines

**Impact:** Published in *JACC* (2024), informing sex-tailored diabetes treatment recommendations.

### Aim 3: Federated Bayesian Transfer Learning Framework
**Novel Methodology for High-Dimensional, Sparse Secondary Health Data**

Developing a **federated Bayesian transfer learning framework** that enables secure knowledge transfer across institutions while addressing data sparsity and heterogeneity in high-dimensional settings.

**Technical Innovation:**
- Incorporates ontological/genetic similarity between covariates into Bayesian priors
- Uses skewed generalization of continuous shrinkage priors for adaptive information borrowing
- Enables meaningful transfer even when covariate definitions differ but are semantically related
- Developed modified ziggurat algorithm for efficient posterior inference under skewed priors

**Applications:**
1. **Observational Health Data**: Propensity score modeling across OHDSI databases
2. **Genomic Data**: Phenotype prediction for underrepresented populations using UK Biobank

**Status:** Algorithm development completed (2024), real-world applications in progress.

## Clinical Natural Language Processing Research

### Multi-Modal Clinical Decision Support
*Boston Children's Hospital & Johns Hopkins University | 2019 - Present*

I developed a comprehensive suite of NLP solutions addressing critical challenges in clinical text analysis and automated healthcare workflows.

**[Please share your NLP project details here - I'll incorporate them into this section]**

## Core Research Areas

### 1. Bayesian Methods for Health Disparities Research
My work advances Bayesian methodology for causal inference in observational health data:

- **Self-Controlled Designs**: Eliminating time-invariant confounding in longitudinal EHR analysis
- **Federated Analytics**: Privacy-preserving multi-institutional collaboration
- **Transfer Learning**: Leveraging information across heterogeneous data sources
- **Shrinkage Priors**: Handling high-dimensional, sparse clinical and genomic data

### 2. Real-World Evidence Generation
I specialize in generating rigorous evidence from observational health data:

- **Causal Inference**: Propensity score methods, negative control outcomes, study diagnostics
- **Federated Analysis**: OMOP common data model, distributed analytics
- **Health Disparities**: Sex differences, racial/ethnic disparities, social determinants of health
- **Comparative Effectiveness**: Drug safety and effectiveness across diverse populations

### 3. Multi-Modal Machine Learning in Healthcare
My research integrates diverse data modalities for improved clinical predictions:

- **Clinical + Imaging**: Combining EHR data with medical imaging for disease prediction
- **Genomics + Phenotypes**: Transfer learning for underrepresented populations
- **Longitudinal Modeling**: Temporal patterns in health outcomes and exposures
- **Cross-Attention Mechanisms**: Novel architectures for multi-modal fusion

### 4. Clinical Natural Language Processing
I develop NLP solutions that integrate into clinical workflows:

- **Long Document Processing**: Handling lengthy clinical narratives
- **Clinical Decision Support**: Automated triage and classification systems  
- **Domain Adaptation**: Adapting general NLP models for medical applications
- **Interpretability**: Ensuring clinical relevance and explainability

## Methodological Contributions

### Statistical Innovation
- **Continuous Self-Controlled Case Series**: Novel application to EHR-based SDoH research
- **Federated Bayesian Transfer Learning**: Ontology-informed information sharing
- **Skewed Shrinkage Priors**: Improved sparsity induction in high-dimensional settings

### Computational Advances
- **Modified Ziggurat Algorithm**: Efficient sampling for skewed distributions
- **Large-Scale Propensity Scoring**: Regularized methods for high-dimensional confounding
- **Federated Analytics Pipeline**: Privacy-preserving distributed computation

## Collaborative Research Networks

### OHDSI/LEGEND-T2DM Network
- 10 international databases across 4 countries
- Standardized OMOP common data model
- Federated analytics preserving data privacy

### Johns Hopkins Health System
- Large-scale EHR analysis (~140,000 T2DM patients)
- Longitudinal SDoH documentation and outcomes
- Clinical implementation and validation

### UK Biobank Genomics
- Population-scale genetic and phenotypic data
- Focus on underrepresented ancestry groups
- Transfer learning for genomic prediction

## Research Philosophy

My research is guided by several core principles:

1. **Methodological Rigor**: Developing statistically sound approaches that address inherent biases in observational data
2. **Health Equity**: Focusing on underrepresented populations and health disparities
3. **Clinical Relevance**: Ensuring research addresses real clinical needs and can be implemented in practice
4. **Open Science**: Releasing analytical code and promoting reproducible research
5. **Interdisciplinary Collaboration**: Working across statistics, computer science, and clinical domains

## Future Directions

I am excited about several emerging research areas:

- **Causal Machine Learning**: Integrating causal inference with modern ML methods
- **Foundation Models for Healthcare**: Adapting large language models for clinical applications
- **Federated Learning at Scale**: Expanding to global health networks and resource-limited settings
- **AI for Health Equity**: Developing algorithms that actively reduce rather than perpetuate disparities

---

*My research aims to bridge the gap between methodological innovation and real-world impact, ultimately contributing to more equitable and effective healthcare for all populations.*