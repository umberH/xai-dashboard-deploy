# Detailed Explanation Report

**Dataset:** diabetes  
**Model:** logistic_regression  
**Explanation Method:** shap_interactive  
**Generated:** 2025-08-22 14:25:40  

## Summary Statistics

- **Total Instances:** 89
- **Valid Explanations:** 89
- **Errors:** 0
- **Model Accuracy:** 0.6517

## Prediction Analysis

- **Correct Predictions:** 58 (65.2%)
- **Incorrect Predictions:** 31 (34.8%)

## Feature Importance Analysis

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.225', '0.617', '0.158']
- **Top Features:**

#### Instance 3

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.025', '0.257', '0.717']
- **Top Features:**

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.879', '0.119', '0.001']
- **Top Features:**

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.262', '0.466', '0.271']
- **Top Features:**

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.036', '0.306', '0.658']
- **Top Features:**

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.052', '0.388', '0.561']
- **Top Features:**

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.897', '0.102', '0.002']
- **Top Features:**

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.003', '0.073', '0.924']
- **Top Features:**

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | N/A | N/A |
| 1 | 0.0 | 2.000 | NO | N/A | N/A |
| 2 | 1.0 | 0.000 | NO | N/A | N/A |
| 3 | 2.0 | 2.000 | YES | N/A | N/A |
| 4 | 0.0 | 0.000 | YES | N/A | N/A |
| 5 | 1.0 | 1.000 | YES | N/A | N/A |
| 6 | 2.0 | 2.000 | YES | N/A | N/A |
| 7 | 1.0 | 2.000 | NO | N/A | N/A |
| 8 | 1.0 | 1.000 | YES | N/A | N/A |
| 9 | 0.0 | 0.000 | YES | N/A | N/A |
| 10 | 1.0 | 0.000 | NO | N/A | N/A |
| 11 | 0.0 | 0.000 | YES | N/A | N/A |
| 12 | 0.0 | 1.000 | NO | N/A | N/A |
| 13 | 2.0 | 1.000 | NO | N/A | N/A |
| 14 | 1.0 | 1.000 | YES | N/A | N/A |
| 15 | 2.0 | 2.000 | YES | N/A | N/A |
| 16 | 0.0 | 0.000 | YES | N/A | N/A |
| 17 | 0.0 | 1.000 | NO | N/A | N/A |
| 18 | 0.0 | 0.000 | YES | N/A | N/A |
| 19 | 0.0 | 0.000 | YES | N/A | N/A |
| 20 | 0.0 | 1.000 | NO | N/A | N/A |
| 21 | 0.0 | 0.000 | YES | N/A | N/A |
| 22 | 0.0 | 0.000 | YES | N/A | N/A |
| 23 | 0.0 | 0.000 | YES | N/A | N/A |
| 24 | 0.0 | 1.000 | NO | N/A | N/A |
| 25 | 2.0 | 1.000 | NO | N/A | N/A |
| 26 | 1.0 | 1.000 | YES | N/A | N/A |
| 27 | 1.0 | 2.000 | NO | N/A | N/A |
| 28 | 2.0 | 2.000 | YES | N/A | N/A |
| 29 | 1.0 | 0.000 | NO | N/A | N/A |
| 30 | 0.0 | 0.000 | YES | N/A | N/A |
| 31 | 2.0 | 1.000 | NO | N/A | N/A |
| 32 | 0.0 | 0.000 | YES | N/A | N/A |
| 33 | 1.0 | 0.000 | NO | N/A | N/A |
| 34 | 0.0 | 0.000 | YES | N/A | N/A |
| 35 | 1.0 | 0.000 | NO | N/A | N/A |
| 36 | 1.0 | 1.000 | YES | N/A | N/A |
| 37 | 0.0 | 1.000 | NO | N/A | N/A |
| 38 | 0.0 | 0.000 | YES | N/A | N/A |
| 39 | 1.0 | 1.000 | YES | N/A | N/A |
| 40 | 0.0 | 0.000 | YES | N/A | N/A |
| 41 | 0.0 | 0.000 | YES | N/A | N/A |
| 42 | 1.0 | 2.000 | NO | N/A | N/A |
| 43 | 2.0 | 2.000 | YES | N/A | N/A |
| 44 | 0.0 | 0.000 | YES | N/A | N/A |
| 45 | 0.0 | 1.000 | NO | N/A | N/A |
| 46 | 2.0 | 2.000 | YES | N/A | N/A |
| 47 | 0.0 | 0.000 | YES | N/A | N/A |
| 48 | 0.0 | 0.000 | YES | N/A | N/A |
| 49 | 1.0 | 1.000 | YES | N/A | N/A |

*Showing first 50 of 89 instances. See JSON file for complete data.*
