# Detailed Explanation Report

**Dataset:** ag_news  
**Model:** svm_text  
**Explanation Method:** attention_visualization  
**Generated:** 2025-08-24 19:03:00  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7900
- **Average Feature Importance:** 0.0641
- **Feature Importance Std:** 0.0494
- **Max Feature Importance:** 0.4629

## Prediction Analysis

- **Correct Predictions:** 158 (79.0%)
- **Incorrect Predictions:** 42 (21.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 136 | 0.0736 | 68.0% |
| 1 | 108 | 0.0824 | 54.0% |
| 2 | 104 | 0.0817 | 52.0% |
| 19 | 22 | 0.0769 | 11.0% |
| 17 | 22 | 0.0837 | 11.0% |
| 24 | 21 | 0.0925 | 10.5% |
| 9 | 21 | 0.1047 | 10.5% |
| 10 | 20 | 0.0688 | 10.0% |
| 20 | 20 | 0.0794 | 10.0% |
| 13 | 20 | 0.1009 | 10.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.062', '0.677', '0.089', '0.172']
- **Top Features:**
  - Feature 15: 0.0525
  - Feature 0: 0.0350
  - Feature 2: 0.0327

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 42: 0.0286
  - Feature 0: 0.0259
  - Feature 43: 0.0256

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.937', '0.009', '0.045', '0.010']
- **Top Features:**
  - Feature 18: 0.0313
  - Feature 1: 0.0306
  - Feature 2: 0.0306

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.025', '0.972', '0.001', '0.001']
- **Top Features:**
  - Feature 0: 0.0363
  - Feature 1: 0.0363
  - Feature 31: 0.0350

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.059', '0.841', '0.068', '0.031']
- **Top Features:**
  - Feature 2: 0.0348
  - Feature 19: 0.0340
  - Feature 10: 0.0324

### Incorrect Predictions (Sample)

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.005', '0.995']
- **Top Features:**
  - Feature 19: 0.1645
  - Feature 0: 0.1555
  - Feature 35: 0.1500

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.766', '0.106', '0.079', '0.049']
- **Top Features:**
  - Feature 11: 0.0293
  - Feature 0: 0.0269
  - Feature 36: 0.0269

#### Instance 22

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.064', '0.036', '0.200', '0.701']
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
| 7 | 1.0 | 0.000 | NO | 11 | 0.029307607766516055 |
| 8 | 0.0 | 0.000 | YES | 26 | 0.027834008097165987 |
| 9 | 3.0 | 3.000 | YES | 1 | 0.1697667552406259 |
| 10 | 3.0 | 3.000 | YES | 11 | 0.1544223945327901 |
| 11 | 3.0 | 3.000 | YES | 31 | 0.32656341320864984 |
| 12 | 1.0 | 1.000 | YES | 1 | 0.02889414236931967 |
| 13 | 2.0 | 2.000 | YES | 40 | 0.09387121799844839 |
| 14 | 3.0 | 3.000 | YES | 16 | 0.13442466244473653 |
| 15 | 3.0 | 3.000 | YES | 1 | 0.15102698348771645 |
| 16 | 2.0 | 2.000 | YES | 8 | 0.19836096107282544 |
| 17 | 0.0 | 0.000 | YES | 5 | 0.03399332061068702 |
| 18 | 1.0 | 1.000 | YES | 12 | 0.04546249344290959 |
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
| 39 | 3.0 | 0.000 | NO | 6 | 0.07195989650711512 |
| 40 | 2.0 | 2.000 | YES | 10 | 0.11970172684458397 |
| 41 | 2.0 | 2.000 | YES | 1 | 0.08852335509794072 |
| 42 | 2.0 | 2.000 | YES | 0 | 0.09273251820304985 |
| 43 | 2.0 | 2.000 | YES | 40 | 0.08102818371607515 |
| 44 | 2.0 | 2.000 | YES | 1 | 0.09477311889718551 |
| 45 | 1.0 | 1.000 | YES | 1 | 0.03065031982942431 |
| 46 | 2.0 | 2.000 | YES | 0 | 0.0798703553652043 |
| 47 | 1.0 | 1.000 | YES | 34 | 0.032203149382891184 |
| 48 | 1.0 | 1.000 | YES | 15 | 0.036041447664814534 |
| 49 | 0.0 | 0.000 | YES | 22 | 0.06300695249130937 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
