# Detailed Explanation Report

**Dataset:** wine_quality  
**Model:** gradient_boosting  
**Explanation Method:** shap_interactive  
**Generated:** 2025-08-22 14:17:58  

## Summary Statistics

- **Total Instances:** 320
- **Valid Explanations:** 320
- **Errors:** 0
- **Model Accuracy:** 0.7000

## Prediction Analysis

- **Correct Predictions:** 224 (70.0%)
- **Incorrect Predictions:** 96 (30.0%)

## Feature Importance Analysis

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.093', '0.535', '0.373']
- **Top Features:**

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.503', '0.470', '0.026']
- **Top Features:**

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.951', '0.041', '0.008']
- **Top Features:**

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.637', '0.345', '0.018']
- **Top Features:**

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.117', '0.581', '0.301']
- **Top Features:**

### Incorrect Predictions (Sample)

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.515', '0.434', '0.050']
- **Top Features:**

#### Instance 9

- **True Label:** 2.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.211', '0.638', '0.151']
- **Top Features:**

#### Instance 15

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.073', '0.180', '0.747']
- **Top Features:**

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | N/A | N/A |
| 1 | 0.0 | 0.000 | YES | N/A | N/A |
| 2 | 0.0 | 0.000 | YES | N/A | N/A |
| 3 | 0.0 | 0.000 | YES | N/A | N/A |
| 4 | 1.0 | 0.000 | NO | N/A | N/A |
| 5 | 1.0 | 1.000 | YES | N/A | N/A |
| 6 | 0.0 | 0.000 | YES | N/A | N/A |
| 7 | 0.0 | 0.000 | YES | N/A | N/A |
| 8 | 1.0 | 1.000 | YES | N/A | N/A |
| 9 | 2.0 | 1.000 | NO | N/A | N/A |
| 10 | 0.0 | 0.000 | YES | N/A | N/A |
| 11 | 1.0 | 1.000 | YES | N/A | N/A |
| 12 | 0.0 | 0.000 | YES | N/A | N/A |
| 13 | 0.0 | 0.000 | YES | N/A | N/A |
| 14 | 0.0 | 0.000 | YES | N/A | N/A |
| 15 | 1.0 | 2.000 | NO | N/A | N/A |
| 16 | 1.0 | 0.000 | NO | N/A | N/A |
| 17 | 0.0 | 1.000 | NO | N/A | N/A |
| 18 | 2.0 | 1.000 | NO | N/A | N/A |
| 19 | 0.0 | 0.000 | YES | N/A | N/A |
| 20 | 1.0 | 1.000 | YES | N/A | N/A |
| 21 | 1.0 | 1.000 | YES | N/A | N/A |
| 22 | 0.0 | 0.000 | YES | N/A | N/A |
| 23 | 1.0 | 0.000 | NO | N/A | N/A |
| 24 | 0.0 | 0.000 | YES | N/A | N/A |
| 25 | 1.0 | 1.000 | YES | N/A | N/A |
| 26 | 1.0 | 1.000 | YES | N/A | N/A |
| 27 | 0.0 | 0.000 | YES | N/A | N/A |
| 28 | 2.0 | 1.000 | NO | N/A | N/A |
| 29 | 0.0 | 0.000 | YES | N/A | N/A |
| 30 | 0.0 | 0.000 | YES | N/A | N/A |
| 31 | 0.0 | 0.000 | YES | N/A | N/A |
| 32 | 1.0 | 1.000 | YES | N/A | N/A |
| 33 | 1.0 | 1.000 | YES | N/A | N/A |
| 34 | 2.0 | 2.000 | YES | N/A | N/A |
| 35 | 0.0 | 0.000 | YES | N/A | N/A |
| 36 | 0.0 | 0.000 | YES | N/A | N/A |
| 37 | 1.0 | 1.000 | YES | N/A | N/A |
| 38 | 0.0 | 0.000 | YES | N/A | N/A |
| 39 | 0.0 | 0.000 | YES | N/A | N/A |
| 40 | 0.0 | 0.000 | YES | N/A | N/A |
| 41 | 0.0 | 1.000 | NO | N/A | N/A |
| 42 | 1.0 | 0.000 | NO | N/A | N/A |
| 43 | 1.0 | 1.000 | YES | N/A | N/A |
| 44 | 2.0 | 2.000 | YES | N/A | N/A |
| 45 | 2.0 | 1.000 | NO | N/A | N/A |
| 46 | 1.0 | 0.000 | NO | N/A | N/A |
| 47 | 1.0 | 1.000 | YES | N/A | N/A |
| 48 | 1.0 | 1.000 | YES | N/A | N/A |
| 49 | 2.0 | 2.000 | YES | N/A | N/A |

*Showing first 50 of 320 instances. See JSON file for complete data.*
