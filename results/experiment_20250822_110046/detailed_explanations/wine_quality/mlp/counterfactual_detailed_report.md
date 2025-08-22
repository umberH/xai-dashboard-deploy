# Detailed Explanation Report

**Dataset:** wine_quality  
**Model:** mlp  
**Explanation Method:** counterfactual  
**Generated:** 2025-08-22 14:18:35  

## Summary Statistics

- **Total Instances:** 320
- **Valid Explanations:** 320
- **Errors:** 0
- **Model Accuracy:** 0.6906

## Prediction Analysis

- **Correct Predictions:** 221 (69.1%)
- **Incorrect Predictions:** 99 (30.9%)

## Feature Importance Analysis

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '0.943', '0.056']
- **Top Features:**

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.891', '0.106', '0.003']
- **Top Features:**

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.715', '0.283', '0.002']
- **Top Features:**

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.230', '0.714', '0.056']
- **Top Features:**

### Incorrect Predictions (Sample)

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.566', '0.122', '0.311']
- **Top Features:**

#### Instance 15

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.017', '0.159', '0.824']
- **Top Features:**

#### Instance 16

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.855', '0.137', '0.008']
- **Top Features:**

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | N/A | N/A |
| 1 | 0.0 | 0.000 | YES | N/A | N/A |
| 2 | 0.0 | 0.000 | YES | N/A | N/A |
| 3 | 0.0 | 0.000 | YES | N/A | N/A |
| 4 | 1.0 | 1.000 | YES | N/A | N/A |
| 5 | 1.0 | 1.000 | YES | N/A | N/A |
| 6 | 0.0 | 0.000 | YES | N/A | N/A |
| 7 | 0.0 | 0.000 | YES | N/A | N/A |
| 8 | 1.0 | 0.000 | NO | N/A | N/A |
| 9 | 2.0 | 2.000 | YES | N/A | N/A |
| 10 | 0.0 | 0.000 | YES | N/A | N/A |
| 11 | 1.0 | 1.000 | YES | N/A | N/A |
| 12 | 0.0 | 0.000 | YES | N/A | N/A |
| 13 | 0.0 | 0.000 | YES | N/A | N/A |
| 14 | 0.0 | 0.000 | YES | N/A | N/A |
| 15 | 1.0 | 2.000 | NO | N/A | N/A |
| 16 | 1.0 | 0.000 | NO | N/A | N/A |
| 17 | 0.0 | 1.000 | NO | N/A | N/A |
| 18 | 2.0 | 2.000 | YES | N/A | N/A |
| 19 | 0.0 | 0.000 | YES | N/A | N/A |
| 20 | 1.0 | 1.000 | YES | N/A | N/A |
| 21 | 1.0 | 1.000 | YES | N/A | N/A |
| 22 | 0.0 | 0.000 | YES | N/A | N/A |
| 23 | 1.0 | 1.000 | YES | N/A | N/A |
| 24 | 0.0 | 0.000 | YES | N/A | N/A |
| 25 | 1.0 | 0.000 | NO | N/A | N/A |
| 26 | 1.0 | 1.000 | YES | N/A | N/A |
| 27 | 0.0 | 0.000 | YES | N/A | N/A |
| 28 | 2.0 | 1.000 | NO | N/A | N/A |
| 29 | 0.0 | 0.000 | YES | N/A | N/A |
| 30 | 0.0 | 0.000 | YES | N/A | N/A |
| 31 | 0.0 | 1.000 | NO | N/A | N/A |
| 32 | 1.0 | 1.000 | YES | N/A | N/A |
| 33 | 1.0 | 1.000 | YES | N/A | N/A |
| 34 | 2.0 | 2.000 | YES | N/A | N/A |
| 35 | 0.0 | 0.000 | YES | N/A | N/A |
| 36 | 0.0 | 0.000 | YES | N/A | N/A |
| 37 | 1.0 | 1.000 | YES | N/A | N/A |
| 38 | 0.0 | 0.000 | YES | N/A | N/A |
| 39 | 0.0 | 0.000 | YES | N/A | N/A |
| 40 | 0.0 | 1.000 | NO | N/A | N/A |
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
