# Detailed Explanation Report

**Dataset:** wine_quality  
**Model:** random_forest  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:29:53  

## Summary Statistics

- **Total Instances:** 320
- **Valid Explanations:** 320
- **Errors:** 0
- **Model Accuracy:** 0.7063
- **Average Feature Importance:** 0.0273
- **Feature Importance Std:** 0.1157
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 226 (70.6%)
- **Incorrect Predictions:** 94 (29.4%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 295 | 0.0508 | 92.2% |
| 0 | 288 | 0.0119 | 90.0% |
| 2 | 276 | 0.0217 | 86.2% |
| 4 | 269 | 0.0518 | 84.1% |
| 3 | 262 | 0.0074 | 81.9% |
| 8 | 49 | 0.2249 | 15.3% |
| 7 | 40 | 0.1402 | 12.5% |
| 10 | 36 | 0.4575 | 11.2% |
| 6 | 35 | 0.3096 | 10.9% |
| 9 | 25 | 0.3207 | 7.8% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.140', '0.462', '0.399']
- **Top Features:**
  - Feature 9: 0.9414
  - Feature 7: 0.0524
  - Feature 4: 0.0062

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.822', '0.168', '0.010']
- **Top Features:**
  - Feature 8: 0.4664
  - Feature 1: 0.3104
  - Feature 7: 0.2232

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.545', '0.441', '0.013']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.424', '0.537', '0.039']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.123', '0.511', '0.366']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.411', '0.556', '0.033']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 9

- **True Label:** 2.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.115', '0.476', '0.409']
- **Top Features:**
  - Feature 10: 0.4531
  - Feature 6: 0.1812
  - Feature 2: 0.0997

#### Instance 15

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.130', '0.293', '0.577']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 9 | 0.9413697459246866 |
| 1 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 2 | 0.0 | 0.000 | YES | 8 | 0.4663711816751417 |
| 3 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 4 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 6 | 0.0 | 0.000 | YES | 6 | 0.6328589665982085 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 2.0 | 1.000 | NO | 10 | 0.45313301829114644 |
| 10 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 11 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 13 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 1.0 | 2.000 | NO | 0 | 0.0 |
| 16 | 1.0 | 0.000 | NO | 9 | 0.490192811248983 |
| 17 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 18 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 21 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 22 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 23 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 24 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 25 | 1.0 | 0.000 | NO | 9 | 0.6715826814511031 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 28 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 29 | 0.0 | 0.000 | YES | 1 | 0.8745389947610803 |
| 30 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 31 | 0.0 | 0.000 | YES | 8 | 0.6252829154154621 |
| 32 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 34 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 35 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 36 | 0.0 | 0.000 | YES | 0 | 0.5390033453956248 |
| 37 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 40 | 0.0 | 0.000 | YES | 1 | 0.7317857887463003 |
| 41 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 42 | 1.0 | 0.000 | NO | 4 | 0.7132403842946313 |
| 43 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 44 | 2.0 | 2.000 | YES | 9 | 0.2610321206767655 |
| 45 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 46 | 1.0 | 0.000 | NO | 1 | 0.8752937555008198 |
| 47 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 48 | 1.0 | 1.000 | YES | 4 | 0.6530126895934245 |
| 49 | 2.0 | 2.000 | YES | 8 | 0.37229844608350154 |

*Showing first 50 of 320 instances. See JSON file for complete data.*
