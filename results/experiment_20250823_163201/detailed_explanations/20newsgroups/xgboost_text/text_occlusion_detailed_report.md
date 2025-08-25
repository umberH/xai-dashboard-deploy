# Detailed Explanation Report

**Dataset:** 20newsgroups  
**Model:** xgboost_text  
**Explanation Method:** text_occlusion  
**Generated:** 2025-08-24 15:41:36  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7050
- **Average Feature Importance:** 1.5000
- **Feature Importance Std:** 0.0000
- **Max Feature Importance:** 1.5000

## Prediction Analysis

- **Correct Predictions:** 141 (70.5%)
- **Incorrect Predictions:** 59 (29.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 200 | 0.2025 | 100.0% |
| 1 | 195 | 0.2256 | 97.5% |
| 2 | 194 | 0.1856 | 97.0% |
| 3 | 194 | 0.1856 | 97.0% |
| 4 | 193 | 0.1865 | 96.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.293', '0.219', '0.371', '0.117']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.059', '0.065', '0.850', '0.026']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.679', '0.119', '0.132', '0.069']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.004', '0.002', '0.002', '0.992']
- **Top Features:**
  - Feature 0: 3.0000
  - Feature 1: 3.0000
  - Feature 2: 3.0000

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.465', '0.169', '0.205', '0.161']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.193', '0.215', '0.288', '0.304']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 1.0000

#### Instance 14

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.396', '0.207', '0.276', '0.120']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 15

- **True Label:** 0.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.140', '0.365', '0.424', '0.071']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 1.0000
  - Feature 2: 1.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 2.0 | 2.000 | YES | 0 | 0 |
| 1 | 2.0 | 2.000 | YES | 0 | 0 |
| 2 | 2.0 | 3.000 | NO | 0 | 0 |
| 3 | 0.0 | 0.000 | YES | 0 | 0 |
| 4 | 3.0 | 3.000 | YES | 0 | 3 |
| 5 | 0.0 | 0.000 | YES | 0 | 0 |
| 6 | 1.0 | 1.000 | YES | 0 | 0 |
| 7 | 3.0 | 3.000 | YES | 0 | 0 |
| 8 | 2.0 | 2.000 | YES | 0 | 0 |
| 9 | 2.0 | 2.000 | YES | 0 | 1.5 |
| 10 | 1.0 | 1.000 | YES | 0 | 0 |
| 11 | 3.0 | 3.000 | YES | 0 | 2 |
| 12 | 2.0 | 2.000 | YES | 0 | 0 |
| 13 | 3.0 | 3.000 | YES | 0 | 0 |
| 14 | 1.0 | 0.000 | NO | 0 | 0 |
| 15 | 0.0 | 2.000 | NO | 0 | 1 |
| 16 | 1.0 | 1.000 | YES | 0 | 0 |
| 17 | 3.0 | 3.000 | YES | 0 | 0 |
| 18 | 0.0 | 1.000 | NO | 0 | 0 |
| 19 | 0.0 | 3.000 | NO | 0 | 0 |
| 20 | 2.0 | 2.000 | YES | 0 | 2 |
| 21 | 3.0 | 3.000 | YES | 0 | 0 |
| 22 | 1.0 | 1.000 | YES | 0 | 0 |
| 23 | 0.0 | 0.000 | YES | 0 | 0 |
| 24 | 2.0 | 2.000 | YES | 0 | 0 |
| 25 | 1.0 | 1.000 | YES | 0 | 0 |
| 26 | 1.0 | 0.000 | NO | 0 | 0 |
| 27 | 3.0 | 3.000 | YES | 0 | 0 |
| 28 | 2.0 | 0.000 | NO | 0 | 2 |
| 29 | 0.0 | 0.000 | YES | 0 | 0 |
| 30 | 1.0 | 1.000 | YES | 0 | 0 |
| 31 | 3.0 | 3.000 | YES | 0 | 0 |
| 32 | 0.0 | 3.000 | NO | 0 | 0 |
| 33 | 2.0 | 1.000 | NO | 0 | 0 |
| 34 | 2.0 | 2.000 | YES | 0 | 0 |
| 35 | 0.0 | 0.000 | YES | 0 | 0 |
| 36 | 2.0 | 2.000 | YES | 0 | 0 |
| 37 | 0.0 | 3.000 | NO | 0 | 0 |
| 38 | 2.0 | 0.000 | NO | 0 | 0 |
| 39 | 1.0 | 1.000 | YES | 0 | 0 |
| 40 | 2.0 | 1.000 | NO | 0 | 1 |
| 41 | 0.0 | 3.000 | NO | 0 | 0 |
| 42 | 2.0 | 2.000 | YES | 0 | 0 |
| 43 | 3.0 | 3.000 | YES | 0 | 0 |
| 44 | 2.0 | 1.000 | NO | 0 | 1 |
| 45 | 2.0 | 2.000 | YES | 0 | 0 |
| 46 | 3.0 | 3.000 | YES | 0 | 0 |
| 47 | 1.0 | 1.000 | YES | 0 | 0 |
| 48 | 3.0 | 2.000 | NO | 0 | 0 |
| 49 | 1.0 | 1.000 | YES | 0 | 0 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
