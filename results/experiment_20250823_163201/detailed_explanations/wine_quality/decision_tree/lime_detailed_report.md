# Detailed Explanation Report

**Dataset:** wine_quality  
**Model:** decision_tree  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:29:30  

## Summary Statistics

- **Total Instances:** 320
- **Valid Explanations:** 320
- **Errors:** 0
- **Model Accuracy:** 0.6406
- **Average Feature Importance:** 0.0375
- **Feature Importance Std:** 0.1785
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 205 (64.1%)
- **Incorrect Predictions:** 115 (35.9%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 314 | 0.0015 | 98.1% |
| 1 | 310 | 0.0826 | 96.9% |
| 2 | 306 | 0.0095 | 95.6% |
| 3 | 286 | 0.0038 | 89.4% |
| 4 | 246 | 0.0667 | 76.9% |
| 10 | 61 | 0.8273 | 19.1% |
| 6 | 34 | 0.6673 | 10.6% |
| 9 | 16 | 0.5321 | 5.0% |
| 8 | 11 | 0.1295 | 3.4% |
| 5 | 9 | 0.1064 | 2.8% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.562', '0.397', '0.041']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.075', '0.925', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 6

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.562', '0.397', '0.041']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 6: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.125', '0.823', '0.052']
- **Top Features:**
  - Feature 4: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 4: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 0.000 | NO | 6 | 1.0 |
| 1 | 0.0 | 1.000 | NO | 4 | 1.0 |
| 2 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 3 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 4 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 0.000 | NO | 4 | 1.0 |
| 6 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 6 | 1.0 |
| 9 | 2.0 | 1.000 | NO | 10 | 1.0 |
| 10 | 0.0 | 0.000 | YES | 1 | 1.0 |
| 11 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 13 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 16 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 17 | 0.0 | 0.000 | YES | 1 | 1.0 |
| 18 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 1.0 | 0.000 | NO | 6 | 1.0 |
| 21 | 1.0 | 1.000 | YES | 10 | 0.8185669796383818 |
| 22 | 0.0 | 0.000 | YES | 10 | 0.6 |
| 23 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 24 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 25 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 26 | 1.0 | 1.000 | YES | 10 | 1.0 |
| 27 | 0.0 | 2.000 | NO | 2 | 1.0 |
| 28 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 29 | 0.0 | 0.000 | YES | 1 | 1.0 |
| 30 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 31 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 32 | 1.0 | 1.000 | YES | 1 | 1.0 |
| 33 | 1.0 | 1.000 | YES | 4 | 1.0 |
| 34 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 35 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 36 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 37 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 40 | 0.0 | 1.000 | NO | 1 | 1.0 |
| 41 | 0.0 | 2.000 | NO | 10 | 0.9552077995703945 |
| 42 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 43 | 1.0 | 1.000 | YES | 10 | 1.0 |
| 44 | 2.0 | 2.000 | YES | 6 | 1.0 |
| 45 | 2.0 | 0.000 | NO | 10 | 0.6666666666666666 |
| 46 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 47 | 1.0 | 0.000 | NO | 10 | 0.9674597446521578 |
| 48 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 49 | 2.0 | 1.000 | NO | 0 | 0.0 |

*Showing first 50 of 320 instances. See JSON file for complete data.*
