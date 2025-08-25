# Detailed Explanation Report

**Dataset:** wine_quality  
**Model:** gradient_boosting  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:32:08  

## Summary Statistics

- **Total Instances:** 320
- **Valid Explanations:** 320
- **Errors:** 0
- **Model Accuracy:** 0.7000
- **Average Feature Importance:** 0.0327
- **Feature Importance Std:** 0.1359
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 224 (70.0%)
- **Incorrect Predictions:** 96 (30.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 303 | 0.0473 | 94.7% |
| 0 | 283 | 0.0079 | 88.4% |
| 2 | 265 | 0.0174 | 82.8% |
| 4 | 260 | 0.0697 | 81.2% |
| 3 | 250 | 0.0174 | 78.1% |
| 8 | 55 | 0.3556 | 17.2% |
| 6 | 46 | 0.4182 | 14.4% |
| 7 | 40 | 0.1397 | 12.5% |
| 10 | 39 | 0.3857 | 12.2% |
| 9 | 32 | 0.2503 | 10.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.093', '0.535', '0.373']
- **Top Features:**
  - Feature 9: 0.7834
  - Feature 10: 0.2166
  - Feature 0: 0.0000

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.503', '0.470', '0.026']
- **Top Features:**
  - Feature 8: 0.4816
  - Feature 4: 0.3026
  - Feature 10: 0.1277

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.951', '0.041', '0.008']
- **Top Features:**
  - Feature 7: 0.6947
  - Feature 8: 0.3053
  - Feature 0: 0.0000

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.637', '0.345', '0.018']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.117', '0.581', '0.301']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.515', '0.434', '0.050']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 9

- **True Label:** 2.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.211', '0.638', '0.151']
- **Top Features:**
  - Feature 3: 0.2710
  - Feature 10: 0.2169
  - Feature 5: 0.1676

#### Instance 15

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.073', '0.180', '0.747']
- **Top Features:**
  - Feature 10: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 9 | 0.783353675774085 |
| 1 | 0.0 | 0.000 | YES | 8 | 0.4815570267916165 |
| 2 | 0.0 | 0.000 | YES | 7 | 0.6947018103345938 |
| 3 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 4 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 6 | 0.0 | 0.000 | YES | 6 | 0.7002719886789405 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 2.0 | 1.000 | NO | 3 | 0.27098672287326725 |
| 10 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 11 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 0.000 | YES | 8 | 0.8626500261630653 |
| 13 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 6 | 1.0 |
| 15 | 1.0 | 2.000 | NO | 10 | 1.0 |
| 16 | 1.0 | 0.000 | NO | 8 | 0.431036324231413 |
| 17 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 18 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 1.0 | 1.000 | YES | 9 | 0.8659780968956214 |
| 21 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 22 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 23 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 24 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 25 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 28 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 29 | 0.0 | 0.000 | YES | 1 | 0.5854397441235789 |
| 30 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 31 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 34 | 2.0 | 2.000 | YES | 10 | 1.0 |
| 35 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 36 | 0.0 | 0.000 | YES | 4 | 0.9545015013756508 |
| 37 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 38 | 0.0 | 0.000 | YES | 3 | 0.45190012420681397 |
| 39 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 40 | 0.0 | 0.000 | YES | 1 | 0.7022046889795959 |
| 41 | 0.0 | 1.000 | NO | 10 | 0.32483434029891184 |
| 42 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 43 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 44 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 45 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 46 | 1.0 | 0.000 | NO | 1 | 0.9310188776466649 |
| 47 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 48 | 1.0 | 1.000 | YES | 4 | 1.0 |
| 49 | 2.0 | 2.000 | YES | 7 | 0.39751476675524816 |

*Showing first 50 of 320 instances. See JSON file for complete data.*
