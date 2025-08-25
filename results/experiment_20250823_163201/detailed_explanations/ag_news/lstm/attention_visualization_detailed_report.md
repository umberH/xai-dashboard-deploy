# Detailed Explanation Report

**Dataset:** ag_news  
**Model:** lstm  
**Explanation Method:** attention_visualization  
**Generated:** 2025-08-24 15:44:26  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7800
- **Average Feature Importance:** 0.0617
- **Feature Importance Std:** 0.0493
- **Max Feature Importance:** 0.6069

## Prediction Analysis

- **Correct Predictions:** 156 (78.0%)
- **Incorrect Predictions:** 44 (22.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 128 | 0.0684 | 64.0% |
| 1 | 109 | 0.0771 | 54.5% |
| 2 | 103 | 0.0703 | 51.5% |
| 19 | 23 | 0.0781 | 11.5% |
| 11 | 22 | 0.1409 | 11.0% |
| 20 | 20 | 0.0825 | 10.0% |
| 24 | 20 | 0.0851 | 10.0% |
| 35 | 19 | 0.0530 | 9.5% |
| 28 | 19 | 0.0985 | 9.5% |
| 23 | 19 | 0.0564 | 9.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.145', '0.400', '0.191', '0.265']
- **Top Features:**
  - Feature 15: 0.0525
  - Feature 0: 0.0350
  - Feature 2: 0.0327

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.030', '0.899', '0.030', '0.041']
- **Top Features:**
  - Feature 42: 0.0286
  - Feature 0: 0.0259
  - Feature 43: 0.0256

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.633', '0.099', '0.165', '0.103']
- **Top Features:**
  - Feature 18: 0.0313
  - Feature 1: 0.0306
  - Feature 2: 0.0306

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.143', '0.754', '0.054', '0.050']
- **Top Features:**
  - Feature 0: 0.0363
  - Feature 1: 0.0363
  - Feature 31: 0.0350

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.104', '0.562', '0.159', '0.175']
- **Top Features:**
  - Feature 2: 0.0348
  - Feature 19: 0.0340
  - Feature 10: 0.0324

### Incorrect Predictions (Sample)

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.358', '0.330', '0.172', '0.139']
- **Top Features:**
  - Feature 35: 0.0394
  - Feature 7: 0.0376
  - Feature 28: 0.0376

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.034', '0.032', '0.067', '0.866']
- **Top Features:**
  - Feature 19: 0.1645
  - Feature 0: 0.1555
  - Feature 35: 0.1500

#### Instance 15

- **True Label:** 3.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.107', '0.356', '0.190', '0.348']
- **Top Features:**
  - Feature 2: 0.0476
  - Feature 19: 0.0473
  - Feature 31: 0.0464

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 15 | 0.052519409346932555 |
| 1 | 1.0 | 1.000 | YES | 42 | 0.028645511791579203 |
| 2 | 0.0 | 0.000 | YES | 18 | 0.03131808278867102 |
| 3 | 1.0 | 1.000 | YES | 0 | 0.036339610175090846 |
| 4 | 1.0 | 1.000 | YES | 2 | 0.03476062569126244 |
| 5 | 1.0 | 0.000 | NO | 35 | 0.039352180707486854 |
| 6 | 2.0 | 3.000 | NO | 19 | 0.16450096765275088 |
| 7 | 1.0 | 1.000 | YES | 2 | 0.032599837000814993 |
| 8 | 0.0 | 0.000 | YES | 26 | 0.027834008097165987 |
| 9 | 3.0 | 3.000 | YES | 1 | 0.1697667552406259 |
| 10 | 3.0 | 3.000 | YES | 11 | 0.1544223945327901 |
| 11 | 3.0 | 3.000 | YES | 16 | 0.18698931489629161 |
| 12 | 1.0 | 1.000 | YES | 1 | 0.02889414236931967 |
| 13 | 2.0 | 2.000 | YES | 40 | 0.09387121799844839 |
| 14 | 3.0 | 3.000 | YES | 16 | 0.13442466244473653 |
| 15 | 3.0 | 1.000 | NO | 2 | 0.04759550006181233 |
| 16 | 2.0 | 2.000 | YES | 19 | 0.18720748829953193 |
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
| 40 | 2.0 | 2.000 | YES | 0 | 0.11501850872554203 |
| 41 | 2.0 | 2.000 | YES | 21 | 0.10913528591352858 |
| 42 | 2.0 | 2.000 | YES | 0 | 0.09273251820304985 |
| 43 | 2.0 | 2.000 | YES | 40 | 0.08102818371607515 |
| 44 | 2.0 | 2.000 | YES | 1 | 0.09477311889718551 |
| 45 | 1.0 | 1.000 | YES | 1 | 0.03065031982942431 |
| 46 | 2.0 | 2.000 | YES | 0 | 0.0798703553652043 |
| 47 | 1.0 | 1.000 | YES | 34 | 0.032203149382891184 |
| 48 | 1.0 | 1.000 | YES | 15 | 0.036041447664814534 |
| 49 | 0.0 | 2.000 | NO | 4 | 0.12233096085409251 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
