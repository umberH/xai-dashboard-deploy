# Detailed Explanation Report

**Dataset:** wine_classification  
**Model:** mlp  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:31:48  

## Summary Statistics

- **Total Instances:** 36
- **Valid Explanations:** 36
- **Errors:** 0
- **Model Accuracy:** 1.0000
- **Average Feature Importance:** 0.0128
- **Feature Importance Std:** 0.0808
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 36 (100.0%)
- **Incorrect Predictions:** 0 (0.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 36 | 0.0052 | 100.0% |
| 3 | 36 | 0.0509 | 100.0% |
| 0 | 35 | 0.0385 | 97.2% |
| 2 | 34 | 0.0359 | 94.4% |
| 4 | 32 | 0.0000 | 88.9% |
| 7 | 3 | 0.3290 | 8.3% |
| 5 | 2 | 0.1546 | 5.6% |
| 6 | 1 | 0.0302 | 2.8% |
| 12 | 1 | 0.0638 | 2.8% |

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
- **Prediction Probabilities:** ['0.011', '0.425', '0.563']
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

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.026', '0.973', '0.001']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.007', '0.992', '0.001']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 1 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 2 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 3 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 4 | 1.0 | 1.000 | YES | 0 | 1.0 |
| 5 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 6 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 7 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 2 | 0.8508058990908349 |
| 9 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 1.000 | YES | 3 | 0.41704876428764087 |
| 11 | 2.0 | 2.000 | YES | 3 | 0.48139161439034606 |
| 12 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 13 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 1.0 | 1.000 | YES | 7 | 0.4326551501090524 |
| 16 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 17 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 18 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 21 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 22 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 23 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 24 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 25 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 26 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 27 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 28 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 29 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 30 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 31 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 33 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 34 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 35 | 2.0 | 2.000 | YES | 3 | 0.41518199260033867 |
