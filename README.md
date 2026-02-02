# Credit Risk Modeling Framework
### End-to-End Implementation of PD, LGD, EAD & Expected Loss Models

## Overview

Comprehensive implementation of credit risk modeling frameworks for Basel III-compliant capital calculation. Built as an intensive 250+ hour learning project demonstrating statistical rigor and regulatory awareness.

**Project Status:** Educational implementation on academic datasets (LendingClub 2007-2014)

## Repository Structure

- **01_data_preparation/** - Data cleaning and feature engineering
- **02_pd_models/** - Probability of Default estimation with p-values
- **03_lgd_models/** - Loss Given Default (two-stage framework)
- **04_ead_models/** - Exposure at Default (CCF estimation)
- **05_expected_loss/** - Expected Loss calculation (PD × LGD × EAD)
- **06_model_monitoring/** - Population Stability Index (PSI) monitoring

## Key Technical Features

### 1. PD Model with Statistical Validation
Custom logistic regression implementing **Fisher Information Matrix** for p-value calculation—regulatory requirement not provided by sklearn.

### 2. Two-Stage LGD Model
Addresses zero-inflated recovery distributions (60% zeros) preventing biased loss estimates.

### 3. SHAP Explainability
Model interpretability for Fair Lending (ECOA) compliance.

### 4. PSI Monitoring
Model drift detection ensuring Basel III capital calculation validity.

## Technical Stack

Python 3.8+ | pandas | numpy | scikit-learn | scipy | matplotlib | seaborn | SHAP | statsmodels

## What This Demonstrates

✅ **Statistical rigor:** Fisher Information, Cramér-Rao bounds, significance testing
✅ **Regulatory awareness:** Basel III frameworks, model governance
✅ **Production thinking:** Validation, monitoring, documentation
✅ **Domain knowledge:** Credit risk vs generic ML

## Learning Outcomes

- **Statistical foundations matter:** Understanding theory separates capable modelers from sklearn users
- **Domain trumps algorithms:** Two-stage models beat hyperparameter tuning
- **Explainability is mandatory:** Black-box models fail regulatory approval
- **Monitoring = readiness:** PSI distinguishes academic projects from operations

## Installation

```bash
git clone https://github.com/PhanasN/credit-risk-modeling-framework.git
cd credit-risk-modeling-framework
pip install numpy pandas scikit-learn scipy matplotlib seaborn shap statsmodels jupyter
jupyter notebook
```

## Data Source

LendingClub historical loan data (2007-2014): ~890K loans, ~45K defaults
Download: [Kaggle - Lending Club Dataset](https://www.kaggle.com/datasets/wordsforthewise/lending-club)

## Honest Scope

**This Project IS:**
- Technical capability demonstration
- End-to-end credit risk pipeline implementation
- Statistical and regulatory foundations

**This Project IS NOT:**
- Production banking system
- Externally validated or regulatory-approved
- Integrated with core banking infrastructure

## About

Built to bridge theoretical understanding with hands-on credit risk implementation. Demonstrates capability for junior-to-mid-level roles requiring statistical rigor and Basel III awareness.

**Currently:** Pursuing FRM Part I (May 2026) | Open to credit risk modeling opportunities

---

**Contact:** [LinkedIn](https://www.linkedin.com/in/phanas-nakhonsri) | [@PhanasN](https://github.com/PhanasN)

⭐ Star this repo if it helps your learning journey!
