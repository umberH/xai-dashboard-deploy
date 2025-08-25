# Detailed Explanation Report

**Dataset:** 20newsgroups  
**Model:** lstm  
**Explanation Method:** text_occlusion  
**Generated:** 2025-08-24 05:21:42  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7100
- **Average Feature Importance:** 1.5000
- **Feature Importance Std:** 0.0000
- **Max Feature Importance:** 1.5000

## Prediction Analysis

- **Correct Predictions:** 142 (71.0%)
- **Incorrect Predictions:** 58 (29.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 200 | 0.1625 | 100.0% |
| 1 | 195 | 0.1385 | 97.5% |
| 2 | 194 | 0.1598 | 97.0% |
| 3 | 194 | 0.1546 | 97.0% |
| 4 | 193 | 0.1192 | 96.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.156', '0.104', '0.562', '0.178']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.599', '0.110', '0.108', '0.182']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.051', '0.016', '0.020', '0.913']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 6

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.151', '0.359', '0.241', '0.249']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 7

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.115', '0.031', '0.057', '0.797']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.417', '0.118', '0.345', '0.120']
- **Top Features:**
  - Feature 0: 2.0000
  - Feature 1: 2.0000
  - Feature 2: 2.0000

#### Instance 2

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.117', '0.114', '0.305', '0.464']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.389', '0.038', '0.082', '0.491']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 2.0 | 2.000 | YES | 0 | 0 |
| 1 | 2.0 | 0.000 | NO | 0 | 2 |
| 2 | 2.0 | 3.000 | NO | 0 | 0 |
| 3 | 0.0 | 0.000 | YES | 0 | 0 |
| 4 | 3.0 | 3.000 | YES | 0 | 0 |
| 5 | 0.0 | 3.000 | NO | 0 | 0 |
| 6 | 1.0 | 1.000 | YES | 0 | 0 |
| 7 | 3.0 | 3.000 | YES | 0 | 0 |
| 8 | 2.0 | 2.000 | YES | 0 | 0 |
| 9 | 2.0 | 2.000 | YES | 0 | 1.5 |
| 10 | 1.0 | 1.000 | YES | 0 | 0 |
| 11 | 3.0 | 3.000 | YES | 0 | 0 |
| 12 | 2.0 | 3.000 | NO | 0 | 0 |
| 13 | 3.0 | 3.000 | YES | 0 | 0 |
| 14 | 1.0 | 1.000 | YES | 0 | 0 |
| 15 | 0.0 | 2.000 | NO | 0 | 0 |
| 16 | 1.0 | 1.000 | YES | 0 | 0 |
| 17 | 3.0 | 3.000 | YES | 0 | 0 |
| 18 | 0.0 | 3.000 | NO | 0 | 2 |
| 19 | 0.0 | 3.000 | NO | 0 | 0 |
| 20 | 2.0 | 2.000 | YES | 0 | 1 |
| 21 | 3.0 | 3.000 | YES | 0 | 0 |
| 22 | 1.0 | 1.000 | YES | 0 | 0 |
| 23 | 0.0 | 3.000 | NO | 0 | 0 |
| 24 | 2.0 | 3.000 | NO | 0 | 0 |
| 25 | 1.0 | 1.000 | YES | 0 | 0 |
| 26 | 1.0 | 1.000 | YES | 0 | 0 |
| 27 | 3.0 | 3.000 | YES | 0 | 0 |
| 28 | 2.0 | 2.000 | YES | 0 | 0 |
| 29 | 0.0 | 0.000 | YES | 0 | 0 |
| 30 | 1.0 | 1.000 | YES | 0 | 0 |
| 31 | 3.0 | 3.000 | YES | 0 | 0 |
| 32 | 0.0 | 3.000 | NO | 0 | 0 |
| 33 | 2.0 | 2.000 | YES | 0 | 0 |
| 34 | 2.0 | 2.000 | YES | 0 | 0 |
| 35 | 0.0 | 3.000 | NO | 0 | 3 |
| 36 | 2.0 | 2.000 | YES | 0 | 0 |
| 37 | 0.0 | 3.000 | NO | 0 | 0 |
| 38 | 2.0 | 3.000 | NO | 0 | 0 |
| 39 | 1.0 | 1.000 | YES | 0 | 0 |
| 40 | 2.0 | 1.000 | NO | 0 | 1 |
| 41 | 0.0 | 0.000 | YES | 0 | 0 |
| 42 | 2.0 | 2.000 | YES | 0 | 0 |
| 43 | 3.0 | 3.000 | YES | 0 | 0 |
| 44 | 2.0 | 3.000 | NO | 0 | 0 |
| 45 | 2.0 | 2.000 | YES | 0 | 0 |
| 46 | 3.0 | 3.000 | YES | 0 | 0 |
| 47 | 1.0 | 1.000 | YES | 0 | 0 |
| 48 | 3.0 | 1.000 | NO | 0 | 0 |
| 49 | 1.0 | 1.000 | YES | 0 | 0 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
