# Detailed Explanation Report

**Dataset:** fashion_mnist  
**Model:** resnet  
**Explanation Method:** prototype  
**Generated:** 2025-08-23 19:04:33  

## Summary Statistics

- **Total Instances:** 400
- **Valid Explanations:** 400
- **Errors:** 0
- **Model Accuracy:** 0.7575

## Prediction Analysis

- **Correct Predictions:** 303 (75.8%)
- **Incorrect Predictions:** 97 (24.2%)

## Feature Importance Analysis

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 9.0
- **Prediction:** 9.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '0.000', '0.000', '0.017', '0.000', '0.260', '0.029', '0.692']
- **Top Features:**

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.015', '0.000', '0.949', '0.006', '0.029', '0.000', '0.001', '0.000', '0.000', '0.000']
- **Top Features:**

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000']
- **Top Features:**

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000']
- **Top Features:**

#### Instance 4

- **True Label:** 6.0
- **Prediction:** 6.0
- **Prediction Probabilities:** ['0.100', '0.004', '0.010', '0.023', '0.151', '0.001', '0.709', '0.001', '0.002', '0.000']
- **Top Features:**

### Incorrect Predictions (Sample)

#### Instance 7

- **True Label:** 6.0
- **Prediction:** 4.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.002', '0.001', '0.844', '0.000', '0.152', '0.000', '0.000', '0.000']
- **Top Features:**

#### Instance 12

- **True Label:** 7.0
- **Prediction:** 5.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '0.000', '0.000', '0.655', '0.000', '0.344', '0.001', '0.000']
- **Top Features:**

#### Instance 17

- **True Label:** 4.0
- **Prediction:** 6.0
- **Prediction Probabilities:** ['0.133', '0.001', '0.002', '0.001', '0.018', '0.000', '0.844', '0.000', '0.000', '0.000']
- **Top Features:**

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 9.0 | 9.000 | YES | N/A | N/A |
| 1 | 2.0 | 2.000 | YES | N/A | N/A |
| 2 | 1.0 | 1.000 | YES | N/A | N/A |
| 3 | 1.0 | 1.000 | YES | N/A | N/A |
| 4 | 6.0 | 6.000 | YES | N/A | N/A |
| 5 | 1.0 | 1.000 | YES | N/A | N/A |
| 6 | 4.0 | 4.000 | YES | N/A | N/A |
| 7 | 6.0 | 4.000 | NO | N/A | N/A |
| 8 | 5.0 | 5.000 | YES | N/A | N/A |
| 9 | 7.0 | 7.000 | YES | N/A | N/A |
| 10 | 4.0 | 4.000 | YES | N/A | N/A |
| 11 | 5.0 | 5.000 | YES | N/A | N/A |
| 12 | 7.0 | 5.000 | NO | N/A | N/A |
| 13 | 3.0 | 3.000 | YES | N/A | N/A |
| 14 | 4.0 | 4.000 | YES | N/A | N/A |
| 15 | 1.0 | 1.000 | YES | N/A | N/A |
| 16 | 2.0 | 2.000 | YES | N/A | N/A |
| 17 | 4.0 | 6.000 | NO | N/A | N/A |
| 18 | 8.0 | 8.000 | YES | N/A | N/A |
| 19 | 0.0 | 0.000 | YES | N/A | N/A |
| 20 | 2.0 | 2.000 | YES | N/A | N/A |
| 21 | 5.0 | 7.000 | NO | N/A | N/A |
| 22 | 7.0 | 7.000 | YES | N/A | N/A |
| 23 | 9.0 | 5.000 | NO | N/A | N/A |
| 24 | 1.0 | 1.000 | YES | N/A | N/A |
| 25 | 4.0 | 2.000 | NO | N/A | N/A |
| 26 | 6.0 | 4.000 | NO | N/A | N/A |
| 27 | 0.0 | 1.000 | NO | N/A | N/A |
| 28 | 9.0 | 9.000 | YES | N/A | N/A |
| 29 | 3.0 | 4.000 | NO | N/A | N/A |
| 30 | 8.0 | 8.000 | YES | N/A | N/A |
| 31 | 8.0 | 5.000 | NO | N/A | N/A |
| 32 | 3.0 | 1.000 | NO | N/A | N/A |
| 33 | 3.0 | 3.000 | YES | N/A | N/A |
| 34 | 8.0 | 8.000 | YES | N/A | N/A |
| 35 | 0.0 | 0.000 | YES | N/A | N/A |
| 36 | 7.0 | 7.000 | YES | N/A | N/A |
| 37 | 5.0 | 5.000 | YES | N/A | N/A |
| 38 | 7.0 | 7.000 | YES | N/A | N/A |
| 39 | 9.0 | 9.000 | YES | N/A | N/A |
| 40 | 6.0 | 0.000 | NO | N/A | N/A |
| 41 | 1.0 | 1.000 | YES | N/A | N/A |
| 42 | 3.0 | 4.000 | NO | N/A | N/A |
| 43 | 7.0 | 7.000 | YES | N/A | N/A |
| 44 | 6.0 | 4.000 | NO | N/A | N/A |
| 45 | 7.0 | 9.000 | NO | N/A | N/A |
| 46 | 2.0 | 4.000 | NO | N/A | N/A |
| 47 | 1.0 | 1.000 | YES | N/A | N/A |
| 48 | 2.0 | 4.000 | NO | N/A | N/A |
| 49 | 2.0 | 6.000 | NO | N/A | N/A |

*Showing first 50 of 400 instances. See JSON file for complete data.*
