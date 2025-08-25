# Detailed Explanation Report

**Dataset:** ag_news  
**Model:** naive_bayes_text  
**Explanation Method:** text_occlusion  
**Generated:** 2025-08-24 19:01:18  

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
| 0 | 200 | 0.0000 | 100.0% |
| 1 | 200 | 0.0350 | 100.0% |
| 2 | 200 | 0.0200 | 100.0% |
| 3 | 200 | 0.0050 | 100.0% |
| 4 | 200 | 0.0000 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.175', '0.344', '0.210', '0.271']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.075', '0.760', '0.088', '0.077']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.629', '0.106', '0.147', '0.119']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.108', '0.756', '0.074', '0.063']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.128', '0.509', '0.203', '0.160']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.061', '0.059', '0.098', '0.782']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.320', '0.282', '0.231', '0.167']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 22

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.217', '0.183', '0.243', '0.358']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 0 | 0 |
| 1 | 1.0 | 1.000 | YES | 0 | 0 |
| 2 | 0.0 | 0.000 | YES | 0 | 0 |
| 3 | 1.0 | 1.000 | YES | 0 | 0 |
| 4 | 1.0 | 1.000 | YES | 0 | 0 |
| 5 | 1.0 | 1.000 | YES | 0 | 0 |
| 6 | 2.0 | 3.000 | NO | 0 | 0 |
| 7 | 1.0 | 0.000 | NO | 0 | 0 |
| 8 | 0.0 | 0.000 | YES | 0 | 0 |
| 9 | 3.0 | 3.000 | YES | 0 | 0 |
| 10 | 3.0 | 3.000 | YES | 0 | 0 |
| 11 | 3.0 | 3.000 | YES | 0 | 0 |
| 12 | 1.0 | 1.000 | YES | 0 | 0 |
| 13 | 2.0 | 2.000 | YES | 0 | 0 |
| 14 | 3.0 | 3.000 | YES | 0 | 0 |
| 15 | 3.0 | 3.000 | YES | 0 | 0 |
| 16 | 2.0 | 2.000 | YES | 0 | 0 |
| 17 | 0.0 | 0.000 | YES | 0 | 0 |
| 18 | 1.0 | 1.000 | YES | 0 | 0 |
| 19 | 2.0 | 2.000 | YES | 0 | 0 |
| 20 | 1.0 | 1.000 | YES | 0 | 0 |
| 21 | 2.0 | 2.000 | YES | 0 | 0 |
| 22 | 2.0 | 3.000 | NO | 0 | 0 |
| 23 | 3.0 | 3.000 | YES | 0 | 0 |
| 24 | 0.0 | 0.000 | YES | 0 | 0 |
| 25 | 2.0 | 3.000 | NO | 0 | 0 |
| 26 | 0.0 | 0.000 | YES | 0 | 0 |
| 27 | 2.0 | 2.000 | YES | 0 | 0 |
| 28 | 3.0 | 3.000 | YES | 0 | 0 |
| 29 | 2.0 | 2.000 | YES | 0 | 0 |
| 30 | 3.0 | 3.000 | YES | 0 | 0 |
| 31 | 0.0 | 0.000 | YES | 0 | 0 |
| 32 | 2.0 | 3.000 | NO | 0 | 0 |
| 33 | 3.0 | 3.000 | YES | 0 | 0 |
| 34 | 0.0 | 1.000 | NO | 0 | 0 |
| 35 | 1.0 | 1.000 | YES | 0 | 0 |
| 36 | 3.0 | 3.000 | YES | 0 | 0 |
| 37 | 2.0 | 2.000 | YES | 0 | 0 |
| 38 | 3.0 | 3.000 | YES | 0 | 0 |
| 39 | 3.0 | 0.000 | NO | 0 | 0 |
| 40 | 2.0 | 2.000 | YES | 0 | 0 |
| 41 | 2.0 | 2.000 | YES | 0 | 0 |
| 42 | 2.0 | 2.000 | YES | 0 | 0 |
| 43 | 2.0 | 2.000 | YES | 0 | 0 |
| 44 | 2.0 | 2.000 | YES | 0 | 0 |
| 45 | 1.0 | 1.000 | YES | 0 | 0 |
| 46 | 2.0 | 2.000 | YES | 0 | 0 |
| 47 | 1.0 | 1.000 | YES | 0 | 0 |
| 48 | 1.0 | 1.000 | YES | 0 | 0 |
| 49 | 0.0 | 0.000 | YES | 0 | 0 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
