# Detailed Explanation Report

**Dataset:** digits  
**Model:** random_forest  
**Explanation Method:** shapley_flow  
**Generated:** 2025-08-22 15:43:19  

## Summary Statistics

- **Total Instances:** 360
- **Valid Explanations:** 360
- **Errors:** 0
- **Model Accuracy:** 0.9611

## Prediction Analysis

- **Correct Predictions:** 346 (96.1%)
- **Incorrect Predictions:** 14 (3.9%)

## Feature Importance Analysis

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 5.0
- **Prediction:** 5.0
- **Prediction Probabilities:** ['0.033', '0.010', '0.000', '0.031', '0.002', '0.529', '0.020', '0.010', '0.010', '0.355']
- **Top Features:**

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.030', '0.899', '0.021', '0.000', '0.020', '0.010', '0.010', '0.010', '0.000']
- **Top Features:**

#### Instance 2

- **True Label:** 8.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.030', '0.146', '0.036', '0.022', '0.067', '0.024', '0.043', '0.013', '0.556', '0.062']
- **Top Features:**

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '0.579', '0.054', '0.010', '0.043', '0.050', '0.111', '0.030', '0.114', '0.010']
- **Top Features:**

#### Instance 4

- **True Label:** 7.0
- **Prediction:** 7.0
- **Prediction Probabilities:** ['0.020', '0.020', '0.036', '0.090', '0.030', '0.050', '0.031', '0.616', '0.066', '0.040']
- **Top Features:**

### Incorrect Predictions (Sample)

#### Instance 36

- **True Label:** 6.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.095', '0.089', '0.044', '0.004', '0.175', '0.083', '0.111', '0.086', '0.283', '0.030']
- **Top Features:**

#### Instance 51

- **True Label:** 8.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.051', '0.547', '0.026', '0.001', '0.045', '0.029', '0.062', '0.023', '0.196', '0.021']
- **Top Features:**

#### Instance 59

- **True Label:** 2.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.330', '0.010', '0.280', '0.060', '0.030', '0.010', '0.020', '0.030', '0.090', '0.140']
- **Top Features:**

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 5.0 | 5.000 | YES | N/A | N/A |
| 1 | 2.0 | 2.000 | YES | N/A | N/A |
| 2 | 8.0 | 8.000 | YES | N/A | N/A |
| 3 | 1.0 | 1.000 | YES | N/A | N/A |
| 4 | 7.0 | 7.000 | YES | N/A | N/A |
| 5 | 2.0 | 2.000 | YES | N/A | N/A |
| 6 | 6.0 | 6.000 | YES | N/A | N/A |
| 7 | 2.0 | 2.000 | YES | N/A | N/A |
| 8 | 6.0 | 6.000 | YES | N/A | N/A |
| 9 | 5.0 | 5.000 | YES | N/A | N/A |
| 10 | 0.0 | 0.000 | YES | N/A | N/A |
| 11 | 5.0 | 5.000 | YES | N/A | N/A |
| 12 | 9.0 | 9.000 | YES | N/A | N/A |
| 13 | 3.0 | 3.000 | YES | N/A | N/A |
| 14 | 4.0 | 4.000 | YES | N/A | N/A |
| 15 | 4.0 | 4.000 | YES | N/A | N/A |
| 16 | 2.0 | 2.000 | YES | N/A | N/A |
| 17 | 4.0 | 4.000 | YES | N/A | N/A |
| 18 | 9.0 | 9.000 | YES | N/A | N/A |
| 19 | 9.0 | 9.000 | YES | N/A | N/A |
| 20 | 6.0 | 6.000 | YES | N/A | N/A |
| 21 | 3.0 | 3.000 | YES | N/A | N/A |
| 22 | 8.0 | 8.000 | YES | N/A | N/A |
| 23 | 1.0 | 1.000 | YES | N/A | N/A |
| 24 | 2.0 | 2.000 | YES | N/A | N/A |
| 25 | 5.0 | 5.000 | YES | N/A | N/A |
| 26 | 6.0 | 6.000 | YES | N/A | N/A |
| 27 | 0.0 | 0.000 | YES | N/A | N/A |
| 28 | 3.0 | 3.000 | YES | N/A | N/A |
| 29 | 4.0 | 4.000 | YES | N/A | N/A |
| 30 | 6.0 | 6.000 | YES | N/A | N/A |
| 31 | 7.0 | 7.000 | YES | N/A | N/A |
| 32 | 2.0 | 2.000 | YES | N/A | N/A |
| 33 | 6.0 | 6.000 | YES | N/A | N/A |
| 34 | 6.0 | 6.000 | YES | N/A | N/A |
| 35 | 6.0 | 6.000 | YES | N/A | N/A |
| 36 | 6.0 | 8.000 | NO | N/A | N/A |
| 37 | 5.0 | 5.000 | YES | N/A | N/A |
| 38 | 0.0 | 0.000 | YES | N/A | N/A |
| 39 | 9.0 | 9.000 | YES | N/A | N/A |
| 40 | 1.0 | 1.000 | YES | N/A | N/A |
| 41 | 7.0 | 7.000 | YES | N/A | N/A |
| 42 | 9.0 | 9.000 | YES | N/A | N/A |
| 43 | 6.0 | 6.000 | YES | N/A | N/A |
| 44 | 5.0 | 5.000 | YES | N/A | N/A |
| 45 | 7.0 | 7.000 | YES | N/A | N/A |
| 46 | 5.0 | 5.000 | YES | N/A | N/A |
| 47 | 2.0 | 2.000 | YES | N/A | N/A |
| 48 | 7.0 | 7.000 | YES | N/A | N/A |
| 49 | 5.0 | 5.000 | YES | N/A | N/A |

*Showing first 50 of 360 instances. See JSON file for complete data.*
