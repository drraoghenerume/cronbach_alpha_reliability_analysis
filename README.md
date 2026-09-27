# cronbach_alpha_reliability_analysis

Conducted in Python, this analysis measured the **internal consistency reliability** of a 20-item, four-construct questionnaire using **Cronbach's alpha (α)**. The instrument measures perceptions across four technology-and-investigation constructs: **Artificial Intelligence (AI)**, **Blockchain Technology (BCT)**, **Big Data Analytics (BDA)**, and **Perceived Effectiveness of Forensic Fraud Investigation (FFI)**.

## 📊 Overview

This script provides a **construct-level reliability analysis** for a 20-item Likert-type instrument (5 items per construct, N = 30 respondents). Cronbach's alpha is computed for each subscale to assess the degree to which items within each construct measure the same underlying dimension. Results are interpreted against standard psychometric thresholds, and a comparative bar chart is generated to visualise construct reliabilities at a glance.

## Analysis Summary

- **AI (Artificial Intelligence):** α = 0.908 — *Excellent*
- **BCT (Blockchain Technology):** α = 0.931 — *Excellent*
- **BDA (Big Data Analytics):** α = 0.945 — *Excellent*
- **FFI (Forensic Fraud Investigation):** α = 0.925 — *Excellent*
- **Sample Size:** 30 respondents
- **Total Items:** 20 (4 constructs × 5 items)

---

## Key Features

- **Cronbach's Alpha** computed per construct using the standard variance-based formula
- **Construct-Level Reliability Table** with interpretation labels
- **Automated Interpretation** using conventional psychometric thresholds
- **Comparative Bar Chart** with Acceptable (0.70) and Good (0.80) reference lines

---

## 📈 Methods Used

| Method | Purpose |
|--------|---------|
| **Cronbach's Alpha (α)** | Internal consistency of items within each construct |
| **Item Variance Summation** | Numerator component of the alpha formula (Σσ²ᵢ) |
| **Total Score Variance** | Denominator component of the alpha formula (σ²ₜ) |
| **Descriptive Reliability Table** | Side-by-side comparison of constructs |
| **Bar Visualisation** | Graphical comparison against threshold benchmarks |

### Formula

$$
\alpha = \frac{k}{k-1} \left( 1 - \frac{\sum_{i=1}^{k} \sigma^2_i}{\sigma^2_T} \right)
$$

Where *k* = number of items, σ²ᵢ = variance of item *i*, and σ²ₜ = variance of total scores.

---

## 📊 Interpretation Guidelines

| Coefficient | Range | Interpretation |
|-------------|-------|----------------|
| **Cronbach's α** | ≥ 0.90 | Excellent |
| | 0.80 – 0.89 | Good |
| | 0.70 – 0.79 | Acceptable |
| | 0.60 – 0.69 | Questionable |
| | < 0.60 | Poor |

---

## 🔬 Key Findings

### Internal Consistency
- **All four constructs exceeded the 0.90 threshold**, indicating **excellent internal consistency**.
- **BDA** recorded the highest reliability (α = 0.945), followed by **BCT** (α = 0.931), **FFI** (α = 0.925), and **AI** (α = 0.908).
- No construct fell below 0.90, suggesting robust item homogeneity within each subscale.

### Construct Comparison
| Rank | Construct | α | Interpretation |
|------|-----------|---|----------------|
| 1 | Big Data Analytics (BDA) | 0.945 | Excellent |
| 2 | Blockchain Technology (BCT) | 0.931 | Excellent |
| 3 | Forensic Fraud Investigation (FFI) | 0.925 | Excellent |
| 4 | Artificial Intelligence (AI) | 0.908 | Excellent |

### Practical Implication
The uniformly high alpha values suggest the instrument is **highly reliable** for measuring the four targeted constructs in this sample.


---

## ⚠️ COPYRIGHT NOTICE

**© 2026 Rioborue Alexander Oghenerume. All Rights Reserved.**
***This repository is for viewing purposes only. No part of this work may be copied, reused, modified, reproduced, or redistributed without prior written permission. Unauthorised use will be pursued legally.***

---

**BY ACCESSING THIS REPOSITORY, YOU AGREE TO THESE TERMS!**
