# Detailed Explanation Report

**Dataset:** heart_disease  
**Model:** linear_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:25:55  

## Summary Statistics

- **Total Instances:** 60
- **Valid Explanations:** 60
- **Errors:** 0
- **Model Accuracy:** 0.8167
- **Average Feature Importance:** 0.0467
- **Feature Importance Std:** 0.1869
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 49 (81.7%)
- **Incorrect Predictions:** 11 (18.3%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 60 | 0.0077 | 100.0% |
| 1 | 60 | 0.0036 | 100.0% |
| 2 | 60 | 0.0200 | 100.0% |
| 3 | 60 | 0.0638 | 100.0% |
| 4 | 60 | 0.1383 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.489', '0.511']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.440', '0.560']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.406', '0.594']
- **Top Features:**
  - Feature 3: 0.4988
  - Feature 2: 0.3953
  - Feature 0: 0.1059

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.429', '0.571']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.383', '0.617']
- **Top Features:**
  - Feature 4: 0.6519
  - Feature 3: 0.3204
  - Feature 1: 0.0235

### Incorrect Predictions (Sample)

#### Instance 26

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.336', '0.664']
- **Top Features:**
  - Feature 4: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 28

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.362', '0.638']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 31

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.432', '0.568']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 1 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 2 | 0.0 | 0.000 | YES | 3 | 0.4987619300474111 |
| 3 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 4 | 0.0 | 0.000 | YES | 4 | 0.651941041564623 |
| 5 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 1.000 | YES | 2 | 0.7400738306922778 |
| 11 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 13 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 14 | 1.0 | 1.000 | YES | 4 | 1.0 |
| 15 | 1.0 | 1.000 | YES | 4 | 1.0 |
| 16 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 17 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 18 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 19 | 1.0 | 1.000 | YES | 4 | 1.0 |
| 20 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 21 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 22 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 23 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 24 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 25 | 0.0 | 0.000 | YES | 3 | 0.9459646227711962 |
| 26 | 0.0 | 1.000 | NO | 4 | 1.0 |
| 27 | 1.0 | 1.000 | YES | 4 | 1.0 |
| 28 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 29 | 1.0 | 1.000 | YES | 4 | 0.9207231900204251 |
| 30 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 31 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 32 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 33 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 35 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 36 | 0.0 | 0.000 | YES | 4 | 0.5154235235983908 |
| 37 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 40 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 41 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 43 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 44 | 0.0 | 0.000 | YES | 3 | 0.8266817806487041 |
| 45 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 46 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 47 | 0.0 | 1.000 | NO | 4 | 1.0 |
| 48 | 1.0 | 0.000 | NO | 3 | 0.7904949912505452 |
| 49 | 0.0 | 1.000 | NO | 0 | 0.0 |

*Showing first 50 of 60 instances. See JSON file for complete data.*
