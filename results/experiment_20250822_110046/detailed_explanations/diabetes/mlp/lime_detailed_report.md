# Detailed Explanation Report

**Dataset:** diabetes  
**Model:** mlp  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:25:04  

## Summary Statistics

- **Total Instances:** 89
- **Valid Explanations:** 89
- **Errors:** 0
- **Model Accuracy:** 0.4494
- **Average Feature Importance:** 0.0494
- **Feature Importance Std:** 0.1479
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 40 (44.9%)
- **Incorrect Predictions:** 49 (55.1%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 77 | 0.1048 | 86.5% |
| 2 | 74 | 0.1052 | 83.1% |
| 1 | 72 | 0.0241 | 80.9% |
| 4 | 69 | 0.0718 | 77.5% |
| 3 | 65 | 0.0301 | 73.0% |
| 8 | 23 | 0.1989 | 25.8% |
| 7 | 17 | 0.1534 | 19.1% |
| 5 | 16 | 0.1688 | 18.0% |
| 9 | 16 | 0.1928 | 18.0% |
| 6 | 16 | 0.3298 | 18.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.226', '0.446', '0.328']
- **Top Features:**
  - Feature 2: 0.3229
  - Feature 8: 0.2012
  - Feature 4: 0.1945

#### Instance 3

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.004', '0.996']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.303', '0.046', '0.651']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.046', '0.866', '0.088']
- **Top Features:**
  - Feature 4: 0.4776
  - Feature 8: 0.3864
  - Feature 5: 0.0680

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.013', '0.038', '0.950']
- **Top Features:**
  - Feature 3: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.984', '0.016', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.828', '0.106', '0.065']
- **Top Features:**
  - Feature 5: 0.3629
  - Feature 7: 0.1785
  - Feature 8: 0.1721

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 2 | 0.3228850872985165 |
| 1 | 0.0 | 2.000 | NO | 3 | 1.0 |
| 2 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 3 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 0.000 | NO | 5 | 0.36291642966182674 |
| 6 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 7 | 1.0 | 2.000 | NO | 9 | 0.27262566649079706 |
| 8 | 1.0 | 1.000 | YES | 4 | 0.47755102040816366 |
| 9 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 0.000 | NO | 0 | 0.6759366990733894 |
| 11 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 1.000 | NO | 2 | 0.7475707124959975 |
| 13 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 14 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 15 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 16 | 0.0 | 0.000 | YES | 4 | 0.2550463351160795 |
| 17 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 18 | 0.0 | 1.000 | NO | 0 | 0.6055427046891644 |
| 19 | 0.0 | 0.000 | YES | 4 | 0.5796964675445408 |
| 20 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 21 | 0.0 | 1.000 | NO | 8 | 0.32912290484599577 |
| 22 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 23 | 0.0 | 0.000 | YES | 0 | 0.7756345228149741 |
| 24 | 0.0 | 0.000 | YES | 7 | 0.391500708378017 |
| 25 | 2.0 | 1.000 | NO | 0 | 0.2495918359052279 |
| 26 | 1.0 | 1.000 | YES | 4 | 0.3771938368307137 |
| 27 | 1.0 | 2.000 | NO | 0 | 0.0 |
| 28 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 29 | 1.0 | 0.000 | NO | 0 | 0.6145268236530551 |
| 30 | 0.0 | 0.000 | YES | 2 | 0.6797850296246318 |
| 31 | 2.0 | 2.000 | YES | 2 | 0.2988620682941514 |
| 32 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 0.000 | NO | 6 | 1.0 |
| 34 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 35 | 1.0 | 0.000 | NO | 6 | 1.0 |
| 36 | 1.0 | 2.000 | NO | 4 | 0.41595604938559294 |
| 37 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 38 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 39 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 40 | 0.0 | 0.000 | YES | 5 | 0.49322468117995105 |
| 41 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 43 | 2.0 | 2.000 | YES | 9 | 0.5956391013243937 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 45 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 46 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 47 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 48 | 0.0 | 0.000 | YES | 0 | 0.623030485163845 |
| 49 | 1.0 | 0.000 | NO | 2 | 0.8972311152414083 |

*Showing first 50 of 89 instances. See JSON file for complete data.*
