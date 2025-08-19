# Detailed Explanation Report

**Dataset:** mnist  
**Model:** cnn  
**Explanation Method:** occlusion  
**Generated:** 2025-08-19 10:03:42  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.9800

## Prediction Analysis

- **Correct Predictions:** 196 (98.0%)
- **Incorrect Predictions:** 4 (2.0%)

## Feature Importance Analysis

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 7.0
- **Prediction:** 7.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '1.000', '0.000', '0.000']
- **Top Features:**

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.000', '1.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000']
- **Top Features:**

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000']
- **Top Features:**

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000', '0.000']
- **Top Features:**

#### Instance 4

- **True Label:** 4.0
- **Prediction:** 4.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.000', '0.000', '1.000', '0.000', '0.000', '0.000', '0.000', '0.000']
- **Top Features:**

### Incorrect Predictions (Sample)

#### Instance 18

- **True Label:** 3.0
- **Prediction:** 5.0
- **Prediction Probabilities:** ['0.001', '0.000', '0.000', '0.406', '0.001', '0.565', '0.000', '0.000', '0.002', '0.025']
- **Top Features:**

#### Instance 61

- **True Label:** 8.0
- **Prediction:** 5.0
- **Prediction Probabilities:** ['0.002', '0.000', '0.010', '0.057', '0.000', '0.906', '0.000', '0.000', '0.009', '0.016']
- **Top Features:**

#### Instance 149

- **True Label:** 2.0
- **Prediction:** 9.0
- **Prediction Probabilities:** ['0.000', '0.006', '0.119', '0.208', '0.138', '0.028', '0.000', '0.005', '0.001', '0.495']
- **Top Features:**

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 7.0 | 7.000 | YES | N/A | N/A |
| 1 | 2.0 | 2.000 | YES | N/A | N/A |
| 2 | 1.0 | 1.000 | YES | N/A | N/A |
| 3 | 0.0 | 0.000 | YES | N/A | N/A |
| 4 | 4.0 | 4.000 | YES | N/A | N/A |
| 5 | 1.0 | 1.000 | YES | N/A | N/A |
| 6 | 4.0 | 4.000 | YES | N/A | N/A |
| 7 | 9.0 | 9.000 | YES | N/A | N/A |
| 8 | 5.0 | 5.000 | YES | N/A | N/A |
| 9 | 9.0 | 9.000 | YES | N/A | N/A |
| 10 | 0.0 | 0.000 | YES | N/A | N/A |
| 11 | 6.0 | 6.000 | YES | N/A | N/A |
| 12 | 9.0 | 9.000 | YES | N/A | N/A |
| 13 | 0.0 | 0.000 | YES | N/A | N/A |
| 14 | 1.0 | 1.000 | YES | N/A | N/A |
| 15 | 5.0 | 5.000 | YES | N/A | N/A |
| 16 | 9.0 | 9.000 | YES | N/A | N/A |
| 17 | 7.0 | 7.000 | YES | N/A | N/A |
| 18 | 3.0 | 5.000 | NO | N/A | N/A |
| 19 | 4.0 | 4.000 | YES | N/A | N/A |
| 20 | 9.0 | 9.000 | YES | N/A | N/A |
| 21 | 6.0 | 6.000 | YES | N/A | N/A |
| 22 | 6.0 | 6.000 | YES | N/A | N/A |
| 23 | 5.0 | 5.000 | YES | N/A | N/A |
| 24 | 4.0 | 4.000 | YES | N/A | N/A |
| 25 | 0.0 | 0.000 | YES | N/A | N/A |
| 26 | 7.0 | 7.000 | YES | N/A | N/A |
| 27 | 4.0 | 4.000 | YES | N/A | N/A |
| 28 | 0.0 | 0.000 | YES | N/A | N/A |
| 29 | 1.0 | 1.000 | YES | N/A | N/A |
| 30 | 3.0 | 3.000 | YES | N/A | N/A |
| 31 | 1.0 | 1.000 | YES | N/A | N/A |
| 32 | 3.0 | 3.000 | YES | N/A | N/A |
| 33 | 4.0 | 4.000 | YES | N/A | N/A |
| 34 | 7.0 | 7.000 | YES | N/A | N/A |
| 35 | 2.0 | 2.000 | YES | N/A | N/A |
| 36 | 7.0 | 7.000 | YES | N/A | N/A |
| 37 | 1.0 | 1.000 | YES | N/A | N/A |
| 38 | 2.0 | 2.000 | YES | N/A | N/A |
| 39 | 1.0 | 1.000 | YES | N/A | N/A |
| 40 | 1.0 | 1.000 | YES | N/A | N/A |
| 41 | 7.0 | 7.000 | YES | N/A | N/A |
| 42 | 4.0 | 4.000 | YES | N/A | N/A |
| 43 | 2.0 | 2.000 | YES | N/A | N/A |
| 44 | 3.0 | 3.000 | YES | N/A | N/A |
| 45 | 5.0 | 5.000 | YES | N/A | N/A |
| 46 | 1.0 | 1.000 | YES | N/A | N/A |
| 47 | 2.0 | 2.000 | YES | N/A | N/A |
| 48 | 4.0 | 4.000 | YES | N/A | N/A |
| 49 | 4.0 | 4.000 | YES | N/A | N/A |

*Showing first 50 of 200 instances. See JSON file for complete data.*
