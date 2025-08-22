# Detailed Explanation Report

**Dataset:** breast_cancer  
**Model:** logistic_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-22 13:57:09  

## Summary Statistics

- **Total Instances:** 114
- **Valid Explanations:** 114
- **Errors:** 0
- **Model Accuracy:** 0.9825
- **Average Feature Importance:** 0.0038
- **Feature Importance Std:** 0.0400
- **Max Feature Importance:** 0.8583

## Prediction Analysis

- **Correct Predictions:** 112 (98.2%)
- **Incorrect Predictions:** 2 (1.8%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 109 | 0.0024 | 95.6% |
| 1 | 105 | 0.0000 | 92.1% |
| 2 | 104 | 0.0031 | 91.2% |
| 4 | 103 | 0.0018 | 90.4% |
| 3 | 102 | 0.0027 | 89.5% |
| 28 | 5 | 0.6740 | 4.4% |
| 24 | 5 | 0.1530 | 4.4% |
| 27 | 4 | 0.2671 | 3.5% |
| 9 | 4 | 0.0377 | 3.5% |
| 5 | 3 | 0.4337 | 2.6% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.994', '0.006']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.466', '0.534']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 16

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.634', '0.366']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 53

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.091', '0.909']
- **Top Features:**
  - Feature 5: 0.6667
  - Feature 27: 0.2222
  - Feature 4: 0.1111

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 1 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 2 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 3 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 9 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 11 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 12 | 1.0 | 1.000 | YES | 28 | 0.7711626097858416 |
| 13 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 16 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 17 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 18 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 19 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 21 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 22 | 1.0 | 1.000 | YES | 28 | 0.5006965509404964 |
| 23 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 24 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 25 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 26 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 27 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 28 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 29 | 1.0 | 1.000 | YES | 10 | 0.36796463795901485 |
| 30 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 31 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 35 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 36 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 37 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 38 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 39 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 40 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 41 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 43 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 45 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 46 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 47 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 48 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 49 | 0.0 | 0.000 | YES | 0 | 0.0 |

*Showing first 50 of 114 instances. See JSON file for complete data.*
