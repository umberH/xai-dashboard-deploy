# Detailed Explanation Report

**Dataset:** wine_quality  
**Model:** decision_tree  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:10:09  

## Summary Statistics

- **Total Instances:** 320
- **Valid Explanations:** 320
- **Errors:** 0
- **Model Accuracy:** 0.6406
- **Average Feature Importance:** 0.0384
- **Feature Importance Std:** 0.1793
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 205 (64.1%)
- **Incorrect Predictions:** 115 (35.9%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 313 | 0.0017 | 97.8% |
| 1 | 312 | 0.0855 | 97.5% |
| 2 | 303 | 0.0128 | 94.7% |
| 3 | 285 | 0.0036 | 89.1% |
| 4 | 244 | 0.0654 | 76.2% |
| 10 | 60 | 0.8368 | 18.8% |
| 6 | 35 | 0.6656 | 10.9% |
| 8 | 16 | 0.1178 | 5.0% |
| 9 | 16 | 0.5703 | 5.0% |
| 5 | 9 | 0.0729 | 2.8% |

## Sample Explanations

### Correct Predictions (Sample)

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
- **Prediction Probabilities:** ['0.562', '0.397', '0.041']
- **Top Features:**
  - Feature 1: 0.9000
  - Feature 0: 0.1000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.075', '0.925', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 6

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.562', '0.397', '0.041']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.125', '0.823', '0.052']
- **Top Features:**
  - Feature 4: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 4: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 1 | 0.0 | 1.000 | NO | 4 | 1.0 |
| 2 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 3 | 0.0 | 0.000 | YES | 1 | 0.9 |
| 4 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 0.000 | NO | 4 | 1.0 |
| 6 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 6 | 1.0 |
| 9 | 2.0 | 1.000 | NO | 10 | 1.0 |
| 10 | 0.0 | 0.000 | YES | 1 | 1.0 |
| 11 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 13 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 16 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 17 | 0.0 | 0.000 | YES | 1 | 1.0 |
| 18 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 1.0 | 0.000 | NO | 6 | 1.0 |
| 21 | 1.0 | 1.000 | YES | 10 | 0.6993409266211092 |
| 22 | 0.0 | 0.000 | YES | 10 | 1.0 |
| 23 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 24 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 25 | 1.0 | 1.000 | YES | 9 | 1.0 |
| 26 | 1.0 | 1.000 | YES | 10 | 1.0 |
| 27 | 0.0 | 2.000 | NO | 2 | 1.0 |
| 28 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 29 | 0.0 | 0.000 | YES | 8 | 0.5714285714285714 |
| 30 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 31 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 32 | 1.0 | 1.000 | YES | 1 | 1.0 |
| 33 | 1.0 | 1.000 | YES | 4 | 1.0 |
| 34 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 35 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 36 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 37 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 40 | 0.0 | 1.000 | NO | 1 | 1.0 |
| 41 | 0.0 | 2.000 | NO | 10 | 0.9029487224654779 |
| 42 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 43 | 1.0 | 1.000 | YES | 10 | 1.0 |
| 44 | 2.0 | 2.000 | YES | 6 | 0.7397706583665387 |
| 45 | 2.0 | 0.000 | NO | 10 | 1.0 |
| 46 | 1.0 | 0.000 | NO | 1 | 1.0 |
| 47 | 1.0 | 0.000 | NO | 10 | 0.9885714285714287 |
| 48 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 49 | 2.0 | 1.000 | NO | 0 | 0.0 |

*Showing first 50 of 320 instances. See JSON file for complete data.*
