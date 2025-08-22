# Detailed Explanation Report

**Dataset:** compas  
**Model:** mlp  
**Explanation Method:** lime  
**Generated:** 2025-08-20 18:42:22  

## Summary Statistics

- **Total Instances:** 1443
- **Valid Explanations:** 1443
- **Errors:** 0
- **Model Accuracy:** 0.6854
- **Average Feature Importance:** 0.1060
- **Feature Importance Std:** 0.2940
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 989 (68.5%)
- **Incorrect Predictions:** 454 (31.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 1443 | 0.0108 | 100.0% |
| 1 | 1443 | 0.1206 | 100.0% |
| 2 | 1443 | 0.1867 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.690', '0.310']
- **Top Features:**
  - Feature 2: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.174', '0.826']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.149', '0.851']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 6

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.769', '0.231']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.704', '0.296']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.651', '0.349']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.525', '0.475']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.458', '0.542']
- **Top Features:**
  - Feature 2: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 1 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 2 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 3 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 4 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 5 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 6 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 9 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 11 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 12 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 13 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 15 | 0.0 | 1.000 | NO | 1 | 0.9448007053568008 |
| 16 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 17 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 18 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 19 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 20 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 21 | 1.0 | 1.000 | YES | 1 | 0.9159855752097923 |
| 22 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 23 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 24 | 1.0 | 1.000 | YES | 1 | 1.0 |
| 25 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 26 | 1.0 | 0.000 | NO | 1 | 0.8260263881135018 |
| 27 | 0.0 | 0.000 | YES | 1 | 0.6624288570001119 |
| 28 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 29 | 1.0 | 1.000 | YES | 2 | 1.0 |
| 30 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 31 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 34 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 35 | 0.0 | 1.000 | NO | 2 | 1.0 |
| 36 | 0.0 | 1.000 | NO | 1 | 0.6587746833959829 |
| 37 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 38 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 39 | 1.0 | 1.000 | YES | 2 | 1.0 |
| 40 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 41 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 43 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 44 | 0.0 | 0.000 | YES | 1 | 0.7962988768795628 |
| 45 | 0.0 | 0.000 | YES | 2 | 1.0 |
| 46 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 47 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 48 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 49 | 0.0 | 1.000 | NO | 1 | 0.6203815827782956 |

*Showing first 50 of 1443 instances. See JSON file for complete data.*
