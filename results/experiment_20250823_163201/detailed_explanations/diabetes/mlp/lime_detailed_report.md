# Detailed Explanation Report

**Dataset:** diabetes  
**Model:** mlp  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:35:39  

## Summary Statistics

- **Total Instances:** 89
- **Valid Explanations:** 89
- **Errors:** 0
- **Model Accuracy:** 0.4494
- **Average Feature Importance:** 0.0438
- **Feature Importance Std:** 0.1321
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 40 (44.9%)
- **Incorrect Predictions:** 49 (55.1%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 78 | 0.0902 | 87.6% |
| 2 | 77 | 0.0975 | 86.5% |
| 4 | 73 | 0.0561 | 82.0% |
| 3 | 70 | 0.0130 | 78.7% |
| 1 | 69 | 0.0215 | 77.5% |
| 9 | 19 | 0.1570 | 21.3% |
| 8 | 19 | 0.2458 | 21.3% |
| 5 | 14 | 0.2101 | 15.7% |
| 6 | 14 | 0.3126 | 15.7% |
| 7 | 12 | 0.1383 | 13.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.226', '0.446', '0.328']
- **Top Features:**
  - Feature 2: 0.3338
  - Feature 4: 0.1852
  - Feature 7: 0.1377

#### Instance 3

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.000', '0.004', '0.996']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['1.000', '0.000', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.303', '0.046', '0.651']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.046', '0.866', '0.088']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.013', '0.038', '0.950']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.984', '0.016', '0.000']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.828', '0.106', '0.065']
- **Top Features:**
  - Feature 5: 0.4392
  - Feature 7: 0.2021
  - Feature 4: 0.1786

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 2 | 0.3337656333809794 |
| 1 | 0.0 | 2.000 | NO | 0 | 0.0 |
| 2 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 3 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 0.000 | NO | 5 | 0.4391635955218116 |
| 6 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 7 | 1.0 | 2.000 | NO | 8 | 0.33147288844814554 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 0.000 | NO | 0 | 0.47884364802954654 |
| 11 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 1.000 | NO | 2 | 0.5949366608944047 |
| 13 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 14 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 15 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 16 | 0.0 | 0.000 | YES | 4 | 0.4799287467805785 |
| 17 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 18 | 0.0 | 1.000 | NO | 0 | 0.689562615693945 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 21 | 0.0 | 1.000 | NO | 0 | 0.37279139193899397 |
| 22 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 23 | 0.0 | 0.000 | YES | 1 | 0.5714285714285714 |
| 24 | 0.0 | 0.000 | YES | 8 | 0.5280185329688258 |
| 25 | 2.0 | 1.000 | NO | 8 | 0.3520970707300917 |
| 26 | 1.0 | 1.000 | YES | 4 | 0.3664427485608141 |
| 27 | 1.0 | 2.000 | NO | 2 | 0.8333333333333334 |
| 28 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 29 | 1.0 | 0.000 | NO | 0 | 0.5996588693957117 |
| 30 | 0.0 | 0.000 | YES | 2 | 0.4519431884079356 |
| 31 | 2.0 | 2.000 | YES | 2 | 0.492710533924116 |
| 32 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 0.000 | NO | 6 | 1.0 |
| 34 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 35 | 1.0 | 0.000 | NO | 6 | 1.0 |
| 36 | 1.0 | 2.000 | NO | 0 | 0.4246527261545828 |
| 37 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 38 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 39 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 40 | 0.0 | 0.000 | YES | 4 | 0.5622167554025708 |
| 41 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 43 | 2.0 | 2.000 | YES | 9 | 0.5804028691537787 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 45 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 46 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 47 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 48 | 0.0 | 0.000 | YES | 0 | 0.5169053043008427 |
| 49 | 1.0 | 0.000 | NO | 2 | 1.0 |

*Showing first 50 of 89 instances. See JSON file for complete data.*
