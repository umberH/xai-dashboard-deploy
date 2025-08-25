# Detailed Explanation Report

**Dataset:** cifar10  
**Model:** vit  
**Explanation Method:** prototype  
**Generated:** 2025-08-23 18:57:38  

## Summary Statistics

- **Total Instances:** 400
- **Valid Explanations:** 400
- **Errors:** 0
- **Model Accuracy:** 0.2525

## Prediction Analysis

- **Correct Predictions:** 101 (25.2%)
- **Incorrect Predictions:** 299 (74.8%)

## Feature Importance Analysis

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 2

- **True Label:** 8.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.171', '0.060', '0.032', '0.032', '0.027', '0.015', '0.006', '0.048', '0.366', '0.242']
- **Top Features:**

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.313', '0.034', '0.185', '0.056', '0.031', '0.044', '0.008', '0.019', '0.272', '0.038']
- **Top Features:**

#### Instance 5

- **True Label:** 6.0
- **Prediction:** 6.0
- **Prediction Probabilities:** ['0.008', '0.103', '0.080', '0.179', '0.089', '0.189', '0.213', '0.095', '0.005', '0.039']
- **Top Features:**

#### Instance 11

- **True Label:** 9.0
- **Prediction:** 9.0
- **Prediction Probabilities:** ['0.058', '0.131', '0.018', '0.081', '0.023', '0.019', '0.021', '0.093', '0.071', '0.486']
- **Top Features:**

#### Instance 12

- **True Label:** 5.0
- **Prediction:** 5.0
- **Prediction Probabilities:** ['0.016', '0.113', '0.126', '0.090', '0.173', '0.202', '0.155', '0.083', '0.016', '0.027']
- **Top Features:**

### Incorrect Predictions (Sample)

#### Instance 0

- **True Label:** 3.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.022', '0.026', '0.284', '0.090', '0.172', '0.212', '0.110', '0.054', '0.020', '0.010']
- **Top Features:**

#### Instance 1

- **True Label:** 8.0
- **Prediction:** 9.0
- **Prediction Probabilities:** ['0.101', '0.102', '0.009', '0.030', '0.011', '0.007', '0.003', '0.027', '0.245', '0.466']
- **Top Features:**

#### Instance 4

- **True Label:** 6.0
- **Prediction:** 4.0
- **Prediction Probabilities:** ['0.013', '0.014', '0.223', '0.037', '0.293', '0.161', '0.121', '0.127', '0.007', '0.004']
- **Top Features:**

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 3.0 | 2.000 | NO | N/A | N/A |
| 1 | 8.0 | 9.000 | NO | N/A | N/A |
| 2 | 8.0 | 8.000 | YES | N/A | N/A |
| 3 | 0.0 | 0.000 | YES | N/A | N/A |
| 4 | 6.0 | 4.000 | NO | N/A | N/A |
| 5 | 6.0 | 6.000 | YES | N/A | N/A |
| 6 | 1.0 | 6.000 | NO | N/A | N/A |
| 7 | 6.0 | 4.000 | NO | N/A | N/A |
| 8 | 3.0 | 5.000 | NO | N/A | N/A |
| 9 | 1.0 | 0.000 | NO | N/A | N/A |
| 10 | 0.0 | 2.000 | NO | N/A | N/A |
| 11 | 9.0 | 9.000 | YES | N/A | N/A |
| 12 | 5.0 | 5.000 | YES | N/A | N/A |
| 13 | 7.0 | 1.000 | NO | N/A | N/A |
| 14 | 9.0 | 7.000 | NO | N/A | N/A |
| 15 | 8.0 | 2.000 | NO | N/A | N/A |
| 16 | 5.0 | 5.000 | YES | N/A | N/A |
| 17 | 7.0 | 2.000 | NO | N/A | N/A |
| 18 | 8.0 | 9.000 | NO | N/A | N/A |
| 19 | 6.0 | 5.000 | NO | N/A | N/A |
| 20 | 7.0 | 2.000 | NO | N/A | N/A |
| 21 | 0.0 | 2.000 | NO | N/A | N/A |
| 22 | 4.0 | 2.000 | NO | N/A | N/A |
| 23 | 9.0 | 3.000 | NO | N/A | N/A |
| 24 | 5.0 | 2.000 | NO | N/A | N/A |
| 25 | 2.0 | 2.000 | YES | N/A | N/A |
| 26 | 4.0 | 4.000 | YES | N/A | N/A |
| 27 | 0.0 | 7.000 | NO | N/A | N/A |
| 28 | 9.0 | 2.000 | NO | N/A | N/A |
| 29 | 6.0 | 6.000 | YES | N/A | N/A |
| 30 | 6.0 | 6.000 | YES | N/A | N/A |
| 31 | 5.0 | 2.000 | NO | N/A | N/A |
| 32 | 4.0 | 2.000 | NO | N/A | N/A |
| 33 | 5.0 | 2.000 | NO | N/A | N/A |
| 34 | 9.0 | 9.000 | YES | N/A | N/A |
| 35 | 2.0 | 5.000 | NO | N/A | N/A |
| 36 | 4.0 | 2.000 | NO | N/A | N/A |
| 37 | 1.0 | 9.000 | NO | N/A | N/A |
| 38 | 9.0 | 3.000 | NO | N/A | N/A |
| 39 | 5.0 | 2.000 | NO | N/A | N/A |
| 40 | 4.0 | 2.000 | NO | N/A | N/A |
| 41 | 6.0 | 6.000 | YES | N/A | N/A |
| 42 | 5.0 | 9.000 | NO | N/A | N/A |
| 43 | 6.0 | 4.000 | NO | N/A | N/A |
| 44 | 0.0 | 0.000 | YES | N/A | N/A |
| 45 | 9.0 | 0.000 | NO | N/A | N/A |
| 46 | 3.0 | 5.000 | NO | N/A | N/A |
| 47 | 9.0 | 0.000 | NO | N/A | N/A |
| 48 | 7.0 | 4.000 | NO | N/A | N/A |
| 49 | 6.0 | 4.000 | NO | N/A | N/A |

*Showing first 50 of 400 instances. See JSON file for complete data.*
