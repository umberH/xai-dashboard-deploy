# Detailed Explanation Report

**Dataset:** imdb  
**Model:** xgboost_text  
**Explanation Method:** lime  
**Generated:** 2025-08-24 05:12:53  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.7900
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0422
- **Max Feature Importance:** 0.9974

## Prediction Analysis

- **Correct Predictions:** 158 (79.0%)
- **Incorrect Predictions:** 42 (21.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 154 | 0.0399 | 77.0% |
| 3 | 149 | 0.0479 | 74.5% |
| 2 | 148 | 0.0396 | 74.0% |
| 0 | 147 | 0.0415 | 73.5% |
| 4 | 146 | 0.0440 | 73.0% |
| 16 | 12 | 0.2314 | 6.0% |
| 11 | 11 | 0.0563 | 5.5% |
| 39 | 10 | 0.2745 | 5.0% |
| 28 | 10 | 0.0610 | 5.0% |
| 43 | 9 | 0.0749 | 4.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.849', '0.151']
- **Top Features:**
  - Feature 39: 0.2153
  - Feature 35: 0.0601
  - Feature 1: 0.0469

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.284', '0.716']
- **Top Features:**
  - Feature 0: 0.0392
  - Feature 1: 0.0384
  - Feature 2: 0.0376

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.256', '0.744']
- **Top Features:**
  - Feature 0: 0.0392
  - Feature 1: 0.0384
  - Feature 2: 0.0376

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.123', '0.877']
- **Top Features:**
  - Feature 0: 0.0392
  - Feature 1: 0.0384
  - Feature 2: 0.0376

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.131', '0.869']
- **Top Features:**
  - Feature 0: 0.0444
  - Feature 1: 0.0434
  - Feature 2: 0.0424

### Incorrect Predictions (Sample)

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.276', '0.724']
- **Top Features:**
  - Feature 0: 0.0392
  - Feature 1: 0.0384
  - Feature 2: 0.0376

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.783', '0.217']
- **Top Features:**
  - Feature 0: 0.0392
  - Feature 1: 0.0384
  - Feature 2: 0.0376

#### Instance 11

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.438', '0.562']
- **Top Features:**
  - Feature 0: 0.0392
  - Feature 1: 0.0384
  - Feature 2: 0.0376

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 39 | 0.21533644623982626 |
| 1 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 2 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 3 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 4 | 1.0 | 1.000 | YES | 0 | 0.044444444444444446 |
| 5 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 7 | 0.0 | 1.000 | NO | 0 | 0.0392156862745098 |
| 8 | 1.0 | 0.000 | NO | 0 | 0.0392156862745098 |
| 9 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 10 | 0.0 | 0.000 | YES | 0 | 0.06788151610333884 |
| 11 | 0.0 | 1.000 | NO | 0 | 0.0392156862745098 |
| 12 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 13 | 1.0 | 1.000 | YES | 28 | 0.056128978946917686 |
| 14 | 0.0 | 0.000 | YES | 17 | 0.23257490049594476 |
| 15 | 0.0 | 0.000 | YES | 11 | 0.11520665309881976 |
| 16 | 1.0 | 0.000 | NO | 21 | 0.9973663336135632 |
| 17 | 0.0 | 1.000 | NO | 0 | 0.0392156862745098 |
| 18 | 1.0 | 1.000 | YES | 26 | 0.19256558750168648 |
| 19 | 0.0 | 1.000 | NO | 16 | 0.22583812001217068 |
| 20 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 21 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 22 | 1.0 | 1.000 | YES | 25 | 0.11712874694595052 |
| 23 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 24 | 0.0 | 0.000 | YES | 21 | 0.17951202305200664 |
| 25 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 27 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 28 | 0.0 | 1.000 | NO | 0 | 0.0392156862745098 |
| 29 | 1.0 | 0.000 | NO | 0 | 0.0392156862745098 |
| 30 | 0.0 | 1.000 | NO | 0 | 0.04878048780487805 |
| 31 | 0.0 | 0.000 | YES | 17 | 0.9973939488309008 |
| 32 | 0.0 | 0.000 | YES | 30 | 0.189207540501483 |
| 33 | 0.0 | 1.000 | NO | 0 | 0.0392156862745098 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 35 | 0.0 | 0.000 | YES | 23 | 0.9968245114516564 |
| 36 | 1.0 | 0.000 | NO | 0 | 0.0392156862745098 |
| 37 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 38 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 39 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 40 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 41 | 0.0 | 1.000 | NO | 0 | 0.0392156862745098 |
| 42 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 43 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 45 | 0.0 | 1.000 | NO | 0 | 0.0392156862745098 |
| 46 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 47 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 48 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 49 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
