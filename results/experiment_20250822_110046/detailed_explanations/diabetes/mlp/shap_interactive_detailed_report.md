# Detailed Explanation Report

**Dataset:** diabetes  
**Model:** mlp  
**Explanation Method:** shap_interactive  
**Generated:** 2025-08-22 14:25:16  

## Summary Statistics

- **Total Instances:** 89
- **Valid Explanations:** 89
- **Errors:** 0
- **Model Accuracy:** 0.4494

## Prediction Analysis

- **Correct Predictions:** 40 (44.9%)
- **Incorrect Predictions:** 49 (55.1%)

## Feature Importance Analysis

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.226', '0.446', '0.328']
- **Top Features:**

#### Instance 3

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.004', '0.996']
- **Top Features:**

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.303', '0.046', '0.651']
- **Top Features:**

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.046', '0.866', '0.088']
- **Top Features:**

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.013', '0.038', '0.950']
- **Top Features:**

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.984', '0.016', '0.000']
- **Top Features:**

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.828', '0.106', '0.065']
- **Top Features:**

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | N/A | N/A |
| 1 | 0.0 | 2.000 | NO | N/A | N/A |
| 2 | 1.0 | 0.000 | NO | N/A | N/A |
| 3 | 2.0 | 2.000 | YES | N/A | N/A |
| 4 | 0.0 | 0.000 | YES | N/A | N/A |
| 5 | 1.0 | 0.000 | NO | N/A | N/A |
| 6 | 2.0 | 2.000 | YES | N/A | N/A |
| 7 | 1.0 | 2.000 | NO | N/A | N/A |
| 8 | 1.0 | 1.000 | YES | N/A | N/A |
| 9 | 0.0 | 0.000 | YES | N/A | N/A |
| 10 | 1.0 | 0.000 | NO | N/A | N/A |
| 11 | 0.0 | 0.000 | YES | N/A | N/A |
| 12 | 0.0 | 1.000 | NO | N/A | N/A |
| 13 | 2.0 | 1.000 | NO | N/A | N/A |
| 14 | 1.0 | 0.000 | NO | N/A | N/A |
| 15 | 2.0 | 2.000 | YES | N/A | N/A |
| 16 | 0.0 | 0.000 | YES | N/A | N/A |
| 17 | 0.0 | 1.000 | NO | N/A | N/A |
| 18 | 0.0 | 1.000 | NO | N/A | N/A |
| 19 | 0.0 | 0.000 | YES | N/A | N/A |
| 20 | 0.0 | 1.000 | NO | N/A | N/A |
| 21 | 0.0 | 1.000 | NO | N/A | N/A |
| 22 | 0.0 | 0.000 | YES | N/A | N/A |
| 23 | 0.0 | 0.000 | YES | N/A | N/A |
| 24 | 0.0 | 0.000 | YES | N/A | N/A |
| 25 | 2.0 | 1.000 | NO | N/A | N/A |
| 26 | 1.0 | 1.000 | YES | N/A | N/A |
| 27 | 1.0 | 2.000 | NO | N/A | N/A |
| 28 | 2.0 | 1.000 | NO | N/A | N/A |
| 29 | 1.0 | 0.000 | NO | N/A | N/A |
| 30 | 0.0 | 0.000 | YES | N/A | N/A |
| 31 | 2.0 | 2.000 | YES | N/A | N/A |
| 32 | 0.0 | 0.000 | YES | N/A | N/A |
| 33 | 1.0 | 0.000 | NO | N/A | N/A |
| 34 | 0.0 | 1.000 | NO | N/A | N/A |
| 35 | 1.0 | 0.000 | NO | N/A | N/A |
| 36 | 1.0 | 2.000 | NO | N/A | N/A |
| 37 | 0.0 | 1.000 | NO | N/A | N/A |
| 38 | 0.0 | 1.000 | NO | N/A | N/A |
| 39 | 1.0 | 0.000 | NO | N/A | N/A |
| 40 | 0.0 | 0.000 | YES | N/A | N/A |
| 41 | 0.0 | 0.000 | YES | N/A | N/A |
| 42 | 1.0 | 1.000 | YES | N/A | N/A |
| 43 | 2.0 | 2.000 | YES | N/A | N/A |
| 44 | 0.0 | 0.000 | YES | N/A | N/A |
| 45 | 0.0 | 1.000 | NO | N/A | N/A |
| 46 | 2.0 | 2.000 | YES | N/A | N/A |
| 47 | 0.0 | 1.000 | NO | N/A | N/A |
| 48 | 0.0 | 0.000 | YES | N/A | N/A |
| 49 | 1.0 | 0.000 | NO | N/A | N/A |

*Showing first 50 of 89 instances. See JSON file for complete data.*
