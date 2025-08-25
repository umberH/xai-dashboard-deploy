# Detailed Explanation Report

**Dataset:** heart_disease  
**Model:** gradient_boosting  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:25:43  

## Summary Statistics

- **Total Instances:** 60
- **Valid Explanations:** 60
- **Errors:** 0
- **Model Accuracy:** 0.7000
- **Average Feature Importance:** 0.0833
- **Feature Importance Std:** 0.2281
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 42 (70.0%)
- **Incorrect Predictions:** 18 (30.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 60 | 0.0395 | 100.0% |
| 1 | 60 | 0.0094 | 100.0% |
| 2 | 60 | 0.1155 | 100.0% |
| 3 | 60 | 0.2318 | 100.0% |
| 4 | 60 | 0.0204 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.916', '0.084']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.689', '0.311']
- **Top Features:**
  - Feature 3: 0.7983
  - Feature 1: 0.2017
  - Feature 0: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.817', '0.183']
- **Top Features:**
  - Feature 2: 0.8842
  - Feature 3: 0.1158
  - Feature 0: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.736', '0.264']
- **Top Features:**
  - Feature 3: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.968', '0.032']
- **Top Features:**
  - Feature 3: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

### Incorrect Predictions (Sample)

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.350', '0.650']
- **Top Features:**
  - Feature 0: 0.6293
  - Feature 3: 0.3386
  - Feature 2: 0.0321

#### Instance 9

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.292', '0.708']
- **Top Features:**
  - Feature 2: 0.5263
  - Feature 3: 0.4737
  - Feature 0: 0.0000

#### Instance 10

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.802', '0.198']
- **Top Features:**
  - Feature 2: 0.9453
  - Feature 0: 0.0547
  - Feature 1: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 1 | 0.0 | 0.000 | YES | 3 | 0.7983430013476231 |
| 2 | 0.0 | 0.000 | YES | 2 | 0.8842466992222825 |
| 3 | 0.0 | 1.000 | NO | 0 | 0.6293395094673432 |
| 4 | 0.0 | 0.000 | YES | 3 | 1.0 |
| 5 | 0.0 | 0.000 | YES | 3 | 1.0 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 3 | 0.7643760418615484 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 0.0 | 1.000 | NO | 2 | 0.5263483390374144 |
| 10 | 1.0 | 0.000 | NO | 2 | 0.9452755851917635 |
| 11 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 13 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 14 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 15 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 16 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 17 | 0.0 | 1.000 | NO | 2 | 0.47630068227585604 |
| 18 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 19 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 21 | 0.0 | 0.000 | YES | 2 | 0.5566787050034311 |
| 22 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 23 | 0.0 | 0.000 | YES | 3 | 1.0 |
| 24 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 25 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 26 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 27 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 28 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 29 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 30 | 0.0 | 0.000 | YES | 3 | 0.7654203878549207 |
| 31 | 1.0 | 0.000 | NO | 3 | 0.866759086580885 |
| 32 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 33 | 0.0 | 0.000 | YES | 3 | 0.6447751927844696 |
| 34 | 0.0 | 0.000 | YES | 3 | 1.0 |
| 35 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 36 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 37 | 1.0 | 0.000 | NO | 2 | 0.8764953163049467 |
| 38 | 0.0 | 0.000 | YES | 3 | 1.0 |
| 39 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 40 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 41 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 1.000 | YES | 2 | 0.6260753540598426 |
| 43 | 1.0 | 0.000 | NO | 0 | 0.7595779207626275 |
| 44 | 0.0 | 1.000 | NO | 2 | 0.5387299504547828 |
| 45 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 46 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 47 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 48 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 49 | 0.0 | 1.000 | NO | 0 | 0.0 |

*Showing first 50 of 60 instances. See JSON file for complete data.*
