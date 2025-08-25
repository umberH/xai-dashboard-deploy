# Detailed Explanation Report

**Dataset:** 20newsgroups  
**Model:** bert  
**Explanation Method:** text_occlusion  
**Generated:** 2025-08-24 05:20:23  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7150
- **Average Feature Importance:** 0.5000
- **Feature Importance Std:** 0.0000
- **Max Feature Importance:** 0.5000

## Prediction Analysis

- **Correct Predictions:** 143 (71.5%)
- **Incorrect Predictions:** 57 (28.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 200 | 0.2025 | 100.0% |
| 1 | 195 | 0.2359 | 97.5% |
| 2 | 194 | 0.1753 | 97.0% |
| 3 | 194 | 0.1959 | 97.0% |
| 4 | 193 | 0.1969 | 96.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.193', '0.173', '0.460', '0.174']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.657', '0.120', '0.119', '0.104']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.076', '0.050', '0.073', '0.801']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.430', '0.106', '0.139', '0.325']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 7

- **True Label:** 3.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.131', '0.074', '0.104', '0.691']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.412', '0.170', '0.355', '0.063']
- **Top Features:**
  - Feature 0: 2.0000
  - Feature 1: 2.0000
  - Feature 2: 2.0000

#### Instance 2

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.108', '0.152', '0.348', '0.391']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 1.0000

#### Instance 6

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.149', '0.311', '0.314', '0.226']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 1.0000
  - Feature 2: 1.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 2.0 | 2.000 | YES | 0 | 0 |
| 1 | 2.0 | 0.000 | NO | 0 | 2 |
| 2 | 2.0 | 3.000 | NO | 0 | 0 |
| 3 | 0.0 | 0.000 | YES | 0 | 0 |
| 4 | 3.0 | 3.000 | YES | 0 | 0 |
| 5 | 0.0 | 0.000 | YES | 0 | 0 |
| 6 | 1.0 | 2.000 | NO | 0 | 0 |
| 7 | 3.0 | 3.000 | YES | 0 | 0 |
| 8 | 2.0 | 1.000 | NO | 0 | 0 |
| 9 | 2.0 | 1.000 | NO | 0 | 0.5 |
| 10 | 1.0 | 1.000 | YES | 0 | 0 |
| 11 | 3.0 | 3.000 | YES | 0 | 1 |
| 12 | 2.0 | 3.000 | NO | 0 | 0 |
| 13 | 3.0 | 3.000 | YES | 0 | 0 |
| 14 | 1.0 | 2.000 | NO | 0 | 2 |
| 15 | 0.0 | 2.000 | NO | 0 | 0 |
| 16 | 1.0 | 1.000 | YES | 0 | 0 |
| 17 | 3.0 | 3.000 | YES | 0 | 0 |
| 18 | 0.0 | 1.000 | NO | 0 | 0 |
| 19 | 0.0 | 3.000 | NO | 0 | 0 |
| 20 | 2.0 | 2.000 | YES | 0 | 2 |
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
| 35 | 0.0 | 3.000 | NO | 0 | 3 |
| 36 | 2.0 | 1.000 | NO | 0 | 0 |
| 37 | 0.0 | 3.000 | NO | 0 | 0 |
| 38 | 2.0 | 0.000 | NO | 0 | 0 |
| 39 | 1.0 | 1.000 | YES | 0 | 0 |
| 40 | 2.0 | 2.000 | YES | 0 | 0 |
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
