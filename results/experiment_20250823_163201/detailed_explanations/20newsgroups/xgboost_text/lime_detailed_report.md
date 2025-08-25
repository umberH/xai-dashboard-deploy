# Detailed Explanation Report

**Dataset:** 20newsgroups  
**Model:** xgboost_text  
**Explanation Method:** lime  
**Generated:** 2025-08-24 15:41:15  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7050
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0664
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 141 (70.5%)
- **Incorrect Predictions:** 59 (29.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 2 | 68 | 0.0695 | 34.0% |
| 4 | 62 | 0.0935 | 31.0% |
| 1 | 62 | 0.1538 | 31.0% |
| 3 | 61 | 0.0694 | 30.5% |
| 0 | 61 | 0.1497 | 30.5% |
| 15 | 28 | 0.0885 | 14.0% |
| 5 | 28 | 0.0796 | 14.0% |
| 17 | 24 | 0.0859 | 12.0% |
| 8 | 23 | 0.0936 | 11.5% |
| 16 | 22 | 0.1094 | 11.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.293', '0.219', '0.371', '0.117']
- **Top Features:**
  - Feature 31: 0.2588
  - Feature 22: 0.0891
  - Feature 10: 0.0776

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.059', '0.065', '0.850', '0.026']
- **Top Features:**
  - Feature 40: 0.1298
  - Feature 31: 0.1253
  - Feature 39: 0.1105

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.679', '0.119', '0.132', '0.069']
- **Top Features:**
  - Feature 13: 0.0545
  - Feature 12: 0.0529
  - Feature 17: 0.0469

#### Instance 4

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.004', '0.002', '0.002', '0.992']
- **Top Features:**
  - Feature 10: 0.9958
  - Feature 22: 0.0003
  - Feature 3: 0.0003

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.465', '0.169', '0.205', '0.161']
- **Top Features:**
  - Feature 9: 0.1620
  - Feature 2: 0.1599
  - Feature 4: 0.0539

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.193', '0.215', '0.288', '0.304']
- **Top Features:**
  - Feature 2: 0.1674
  - Feature 48: 0.1183
  - Feature 11: 0.0388

#### Instance 14

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.396', '0.207', '0.276', '0.120']
- **Top Features:**
  - Feature 40: 0.1267
  - Feature 23: 0.1102
  - Feature 28: 0.0937

#### Instance 15

- **True Label:** 0.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.140', '0.365', '0.424', '0.071']
- **Top Features:**
  - Feature 6: 0.1948
  - Feature 49: 0.0677
  - Feature 16: 0.0450

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 2.0 | 2.000 | YES | 31 | 0.25882356304338794 |
| 1 | 2.0 | 2.000 | YES | 40 | 0.12975988688682494 |
| 2 | 2.0 | 3.000 | NO | 2 | 0.16736085954655286 |
| 3 | 0.0 | 0.000 | YES | 13 | 0.054535681398543645 |
| 4 | 3.0 | 3.000 | YES | 10 | 0.9957517557683759 |
| 5 | 0.0 | 0.000 | YES | 9 | 0.16198402799488199 |
| 6 | 1.0 | 1.000 | YES | 25 | 0.9957847810722396 |
| 7 | 3.0 | 3.000 | YES | 20 | 0.9966400921358921 |
| 8 | 2.0 | 2.000 | YES | 3 | 0.22905016622907004 |
| 9 | 2.0 | 2.000 | YES | 0 | 1.0 |
| 10 | 1.0 | 1.000 | YES | 9 | 0.053510310567497485 |
| 11 | 3.0 | 3.000 | YES | 33 | 0.11343731127292403 |
| 12 | 2.0 | 2.000 | YES | 0 | 0.041666666666666664 |
| 13 | 3.0 | 3.000 | YES | 17 | 0.047538525325660476 |
| 14 | 1.0 | 0.000 | NO | 40 | 0.12671412147594993 |
| 15 | 0.0 | 2.000 | NO | 6 | 0.19475296050892638 |
| 16 | 1.0 | 1.000 | YES | 23 | 0.09107903626098873 |
| 17 | 3.0 | 3.000 | YES | 41 | 0.11955927294902563 |
| 18 | 0.0 | 1.000 | NO | 4 | 0.9987384560535666 |
| 19 | 0.0 | 3.000 | NO | 37 | 0.12452615327258629 |
| 20 | 2.0 | 2.000 | YES | 2 | 0.16813765852954693 |
| 21 | 3.0 | 3.000 | YES | 4 | 0.9971798753541569 |
| 22 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 23 | 0.0 | 0.000 | YES | 22 | 0.7501242322114305 |
| 24 | 2.0 | 2.000 | YES | 0 | 0.04 |
| 25 | 1.0 | 1.000 | YES | 13 | 0.07182205838123784 |
| 26 | 1.0 | 0.000 | NO | 20 | 0.24863664092561324 |
| 27 | 3.0 | 3.000 | YES | 9 | 0.19698226946423145 |
| 28 | 2.0 | 0.000 | NO | 0 | 0.0392156862745098 |
| 29 | 0.0 | 0.000 | YES | 2 | 0.6849468683909502 |
| 30 | 1.0 | 1.000 | YES | 16 | 0.08789839093729694 |
| 31 | 3.0 | 3.000 | YES | 28 | 0.20591190798572565 |
| 32 | 0.0 | 3.000 | NO | 29 | 0.14013980243182833 |
| 33 | 2.0 | 1.000 | NO | 38 | 0.15719381229844567 |
| 34 | 2.0 | 2.000 | YES | 0 | 0.0392156862745098 |
| 35 | 0.0 | 0.000 | YES | 4 | 0.21541294788792298 |
| 36 | 2.0 | 2.000 | YES | 3 | 0.18382696626942788 |
| 37 | 0.0 | 3.000 | NO | 17 | 0.19959547991604085 |
| 38 | 2.0 | 0.000 | NO | 1 | 0.9994068417525434 |
| 39 | 1.0 | 1.000 | YES | 6 | 0.4006830525083533 |
| 40 | 2.0 | 1.000 | NO | 0 | 0.0392156862745098 |
| 41 | 0.0 | 3.000 | NO | 31 | 0.17083378159419263 |
| 42 | 2.0 | 2.000 | YES | 0 | 0.0392156862745098 |
| 43 | 3.0 | 3.000 | YES | 41 | 0.11640836128882065 |
| 44 | 2.0 | 1.000 | NO | 48 | 0.13637824717846886 |
| 45 | 2.0 | 2.000 | YES | 1 | 0.05525711939913195 |
| 46 | 3.0 | 3.000 | YES | 40 | 0.3075364547569988 |
| 47 | 1.0 | 1.000 | YES | 5 | 0.99853831004963 |
| 48 | 3.0 | 2.000 | NO | 28 | 0.2808097230556774 |
| 49 | 1.0 | 1.000 | YES | 38 | 0.1872075723015193 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
