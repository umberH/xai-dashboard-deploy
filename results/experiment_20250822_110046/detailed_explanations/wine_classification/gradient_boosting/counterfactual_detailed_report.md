# Detailed Explanation Report

**Dataset:** wine_classification  
**Model:** gradient_boosting  
**Explanation Method:** counterfactual  
**Generated:** 2025-08-22 14:31:45  

## Summary Statistics

- **Total Instances:** 36
- **Valid Explanations:** 36
- **Errors:** 0
- **Model Accuracy:** 0.9444

## Prediction Analysis

- **Correct Predictions:** 34 (94.4%)
- **Incorrect Predictions:** 2 (5.6%)

## Feature Importance Analysis

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.009', '0.991']
- **Top Features:**

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000', '0.000']
- **Top Features:**

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**

### Incorrect Predictions (Sample)

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**

#### Instance 13

- **True Label:** 2.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '0.999', '0.000']
- **Top Features:**

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | N/A | N/A |
| 1 | 2.0 | 2.000 | YES | N/A | N/A |
| 2 | 0.0 | 0.000 | YES | N/A | N/A |
| 3 | 1.0 | 0.000 | NO | N/A | N/A |
| 4 | 1.0 | 1.000 | YES | N/A | N/A |
| 5 | 0.0 | 0.000 | YES | N/A | N/A |
| 6 | 0.0 | 0.000 | YES | N/A | N/A |
| 7 | 1.0 | 1.000 | YES | N/A | N/A |
| 8 | 1.0 | 1.000 | YES | N/A | N/A |
| 9 | 2.0 | 2.000 | YES | N/A | N/A |
| 10 | 1.0 | 1.000 | YES | N/A | N/A |
| 11 | 2.0 | 2.000 | YES | N/A | N/A |
| 12 | 0.0 | 0.000 | YES | N/A | N/A |
| 13 | 2.0 | 1.000 | NO | N/A | N/A |
| 14 | 0.0 | 0.000 | YES | N/A | N/A |
| 15 | 1.0 | 1.000 | YES | N/A | N/A |
| 16 | 1.0 | 1.000 | YES | N/A | N/A |
| 17 | 0.0 | 0.000 | YES | N/A | N/A |
| 18 | 1.0 | 1.000 | YES | N/A | N/A |
| 19 | 0.0 | 0.000 | YES | N/A | N/A |
| 20 | 1.0 | 1.000 | YES | N/A | N/A |
| 21 | 1.0 | 1.000 | YES | N/A | N/A |
| 22 | 0.0 | 0.000 | YES | N/A | N/A |
| 23 | 0.0 | 0.000 | YES | N/A | N/A |
| 24 | 1.0 | 1.000 | YES | N/A | N/A |
| 25 | 1.0 | 1.000 | YES | N/A | N/A |
| 26 | 0.0 | 0.000 | YES | N/A | N/A |
| 27 | 2.0 | 2.000 | YES | N/A | N/A |
| 28 | 1.0 | 1.000 | YES | N/A | N/A |
| 29 | 2.0 | 2.000 | YES | N/A | N/A |
| 30 | 0.0 | 0.000 | YES | N/A | N/A |
| 31 | 2.0 | 2.000 | YES | N/A | N/A |
| 32 | 1.0 | 1.000 | YES | N/A | N/A |
| 33 | 2.0 | 2.000 | YES | N/A | N/A |
| 34 | 2.0 | 2.000 | YES | N/A | N/A |
| 35 | 2.0 | 2.000 | YES | N/A | N/A |
