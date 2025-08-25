# Detailed Explanation Report

**Dataset:** imdb  
**Model:** bert  
**Explanation Method:** lime  
**Generated:** 2025-08-23 19:05:14  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8100
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0215
- **Max Feature Importance:** 0.3102

## Prediction Analysis

- **Correct Predictions:** 162 (81.0%)
- **Incorrect Predictions:** 38 (19.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 47 | 0.0538 | 23.5% |
| 4 | 41 | 0.0661 | 20.5% |
| 3 | 41 | 0.0586 | 20.5% |
| 2 | 39 | 0.0535 | 19.5% |
| 0 | 35 | 0.0504 | 17.5% |
| 13 | 30 | 0.0726 | 15.0% |
| 20 | 27 | 0.0609 | 13.5% |
| 8 | 27 | 0.0695 | 13.5% |
| 7 | 26 | 0.0651 | 13.0% |
| 45 | 25 | 0.0639 | 12.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.753', '0.247']
- **Top Features:**
  - Feature 39: 0.0740
  - Feature 4: 0.0627
  - Feature 27: 0.0566

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.320', '0.680']
- **Top Features:**
  - Feature 0: 0.0392
  - Feature 1: 0.0384
  - Feature 2: 0.0376

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.350', '0.650']
- **Top Features:**
  - Feature 43: 0.0998
  - Feature 17: 0.0863
  - Feature 7: 0.0630

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.259', '0.741']
- **Top Features:**
  - Feature 2: 0.0590
  - Feature 35: 0.0449
  - Feature 37: 0.0415

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.371', '0.629']
- **Top Features:**
  - Feature 48: 0.0613
  - Feature 22: 0.0548
  - Feature 3: 0.0481

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.510', '0.490']
- **Top Features:**
  - Feature 4: 0.1067
  - Feature 23: 0.0943
  - Feature 1: 0.0556

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.405', '0.595']
- **Top Features:**
  - Feature 3: 0.0487
  - Feature 40: 0.0462
  - Feature 1: 0.0407

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.656', '0.344']
- **Top Features:**
  - Feature 49: 0.1734
  - Feature 7: 0.1435
  - Feature 18: 0.0497

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 39 | 0.07399514711864986 |
| 1 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 2 | 1.0 | 0.000 | NO | 4 | 0.10669327180319858 |
| 3 | 1.0 | 1.000 | YES | 43 | 0.09975630975487586 |
| 4 | 1.0 | 1.000 | YES | 2 | 0.058984656961156165 |
| 5 | 1.0 | 1.000 | YES | 48 | 0.06126770538913944 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 7 | 0.0 | 1.000 | NO | 3 | 0.04870289006489559 |
| 8 | 1.0 | 0.000 | NO | 49 | 0.1733913620531347 |
| 9 | 1.0 | 1.000 | YES | 49 | 0.056051043183195134 |
| 10 | 0.0 | 0.000 | YES | 30 | 0.12684758275557892 |
| 11 | 0.0 | 0.000 | YES | 46 | 0.128324723723774 |
| 12 | 1.0 | 1.000 | YES | 22 | 0.05313024352903935 |
| 13 | 1.0 | 1.000 | YES | 43 | 0.08369204386507438 |
| 14 | 0.0 | 0.000 | YES | 17 | 0.07560949015571966 |
| 15 | 0.0 | 0.000 | YES | 42 | 0.1165099856880962 |
| 16 | 1.0 | 1.000 | YES | 21 | 0.14775365061270218 |
| 17 | 0.0 | 1.000 | NO | 48 | 0.06069678596461113 |
| 18 | 1.0 | 1.000 | YES | 26 | 0.14159606806736844 |
| 19 | 0.0 | 1.000 | NO | 16 | 0.09918795203645737 |
| 20 | 1.0 | 1.000 | YES | 3 | 0.19990399792557043 |
| 21 | 0.0 | 0.000 | YES | 38 | 0.055964812871491056 |
| 22 | 1.0 | 1.000 | YES | 25 | 0.09747914251935548 |
| 23 | 1.0 | 1.000 | YES | 20 | 0.09030466986266121 |
| 24 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 25 | 1.0 | 1.000 | YES | 22 | 0.11948217068290305 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 27 | 0.0 | 0.000 | YES | 8 | 0.1007444747045385 |
| 28 | 0.0 | 1.000 | NO | 14 | 0.0533513804110984 |
| 29 | 1.0 | 1.000 | YES | 24 | 0.09240679484441298 |
| 30 | 0.0 | 0.000 | YES | 26 | 0.06809022317306575 |
| 31 | 0.0 | 0.000 | YES | 17 | 0.31024773010010065 |
| 32 | 0.0 | 0.000 | YES | 18 | 0.059451032121208884 |
| 33 | 0.0 | 1.000 | NO | 16 | 0.11854055969580582 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 35 | 0.0 | 0.000 | YES | 23 | 0.1968760534857572 |
| 36 | 1.0 | 1.000 | YES | 17 | 0.15109404018776504 |
| 37 | 1.0 | 1.000 | YES | 43 | 0.04451648195469131 |
| 38 | 1.0 | 1.000 | YES | 47 | 0.0699383490954309 |
| 39 | 0.0 | 0.000 | YES | 13 | 0.0757576169069566 |
| 40 | 0.0 | 0.000 | YES | 43 | 0.17954708287063148 |
| 41 | 0.0 | 1.000 | NO | 48 | 0.17222104066856153 |
| 42 | 1.0 | 1.000 | YES | 45 | 0.07803011297731566 |
| 43 | 1.0 | 1.000 | YES | 22 | 0.07982192272247039 |
| 44 | 0.0 | 0.000 | YES | 39 | 0.08780636750871282 |
| 45 | 0.0 | 0.000 | YES | 34 | 0.11931560038806892 |
| 46 | 1.0 | 1.000 | YES | 6 | 0.07783954998225859 |
| 47 | 1.0 | 1.000 | YES | 36 | 0.07977799115268612 |
| 48 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 49 | 0.0 | 0.000 | YES | 22 | 0.0757507107074803 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
