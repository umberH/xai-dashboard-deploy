# Detailed Explanation Report

**Dataset:** ag_news  
**Model:** naive_bayes_text  
**Explanation Method:** attention_visualization  
**Generated:** 2025-08-24 19:01:35  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8150
- **Average Feature Importance:** 0.0625
- **Feature Importance Std:** 0.0488
- **Max Feature Importance:** 0.4629

## Prediction Analysis

- **Correct Predictions:** 163 (81.5%)
- **Incorrect Predictions:** 37 (18.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 133 | 0.0714 | 66.5% |
| 1 | 113 | 0.0813 | 56.5% |
| 2 | 104 | 0.0785 | 52.0% |
| 24 | 21 | 0.0906 | 10.5% |
| 19 | 20 | 0.0829 | 10.0% |
| 20 | 20 | 0.0777 | 10.0% |
| 6 | 20 | 0.1031 | 10.0% |
| 9 | 20 | 0.0940 | 10.0% |
| 11 | 19 | 0.1119 | 9.5% |
| 17 | 19 | 0.0689 | 9.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.175', '0.344', '0.210', '0.271']
- **Top Features:**
  - Feature 15: 0.0525
  - Feature 0: 0.0350
  - Feature 2: 0.0327

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.075', '0.760', '0.088', '0.077']
- **Top Features:**
  - Feature 42: 0.0286
  - Feature 0: 0.0259
  - Feature 43: 0.0256

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.629', '0.106', '0.147', '0.119']
- **Top Features:**
  - Feature 18: 0.0313
  - Feature 1: 0.0306
  - Feature 2: 0.0306

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.108', '0.756', '0.074', '0.063']
- **Top Features:**
  - Feature 0: 0.0363
  - Feature 1: 0.0363
  - Feature 31: 0.0350

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.128', '0.509', '0.203', '0.160']
- **Top Features:**
  - Feature 2: 0.0348
  - Feature 19: 0.0340
  - Feature 10: 0.0324

### Incorrect Predictions (Sample)

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.061', '0.059', '0.098', '0.782']
- **Top Features:**
  - Feature 19: 0.1645
  - Feature 0: 0.1555
  - Feature 35: 0.1500

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.320', '0.282', '0.231', '0.167']
- **Top Features:**
  - Feature 11: 0.0373
  - Feature 5: 0.0314
  - Feature 7: 0.0314

#### Instance 22

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.217', '0.183', '0.243', '0.358']
- **Top Features:**
  - Feature 27: 0.1982
  - Feature 0: 0.1918
  - Feature 1: 0.1872

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 15 | 0.052519409346932555 |
| 1 | 1.0 | 1.000 | YES | 42 | 0.028645511791579203 |
| 2 | 0.0 | 0.000 | YES | 18 | 0.03131808278867102 |
| 3 | 1.0 | 1.000 | YES | 0 | 0.036339610175090846 |
| 4 | 1.0 | 1.000 | YES | 2 | 0.03476062569126244 |
| 5 | 1.0 | 1.000 | YES | 0 | 0.03235769966171495 |
| 6 | 2.0 | 3.000 | NO | 19 | 0.16450096765275088 |
| 7 | 1.0 | 0.000 | NO | 11 | 0.037256956572359994 |
| 8 | 0.0 | 0.000 | YES | 26 | 0.027834008097165987 |
| 9 | 3.0 | 3.000 | YES | 1 | 0.1697667552406259 |
| 10 | 3.0 | 3.000 | YES | 11 | 0.1544223945327901 |
| 11 | 3.0 | 3.000 | YES | 16 | 0.18698931489629161 |
| 12 | 1.0 | 1.000 | YES | 1 | 0.02889414236931967 |
| 13 | 2.0 | 2.000 | YES | 40 | 0.09387121799844839 |
| 14 | 3.0 | 3.000 | YES | 16 | 0.13442466244473653 |
| 15 | 3.0 | 3.000 | YES | 1 | 0.15102698348771645 |
| 16 | 2.0 | 2.000 | YES | 8 | 0.19836096107282544 |
| 17 | 0.0 | 0.000 | YES | 0 | 0.02735894941634241 |
| 18 | 1.0 | 1.000 | YES | 0 | 0.03901400957616598 |
| 19 | 2.0 | 2.000 | YES | 30 | 0.10392720306513407 |
| 20 | 1.0 | 1.000 | YES | 32 | 0.03648915187376725 |
| 21 | 2.0 | 2.000 | YES | 32 | 0.07412398921832883 |
| 22 | 2.0 | 3.000 | NO | 27 | 0.1982097186700767 |
| 23 | 3.0 | 3.000 | YES | 8 | 0.24407976734524303 |
| 24 | 0.0 | 0.000 | YES | 1 | 0.06384790011350738 |
| 25 | 2.0 | 3.000 | NO | 29 | 0.1909488559892328 |
| 26 | 0.0 | 0.000 | YES | 20 | 0.027065343472096916 |
| 27 | 2.0 | 2.000 | YES | 20 | 0.07500833425936215 |
| 28 | 3.0 | 3.000 | YES | 1 | 0.17180874396841642 |
| 29 | 2.0 | 2.000 | YES | 35 | 0.07492507492507491 |
| 30 | 3.0 | 3.000 | YES | 7 | 0.1990379830817714 |
| 31 | 0.0 | 0.000 | YES | 13 | 0.035325287017957015 |
| 32 | 2.0 | 3.000 | NO | 53 | 0.11740659758532179 |
| 33 | 3.0 | 3.000 | YES | 28 | 0.15990696322139844 |
| 34 | 0.0 | 1.000 | NO | 25 | 0.043540768124871634 |
| 35 | 1.0 | 1.000 | YES | 0 | 0.03186558516801854 |
| 36 | 3.0 | 3.000 | YES | 2 | 0.203756201275691 |
| 37 | 2.0 | 2.000 | YES | 30 | 0.11455108359133125 |
| 38 | 3.0 | 3.000 | YES | 30 | 0.185501795178663 |
| 39 | 3.0 | 0.000 | NO | 28 | 0.039796633941093965 |
| 40 | 2.0 | 2.000 | YES | 2 | 0.09116693679092382 |
| 41 | 2.0 | 2.000 | YES | 1 | 0.08852335509794072 |
| 42 | 2.0 | 2.000 | YES | 0 | 0.09273251820304985 |
| 43 | 2.0 | 2.000 | YES | 40 | 0.08102818371607515 |
| 44 | 2.0 | 2.000 | YES | 1 | 0.09477311889718551 |
| 45 | 1.0 | 1.000 | YES | 1 | 0.03065031982942431 |
| 46 | 2.0 | 2.000 | YES | 0 | 0.0798703553652043 |
| 47 | 1.0 | 1.000 | YES | 34 | 0.032203149382891184 |
| 48 | 1.0 | 1.000 | YES | 15 | 0.036041447664814534 |
| 49 | 0.0 | 0.000 | YES | 2 | 0.039015606242496996 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
