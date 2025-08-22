# Detailed Explanation Report

**Dataset:** heart_disease  
**Model:** gradient_boosting  
**Explanation Method:** feature_ablation  
**Generated:** 2025-08-22 14:01:20  

## Summary Statistics

- **Total Instances:** 60
- **Valid Explanations:** 60
- **Errors:** 0
- **Model Accuracy:** 0.7000

## Prediction Analysis

- **Correct Predictions:** 42 (70.0%)
- **Incorrect Predictions:** 18 (30.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 60 | 0.0667 | 100.0% |
| 1 | 60 | 0.0833 | 100.0% |
| 2 | 60 | 0.2333 | 100.0% |
| 3 | 60 | 0.1833 | 100.0% |
| 4 | 60 | 0.0833 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.916', '0.084']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.689', '0.311']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.817', '0.183']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.736', '0.264']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 1.0000

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.968', '0.032']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.350', '0.650']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 9

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.292', '0.708']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 1.0000
  - Feature 2: 0.0000

#### Instance 10

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.802', '0.198']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 1.0000
  - Feature 2: 1.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0 |
| 1 | 0.0 | 0.000 | YES | 0 | 0 |
| 2 | 0.0 | 0.000 | YES | 0 | 0 |
| 3 | 0.0 | 1.000 | NO | 0 | 1 |
| 4 | 0.0 | 0.000 | YES | 0 | 0 |
| 5 | 0.0 | 0.000 | YES | 0 | 0 |
| 6 | 1.0 | 1.000 | YES | 0 | 0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0 |
| 9 | 0.0 | 1.000 | NO | 0 | 0 |
| 10 | 1.0 | 0.000 | NO | 0 | 0 |
| 11 | 0.0 | 0.000 | YES | 0 | 0 |
| 12 | 0.0 | 1.000 | NO | 0 | 1 |
| 13 | 1.0 | 0.000 | NO | 0 | 0 |
| 14 | 1.0 | 1.000 | YES | 0 | 0 |
| 15 | 1.0 | 1.000 | YES | 0 | 0 |
| 16 | 1.0 | 1.000 | YES | 0 | 0 |
| 17 | 0.0 | 1.000 | NO | 0 | 0 |
| 18 | 1.0 | 1.000 | YES | 0 | 0 |
| 19 | 1.0 | 1.000 | YES | 0 | 0 |
| 20 | 0.0 | 0.000 | YES | 0 | 0 |
| 21 | 0.0 | 0.000 | YES | 0 | 0 |
| 22 | 1.0 | 1.000 | YES | 0 | 0 |
| 23 | 0.0 | 0.000 | YES | 0 | 0 |
| 24 | 1.0 | 1.000 | YES | 0 | 0 |
| 25 | 0.0 | 0.000 | YES | 0 | 0 |
| 26 | 0.0 | 0.000 | YES | 0 | 1 |
| 27 | 1.0 | 1.000 | YES | 0 | 0 |
| 28 | 0.0 | 1.000 | NO | 0 | 0 |
| 29 | 1.0 | 1.000 | YES | 0 | 0 |
| 30 | 0.0 | 0.000 | YES | 0 | 0 |
| 31 | 1.0 | 0.000 | NO | 0 | 0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0 |
| 33 | 0.0 | 0.000 | YES | 0 | 0 |
| 34 | 0.0 | 0.000 | YES | 0 | 0 |
| 35 | 1.0 | 1.000 | YES | 0 | 0 |
| 36 | 0.0 | 0.000 | YES | 0 | 0 |
| 37 | 1.0 | 0.000 | NO | 0 | 0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0 |
| 39 | 1.0 | 1.000 | YES | 0 | 0 |
| 40 | 0.0 | 1.000 | NO | 0 | 0 |
| 41 | 1.0 | 1.000 | YES | 0 | 0 |
| 42 | 1.0 | 1.000 | YES | 0 | 0 |
| 43 | 1.0 | 0.000 | NO | 0 | 0 |
| 44 | 0.0 | 1.000 | NO | 0 | 0 |
| 45 | 0.0 | 0.000 | YES | 0 | 0 |
| 46 | 1.0 | 1.000 | YES | 0 | 0 |
| 47 | 0.0 | 1.000 | NO | 0 | 1 |
| 48 | 1.0 | 0.000 | NO | 0 | 0 |
| 49 | 0.0 | 1.000 | NO | 0 | 0 |

*Showing first 50 of 60 instances. See JSON file for complete data.*
