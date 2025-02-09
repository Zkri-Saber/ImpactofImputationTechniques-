# Impact of Imputation Techniques on Thyroid Disease Prediction: A Hybrid Approach and Comparative Analysis

[![CI/CD](https://github.com/Zkri-Saber/ImpactofImputationTechniques-/actions/workflows/python-app.yml/badge.svg)](https://github.com/Zkri-Saber/ImpactofImputationTechniques-/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)

![Thyroid Prediction Pipeline](docs/pipeline.png) <!-- Add actual image path -->

A comprehensive framework for evaluating missing data imputation techniques in thyroid disease prediction, featuring advanced machine learning models and rigorous statistical validation.

## Table of Contents
- [Key Features](#key-features)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [Citation](#citation)
- [License](#license)
- [Contact](#contact)

## Key Features

### 🧬 Imputation Methods
- **Cold-Deck Imputation** with external reference datasets
- **KNN Imputation** with feature importance weighting
- **Mean Imputation** with biomarker stability analysis

### 🧠 Machine Learning Pipeline
- **Hybrid KNN-Feature Importance Weighted Imputation**
- **Classifier Comparison** (LightGBM, RNN, SVM, Naive Bayes)
- **Ablation Experiments** for biomarker validation

### 📊 Advanced Analytics
- Feature importance analysis using Random Forest
- Statistical significance testing (paired t-tests)
- Comprehensive performance metrics:
  - Accuracy, F1-Score, Recall
  - 95% Confidence Intervals

## Installation

### Prerequisites
- Python 3.10+
- Git

### Quick Start
```bash
# Clone repository
git clone https://github.com/Zkri-Saber/ImpactofImputationTechniques-.git
cd ImpactofImputationTechniques-

# Create virtual environment
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
.\.venv\Scripts\activate   # Windows

# Install dependencies
pip install -r requirements.txt
