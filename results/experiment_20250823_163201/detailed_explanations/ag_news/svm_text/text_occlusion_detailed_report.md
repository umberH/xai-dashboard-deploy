# Detailed Explanation Report

**Dataset:** ag_news  
**Model:** svm_text  
**Explanation Method:** text_occlusion  
**Generated:** 2025-08-24 19:02:28  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7900

## Prediction Analysis

- **Correct Predictions:** 158 (79.0%)
- **Incorrect Predictions:** 42 (21.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 200 | 0.0050 | 100.0% |
| 1 | 200 | 0.0250 | 100.0% |
| 2 | 200 | 0.0350 | 100.0% |
| 3 | 200 | 0.0350 | 100.0% |
| 4 | 200 | 0.0250 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.062', '0.677', '0.089', '0.172']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.937', '0.009', '0.045', '0.010']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.025', '0.972', '0.001', '0.001']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.059', '0.841', '0.068', '0.031']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.000', '0.000', '0.005', '0.995']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.766', '0.106', '0.079', '0.049']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 22

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.064', '0.036', '0.200', '0.701']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 0 | 0 |
| 1 | 1.0 | 1.000 | YES | 0 | 0 |
| 2 | 0.0 | 0.000 | YES | 0 | 0 |
| 3 | 1.0 | 1.000 | YES | 0 | 0 |
| 4 | 1.0 | 1.000 | YES | 0 | 0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0 |
| 6 | 2.0 | 3.000 | NO | 0 | 0 |
| 7 | 1.0 | 0.000 | NO | 0 | 0 |
| 8 | 0.0 | 0.000 | YES | 0 | 0 |
| 9 | 3.0 | 3.000 | YES | 0 | 0 |
| 10 | 3.0 | 3.000 | YES | 0 | 0 |
| 11 | 3.0 | 3.000 | YES | 0 | 0 |
| 12 | 1.0 | 1.000 | YES | 0 | 0 |
| 13 | 2.0 | 2.000 | YES | 0 | 0 |
| 14 | 3.0 | 3.000 | YES | 0 | 0 |
| 15 | 3.0 | 3.000 | YES | 0 | 0 |
| 16 | 2.0 | 2.000 | YES | 0 | 0 |
| 17 | 0.0 | 0.000 | YES | 0 | 0 |
| 18 | 1.0 | 1.000 | YES | 0 | 0 |
| 19 | 2.0 | 2.000 | YES | 0 | 0 |
| 20 | 1.0 | 1.000 | YES | 0 | 0 |
| 21 | 2.0 | 2.000 | YES | 0 | 0 |
| 22 | 2.0 | 3.000 | NO | 0 | 0 |
| 23 | 3.0 | 3.000 | YES | 0 | 0 |
| 24 | 0.0 | 0.000 | YES | 0 | 0 |
| 25 | 2.0 | 3.000 | NO | 0 | 0 |
| 26 | 0.0 | 0.000 | YES | 0 | 0 |
| 27 | 2.0 | 2.000 | YES | 0 | 0 |
| 28 | 3.0 | 3.000 | YES | 0 | 0 |
| 29 | 2.0 | 2.000 | YES | 0 | 0 |
| 30 | 3.0 | 3.000 | YES | 0 | 0 |
| 31 | 0.0 | 0.000 | YES | 0 | 0 |
| 32 | 2.0 | 3.000 | NO | 0 | 0 |
| 33 | 3.0 | 3.000 | YES | 0 | 0 |
| 34 | 0.0 | 1.000 | NO | 0 | 0 |
| 35 | 1.0 | 1.000 | YES | 0 | 0 |
| 36 | 3.0 | 3.000 | YES | 0 | 0 |
| 37 | 2.0 | 2.000 | YES | 0 | 0 |
| 38 | 3.0 | 3.000 | YES | 0 | 0 |
| 39 | 3.0 | 0.000 | NO | 0 | 0 |
| 40 | 2.0 | 2.000 | YES | 0 | 0 |
| 41 | 2.0 | 2.000 | YES | 0 | 0 |
| 42 | 2.0 | 2.000 | YES | 0 | 0 |
| 43 | 2.0 | 2.000 | YES | 0 | 0 |
| 44 | 2.0 | 2.000 | YES | 0 | 0 |
| 45 | 1.0 | 1.000 | YES | 0 | 0 |
| 46 | 2.0 | 2.000 | YES | 0 | 0 |
| 47 | 1.0 | 1.000 | YES | 0 | 0 |
| 48 | 1.0 | 1.000 | YES | 0 | 0 |
| 49 | 0.0 | 0.000 | YES | 0 | 0 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
