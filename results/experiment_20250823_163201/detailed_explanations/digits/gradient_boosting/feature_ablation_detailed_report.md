# Detailed Explanation Report

**Dataset:** digits  
**Model:** gradient_boosting  
**Explanation Method:** feature_ablation  
**Generated:** 2025-08-23 18:52:13  

## Summary Statistics

- **Total Instances:** 360
- **Valid Explanations:** 360
- **Errors:** 0
- **Model Accuracy:** 0.9528

## Prediction Analysis

- **Correct Predictions:** 343 (95.3%)
- **Incorrect Predictions:** 17 (4.7%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 360 | 0.0000 | 100.0% |
| 1 | 360 | 0.0000 | 100.0% |
| 2 | 360 | 0.0111 | 100.0% |
| 3 | 360 | 0.0056 | 100.0% |
| 4 | 360 | 0.0028 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 5.0
- **Prediction:** 5.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '0.000', '0.000', '0.990', '0.000', '0.000', '0.000', '0.010']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.000', '1.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 8.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.000', '0.001', '0.000', '0.001', '0.000', '0.000', '0.000', '0.000', '0.997', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '0.897', '0.000', '0.000', '0.000', '0.001', '0.096', '0.000', '0.005', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 7.0
- **Prediction:** 7.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.999', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 24

- **True Label:** 2.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.000', '0.001', '0.122', '0.004', '0.000', '0.000', '0.000', '0.000', '0.870', '0.002']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 36

- **True Label:** 6.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.000', '0.003', '0.001', '0.001', '0.007', '0.003', '0.001', '0.002', '0.982', '0.001']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 51

- **True Label:** 8.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '0.919', '0.000', '0.001', '0.003', '0.001', '0.000', '0.000', '0.068', '0.009']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 5.0 | 5.000 | YES | 0 | 0 |
| 1 | 2.0 | 2.000 | YES | 0 | 0 |
| 2 | 8.0 | 8.000 | YES | 0 | 0 |
| 3 | 1.0 | 1.000 | YES | 0 | 0 |
| 4 | 7.0 | 7.000 | YES | 0 | 0 |
| 5 | 2.0 | 2.000 | YES | 0 | 0 |
| 6 | 6.0 | 6.000 | YES | 0 | 0 |
| 7 | 2.0 | 2.000 | YES | 0 | 0 |
| 8 | 6.0 | 6.000 | YES | 0 | 0 |
| 9 | 5.0 | 5.000 | YES | 0 | 0 |
| 10 | 0.0 | 0.000 | YES | 0 | 0 |
| 11 | 5.0 | 5.000 | YES | 0 | 0 |
| 12 | 9.0 | 9.000 | YES | 0 | 0 |
| 13 | 3.0 | 3.000 | YES | 0 | 0 |
| 14 | 4.0 | 4.000 | YES | 0 | 0 |
| 15 | 4.0 | 4.000 | YES | 0 | 0 |
| 16 | 2.0 | 2.000 | YES | 0 | 0 |
| 17 | 4.0 | 4.000 | YES | 0 | 0 |
| 18 | 9.0 | 9.000 | YES | 0 | 0 |
| 19 | 9.0 | 9.000 | YES | 0 | 0 |
| 20 | 6.0 | 6.000 | YES | 0 | 0 |
| 21 | 3.0 | 3.000 | YES | 0 | 0 |
| 22 | 8.0 | 8.000 | YES | 0 | 0 |
| 23 | 1.0 | 1.000 | YES | 0 | 0 |
| 24 | 2.0 | 8.000 | NO | 0 | 0 |
| 25 | 5.0 | 5.000 | YES | 0 | 0 |
| 26 | 6.0 | 6.000 | YES | 0 | 0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0 |
| 28 | 3.0 | 3.000 | YES | 0 | 0 |
| 29 | 4.0 | 4.000 | YES | 0 | 0 |
| 30 | 6.0 | 6.000 | YES | 0 | 0 |
| 31 | 7.0 | 7.000 | YES | 0 | 0 |
| 32 | 2.0 | 2.000 | YES | 0 | 0 |
| 33 | 6.0 | 6.000 | YES | 0 | 0 |
| 34 | 6.0 | 6.000 | YES | 0 | 0 |
| 35 | 6.0 | 6.000 | YES | 0 | 0 |
| 36 | 6.0 | 8.000 | NO | 0 | 0 |
| 37 | 5.0 | 5.000 | YES | 0 | 0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0 |
| 39 | 9.0 | 9.000 | YES | 0 | 0 |
| 40 | 1.0 | 1.000 | YES | 0 | 0 |
| 41 | 7.0 | 7.000 | YES | 0 | 0 |
| 42 | 9.0 | 9.000 | YES | 0 | 0 |
| 43 | 6.0 | 6.000 | YES | 0 | 0 |
| 44 | 5.0 | 5.000 | YES | 0 | 0 |
| 45 | 7.0 | 7.000 | YES | 0 | 0 |
| 46 | 5.0 | 5.000 | YES | 0 | 0 |
| 47 | 2.0 | 2.000 | YES | 0 | 0 |
| 48 | 7.0 | 7.000 | YES | 0 | 0 |
| 49 | 5.0 | 5.000 | YES | 0 | 0 |

*Showing first 50 of 360 instances. See JSON file for complete data.*
