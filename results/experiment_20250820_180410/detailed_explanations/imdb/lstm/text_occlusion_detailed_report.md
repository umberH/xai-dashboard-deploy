# Detailed Explanation Report

**Dataset:** imdb  
**Model:** lstm  
**Explanation Method:** text_occlusion  
**Generated:** 2025-08-20 18:46:11  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8150

## Prediction Analysis

- **Correct Predictions:** 163 (81.5%)
- **Incorrect Predictions:** 37 (18.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 200 | 0.1600 | 100.0% |
| 1 | 200 | 0.1750 | 100.0% |
| 2 | 200 | 0.1550 | 100.0% |
| 3 | 200 | 0.1650 | 100.0% |
| 4 | 200 | 0.1750 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.781', '0.219']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.356', '0.644']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.397', '0.603']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.323', '0.677']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.341', '0.659']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.503', '0.497']
- **Top Features:**
  - Feature 0: 1.0000
  - Feature 1: 1.0000
  - Feature 2: 1.0000

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.413', '0.587']
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
| 11 | 0.0 | 1.000 | NO | 0 | 1 |
| 12 | 1.0 | 1.000 | YES | 0 | 0 |
| 13 | 1.0 | 1.000 | YES | 0 | 0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0 |
| 15 | 0.0 | 0.000 | YES | 0 | 0 |
| 16 | 1.0 | 1.000 | YES | 0 | 0 |
| 17 | 0.0 | 1.000 | NO | 0 | 0 |
| 18 | 1.0 | 1.000 | YES | 0 | 0 |
| 19 | 0.0 | 1.000 | NO | 0 | 0 |
| 20 | 1.0 | 1.000 | YES | 0 | 0 |
| 21 | 0.0 | 0.000 | YES | 0 | 0 |
| 22 | 1.0 | 1.000 | YES | 0 | 1 |
| 23 | 1.0 | 0.000 | NO | 0 | 1 |
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
| 35 | 0.0 | 0.000 | YES | 0 | 0 |
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
| 46 | 1.0 | 1.000 | YES | 0 | 1 |
| 47 | 1.0 | 1.000 | YES | 0 | 0 |
| 48 | 1.0 | 1.000 | YES | 0 | 0 |
| 49 | 0.0 | 0.000 | YES | 0 | 1 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
