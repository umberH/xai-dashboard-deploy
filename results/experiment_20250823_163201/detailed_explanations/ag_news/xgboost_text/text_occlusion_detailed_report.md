# Detailed Explanation Report

**Dataset:** ag_news  
**Model:** xgboost_text  
**Explanation Method:** text_occlusion  
**Generated:** 2025-08-24 19:04:08  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7100

## Prediction Analysis

- **Correct Predictions:** 142 (71.0%)
- **Incorrect Predictions:** 58 (29.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 200 | 0.0450 | 100.0% |
| 1 | 200 | 0.0400 | 100.0% |
| 2 | 200 | 0.0450 | 100.0% |
| 3 | 200 | 0.0200 | 100.0% |
| 4 | 200 | 0.0400 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.178', '0.393', '0.211', '0.219']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.007', '0.971', '0.008', '0.014']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.657', '0.047', '0.166', '0.131']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.150', '0.654', '0.097', '0.098']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.193', '0.364', '0.248', '0.196']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.292', '0.094', '0.426', '0.189']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.014', '0.018', '0.041', '0.927']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.793', '0.120', '0.043', '0.045']
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
| 5 | 1.0 | 2.000 | NO | 0 | 0 |
| 6 | 2.0 | 3.000 | NO | 0 | 0 |
| 7 | 1.0 | 0.000 | NO | 0 | 0 |
| 8 | 0.0 | 3.000 | NO | 0 | 0 |
| 9 | 3.0 | 3.000 | YES | 0 | 0 |
| 10 | 3.0 | 3.000 | YES | 0 | 0 |
| 11 | 3.0 | 2.000 | NO | 0 | 0 |
| 12 | 1.0 | 1.000 | YES | 0 | 0 |
| 13 | 2.0 | 2.000 | YES | 0 | 0 |
| 14 | 3.0 | 2.000 | NO | 0 | 0 |
| 15 | 3.0 | 3.000 | YES | 0 | 0 |
| 16 | 2.0 | 2.000 | YES | 0 | 0 |
| 17 | 0.0 | 1.000 | NO | 0 | 0 |
| 18 | 1.0 | 1.000 | YES | 0 | 0 |
| 19 | 2.0 | 2.000 | YES | 0 | 0 |
| 20 | 1.0 | 1.000 | YES | 0 | 0 |
| 21 | 2.0 | 2.000 | YES | 0 | 0 |
| 22 | 2.0 | 2.000 | YES | 0 | 0 |
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
| 39 | 3.0 | 3.000 | YES | 0 | 3 |
| 40 | 2.0 | 3.000 | NO | 0 | 0 |
| 41 | 2.0 | 3.000 | NO | 0 | 1 |
| 42 | 2.0 | 2.000 | YES | 0 | 0 |
| 43 | 2.0 | 2.000 | YES | 0 | 0 |
| 44 | 2.0 | 2.000 | YES | 0 | 0 |
| 45 | 1.0 | 1.000 | YES | 0 | 0 |
| 46 | 2.0 | 0.000 | NO | 0 | 0 |
| 47 | 1.0 | 0.000 | NO | 0 | 0 |
| 48 | 1.0 | 1.000 | YES | 0 | 0 |
| 49 | 0.0 | 2.000 | NO | 0 | 0 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
