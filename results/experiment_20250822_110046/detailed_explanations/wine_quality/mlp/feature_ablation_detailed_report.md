# Detailed Explanation Report

**Dataset:** wine_quality  
**Model:** mlp  
**Explanation Method:** feature_ablation  
**Generated:** 2025-08-22 14:18:44  

## Summary Statistics

- **Total Instances:** 320
- **Valid Explanations:** 320
- **Errors:** 0
- **Model Accuracy:** 0.6906

## Prediction Analysis

- **Correct Predictions:** 221 (69.1%)
- **Incorrect Predictions:** 99 (30.9%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 320 | 0.1844 | 100.0% |
| 1 | 320 | 0.1750 | 100.0% |
| 2 | 320 | 0.1844 | 100.0% |
| 3 | 320 | 0.1062 | 100.0% |
| 4 | 320 | 0.0875 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '0.943', '0.056']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.891', '0.106', '0.003']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.715', '0.283', '0.002']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 1.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.230', '0.714', '0.056']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 1.0000

### Incorrect Predictions (Sample)

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.566', '0.122', '0.311']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 1.0000

#### Instance 15

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.017', '0.159', '0.824']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 1.0000
  - Feature 2: 0.0000

#### Instance 16

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.855', '0.137', '0.008']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 0 | 0 |
| 1 | 0.0 | 0.000 | YES | 0 | 0 |
| 2 | 0.0 | 0.000 | YES | 0 | 0 |
| 3 | 0.0 | 0.000 | YES | 0 | 0 |
| 4 | 1.0 | 1.000 | YES | 0 | 0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0 |
| 6 | 0.0 | 0.000 | YES | 0 | 0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0 |
| 8 | 1.0 | 0.000 | NO | 0 | 0 |
| 9 | 2.0 | 2.000 | YES | 0 | 1 |
| 10 | 0.0 | 0.000 | YES | 0 | 0 |
| 11 | 1.0 | 1.000 | YES | 0 | 0 |
| 12 | 0.0 | 0.000 | YES | 0 | 0 |
| 13 | 0.0 | 0.000 | YES | 0 | 0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0 |
| 15 | 1.0 | 2.000 | NO | 0 | 0 |
| 16 | 1.0 | 0.000 | NO | 0 | 0 |
| 17 | 0.0 | 1.000 | NO | 0 | 0 |
| 18 | 2.0 | 2.000 | YES | 0 | 0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0 |
| 20 | 1.0 | 1.000 | YES | 0 | 1 |
| 21 | 1.0 | 1.000 | YES | 0 | 0 |
| 22 | 0.0 | 0.000 | YES | 0 | 0 |
| 23 | 1.0 | 1.000 | YES | 0 | 0 |
| 24 | 0.0 | 0.000 | YES | 0 | 0 |
| 25 | 1.0 | 0.000 | NO | 0 | 1 |
| 26 | 1.0 | 1.000 | YES | 0 | 0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0 |
| 28 | 2.0 | 1.000 | NO | 0 | 0 |
| 29 | 0.0 | 0.000 | YES | 0 | 0 |
| 30 | 0.0 | 0.000 | YES | 0 | 0 |
| 31 | 0.0 | 1.000 | NO | 0 | 0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0 |
| 33 | 1.0 | 1.000 | YES | 0 | 0 |
| 34 | 2.0 | 2.000 | YES | 0 | 0 |
| 35 | 0.0 | 0.000 | YES | 0 | 0 |
| 36 | 0.0 | 0.000 | YES | 0 | 0 |
| 37 | 1.0 | 1.000 | YES | 0 | 1 |
| 38 | 0.0 | 0.000 | YES | 0 | 0 |
| 39 | 0.0 | 0.000 | YES | 0 | 0 |
| 40 | 0.0 | 1.000 | NO | 0 | 0 |
| 41 | 0.0 | 1.000 | NO | 0 | 0 |
| 42 | 1.0 | 0.000 | NO | 0 | 0 |
| 43 | 1.0 | 1.000 | YES | 0 | 1 |
| 44 | 2.0 | 2.000 | YES | 0 | 0 |
| 45 | 2.0 | 1.000 | NO | 0 | 0 |
| 46 | 1.0 | 0.000 | NO | 0 | 0 |
| 47 | 1.0 | 1.000 | YES | 0 | 0 |
| 48 | 1.0 | 1.000 | YES | 0 | 0 |
| 49 | 2.0 | 2.000 | YES | 0 | 0 |

*Showing first 50 of 320 instances. See JSON file for complete data.*
