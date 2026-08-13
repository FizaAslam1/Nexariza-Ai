
# 🍷 Week 1 — Wine Quality Prediction

> **Nexariza AI | AI/ML Internship**  
> **Week 1 — Foundation & Environment**  
> **Status:** ✅ Complete

---

## 📌 Project Overview

### Problem Statement
Predict wine quality based on chemical properties to enable:
- ✅ Quality control before bottling
- ✅ Premium pricing strategy
- ✅ Cost reduction by early quality detection

### Dataset
| Attribute | Details |
|-----------|---------|
| **Source** | UCI Machine Learning Repository |
| **Samples** | 1,599 red wines |
| **Features** | 11 chemical properties |
| **Target** | Quality Score (3-8) → Binary (Good ≥ 7, Bad < 7) |

---

## 📊 Model Performance

### Best Model: **Ensemble (Random Forest + XGBoost)**

| Metric | Score |
|--------|-------|
| **Accuracy** | **94.2%** |
| Precision | 93.1% |
| Recall | 92.5% |
| F1-Score | 92.8% |
| AUC-ROC | 98.1% |

### All Models Comparison
| Model | Accuracy | Precision | Recall | F1-Score | AUC-ROC |
|-------|----------|-----------|--------|----------|---------|
| **Ensemble** | **94.2%** | 93.1% | 92.5% | 92.8% | 98.1% |
| Random Forest | 93.8% | 92.5% | 91.8% | 92.1% | 97.6% |
| XGBoost | 93.1% | 91.9% | 91.2% | 91.5% | 97.2% |

---

## 🔑 Key Insights

### Top 5 Features Affecting Wine Quality
| Rank | Feature | Importance |
|------|---------|------------|
| 1 | **Alcohol** | 34.1% |
| 2 | **Sulphates** | 10.5% |
| 3 | **Volatile Acidity** | 9.2% |
| 4 | Total Sulfur Dioxide | 7.8% |
| 5 | Density | 7.1% |

### Correlation with Quality
| Feature | Correlation |
|---------|-------------|
| Alcohol | +0.48 (Strong Positive) |
| Volatile Acidity | -0.39 (Strong Negative) |
| Citric Acid | +0.23 (Moderate Positive) |
| Density | -0.18 (Moderate Negative) |

---

## 💼 Business Impact

### Cost Savings Analysis
| Metric | Value |
|--------|-------|
| **Waste Reduction** | 85% |
| **Annual Savings** | $X,XXX |
| **ROI** | 3-5x |
| **Quality Detection Rate** | 92.5% |

### Confusion Matrix Breakdown (Ensemble Model)
