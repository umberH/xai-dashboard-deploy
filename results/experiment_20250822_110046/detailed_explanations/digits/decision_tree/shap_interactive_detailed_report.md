# Detailed Explanation Report

**Dataset:** digits  
**Model:** decision_tree  
**Explanation Method:** shap_interactive  
**Generated:** 2025-08-22 14:33:46  

## Summary Statistics

- **Total Instances:** 360
- **Valid Explanations:** 360
- **Errors:** 0
- **Model Accuracy:** 0.8083

## Prediction Analysis

- **Correct Predictions:** 291 (80.8%)
- **Incorrect Predictions:** 69 (19.2%)

## Feature Importance Analysis

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 5.0
- **Prediction:** 5.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '0.000', '0.000', '1.000', '0.000', '0.000', '0.000', '0.000']
- **Top Features:**

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.000', '1.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000']
- **Top Features:**

#### Instance 2

- **True Label:** 8.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.010', '0.020', '0.000', '0.000', '0.000', '0.000', '0.949', '0.020']
- **Top Features:**

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000']
- **Top Features:**

#### Instance 4

- **True Label:** 7.0
- **Prediction:** 7.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '1.000', '0.000', '0.000']
- **Top Features:**

### Incorrect Predictions (Sample)

#### Instance 7

- **True Label:** 2.0
- **Prediction:** 5.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '0.000', '0.000', '1.000', '0.000', '0.000', '0.000', '0.000']
- **Top Features:**

#### Instance 14

- **True Label:** 4.0
- **Prediction:** 8.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '1.000', '0.000']
- **Top Features:**

#### Instance 18

- **True Label:** 9.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '1.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000']
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
| 7 | 2.0 | 5.000 | NO | N/A | N/A |
| 8 | 6.0 | 6.000 | YES | N/A | N/A |
| 9 | 5.0 | 5.000 | YES | N/A | N/A |
| 10 | 0.0 | 0.000 | YES | N/A | N/A |
| 11 | 5.0 | 5.000 | YES | N/A | N/A |
| 12 | 9.0 | 9.000 | YES | N/A | N/A |
| 13 | 3.0 | 3.000 | YES | N/A | N/A |
| 14 | 4.0 | 8.000 | NO | N/A | N/A |
| 15 | 4.0 | 4.000 | YES | N/A | N/A |
| 16 | 2.0 | 2.000 | YES | N/A | N/A |
| 17 | 4.0 | 4.000 | YES | N/A | N/A |
| 18 | 9.0 | 3.000 | NO | N/A | N/A |
| 19 | 9.0 | 9.000 | YES | N/A | N/A |
| 20 | 6.0 | 6.000 | YES | N/A | N/A |
| 21 | 3.0 | 3.000 | YES | N/A | N/A |
| 22 | 8.0 | 8.000 | YES | N/A | N/A |
| 23 | 1.0 | 8.000 | NO | N/A | N/A |
| 24 | 2.0 | 2.000 | YES | N/A | N/A |
| 25 | 5.0 | 5.000 | YES | N/A | N/A |
| 26 | 6.0 | 6.000 | YES | N/A | N/A |
| 27 | 0.0 | 0.000 | YES | N/A | N/A |
| 28 | 3.0 | 9.000 | NO | N/A | N/A |
| 29 | 4.0 | 4.000 | YES | N/A | N/A |
| 30 | 6.0 | 6.000 | YES | N/A | N/A |
| 31 | 7.0 | 7.000 | YES | N/A | N/A |
| 32 | 2.0 | 2.000 | YES | N/A | N/A |
| 33 | 6.0 | 6.000 | YES | N/A | N/A |
| 34 | 6.0 | 6.000 | YES | N/A | N/A |
| 35 | 6.0 | 5.000 | NO | N/A | N/A |
| 36 | 6.0 | 1.000 | NO | N/A | N/A |
| 37 | 5.0 | 5.000 | YES | N/A | N/A |
| 38 | 0.0 | 0.000 | YES | N/A | N/A |
| 39 | 9.0 | 3.000 | NO | N/A | N/A |
| 40 | 1.0 | 1.000 | YES | N/A | N/A |
| 41 | 7.0 | 7.000 | YES | N/A | N/A |
| 42 | 9.0 | 8.000 | NO | N/A | N/A |
| 43 | 6.0 | 6.000 | YES | N/A | N/A |
| 44 | 5.0 | 5.000 | YES | N/A | N/A |
| 45 | 7.0 | 9.000 | NO | N/A | N/A |
| 46 | 5.0 | 5.000 | YES | N/A | N/A |
| 47 | 2.0 | 2.000 | YES | N/A | N/A |
| 48 | 7.0 | 7.000 | YES | N/A | N/A |
| 49 | 5.0 | 5.000 | YES | N/A | N/A |

*Showing first 50 of 360 instances. See JSON file for complete data.*
