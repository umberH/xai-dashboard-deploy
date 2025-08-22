# Detailed Explanation Report

**Dataset:** compas  
**Model:** random_forest  
**Explanation Method:** feature_ablation  
**Generated:** 2025-08-22 13:31:42  

## Summary Statistics

- **Total Instances:** 1443
- **Valid Explanations:** 1443
- **Errors:** 0
- **Model Accuracy:** 0.6826

## Prediction Analysis

- **Correct Predictions:** 985 (68.3%)
- **Incorrect Predictions:** 458 (31.7%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 1443 | 0.2661 | 100.0% |
| 1 | 1443 | 0.3368 | 100.0% |
| 2 | 1443 | 0.3174 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.733', '0.267']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.422', '0.578']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 0.0000
  - Feature 2: 1.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.352', '0.648']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.271', '0.729']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 6

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.885', '0.115']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.628', '0.372']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.478', '0.522']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 8

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.466', '0.534']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 0.0000
  - Feature 2: 1.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 0.000 | NO | 0 | 0 |
| 1 | 0.0 | 0.000 | YES | 0 | 0 |
| 2 | 1.0 | 1.000 | YES | 0 | 1 |
| 3 | 1.0 | 1.000 | YES | 0 | 1 |
| 4 | 1.0 | 1.000 | YES | 0 | 0 |
| 5 | 0.0 | 1.000 | NO | 0 | 1 |
| 6 | 0.0 | 0.000 | YES | 0 | 0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0 |
| 8 | 0.0 | 1.000 | NO | 0 | 1 |
| 9 | 1.0 | 1.000 | YES | 0 | 1 |
| 10 | 1.0 | 0.000 | NO | 0 | 0 |
| 11 | 0.0 | 1.000 | NO | 0 | 0 |
| 12 | 0.0 | 1.000 | NO | 0 | 0 |
| 13 | 1.0 | 0.000 | NO | 0 | 0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0 |
| 15 | 0.0 | 1.000 | NO | 0 | 1 |
| 16 | 0.0 | 1.000 | NO | 0 | 0 |
| 17 | 0.0 | 0.000 | YES | 0 | 0 |
| 18 | 0.0 | 0.000 | YES | 0 | 0 |
| 19 | 0.0 | 1.000 | NO | 0 | 1 |
| 20 | 0.0 | 1.000 | NO | 0 | 0 |
| 21 | 1.0 | 1.000 | YES | 0 | 1 |
| 22 | 0.0 | 1.000 | NO | 0 | 1 |
| 23 | 1.0 | 1.000 | YES | 0 | 1 |
| 24 | 1.0 | 1.000 | YES | 0 | 1 |
| 25 | 0.0 | 0.000 | YES | 0 | 0 |
| 26 | 1.0 | 0.000 | NO | 0 | 1 |
| 27 | 0.0 | 0.000 | YES | 0 | 0 |
| 28 | 0.0 | 1.000 | NO | 0 | 0 |
| 29 | 1.0 | 1.000 | YES | 0 | 1 |
| 30 | 1.0 | 1.000 | YES | 0 | 0 |
| 31 | 0.0 | 0.000 | YES | 0 | 0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0 |
| 33 | 1.0 | 1.000 | YES | 0 | 0 |
| 34 | 1.0 | 0.000 | NO | 0 | 0 |
| 35 | 0.0 | 1.000 | NO | 0 | 1 |
| 36 | 0.0 | 1.000 | NO | 0 | 1 |
| 37 | 0.0 | 0.000 | YES | 0 | 0 |
| 38 | 1.0 | 0.000 | NO | 0 | 0 |
| 39 | 1.0 | 1.000 | YES | 0 | 1 |
| 40 | 0.0 | 1.000 | NO | 0 | 1 |
| 41 | 0.0 | 0.000 | YES | 0 | 0 |
| 42 | 1.0 | 0.000 | NO | 0 | 0 |
| 43 | 0.0 | 0.000 | YES | 0 | 0 |
| 44 | 0.0 | 0.000 | YES | 0 | 0 |
| 45 | 0.0 | 0.000 | YES | 0 | 0 |
| 46 | 0.0 | 0.000 | YES | 0 | 0 |
| 47 | 0.0 | 1.000 | NO | 0 | 0 |
| 48 | 1.0 | 0.000 | NO | 0 | 0 |
| 49 | 0.0 | 1.000 | NO | 0 | 1 |

*Showing first 50 of 1443 instances. See JSON file for complete data.*
