# Detailed Explanation Report

**Dataset:** cifar10  
**Model:** resnet  
**Explanation Method:** counterfactual  
**Generated:** 2025-08-23 19:01:35  

## Summary Statistics

- **Total Instances:** 400
- **Valid Explanations:** 400
- **Errors:** 0
- **Model Accuracy:** 0.3950

## Prediction Analysis

- **Correct Predictions:** 158 (39.5%)
- **Incorrect Predictions:** 242 (60.5%)

## Feature Importance Analysis

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 2

- **True Label:** 8.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.065', '0.002', '0.000', '0.000', '0.008', '0.000', '0.000', '0.000', '0.866', '0.059']
- **Top Features:**

#### Instance 4

- **True Label:** 6.0
- **Prediction:** 6.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.001', '0.087', '0.419', '0.010', '0.468', '0.015', '0.000', '0.000']
- **Top Features:**

#### Instance 8

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.002', '0.001', '0.019', '0.490', '0.361', '0.101', '0.014', '0.008', '0.003', '0.001']
- **Top Features:**

#### Instance 10

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.348', '0.000', '0.207', '0.261', '0.024', '0.015', '0.013', '0.000', '0.130', '0.000']
- **Top Features:**

#### Instance 11

- **True Label:** 9.0
- **Prediction:** 9.0
- **Prediction Probabilities:** ['0.000', '0.001', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.999']
- **Top Features:**

### Incorrect Predictions (Sample)

#### Instance 0

- **True Label:** 3.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.005', '0.003', '0.051', '0.294', '0.012', '0.007', '0.039', '0.000', '0.589', '0.000']
- **Top Features:**

#### Instance 1

- **True Label:** 8.0
- **Prediction:** 9.0
- **Prediction Probabilities:** ['0.037', '0.036', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.020', '0.906']
- **Top Features:**

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.005', '0.000', '0.000', '0.000', '0.001', '0.000', '0.000', '0.000', '0.994', '0.000']
- **Top Features:**

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 3.0 | 8.000 | NO | N/A | N/A |
| 1 | 8.0 | 9.000 | NO | N/A | N/A |
| 2 | 8.0 | 8.000 | YES | N/A | N/A |
| 3 | 0.0 | 8.000 | NO | N/A | N/A |
| 4 | 6.0 | 6.000 | YES | N/A | N/A |
| 5 | 6.0 | 2.000 | NO | N/A | N/A |
| 6 | 1.0 | 3.000 | NO | N/A | N/A |
| 7 | 6.0 | 4.000 | NO | N/A | N/A |
| 8 | 3.0 | 3.000 | YES | N/A | N/A |
| 9 | 1.0 | 9.000 | NO | N/A | N/A |
| 10 | 0.0 | 0.000 | YES | N/A | N/A |
| 11 | 9.0 | 9.000 | YES | N/A | N/A |
| 12 | 5.0 | 5.000 | YES | N/A | N/A |
| 13 | 7.0 | 7.000 | YES | N/A | N/A |
| 14 | 9.0 | 9.000 | YES | N/A | N/A |
| 15 | 8.0 | 8.000 | YES | N/A | N/A |
| 16 | 5.0 | 3.000 | NO | N/A | N/A |
| 17 | 7.0 | 7.000 | YES | N/A | N/A |
| 18 | 8.0 | 8.000 | YES | N/A | N/A |
| 19 | 6.0 | 6.000 | YES | N/A | N/A |
| 20 | 7.0 | 7.000 | YES | N/A | N/A |
| 21 | 0.0 | 2.000 | NO | N/A | N/A |
| 22 | 4.0 | 0.000 | NO | N/A | N/A |
| 23 | 9.0 | 9.000 | YES | N/A | N/A |
| 24 | 5.0 | 2.000 | NO | N/A | N/A |
| 25 | 2.0 | 3.000 | NO | N/A | N/A |
| 26 | 4.0 | 6.000 | NO | N/A | N/A |
| 27 | 0.0 | 7.000 | NO | N/A | N/A |
| 28 | 9.0 | 1.000 | NO | N/A | N/A |
| 29 | 6.0 | 4.000 | NO | N/A | N/A |
| 30 | 6.0 | 7.000 | NO | N/A | N/A |
| 31 | 5.0 | 4.000 | NO | N/A | N/A |
| 32 | 4.0 | 4.000 | YES | N/A | N/A |
| 33 | 5.0 | 3.000 | NO | N/A | N/A |
| 34 | 9.0 | 9.000 | YES | N/A | N/A |
| 35 | 2.0 | 6.000 | NO | N/A | N/A |
| 36 | 4.0 | 4.000 | YES | N/A | N/A |
| 37 | 1.0 | 9.000 | NO | N/A | N/A |
| 38 | 9.0 | 9.000 | YES | N/A | N/A |
| 39 | 5.0 | 3.000 | NO | N/A | N/A |
| 40 | 4.0 | 7.000 | NO | N/A | N/A |
| 41 | 6.0 | 6.000 | YES | N/A | N/A |
| 42 | 5.0 | 3.000 | NO | N/A | N/A |
| 43 | 6.0 | 4.000 | NO | N/A | N/A |
| 44 | 0.0 | 8.000 | NO | N/A | N/A |
| 45 | 9.0 | 9.000 | YES | N/A | N/A |
| 46 | 3.0 | 5.000 | NO | N/A | N/A |
| 47 | 9.0 | 3.000 | NO | N/A | N/A |
| 48 | 7.0 | 4.000 | NO | N/A | N/A |
| 49 | 6.0 | 4.000 | NO | N/A | N/A |

*Showing first 50 of 400 instances. See JSON file for complete data.*
