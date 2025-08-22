# Detailed Explanation Report

**Dataset:** diabetes  
**Model:** random_forest  
**Explanation Method:** feature_ablation  
**Generated:** 2025-08-22 14:24:20  

## Summary Statistics

- **Total Instances:** 89
- **Valid Explanations:** 89
- **Errors:** 0
- **Model Accuracy:** 0.5843

## Prediction Analysis

- **Correct Predictions:** 52 (58.4%)
- **Incorrect Predictions:** 37 (41.6%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 89 | 0.0787 | 100.0% |
| 1 | 89 | 0.0562 | 100.0% |
| 2 | 89 | 0.2022 | 100.0% |
| 3 | 89 | 0.0787 | 100.0% |
| 4 | 89 | 0.0674 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.285', '0.479', '0.235']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.213', '0.299', '0.488']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 1.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.967', '0.033', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.239', '0.568', '0.193']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.164', '0.353', '0.483']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 1.0000

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.164', '0.442', '0.394']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.958', '0.042', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.010', '0.255', '0.735']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 0 | 0 |
| 1 | 0.0 | 1.000 | NO | 0 | 1 |
| 2 | 1.0 | 0.000 | NO | 0 | 0 |
| 3 | 2.0 | 2.000 | YES | 0 | 0 |
| 4 | 0.0 | 0.000 | YES | 0 | 0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0 |
| 6 | 2.0 | 2.000 | YES | 0 | 0 |
| 7 | 1.0 | 2.000 | NO | 0 | 0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0 |
| 9 | 0.0 | 0.000 | YES | 0 | 0 |
| 10 | 1.0 | 0.000 | NO | 0 | 0 |
| 11 | 0.0 | 0.000 | YES | 0 | 0 |
| 12 | 0.0 | 1.000 | NO | 0 | 0 |
| 13 | 2.0 | 0.000 | NO | 0 | 0 |
| 14 | 1.0 | 1.000 | YES | 0 | 0 |
| 15 | 2.0 | 2.000 | YES | 0 | 0 |
| 16 | 0.0 | 1.000 | NO | 0 | 0 |
| 17 | 0.0 | 1.000 | NO | 0 | 0 |
| 18 | 0.0 | 0.000 | YES | 0 | 0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0 |
| 20 | 0.0 | 1.000 | NO | 0 | 0 |
| 21 | 0.0 | 0.000 | YES | 0 | 0 |
| 22 | 0.0 | 0.000 | YES | 0 | 0 |
| 23 | 0.0 | 0.000 | YES | 0 | 0 |
| 24 | 0.0 | 1.000 | NO | 0 | 1 |
| 25 | 2.0 | 1.000 | NO | 0 | 0 |
| 26 | 1.0 | 1.000 | YES | 0 | 0 |
| 27 | 1.0 | 2.000 | NO | 0 | 0 |
| 28 | 2.0 | 1.000 | NO | 0 | 0 |
| 29 | 1.0 | 0.000 | NO | 0 | 0 |
| 30 | 0.0 | 0.000 | YES | 0 | 1 |
| 31 | 2.0 | 2.000 | YES | 0 | 0 |
| 32 | 0.0 | 0.000 | YES | 0 | 0 |
| 33 | 1.0 | 0.000 | NO | 0 | 0 |
| 34 | 0.0 | 0.000 | YES | 0 | 0 |
| 35 | 1.0 | 0.000 | NO | 0 | 0 |
| 36 | 1.0 | 1.000 | YES | 0 | 0 |
| 37 | 0.0 | 0.000 | YES | 0 | 0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0 |
| 39 | 1.0 | 0.000 | NO | 0 | 0 |
| 40 | 0.0 | 0.000 | YES | 0 | 0 |
| 41 | 0.0 | 0.000 | YES | 0 | 0 |
| 42 | 1.0 | 1.000 | YES | 0 | 0 |
| 43 | 2.0 | 2.000 | YES | 0 | 0 |
| 44 | 0.0 | 0.000 | YES | 0 | 0 |
| 45 | 0.0 | 1.000 | NO | 0 | 0 |
| 46 | 2.0 | 2.000 | YES | 0 | 0 |
| 47 | 0.0 | 0.000 | YES | 0 | 0 |
| 48 | 0.0 | 0.000 | YES | 0 | 0 |
| 49 | 1.0 | 0.000 | NO | 0 | 0 |

*Showing first 50 of 89 instances. See JSON file for complete data.*
