# Detailed Explanation Report

**Dataset:** 20newsgroups  
**Model:** roberta  
**Explanation Method:** text_occlusion  
**Generated:** 2025-08-24 13:14:39  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8400
- **Average Feature Importance:** 0.5000
- **Feature Importance Std:** 0.0000
- **Max Feature Importance:** 0.5000

## Prediction Analysis

- **Correct Predictions:** 168 (84.0%)
- **Incorrect Predictions:** 32 (16.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 200 | 0.1025 | 100.0% |
| 1 | 195 | 0.1026 | 97.5% |
| 2 | 194 | 0.0928 | 97.0% |
| 3 | 194 | 0.0825 | 97.0% |
| 4 | 193 | 0.1036 | 96.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.002', '0.001', '0.995', '0.002']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.001', '0.001', '0.996', '0.002']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.003', '0.004', '0.990', '0.003']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.984', '0.004', '0.007', '0.005']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.017', '0.001', '0.003', '0.979']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 8

- **True Label:** 2.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.106', '0.820', '0.037', '0.037']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 9

- **True Label:** 2.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.196', '0.355', '0.242', '0.207']
- **Top Features:**
  - Feature 0: 0.5000

#### Instance 12

- **True Label:** 2.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.599', '0.015', '0.257', '0.129']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 2.0 | 2.000 | YES | 0 | 0 |
| 1 | 2.0 | 2.000 | YES | 0 | 0 |
| 2 | 2.0 | 2.000 | YES | 0 | 0 |
| 3 | 0.0 | 0.000 | YES | 0 | 0 |
| 4 | 3.0 | 3.000 | YES | 0 | 0 |
| 5 | 0.0 | 0.000 | YES | 0 | 0 |
| 6 | 1.0 | 1.000 | YES | 0 | 0 |
| 7 | 3.0 | 3.000 | YES | 0 | 0 |
| 8 | 2.0 | 1.000 | NO | 0 | 0 |
| 9 | 2.0 | 1.000 | NO | 0 | 0.5 |
| 10 | 1.0 | 1.000 | YES | 0 | 0 |
| 11 | 3.0 | 3.000 | YES | 0 | 0 |
| 12 | 2.0 | 0.000 | NO | 0 | 0 |
| 13 | 3.0 | 3.000 | YES | 0 | 0 |
| 14 | 1.0 | 0.000 | NO | 0 | 0 |
| 15 | 0.0 | 2.000 | NO | 0 | 0 |
| 16 | 1.0 | 1.000 | YES | 0 | 0 |
| 17 | 3.0 | 3.000 | YES | 0 | 0 |
| 18 | 0.0 | 2.000 | NO | 0 | 0 |
| 19 | 0.0 | 3.000 | NO | 0 | 0 |
| 20 | 2.0 | 2.000 | YES | 0 | 0 |
| 21 | 3.0 | 3.000 | YES | 0 | 0 |
| 22 | 1.0 | 1.000 | YES | 0 | 0 |
| 23 | 0.0 | 3.000 | NO | 0 | 0 |
| 24 | 2.0 | 2.000 | YES | 0 | 0 |
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
| 35 | 0.0 | 0.000 | YES | 0 | 0 |
| 36 | 2.0 | 2.000 | YES | 0 | 0 |
| 37 | 0.0 | 0.000 | YES | 0 | 0 |
| 38 | 2.0 | 2.000 | YES | 0 | 0 |
| 39 | 1.0 | 1.000 | YES | 0 | 0 |
| 40 | 2.0 | 2.000 | YES | 0 | 0 |
| 41 | 0.0 | 3.000 | NO | 0 | 0 |
| 42 | 2.0 | 2.000 | YES | 0 | 0 |
| 43 | 3.0 | 3.000 | YES | 0 | 0 |
| 44 | 2.0 | 2.000 | YES | 0 | 0 |
| 45 | 2.0 | 2.000 | YES | 0 | 0 |
| 46 | 3.0 | 3.000 | YES | 0 | 0 |
| 47 | 1.0 | 1.000 | YES | 0 | 0 |
| 48 | 3.0 | 1.000 | NO | 0 | 0 |
| 49 | 1.0 | 1.000 | YES | 0 | 0 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
