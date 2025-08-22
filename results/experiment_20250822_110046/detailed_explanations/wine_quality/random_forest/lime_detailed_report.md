# Detailed Explanation Report

**Dataset:** wine_quality  
**Model:** random_forest  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:11:00  

## Summary Statistics

- **Total Instances:** 320
- **Valid Explanations:** 320
- **Errors:** 0
- **Model Accuracy:** 0.7063
- **Average Feature Importance:** 0.0276
- **Feature Importance Std:** 0.1165
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 226 (70.6%)
- **Incorrect Predictions:** 94 (29.4%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 291 | 0.0500 | 90.9% |
| 0 | 280 | 0.0090 | 87.5% |
| 2 | 280 | 0.0254 | 87.5% |
| 4 | 277 | 0.0546 | 86.6% |
| 3 | 265 | 0.0131 | 82.8% |
| 8 | 50 | 0.2459 | 15.6% |
| 6 | 39 | 0.3490 | 12.2% |
| 10 | 36 | 0.3638 | 11.2% |
| 7 | 35 | 0.1031 | 10.9% |
| 9 | 25 | 0.3236 | 7.8% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.140', '0.462', '0.399']
- **Top Features:**
  - Feature 9: 0.8659
  - Feature 4: 0.1263
  - Feature 7: 0.0078

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.822', '0.168', '0.010']
- **Top Features:**
  - Feature 1: 0.5211
  - Feature 7: 0.2421
  - Feature 8: 0.2367

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
  - Feature 10: 0.5903
  - Feature 2: 0.1705
  - Feature 8: 0.1111

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
| 0 | 1.0 | 1.000 | YES | 9 | 0.8659211333025341 |
| 1 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 2 | 0.0 | 0.000 | YES | 1 | 0.5211429032114493 |
| 3 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 4 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 6 | 0.0 | 0.000 | YES | 6 | 0.48620161669972833 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 2.0 | 1.000 | NO | 10 | 0.5902772056533003 |
| 10 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 11 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 13 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 1.0 | 2.000 | NO | 0 | 0.0 |
| 16 | 1.0 | 0.000 | NO | 9 | 0.7230135994823278 |
| 17 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 18 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 21 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 22 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 23 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 24 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 25 | 1.0 | 0.000 | NO | 8 | 0.6489898989898992 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 28 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 29 | 0.0 | 0.000 | YES | 1 | 0.8260295000204089 |
| 30 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 31 | 0.0 | 0.000 | YES | 4 | 1.0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 34 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 35 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 36 | 0.0 | 0.000 | YES | 0 | 0.4745310225393786 |
| 37 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 40 | 0.0 | 0.000 | YES | 1 | 0.7420793566624266 |
| 41 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 42 | 1.0 | 0.000 | NO | 4 | 0.7375237635474512 |
| 43 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 44 | 2.0 | 2.000 | YES | 2 | 0.3817783580891236 |
| 45 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 46 | 1.0 | 0.000 | NO | 1 | 0.8888853942677939 |
| 47 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 48 | 1.0 | 1.000 | YES | 4 | 0.6414127022731706 |
| 49 | 2.0 | 2.000 | YES | 8 | 0.43263693320783486 |

*Showing first 50 of 320 instances. See JSON file for complete data.*
