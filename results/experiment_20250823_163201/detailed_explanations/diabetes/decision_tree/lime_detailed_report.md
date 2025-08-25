# Detailed Explanation Report

**Dataset:** diabetes  
**Model:** decision_tree  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:33:15  

## Summary Statistics

- **Total Instances:** 89
- **Valid Explanations:** 89
- **Errors:** 0
- **Model Accuracy:** 0.4944
- **Average Feature Importance:** 0.0427
- **Feature Importance Std:** 0.1918
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 44 (49.4%)
- **Incorrect Predictions:** 45 (50.6%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 2 | 89 | 0.2911 | 100.0% |
| 0 | 88 | 0.0357 | 98.9% |
| 1 | 87 | 0.0000 | 97.8% |
| 3 | 83 | 0.0241 | 93.3% |
| 4 | 77 | 0.0010 | 86.5% |
| 8 | 7 | 0.4196 | 7.9% |
| 9 | 5 | 0.2306 | 5.6% |
| 5 | 4 | 0.5800 | 4.5% |
| 7 | 4 | 0.0898 | 4.5% |
| 6 | 1 | 0.0934 | 1.1% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 3

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.000', '1.000']
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

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.000', '1.000']
- **Top Features:**
  - Feature 8: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.000', '1.000']
- **Top Features:**
  - Feature 2: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.000', '1.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 2.000 | NO | 2 | 1.0 |
| 1 | 0.0 | 2.000 | NO | 0 | 0.0 |
| 2 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 3 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 6 | 2.0 | 2.000 | YES | 8 | 1.0 |
| 7 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 11 | 0.0 | 0.000 | YES | 0 | 1.0 |
| 12 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 13 | 2.0 | 0.000 | NO | 2 | 1.0 |
| 14 | 1.0 | 0.000 | NO | 2 | 1.0 |
| 15 | 2.0 | 1.000 | NO | 2 | 1.0 |
| 16 | 0.0 | 0.000 | YES | 5 | 1.0 |
| 17 | 0.0 | 2.000 | NO | 2 | 1.0 |
| 18 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 1.000 | NO | 2 | 0.5775712973849418 |
| 21 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 22 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 23 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 24 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 25 | 2.0 | 2.000 | YES | 2 | 0.928173797366879 |
| 26 | 1.0 | 1.000 | YES | 2 | 0.6201926917733962 |
| 27 | 1.0 | 2.000 | NO | 5 | 0.9896103896103896 |
| 28 | 2.0 | 2.000 | YES | 2 | 0.5916881635793336 |
| 29 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 30 | 0.0 | 1.000 | NO | 2 | 0.9948580830933772 |
| 31 | 2.0 | 1.000 | NO | 2 | 1.0 |
| 32 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 34 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 35 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 36 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 37 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 38 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 39 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 40 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 41 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 2.000 | NO | 0 | 0.0 |
| 43 | 2.0 | 0.000 | NO | 2 | 0.8273809523809524 |
| 44 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 45 | 0.0 | 2.000 | NO | 8 | 0.8031742505206092 |
| 46 | 2.0 | 1.000 | NO | 2 | 0.8333333333333334 |
| 47 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 48 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 49 | 1.0 | 0.000 | NO | 3 | 1.0 |

*Showing first 50 of 89 instances. See JSON file for complete data.*
