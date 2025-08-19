# Detailed Explanation Report

**Dataset:** imdb  
**Model:** lstm  
**Explanation Method:** lime  
**Generated:** 2025-08-19 18:35:21  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8150
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0236
- **Max Feature Importance:** 0.5687

## Prediction Analysis

- **Correct Predictions:** 163 (81.5%)
- **Incorrect Predictions:** 37 (18.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 4 | 34 | 0.0674 | 17.0% |
| 1 | 32 | 0.0642 | 16.0% |
| 2 | 30 | 0.0585 | 15.0% |
| 12 | 29 | 0.0690 | 14.5% |
| 43 | 29 | 0.0710 | 14.5% |
| 8 | 29 | 0.0700 | 14.5% |
| 15 | 29 | 0.0676 | 14.5% |
| 13 | 29 | 0.0665 | 14.5% |
| 3 | 28 | 0.0733 | 14.0% |
| 38 | 26 | 0.0721 | 13.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.781', '0.219']
- **Top Features:**
  - Feature 4: 0.0738
  - Feature 38: 0.0685
  - Feature 20: 0.0472

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.356', '0.644']
- **Top Features:**
  - Feature 19: 0.0500
  - Feature 23: 0.0481
  - Feature 25: 0.0466

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.397', '0.603']
- **Top Features:**
  - Feature 6: 0.0662
  - Feature 43: 0.0653
  - Feature 35: 0.0649

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.323', '0.677']
- **Top Features:**
  - Feature 24: 0.0433
  - Feature 42: 0.0423
  - Feature 14: 0.0421

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.341', '0.659']
- **Top Features:**
  - Feature 44: 0.1074
  - Feature 48: 0.0715
  - Feature 22: 0.0607

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.503', '0.497']
- **Top Features:**
  - Feature 23: 0.1465
  - Feature 35: 0.0851
  - Feature 4: 0.0689

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.413', '0.587']
- **Top Features:**
  - Feature 46: 0.0916
  - Feature 2: 0.0801
  - Feature 3: 0.0800

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.656', '0.344']
- **Top Features:**
  - Feature 5: 0.0803
  - Feature 49: 0.0635
  - Feature 7: 0.0634

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 4 | 0.07379628856079394 |
| 1 | 1.0 | 1.000 | YES | 19 | 0.049993705738148694 |
| 2 | 1.0 | 0.000 | NO | 23 | 0.14647715837381156 |
| 3 | 1.0 | 1.000 | YES | 6 | 0.06623298242536166 |
| 4 | 1.0 | 1.000 | YES | 24 | 0.043298307118940706 |
| 5 | 1.0 | 1.000 | YES | 44 | 0.10738526685676085 |
| 6 | 1.0 | 1.000 | YES | 15 | 0.04946230209270844 |
| 7 | 0.0 | 1.000 | NO | 46 | 0.09164017467212528 |
| 8 | 1.0 | 0.000 | NO | 5 | 0.08034232913237487 |
| 9 | 1.0 | 1.000 | YES | 30 | 0.05499665824056439 |
| 10 | 0.0 | 0.000 | YES | 30 | 0.14618306218685792 |
| 11 | 0.0 | 1.000 | NO | 9 | 0.1950064069941553 |
| 12 | 1.0 | 1.000 | YES | 44 | 0.12601521019175943 |
| 13 | 1.0 | 1.000 | YES | 43 | 0.09303731858398226 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 15 | 0.0 | 0.000 | YES | 28 | 0.10644843505050618 |
| 16 | 1.0 | 1.000 | YES | 21 | 0.27120473418712 |
| 17 | 0.0 | 1.000 | NO | 18 | 0.05357939481734367 |
| 18 | 1.0 | 1.000 | YES | 29 | 0.25013448994261256 |
| 19 | 0.0 | 1.000 | NO | 16 | 0.1558104822380472 |
| 20 | 1.0 | 1.000 | YES | 3 | 0.34003794705803747 |
| 21 | 0.0 | 0.000 | YES | 19 | 0.08187307389563987 |
| 22 | 1.0 | 1.000 | YES | 23 | 0.08934693034804411 |
| 23 | 1.0 | 0.000 | NO | 15 | 0.09143529244812895 |
| 24 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 25 | 1.0 | 1.000 | YES | 49 | 0.08497110868931816 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 27 | 0.0 | 0.000 | YES | 30 | 0.0854128731546888 |
| 28 | 0.0 | 1.000 | NO | 7 | 0.08394834773422127 |
| 29 | 1.0 | 1.000 | YES | 4 | 0.16218305234462554 |
| 30 | 0.0 | 0.000 | YES | 23 | 0.04857555102976245 |
| 31 | 0.0 | 0.000 | YES | 17 | 0.23178369204177388 |
| 32 | 0.0 | 0.000 | YES | 20 | 0.04480333155008355 |
| 33 | 0.0 | 1.000 | NO | 23 | 0.12739383268239288 |
| 34 | 0.0 | 0.000 | YES | 6 | 0.046708636898768245 |
| 35 | 0.0 | 0.000 | YES | 23 | 0.15506472354233167 |
| 36 | 1.0 | 1.000 | YES | 17 | 0.14143245796647244 |
| 37 | 1.0 | 1.000 | YES | 33 | 0.08074251913103249 |
| 38 | 1.0 | 1.000 | YES | 38 | 0.10926580693247366 |
| 39 | 0.0 | 0.000 | YES | 24 | 0.16127193020795644 |
| 40 | 0.0 | 0.000 | YES | 43 | 0.2095280726530389 |
| 41 | 0.0 | 1.000 | NO | 17 | 0.16259249705298565 |
| 42 | 1.0 | 1.000 | YES | 2 | 0.0750963115886383 |
| 43 | 1.0 | 1.000 | YES | 22 | 0.07956709299409473 |
| 44 | 0.0 | 0.000 | YES | 20 | 0.06366699872192047 |
| 45 | 0.0 | 0.000 | YES | 34 | 0.12039361373429548 |
| 46 | 1.0 | 1.000 | YES | 6 | 0.12894195279899573 |
| 47 | 1.0 | 1.000 | YES | 43 | 0.14637937287732905 |
| 48 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 49 | 0.0 | 0.000 | YES | 9 | 0.11002921832190235 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
