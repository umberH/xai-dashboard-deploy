# Detailed Explanation Report

**Dataset:** wine_quality  
**Model:** random_forest  
**Explanation Method:** feature_ablation  
**Generated:** 2025-08-22 14:17:07  

## Summary Statistics

- **Total Instances:** 320
- **Valid Explanations:** 320
- **Errors:** 0
- **Model Accuracy:** 0.7063

## Prediction Analysis

- **Correct Predictions:** 226 (70.6%)
- **Incorrect Predictions:** 94 (29.4%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 320 | 0.0312 | 100.0% |
| 1 | 320 | 0.1688 | 100.0% |
| 2 | 320 | 0.0906 | 100.0% |
| 3 | 320 | 0.0563 | 100.0% |
| 4 | 320 | 0.0563 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.140', '0.462', '0.399']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 1.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.822', '0.168', '0.010']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.545', '0.441', '0.013']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 1.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.424', '0.537', '0.039']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.123', '0.511', '0.366']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.411', '0.556', '0.033']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 9

- **True Label:** 2.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.115', '0.476', '0.409']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 15

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.130', '0.293', '0.577']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 1.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 0 | 0 |
| 1 | 0.0 | 1.000 | NO | 0 | 0 |
| 2 | 0.0 | 0.000 | YES | 0 | 0 |
| 3 | 0.0 | 0.000 | YES | 0 | 0 |
| 4 | 1.0 | 1.000 | YES | 0 | 0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0 |
| 6 | 0.0 | 0.000 | YES | 0 | 0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0 |
| 9 | 2.0 | 1.000 | NO | 0 | 0 |
| 10 | 0.0 | 0.000 | YES | 0 | 0 |
| 11 | 1.0 | 1.000 | YES | 0 | 0 |
| 12 | 0.0 | 0.000 | YES | 0 | 0 |
| 13 | 0.0 | 0.000 | YES | 0 | 0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0 |
| 15 | 1.0 | 2.000 | NO | 0 | 0 |
| 16 | 1.0 | 0.000 | NO | 0 | 0 |
| 17 | 0.0 | 0.000 | YES | 0 | 0 |
| 18 | 2.0 | 1.000 | NO | 0 | 0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0 |
| 20 | 1.0 | 1.000 | YES | 0 | 0 |
| 21 | 1.0 | 1.000 | YES | 0 | 0 |
| 22 | 0.0 | 0.000 | YES | 0 | 0 |
| 23 | 1.0 | 0.000 | NO | 0 | 0 |
| 24 | 0.0 | 0.000 | YES | 0 | 0 |
| 25 | 1.0 | 0.000 | NO | 0 | 0 |
| 26 | 1.0 | 1.000 | YES | 0 | 0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0 |
| 28 | 2.0 | 1.000 | NO | 0 | 0 |
| 29 | 0.0 | 0.000 | YES | 0 | 0 |
| 30 | 0.0 | 0.000 | YES | 0 | 0 |
| 31 | 0.0 | 0.000 | YES | 0 | 0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0 |
| 33 | 1.0 | 1.000 | YES | 0 | 0 |
| 34 | 2.0 | 2.000 | YES | 0 | 0 |
| 35 | 0.0 | 0.000 | YES | 0 | 0 |
| 36 | 0.0 | 0.000 | YES | 0 | 0 |
| 37 | 1.0 | 1.000 | YES | 0 | 0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0 |
| 39 | 0.0 | 0.000 | YES | 0 | 0 |
| 40 | 0.0 | 0.000 | YES | 0 | 1 |
| 41 | 0.0 | 1.000 | NO | 0 | 0 |
| 42 | 1.0 | 0.000 | NO | 0 | 0 |
| 43 | 1.0 | 1.000 | YES | 0 | 0 |
| 44 | 2.0 | 2.000 | YES | 0 | 0 |
| 45 | 2.0 | 1.000 | NO | 0 | 0 |
| 46 | 1.0 | 0.000 | NO | 0 | 0 |
| 47 | 1.0 | 1.000 | YES | 0 | 0 |
| 48 | 1.0 | 1.000 | YES | 0 | 0 |
| 49 | 2.0 | 2.000 | YES | 0 | 0 |

*Showing first 50 of 320 instances. See JSON file for complete data.*
