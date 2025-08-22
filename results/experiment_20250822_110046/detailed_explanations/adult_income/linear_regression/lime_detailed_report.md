# Detailed Explanation Report

**Dataset:** adult_income  
**Model:** linear_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-22 13:16:02  

## Summary Statistics

- **Total Instances:** 6033
- **Valid Explanations:** 6033
- **Errors:** 0
- **Model Accuracy:** 0.7915
- **Average Feature Importance:** 0.0154
- **Feature Importance Std:** 0.0912
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 4775 (79.1%)
- **Incorrect Predictions:** 1258 (20.9%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 6033 | 0.0256 | 100.0% |
| 1 | 6033 | 0.0333 | 100.0% |
| 2 | 6033 | 0.0007 | 100.0% |
| 3 | 6033 | 0.0023 | 100.0% |
| 4 | 6033 | 0.0150 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.476', '0.524']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.438', '0.562']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.492', '0.508']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 6

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.361', '0.639']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.469', '0.531']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.361', '0.639']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.408', '0.592']
- **Top Features:**
  - Feature 1: 0.8887
  - Feature 4: 0.1113
  - Feature 0: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.401', '0.599']
- **Top Features:**
  - Feature 1: 0.7345
  - Feature 3: 0.2387
  - Feature 4: 0.0268

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 1 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 2 | 1.0 | 0.000 | NO | 1 | 0.8886668069289572 |
| 3 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 0.000 | NO | 1 | 0.7345139492552958 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 9 | 1.0 | 0.000 | NO | 4 | 0.6280302865037555 |
| 10 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 11 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 12 | 0.0 | 0.000 | YES | 1 | 0.5160261325773037 |
| 13 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 16 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 17 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 18 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 21 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 22 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 23 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 24 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 25 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 26 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 28 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 29 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 30 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 31 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 32 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 33 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 35 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 36 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 37 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 40 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 41 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 42 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 43 | 0.0 | 0.000 | YES | 1 | 0.7230160142395354 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 45 | 1.0 | 0.000 | NO | 1 | 0.543618773878563 |
| 46 | 1.0 | 0.000 | NO | 0 | 0.4692028758254011 |
| 47 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 48 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 49 | 1.0 | 0.000 | NO | 1 | 0.9540096602599824 |

*Showing first 50 of 6033 instances. See JSON file for complete data.*
