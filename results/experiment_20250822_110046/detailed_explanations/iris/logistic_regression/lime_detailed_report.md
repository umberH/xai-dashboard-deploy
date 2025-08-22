# Detailed Explanation Report

**Dataset:** iris  
**Model:** logistic_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:09:54  

## Summary Statistics

- **Total Instances:** 30
- **Valid Explanations:** 30
- **Errors:** 0
- **Model Accuracy:** 0.9333
- **Average Feature Importance:** 0.0583
- **Feature Importance Std:** 0.1858
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 28 (93.3%)
- **Incorrect Predictions:** 2 (6.7%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 30 | 0.0079 | 100.0% |
| 1 | 30 | 0.0688 | 100.0% |
| 2 | 30 | 0.0517 | 100.0% |
| 3 | 30 | 0.1050 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.979', '0.021', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.004', '0.369', '0.627']
- **Top Features:**
  - Feature 3: 0.6953
  - Feature 2: 0.2344
  - Feature 0: 0.0704

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.149', '0.842', '0.009']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.095', '0.895', '0.010']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.988', '0.012', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 23

- **True Label:** 2.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.001', '0.515', '0.484']
- **Top Features:**
  - Feature 3: 0.4838
  - Feature 2: 0.4531
  - Feature 0: 0.0631

#### Instance 25

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.001', '0.442', '0.557']
- **Top Features:**
  - Feature 3: 0.6035
  - Feature 2: 0.3624
  - Feature 0: 0.0341

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 1 | 2.0 | 2.000 | YES | 3 | 0.6952535853624688 |
| 2 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 3 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 3 | 0.6951944532725001 |
| 6 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 9 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 10 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 11 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 12 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 13 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 16 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 17 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 18 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 19 | 2.0 | 2.000 | YES | 3 | 0.6720697040947601 |
| 20 | 0.0 | 0.000 | YES | 1 | 1.0 |
| 21 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 22 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 23 | 2.0 | 1.000 | NO | 3 | 0.48384504491342256 |
| 24 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 25 | 1.0 | 2.000 | NO | 3 | 0.603458021209615 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 27 | 0.0 | 0.000 | YES | 1 | 1.0 |
| 28 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 29 | 0.0 | 0.000 | YES | 0 | 0.0 |
