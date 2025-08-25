# Detailed Explanation Report

**Dataset:** fashion_mnist  
**Model:** vit  
**Explanation Method:** concept_bottleneck  
**Generated:** 2025-08-23 19:02:31  

## Summary Statistics

- **Total Instances:** 400
- **Valid Explanations:** 400
- **Errors:** 0
- **Model Accuracy:** 0.7100

## Prediction Analysis

- **Correct Predictions:** 284 (71.0%)
- **Incorrect Predictions:** 116 (29.0%)

## Feature Importance Analysis

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.011', '0.001', '0.591', '0.016', '0.132', '0.001', '0.242', '0.000', '0.006', '0.000']
- **Top Features:**

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.006', '0.972', '0.003', '0.010', '0.004', '0.000', '0.001', '0.000', '0.003', '0.000']
- **Top Features:**

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.003', '0.979', '0.001', '0.012', '0.003', '0.000', '0.001', '0.000', '0.001', '0.000']
- **Top Features:**

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.007', '0.957', '0.007', '0.010', '0.014', '0.000', '0.002', '0.000', '0.004', '0.000']
- **Top Features:**

#### Instance 7

- **True Label:** 6.0
- **Prediction:** 6.0
- **Prediction Probabilities:** ['0.033', '0.001', '0.396', '0.012', '0.099', '0.001', '0.453', '0.000', '0.004', '0.001']
- **Top Features:**

### Incorrect Predictions (Sample)

#### Instance 0

- **True Label:** 9.0
- **Prediction:** 5.0
- **Prediction Probabilities:** ['0.002', '0.000', '0.002', '0.001', '0.002', '0.769', '0.003', '0.090', '0.011', '0.121']
- **Top Features:**

#### Instance 4

- **True Label:** 6.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.021', '0.001', '0.605', '0.024', '0.099', '0.001', '0.246', '0.000', '0.002', '0.000']
- **Top Features:**

#### Instance 6

- **True Label:** 4.0
- **Prediction:** 6.0
- **Prediction Probabilities:** ['0.087', '0.002', '0.390', '0.016', '0.106', '0.002', '0.394', '0.000', '0.002', '0.001']
- **Top Features:**

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 9.0 | 5.000 | NO | N/A | N/A |
| 1 | 2.0 | 2.000 | YES | N/A | N/A |
| 2 | 1.0 | 1.000 | YES | N/A | N/A |
| 3 | 1.0 | 1.000 | YES | N/A | N/A |
| 4 | 6.0 | 2.000 | NO | N/A | N/A |
| 5 | 1.0 | 1.000 | YES | N/A | N/A |
| 6 | 4.0 | 6.000 | NO | N/A | N/A |
| 7 | 6.0 | 6.000 | YES | N/A | N/A |
| 8 | 5.0 | 5.000 | YES | N/A | N/A |
| 9 | 7.0 | 7.000 | YES | N/A | N/A |
| 10 | 4.0 | 4.000 | YES | N/A | N/A |
| 11 | 5.0 | 5.000 | YES | N/A | N/A |
| 12 | 7.0 | 8.000 | NO | N/A | N/A |
| 13 | 3.0 | 3.000 | YES | N/A | N/A |
| 14 | 4.0 | 4.000 | YES | N/A | N/A |
| 15 | 1.0 | 1.000 | YES | N/A | N/A |
| 16 | 2.0 | 2.000 | YES | N/A | N/A |
| 17 | 4.0 | 2.000 | NO | N/A | N/A |
| 18 | 8.0 | 8.000 | YES | N/A | N/A |
| 19 | 0.0 | 0.000 | YES | N/A | N/A |
| 20 | 2.0 | 2.000 | YES | N/A | N/A |
| 21 | 5.0 | 7.000 | NO | N/A | N/A |
| 22 | 7.0 | 7.000 | YES | N/A | N/A |
| 23 | 9.0 | 5.000 | NO | N/A | N/A |
| 24 | 1.0 | 1.000 | YES | N/A | N/A |
| 25 | 4.0 | 2.000 | NO | N/A | N/A |
| 26 | 6.0 | 4.000 | NO | N/A | N/A |
| 27 | 0.0 | 3.000 | NO | N/A | N/A |
| 28 | 9.0 | 7.000 | NO | N/A | N/A |
| 29 | 3.0 | 4.000 | NO | N/A | N/A |
| 30 | 8.0 | 8.000 | YES | N/A | N/A |
| 31 | 8.0 | 6.000 | NO | N/A | N/A |
| 32 | 3.0 | 3.000 | YES | N/A | N/A |
| 33 | 3.0 | 4.000 | NO | N/A | N/A |
| 34 | 8.0 | 8.000 | YES | N/A | N/A |
| 35 | 0.0 | 0.000 | YES | N/A | N/A |
| 36 | 7.0 | 7.000 | YES | N/A | N/A |
| 37 | 5.0 | 5.000 | YES | N/A | N/A |
| 38 | 7.0 | 7.000 | YES | N/A | N/A |
| 39 | 9.0 | 9.000 | YES | N/A | N/A |
| 40 | 6.0 | 6.000 | YES | N/A | N/A |
| 41 | 1.0 | 1.000 | YES | N/A | N/A |
| 42 | 3.0 | 3.000 | YES | N/A | N/A |
| 43 | 7.0 | 7.000 | YES | N/A | N/A |
| 44 | 6.0 | 2.000 | NO | N/A | N/A |
| 45 | 7.0 | 5.000 | NO | N/A | N/A |
| 46 | 2.0 | 2.000 | YES | N/A | N/A |
| 47 | 1.0 | 1.000 | YES | N/A | N/A |
| 48 | 2.0 | 4.000 | NO | N/A | N/A |
| 49 | 2.0 | 2.000 | YES | N/A | N/A |

*Showing first 50 of 400 instances. See JSON file for complete data.*
