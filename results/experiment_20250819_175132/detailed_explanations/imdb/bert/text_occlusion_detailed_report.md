# Detailed Explanation Report

**Dataset:** imdb  
**Model:** bert  
**Explanation Method:** text_occlusion  
**Generated:** 2025-08-19 18:34:37  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8100

## Prediction Analysis

- **Correct Predictions:** 162 (81.0%)
- **Incorrect Predictions:** 38 (19.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 200 | 0.1700 | 100.0% |
| 1 | 200 | 0.1650 | 100.0% |
| 2 | 200 | 0.1550 | 100.0% |
| 3 | 200 | 0.1650 | 100.0% |
| 4 | 200 | 0.1750 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.753', '0.247']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.320', '0.680']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.350', '0.650']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.259', '0.741']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.371', '0.629']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.510', '0.490']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 1.0000
  - Feature 2: 1.0000

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.405', '0.595']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.656', '0.344']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0 |
| 1 | 1.0 | 1.000 | YES | 0 | 0 |
| 2 | 1.0 | 0.000 | NO | 0 | 1 |
| 3 | 1.0 | 1.000 | YES | 0 | 0 |
| 4 | 1.0 | 1.000 | YES | 0 | 0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0 |
| 6 | 1.0 | 1.000 | YES | 0 | 0 |
| 7 | 0.0 | 1.000 | NO | 0 | 0 |
| 8 | 1.0 | 0.000 | NO | 0 | 0 |
| 9 | 1.0 | 1.000 | YES | 0 | 0 |
| 10 | 0.0 | 0.000 | YES | 0 | 0 |
| 11 | 0.0 | 0.000 | YES | 0 | 0 |
| 12 | 1.0 | 1.000 | YES | 0 | 0 |
| 13 | 1.0 | 1.000 | YES | 0 | 0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0 |
| 15 | 0.0 | 0.000 | YES | 0 | 0 |
| 16 | 1.0 | 1.000 | YES | 0 | 0 |
| 17 | 0.0 | 1.000 | NO | 0 | 0 |
| 18 | 1.0 | 1.000 | YES | 0 | 1 |
| 19 | 0.0 | 1.000 | NO | 0 | 0 |
| 20 | 1.0 | 1.000 | YES | 0 | 1 |
| 21 | 0.0 | 0.000 | YES | 0 | 0 |
| 22 | 1.0 | 1.000 | YES | 0 | 1 |
| 23 | 1.0 | 1.000 | YES | 0 | 0 |
| 24 | 0.0 | 0.000 | YES | 0 | 0 |
| 25 | 1.0 | 1.000 | YES | 0 | 0 |
| 26 | 1.0 | 1.000 | YES | 0 | 0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0 |
| 28 | 0.0 | 1.000 | NO | 0 | 0 |
| 29 | 1.0 | 1.000 | YES | 0 | 1 |
| 30 | 0.0 | 0.000 | YES | 0 | 0 |
| 31 | 0.0 | 0.000 | YES | 0 | 0 |
| 32 | 0.0 | 0.000 | YES | 0 | 0 |
| 33 | 0.0 | 1.000 | NO | 0 | 1 |
| 34 | 0.0 | 0.000 | YES | 0 | 1 |
| 35 | 0.0 | 0.000 | YES | 0 | 1 |
| 36 | 1.0 | 1.000 | YES | 0 | 0 |
| 37 | 1.0 | 1.000 | YES | 0 | 0 |
| 38 | 1.0 | 1.000 | YES | 0 | 0 |
| 39 | 0.0 | 0.000 | YES | 0 | 1 |
| 40 | 0.0 | 0.000 | YES | 0 | 0 |
| 41 | 0.0 | 1.000 | NO | 0 | 1 |
| 42 | 1.0 | 1.000 | YES | 0 | 0 |
| 43 | 1.0 | 1.000 | YES | 0 | 0 |
| 44 | 0.0 | 0.000 | YES | 0 | 0 |
| 45 | 0.0 | 0.000 | YES | 0 | 0 |
| 46 | 1.0 | 1.000 | YES | 0 | 0 |
| 47 | 1.0 | 1.000 | YES | 0 | 0 |
| 48 | 1.0 | 1.000 | YES | 0 | 0 |
| 49 | 0.0 | 0.000 | YES | 0 | 1 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
