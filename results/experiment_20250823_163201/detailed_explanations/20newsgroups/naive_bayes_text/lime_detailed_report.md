# Detailed Explanation Report

**Dataset:** 20newsgroups  
**Model:** naive_bayes_text  
**Explanation Method:** lime  
**Generated:** 2025-08-24 15:36:17  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7350
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0356
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 147 (73.5%)
- **Incorrect Predictions:** 53 (26.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 4 | 52 | 0.0836 | 26.0% |
| 1 | 48 | 0.0941 | 24.0% |
| 0 | 44 | 0.1938 | 22.0% |
| 2 | 43 | 0.0759 | 21.5% |
| 3 | 43 | 0.0707 | 21.5% |
| 5 | 34 | 0.0888 | 17.0% |
| 8 | 28 | 0.0914 | 14.0% |
| 11 | 27 | 0.0621 | 13.5% |
| 7 | 26 | 0.0818 | 13.0% |
| 20 | 25 | 0.0639 | 12.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.109', '0.118', '0.643', '0.130']
- **Top Features:**
  - Feature 0: 0.0557
  - Feature 26: 0.0465
  - Feature 37: 0.0458

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.079', '0.067', '0.770', '0.084']
- **Top Features:**
  - Feature 0: 0.0392
  - Feature 1: 0.0384
  - Feature 2: 0.0376

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.493', '0.140', '0.154', '0.213']
- **Top Features:**
  - Feature 2: 0.0625
  - Feature 14: 0.0568
  - Feature 28: 0.0563

#### Instance 4

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.090', '0.077', '0.097', '0.736']
- **Top Features:**
  - Feature 46: 0.0393
  - Feature 8: 0.0379
  - Feature 22: 0.0356

#### Instance 6

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.091', '0.498', '0.218', '0.193']
- **Top Features:**
  - Feature 15: 0.0825
  - Feature 25: 0.0729
  - Feature 9: 0.0623

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.161', '0.150', '0.314', '0.375']
- **Top Features:**
  - Feature 2: 0.1367
  - Feature 23: 0.1027
  - Feature 42: 0.0545

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.376', '0.085', '0.153', '0.386']
- **Top Features:**
  - Feature 11: 0.1480
  - Feature 45: 0.1033
  - Feature 12: 0.0617

#### Instance 12

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.213', '0.145', '0.217', '0.425']
- **Top Features:**
  - Feature 1: 0.0635
  - Feature 26: 0.0533
  - Feature 7: 0.0455

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 2.0 | 2.000 | YES | 0 | 0.05566491663384679 |
| 1 | 2.0 | 2.000 | YES | 0 | 0.0392156862745098 |
| 2 | 2.0 | 3.000 | NO | 2 | 0.1367091564889613 |
| 3 | 0.0 | 0.000 | YES | 2 | 0.062459738610449095 |
| 4 | 3.0 | 3.000 | YES | 46 | 0.03933162953848108 |
| 5 | 0.0 | 3.000 | NO | 11 | 0.14795614524121264 |
| 6 | 1.0 | 1.000 | YES | 15 | 0.08250622029178174 |
| 7 | 3.0 | 3.000 | YES | 31 | 0.05199650580910689 |
| 8 | 2.0 | 2.000 | YES | 4 | 0.21825988100049667 |
| 9 | 2.0 | 2.000 | YES | 0 | 1.0 |
| 10 | 1.0 | 1.000 | YES | 38 | 0.04806620789232655 |
| 11 | 3.0 | 3.000 | YES | 36 | 0.05179343654870323 |
| 12 | 2.0 | 3.000 | NO | 1 | 0.06348047367440308 |
| 13 | 3.0 | 3.000 | YES | 7 | 0.05195133384939826 |
| 14 | 1.0 | 3.000 | NO | 7 | 0.055671467722935235 |
| 15 | 0.0 | 2.000 | NO | 8 | 0.07910485651672333 |
| 16 | 1.0 | 1.000 | YES | 21 | 0.12560276641294493 |
| 17 | 3.0 | 3.000 | YES | 17 | 0.05366436441354381 |
| 18 | 0.0 | 2.000 | NO | 1 | 0.28765271985000057 |
| 19 | 0.0 | 3.000 | NO | 37 | 0.12590412864814401 |
| 20 | 2.0 | 2.000 | YES | 10 | 0.09472637758519968 |
| 21 | 3.0 | 3.000 | YES | 4 | 0.19674953910587462 |
| 22 | 1.0 | 1.000 | YES | 26 | 0.11214679810596698 |
| 23 | 0.0 | 3.000 | NO | 7 | 0.13309015965598164 |
| 24 | 2.0 | 2.000 | YES | 35 | 0.09711391592623361 |
| 25 | 1.0 | 1.000 | YES | 22 | 0.06202385861673608 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.08880717424884217 |
| 27 | 3.0 | 3.000 | YES | 33 | 0.07127759869954983 |
| 28 | 2.0 | 2.000 | YES | 7 | 0.05369636877275245 |
| 29 | 0.0 | 3.000 | NO | 18 | 0.23701758538164505 |
| 30 | 1.0 | 1.000 | YES | 17 | 0.05410538780841638 |
| 31 | 3.0 | 3.000 | YES | 16 | 0.03906622960875951 |
| 32 | 0.0 | 3.000 | NO | 29 | 0.07606238680178007 |
| 33 | 2.0 | 2.000 | YES | 41 | 0.07530302867964168 |
| 34 | 2.0 | 2.000 | YES | 0 | 0.0392156862745098 |
| 35 | 0.0 | 3.000 | NO | 7 | 0.10530901296233192 |
| 36 | 2.0 | 2.000 | YES | 4 | 0.1852174866244838 |
| 37 | 0.0 | 2.000 | NO | 41 | 0.07940857995503187 |
| 38 | 2.0 | 3.000 | NO | 2 | 0.3517980769567334 |
| 39 | 1.0 | 1.000 | YES | 6 | 0.35336926638695976 |
| 40 | 2.0 | 2.000 | YES | 5 | 0.07792978543667971 |
| 41 | 0.0 | 3.000 | NO | 18 | 0.08774580471210272 |
| 42 | 2.0 | 2.000 | YES | 0 | 0.0392156862745098 |
| 43 | 3.0 | 3.000 | YES | 3 | 0.041522458120775846 |
| 44 | 2.0 | 3.000 | NO | 44 | 0.05121231863778907 |
| 45 | 2.0 | 2.000 | YES | 32 | 0.04556080182196927 |
| 46 | 3.0 | 3.000 | YES | 21 | 0.06481366962526375 |
| 47 | 1.0 | 1.000 | YES | 20 | 0.18642857759050116 |
| 48 | 3.0 | 1.000 | NO | 31 | 0.13749461599576934 |
| 49 | 1.0 | 1.000 | YES | 38 | 0.09772943669636841 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
