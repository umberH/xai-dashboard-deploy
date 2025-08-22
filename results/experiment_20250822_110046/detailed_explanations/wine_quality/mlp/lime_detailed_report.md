# Detailed Explanation Report

**Dataset:** wine_quality  
**Model:** mlp  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:18:19  

## Summary Statistics

- **Total Instances:** 320
- **Valid Explanations:** 320
- **Errors:** 0
- **Model Accuracy:** 0.6906
- **Average Feature Importance:** 0.0321
- **Feature Importance Std:** 0.1181
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 221 (69.1%)
- **Incorrect Predictions:** 99 (30.9%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 284 | 0.0263 | 88.8% |
| 1 | 284 | 0.0214 | 88.8% |
| 2 | 282 | 0.0392 | 88.1% |
| 3 | 249 | 0.0110 | 77.8% |
| 4 | 245 | 0.0291 | 76.6% |
| 8 | 62 | 0.4243 | 19.4% |
| 10 | 52 | 0.3076 | 16.2% |
| 7 | 42 | 0.1898 | 13.1% |
| 9 | 38 | 0.2385 | 11.9% |
| 6 | 32 | 0.3722 | 10.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.000', '0.943', '0.056']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.891', '0.106', '0.003']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

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
- **Prediction Probabilities:** ['0.715', '0.283', '0.002']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.230', '0.714', '0.056']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.566', '0.122', '0.311']
- **Top Features:**
  - Feature 5: 0.6918
  - Feature 10: 0.1870
  - Feature 8: 0.0790

#### Instance 15

- **True Label:** 1.0
- **Prediction:** 2.0
- **Prediction Probabilities:** ['0.017', '0.159', '0.824']
- **Top Features:**
  - Feature 10: 0.3780
  - Feature 9: 0.3405
  - Feature 2: 0.2401

#### Instance 16

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.855', '0.137', '0.008']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 1 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 2 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 3 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 4 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 6 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 6 | 0.7612337976222683 |
| 8 | 1.0 | 0.000 | NO | 5 | 0.6918355857254388 |
| 9 | 2.0 | 2.000 | YES | 2 | 0.30644393700639283 |
| 10 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 11 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 0.000 | YES | 8 | 0.3797069977150666 |
| 13 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 15 | 1.0 | 2.000 | NO | 10 | 0.37800420123095185 |
| 16 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 17 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 18 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 19 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 20 | 1.0 | 1.000 | YES | 9 | 0.62823866350356 |
| 21 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 22 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 23 | 1.0 | 1.000 | YES | 8 | 0.9457040035987404 |
| 24 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 25 | 1.0 | 0.000 | NO | 8 | 0.5369039029753316 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 27 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 28 | 2.0 | 1.000 | NO | 0 | 0.43233526094389996 |
| 29 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 30 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 31 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 32 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 33 | 1.0 | 1.000 | YES | 4 | 0.3083644335761098 |
| 34 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 35 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 36 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 37 | 1.0 | 1.000 | YES | 10 | 0.47654407184281367 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 40 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 41 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 42 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 43 | 1.0 | 1.000 | YES | 8 | 0.6803224244667943 |
| 44 | 2.0 | 2.000 | YES | 0 | 0.0 |
| 45 | 2.0 | 1.000 | NO | 0 | 0.0 |
| 46 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 47 | 1.0 | 1.000 | YES | 2 | 0.674043334849499 |
| 48 | 1.0 | 1.000 | YES | 8 | 0.6350503774350444 |
| 49 | 2.0 | 2.000 | YES | 8 | 0.35984115048680587 |

*Showing first 50 of 320 instances. See JSON file for complete data.*
