# Detailed Explanation Report

**Dataset:** ag_news  
**Model:** bert  
**Explanation Method:** attention_visualization  
**Generated:** 2025-08-24 15:43:39  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7900
- **Average Feature Importance:** 0.0656
- **Feature Importance Std:** 0.0505
- **Max Feature Importance:** 0.6069

## Prediction Analysis

- **Correct Predictions:** 158 (79.0%)
- **Incorrect Predictions:** 42 (21.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 132 | 0.0740 | 66.0% |
| 1 | 110 | 0.0856 | 55.0% |
| 2 | 99 | 0.0832 | 49.5% |
| 19 | 24 | 0.0913 | 12.0% |
| 20 | 22 | 0.0862 | 11.0% |
| 22 | 21 | 0.0792 | 10.5% |
| 28 | 21 | 0.1033 | 10.5% |
| 24 | 20 | 0.0888 | 10.0% |
| 23 | 19 | 0.0582 | 9.5% |
| 17 | 19 | 0.0772 | 9.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.164', '0.362', '0.216', '0.258']
- **Top Features:**
  - Feature 15: 0.0525
  - Feature 0: 0.0350
  - Feature 2: 0.0327

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.026', '0.902', '0.032', '0.040']
- **Top Features:**
  - Feature 42: 0.0286
  - Feature 0: 0.0259
  - Feature 43: 0.0256

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.536', '0.127', '0.219', '0.118']
- **Top Features:**
  - Feature 18: 0.0313
  - Feature 1: 0.0306
  - Feature 2: 0.0306

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.206', '0.622', '0.093', '0.079']
- **Top Features:**
  - Feature 0: 0.0363
  - Feature 1: 0.0363
  - Feature 31: 0.0350

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.165', '0.393', '0.237', '0.205']
- **Top Features:**
  - Feature 2: 0.0348
  - Feature 19: 0.0340
  - Feature 10: 0.0324

### Incorrect Predictions (Sample)

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.054', '0.047', '0.086', '0.813']
- **Top Features:**
  - Feature 19: 0.1645
  - Feature 0: 0.1555
  - Feature 35: 0.1500

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.432', '0.288', '0.139', '0.142']
- **Top Features:**
  - Feature 11: 0.0293
  - Feature 0: 0.0269
  - Feature 36: 0.0269

#### Instance 22

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.140', '0.208', '0.253', '0.398']
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
| 5 | 1.0 | 1.000 | YES | 33 | 0.04171934260429835 |
| 6 | 2.0 | 3.000 | NO | 19 | 0.16450096765275088 |
| 7 | 1.0 | 0.000 | NO | 11 | 0.029307607766516055 |
| 8 | 0.0 | 0.000 | YES | 26 | 0.027834008097165987 |
| 9 | 3.0 | 3.000 | YES | 1 | 0.1697667552406259 |
| 10 | 3.0 | 3.000 | YES | 11 | 0.1544223945327901 |
| 11 | 3.0 | 3.000 | YES | 25 | 0.3177966101694915 |
| 12 | 1.0 | 1.000 | YES | 1 | 0.02889414236931967 |
| 13 | 2.0 | 2.000 | YES | 40 | 0.09387121799844839 |
| 14 | 3.0 | 3.000 | YES | 16 | 0.13442466244473653 |
| 15 | 3.0 | 3.000 | YES | 1 | 0.15102698348771645 |
| 16 | 2.0 | 2.000 | YES | 2 | 0.15415672600477148 |
| 17 | 0.0 | 0.000 | YES | 5 | 0.03399332061068702 |
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
| 40 | 2.0 | 2.000 | YES | 0 | 0.11624799572421164 |
| 41 | 2.0 | 2.000 | YES | 1 | 0.08852335509794072 |
| 42 | 2.0 | 2.000 | YES | 0 | 0.09273251820304985 |
| 43 | 2.0 | 2.000 | YES | 40 | 0.08102818371607515 |
| 44 | 2.0 | 2.000 | YES | 1 | 0.09477311889718551 |
| 45 | 1.0 | 1.000 | YES | 1 | 0.03065031982942431 |
| 46 | 2.0 | 2.000 | YES | 0 | 0.0798703553652043 |
| 47 | 1.0 | 1.000 | YES | 33 | 0.039276195819890586 |
| 48 | 1.0 | 1.000 | YES | 15 | 0.036041447664814534 |
| 49 | 0.0 | 2.000 | NO | 4 | 0.12089683470105508 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
