# Detailed Explanation Report

**Dataset:** cifar10  
**Model:** cnn  
**Explanation Method:** occlusion  
**Generated:** 2025-08-23 18:57:08  

## Summary Statistics

- **Total Instances:** 400
- **Valid Explanations:** 400
- **Errors:** 0
- **Model Accuracy:** 0.5125

## Prediction Analysis

- **Correct Predictions:** 205 (51.2%)
- **Incorrect Predictions:** 195 (48.8%)

## Feature Importance Analysis

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.001', '0.000', '0.105', '0.740', '0.005', '0.106', '0.038', '0.001', '0.004', '0.000']
- **Top Features:**

#### Instance 1

- **True Label:** 8.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.448', '0.074', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.473', '0.005']
- **Top Features:**

#### Instance 2

- **True Label:** 8.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.421', '0.045', '0.000', '0.000', '0.001', '0.000', '0.000', '0.000', '0.528', '0.005']
- **Top Features:**

#### Instance 4

- **True Label:** 6.0
- **Prediction:** 6.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.011', '0.043', '0.076', '0.014', '0.855', '0.001', '0.000', '0.000']
- **Top Features:**

#### Instance 10

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.866', '0.000', '0.087', '0.001', '0.011', '0.002', '0.002', '0.000', '0.032', '0.000']
- **Top Features:**

### Incorrect Predictions (Sample)

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.474', '0.003', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.522', '0.000']
- **Top Features:**

#### Instance 5

- **True Label:** 6.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.000', '0.001', '0.016', '0.619', '0.063', '0.010', '0.251', '0.035', '0.001', '0.004']
- **Top Features:**

#### Instance 6

- **True Label:** 1.0
- **Prediction:** 9.0
- **Prediction Probabilities:** ['0.010', '0.074', '0.000', '0.396', '0.002', '0.003', '0.005', '0.084', '0.009', '0.416']
- **Top Features:**

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 3.0 | 3.000 | YES | N/A | N/A |
| 1 | 8.0 | 8.000 | YES | N/A | N/A |
| 2 | 8.0 | 8.000 | YES | N/A | N/A |
| 3 | 0.0 | 8.000 | NO | N/A | N/A |
| 4 | 6.0 | 6.000 | YES | N/A | N/A |
| 5 | 6.0 | 3.000 | NO | N/A | N/A |
| 6 | 1.0 | 9.000 | NO | N/A | N/A |
| 7 | 6.0 | 4.000 | NO | N/A | N/A |
| 8 | 3.0 | 4.000 | NO | N/A | N/A |
| 9 | 1.0 | 9.000 | NO | N/A | N/A |
| 10 | 0.0 | 0.000 | YES | N/A | N/A |
| 11 | 9.0 | 9.000 | YES | N/A | N/A |
| 12 | 5.0 | 5.000 | YES | N/A | N/A |
| 13 | 7.0 | 7.000 | YES | N/A | N/A |
| 14 | 9.0 | 9.000 | YES | N/A | N/A |
| 15 | 8.0 | 0.000 | NO | N/A | N/A |
| 16 | 5.0 | 3.000 | NO | N/A | N/A |
| 17 | 7.0 | 7.000 | YES | N/A | N/A |
| 18 | 8.0 | 8.000 | YES | N/A | N/A |
| 19 | 6.0 | 6.000 | YES | N/A | N/A |
| 20 | 7.0 | 5.000 | NO | N/A | N/A |
| 21 | 0.0 | 0.000 | YES | N/A | N/A |
| 22 | 4.0 | 0.000 | NO | N/A | N/A |
| 23 | 9.0 | 1.000 | NO | N/A | N/A |
| 24 | 5.0 | 4.000 | NO | N/A | N/A |
| 25 | 2.0 | 2.000 | YES | N/A | N/A |
| 26 | 4.0 | 6.000 | NO | N/A | N/A |
| 27 | 0.0 | 4.000 | NO | N/A | N/A |
| 28 | 9.0 | 1.000 | NO | N/A | N/A |
| 29 | 6.0 | 6.000 | YES | N/A | N/A |
| 30 | 6.0 | 3.000 | NO | N/A | N/A |
| 31 | 5.0 | 4.000 | NO | N/A | N/A |
| 32 | 4.0 | 4.000 | YES | N/A | N/A |
| 33 | 5.0 | 3.000 | NO | N/A | N/A |
| 34 | 9.0 | 9.000 | YES | N/A | N/A |
| 35 | 2.0 | 6.000 | NO | N/A | N/A |
| 36 | 4.0 | 4.000 | YES | N/A | N/A |
| 37 | 1.0 | 1.000 | YES | N/A | N/A |
| 38 | 9.0 | 9.000 | YES | N/A | N/A |
| 39 | 5.0 | 5.000 | YES | N/A | N/A |
| 40 | 4.0 | 0.000 | NO | N/A | N/A |
| 41 | 6.0 | 6.000 | YES | N/A | N/A |
| 42 | 5.0 | 3.000 | NO | N/A | N/A |
| 43 | 6.0 | 4.000 | NO | N/A | N/A |
| 44 | 0.0 | 0.000 | YES | N/A | N/A |
| 45 | 9.0 | 9.000 | YES | N/A | N/A |
| 46 | 3.0 | 3.000 | YES | N/A | N/A |
| 47 | 9.0 | 9.000 | YES | N/A | N/A |
| 48 | 7.0 | 4.000 | NO | N/A | N/A |
| 49 | 6.0 | 4.000 | NO | N/A | N/A |

*Showing first 50 of 400 instances. See JSON file for complete data.*
