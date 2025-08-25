# Detailed Explanation Report

**Dataset:** imdb  
**Model:** xgboost_text  
**Explanation Method:** text_occlusion  
**Generated:** 2025-08-24 05:13:21  

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
| 0 | 200 | 0.1950 | 100.0% |
| 1 | 200 | 0.1950 | 100.0% |
| 2 | 200 | 0.1950 | 100.0% |
| 3 | 200 | 0.2050 | 100.0% |
| 4 | 200 | 0.1900 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.849', '0.151']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.284', '0.716']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.256', '0.744']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.123', '0.877']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.131', '0.869']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.276', '0.724']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.783', '0.217']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 1.0000
  - Feature 2: 1.0000

#### Instance 11

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.438', '0.562']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 1.0000
  - Feature 2: 1.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0 |
| 1 | 1.0 | 1.000 | YES | 0 | 0 |
| 2 | 1.0 | 1.000 | YES | 0 | 0 |
| 3 | 1.0 | 1.000 | YES | 0 | 0 |
| 4 | 1.0 | 1.000 | YES | 0 | 0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0 |
| 6 | 1.0 | 1.000 | YES | 0 | 0 |
| 7 | 0.0 | 1.000 | NO | 0 | 0 |
| 8 | 1.0 | 0.000 | NO | 0 | 1 |
| 9 | 1.0 | 1.000 | YES | 0 | 0 |
| 10 | 0.0 | 0.000 | YES | 0 | 1 |
| 11 | 0.0 | 1.000 | NO | 0 | 1 |
| 12 | 1.0 | 1.000 | YES | 0 | 0 |
| 13 | 1.0 | 1.000 | YES | 0 | 0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0 |
| 15 | 0.0 | 0.000 | YES | 0 | 0 |
| 16 | 1.0 | 0.000 | NO | 0 | 0 |
| 17 | 0.0 | 1.000 | NO | 0 | 0 |
| 18 | 1.0 | 1.000 | YES | 0 | 1 |
| 19 | 0.0 | 1.000 | NO | 0 | 0 |
| 20 | 1.0 | 1.000 | YES | 0 | 0 |
| 21 | 0.0 | 0.000 | YES | 0 | 0 |
| 22 | 1.0 | 1.000 | YES | 0 | 0 |
| 23 | 1.0 | 1.000 | YES | 0 | 0 |
| 24 | 0.0 | 0.000 | YES | 0 | 0 |
| 25 | 1.0 | 1.000 | YES | 0 | 0 |
| 26 | 1.0 | 1.000 | YES | 0 | 0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0 |
| 28 | 0.0 | 1.000 | NO | 0 | 0 |
| 29 | 1.0 | 0.000 | NO | 0 | 0 |
| 30 | 0.0 | 1.000 | NO | 0 | 0 |
| 31 | 0.0 | 0.000 | YES | 0 | 0 |
| 32 | 0.0 | 0.000 | YES | 0 | 0 |
| 33 | 0.0 | 1.000 | NO | 0 | 0 |
| 34 | 0.0 | 0.000 | YES | 0 | 1 |
| 35 | 0.0 | 0.000 | YES | 0 | 0 |
| 36 | 1.0 | 0.000 | NO | 0 | 1 |
| 37 | 1.0 | 1.000 | YES | 0 | 0 |
| 38 | 1.0 | 1.000 | YES | 0 | 0 |
| 39 | 0.0 | 0.000 | YES | 0 | 1 |
| 40 | 0.0 | 0.000 | YES | 0 | 0 |
| 41 | 0.0 | 1.000 | NO | 0 | 0 |
| 42 | 1.0 | 1.000 | YES | 0 | 1 |
| 43 | 1.0 | 1.000 | YES | 0 | 0 |
| 44 | 0.0 | 0.000 | YES | 0 | 0 |
| 45 | 0.0 | 1.000 | NO | 0 | 0 |
| 46 | 1.0 | 1.000 | YES | 0 | 0 |
| 47 | 1.0 | 1.000 | YES | 0 | 0 |
| 48 | 1.0 | 1.000 | YES | 0 | 0 |
| 49 | 0.0 | 0.000 | YES | 0 | 1 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
