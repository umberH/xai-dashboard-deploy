# Detailed Explanation Report

**Dataset:** diabetes  
**Model:** decision_tree  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:19:33  

## Summary Statistics

- **Total Instances:** 89
- **Valid Explanations:** 89
- **Errors:** 0
- **Model Accuracy:** 0.4944
- **Average Feature Importance:** 0.0461
- **Feature Importance Std:** 0.1972
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 44 (49.4%)
- **Incorrect Predictions:** 45 (50.6%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 2 | 89 | 0.2813 | 100.0% |
| 0 | 87 | 0.0385 | 97.8% |
| 1 | 85 | 0.0013 | 95.5% |
| 3 | 82 | 0.0247 | 92.1% |
| 4 | 70 | 0.0015 | 78.7% |
| 8 | 15 | 0.4445 | 16.9% |
| 9 | 8 | 0.1566 | 9.0% |
| 5 | 6 | 0.3413 | 6.7% |
| 7 | 2 | 0.0689 | 2.2% |
| 6 | 1 | 0.0724 | 1.1% |

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
  - Feature 8: 0.9859
  - Feature 2: 0.0099
  - Feature 0: 0.0042

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
  - Feature 2: 0.7807
  - Feature 8: 0.1359
  - Feature 3: 0.0706

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.000', '1.000']
- **Top Features:**
  - Feature 8: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

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
| 0 | 1.0 | 2.000 | NO | 2 | 0.7807456788982521 |
| 1 | 0.0 | 2.000 | NO | 8 | 1.0 |
| 2 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 3 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 6 | 2.0 | 2.000 | YES | 8 | 0.9859054134008763 |
| 7 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 8 | 1.0 |
| 9 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 11 | 0.0 | 0.000 | YES | 0 | 1.0 |
| 12 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 13 | 2.0 | 0.000 | NO | 2 | 1.0 |
| 14 | 1.0 | 0.000 | NO | 2 | 1.0 |
| 15 | 2.0 | 1.000 | NO | 2 | 0.9 |
| 16 | 0.0 | 0.000 | YES | 5 | 0.9670660728694489 |
| 17 | 0.0 | 2.000 | NO | 2 | 1.0 |
| 18 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 1.000 | NO | 8 | 0.504266877515027 |
| 21 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 22 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 23 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 24 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 25 | 2.0 | 2.000 | YES | 2 | 0.8786401615266575 |
| 26 | 1.0 | 1.000 | YES | 2 | 0.6597496358342637 |
| 27 | 1.0 | 2.000 | NO | 5 | 0.9799979343248574 |
| 28 | 2.0 | 2.000 | YES | 2 | 0.5544594539528941 |
| 29 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 30 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 31 | 2.0 | 1.000 | NO | 2 | 1.0 |
| 32 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 34 | 0.0 | 0.000 | YES | 2 | 0.8571428571428571 |
| 35 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 36 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 37 | 0.0 | 1.000 | NO | 8 | 1.0 |
| 38 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 39 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 40 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 41 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 2.000 | NO | 0 | 0.0 |
| 43 | 2.0 | 0.000 | NO | 2 | 1.0 |
| 44 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 45 | 0.0 | 2.000 | NO | 8 | 0.919618887452577 |
| 46 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 47 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 48 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 49 | 1.0 | 0.000 | NO | 3 | 1.0 |

*Showing first 50 of 89 instances. See JSON file for complete data.*
