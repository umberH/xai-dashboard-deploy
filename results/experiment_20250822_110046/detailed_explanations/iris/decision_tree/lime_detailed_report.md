# Detailed Explanation Report

**Dataset:** iris  
**Model:** decision_tree  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:07:45  

## Summary Statistics

- **Total Instances:** 30
- **Valid Explanations:** 30
- **Errors:** 0
- **Model Accuracy:** 0.9333
- **Average Feature Importance:** 0.0750
- **Feature Importance Std:** 0.2414
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 28 (93.3%)
- **Incorrect Predictions:** 2 (6.7%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 30 | 0.0493 | 100.0% |
| 1 | 30 | 0.0032 | 100.0% |
| 2 | 30 | 0.2341 | 100.0% |
| 3 | 30 | 0.0134 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.000', '1.000']
- **Top Features:**
  - Feature 2: 0.9544
  - Feature 3: 0.0456
  - Feature 0: 0.0000

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 23

- **True Label:** 2.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000', '0.000']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 25

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.000', '1.000']
- **Top Features:**
  - Feature 2: 0.9661
  - Feature 0: 0.0258
  - Feature 3: 0.0081

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 1 | 2.0 | 2.000 | YES | 2 | 0.9544294258144863 |
| 2 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 3 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 2 | 0.674819145712391 |
| 6 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 2.0 | 2.000 | YES | 2 | 1.0 |
| 9 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 10 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 11 | 2.0 | 2.000 | YES | 2 | 1.0 |
| 12 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 13 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 16 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 17 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 18 | 1.0 | 1.000 | YES | 2 | 0.4703882033814027 |
| 19 | 2.0 | 2.000 | YES | 2 | 0.9584125478004014 |
| 20 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 21 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 22 | 1.0 | 1.000 | YES | 2 | 1.0 |
| 23 | 2.0 | 1.000 | NO | 0 | 1.0 |
| 24 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 25 | 1.0 | 2.000 | NO | 2 | 0.9661319851272474 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 28 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 29 | 0.0 | 0.000 | YES | 0 | 0.0 |
