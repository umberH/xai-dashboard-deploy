# Detailed Explanation Report

**Dataset:** 20newsgroups  
**Model:** roberta  
**Explanation Method:** lime  
**Generated:** 2025-08-24 12:28:32  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8400
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0354
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 168 (84.0%)
- **Incorrect Predictions:** 32 (16.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 4 | 62 | 0.0647 | 31.0% |
| 0 | 60 | 0.1597 | 30.0% |
| 1 | 54 | 0.0562 | 27.0% |
| 3 | 52 | 0.0573 | 26.0% |
| 2 | 51 | 0.0556 | 25.5% |
| 15 | 27 | 0.0756 | 13.5% |
| 5 | 25 | 0.0964 | 12.5% |
| 8 | 25 | 0.0898 | 12.5% |
| 14 | 24 | 0.0645 | 12.0% |
| 6 | 23 | 0.1062 | 11.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.002', '0.001', '0.995', '0.002']
- **Top Features:**
  - Feature 12: 0.0466
  - Feature 27: 0.0396
  - Feature 0: 0.0362

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.001', '0.001', '0.996', '0.002']
- **Top Features:**
  - Feature 0: 0.0392
  - Feature 1: 0.0384
  - Feature 2: 0.0376

#### Instance 2

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.003', '0.004', '0.990', '0.003']
- **Top Features:**
  - Feature 37: 0.0466
  - Feature 30: 0.0447
  - Feature 36: 0.0377

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.984', '0.004', '0.007', '0.005']
- **Top Features:**
  - Feature 0: 0.0392
  - Feature 1: 0.0384
  - Feature 2: 0.0376

#### Instance 4

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.017', '0.001', '0.003', '0.979']
- **Top Features:**
  - Feature 14: 0.0567
  - Feature 33: 0.0522
  - Feature 1: 0.0502

### Incorrect Predictions (Sample)

#### Instance 8

- **True Label:** 2.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.106', '0.820', '0.037', '0.037']
- **Top Features:**
  - Feature 4: 0.5571
  - Feature 3: 0.2137
  - Feature 0: 0.1709

#### Instance 9

- **True Label:** 2.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.196', '0.355', '0.242', '0.207']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 12

- **True Label:** 2.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.599', '0.015', '0.257', '0.129']
- **Top Features:**
  - Feature 5: 0.1763
  - Feature 16: 0.0617
  - Feature 27: 0.0472

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 2.0 | 2.000 | YES | 12 | 0.046598296996212034 |
| 1 | 2.0 | 2.000 | YES | 0 | 0.0392156862745098 |
| 2 | 2.0 | 2.000 | YES | 37 | 0.04658561841212573 |
| 3 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 4 | 3.0 | 3.000 | YES | 14 | 0.0566762312813878 |
| 5 | 0.0 | 0.000 | YES | 42 | 0.08899775457573048 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 7 | 3.0 | 3.000 | YES | 17 | 0.06559764409977911 |
| 8 | 2.0 | 1.000 | NO | 4 | 0.5571012445372148 |
| 9 | 2.0 | 1.000 | NO | 0 | 1.0 |
| 10 | 1.0 | 1.000 | YES | 0 | 0.043478260869565216 |
| 11 | 3.0 | 3.000 | YES | 24 | 0.04080406383250691 |
| 12 | 2.0 | 0.000 | NO | 5 | 0.17630134808907472 |
| 13 | 3.0 | 3.000 | YES | 43 | 0.06511463912791599 |
| 14 | 1.0 | 0.000 | NO | 31 | 0.07459860869825655 |
| 15 | 0.0 | 2.000 | NO | 33 | 0.14941781974728383 |
| 16 | 1.0 | 1.000 | YES | 49 | 0.0634757647592764 |
| 17 | 3.0 | 3.000 | YES | 41 | 0.07017038389244215 |
| 18 | 0.0 | 2.000 | NO | 17 | 0.2493337324815983 |
| 19 | 0.0 | 3.000 | NO | 46 | 0.1104938005657727 |
| 20 | 2.0 | 2.000 | YES | 18 | 0.1491250010774888 |
| 21 | 3.0 | 3.000 | YES | 35 | 0.09002193051780269 |
| 22 | 1.0 | 1.000 | YES | 25 | 0.06175416478654547 |
| 23 | 0.0 | 3.000 | NO | 7 | 0.16480441185062852 |
| 24 | 2.0 | 2.000 | YES | 41 | 0.042205952779034106 |
| 25 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 26 | 1.0 | 1.000 | YES | 5 | 0.06699844173156193 |
| 27 | 3.0 | 3.000 | YES | 9 | 0.11392502846827957 |
| 28 | 2.0 | 2.000 | YES | 42 | 0.07320586090411343 |
| 29 | 0.0 | 0.000 | YES | 2 | 0.12944189294324487 |
| 30 | 1.0 | 1.000 | YES | 7 | 0.04591083930195143 |
| 31 | 3.0 | 3.000 | YES | 38 | 0.1447061703745126 |
| 32 | 0.0 | 3.000 | NO | 13 | 0.11517874372362796 |
| 33 | 2.0 | 2.000 | YES | 38 | 0.06073255818915356 |
| 34 | 2.0 | 2.000 | YES | 0 | 0.0392156862745098 |
| 35 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 36 | 2.0 | 2.000 | YES | 4 | 0.3286306280090457 |
| 37 | 0.0 | 0.000 | YES | 45 | 0.05982399247954927 |
| 38 | 2.0 | 2.000 | YES | 6 | 0.3951325468144362 |
| 39 | 1.0 | 1.000 | YES | 6 | 0.21111340672890408 |
| 40 | 2.0 | 2.000 | YES | 5 | 0.11392038374362976 |
| 41 | 0.0 | 3.000 | NO | 9 | 0.21717043071721934 |
| 42 | 2.0 | 2.000 | YES | 0 | 0.0392156862745098 |
| 43 | 3.0 | 3.000 | YES | 0 | 0.0392156862745098 |
| 44 | 2.0 | 2.000 | YES | 20 | 0.0685146919847283 |
| 45 | 2.0 | 2.000 | YES | 0 | 0.0392156862745098 |
| 46 | 3.0 | 3.000 | YES | 43 | 0.11063726237744433 |
| 47 | 1.0 | 1.000 | YES | 5 | 0.12718255181804006 |
| 48 | 3.0 | 1.000 | NO | 26 | 0.10238133923795043 |
| 49 | 1.0 | 1.000 | YES | 25 | 0.07296688472758871 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
