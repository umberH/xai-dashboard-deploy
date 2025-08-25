# Detailed Explanation Report

**Dataset:** ag_news  
**Model:** roberta  
**Explanation Method:** text_occlusion  
**Generated:** 2025-08-24 18:00:51  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.9000

## Prediction Analysis

- **Correct Predictions:** 180 (90.0%)
- **Incorrect Predictions:** 20 (10.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 200 | 0.0250 | 100.0% |
| 1 | 200 | 0.0000 | 100.0% |
| 2 | 200 | 0.0100 | 100.0% |
| 3 | 200 | 0.0150 | 100.0% |
| 4 | 200 | 0.0100 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.050', '0.942', '0.003', '0.005']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.004', '0.992', '0.002', '0.002']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.991', '0.003', '0.003', '0.003']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.005', '0.992', '0.002', '0.002']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.003', '0.993', '0.002', '0.002']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.002', '0.002', '0.009', '0.987']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 22

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.037', '0.027', '0.236', '0.700']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 32

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.003', '0.002', '0.045', '0.949']
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
| 7 | 1.0 | 1.000 | YES | 0 | 0 |
| 8 | 0.0 | 0.000 | YES | 0 | 1 |
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
| 25 | 2.0 | 2.000 | YES | 0 | 0 |
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
| 49 | 0.0 | 1.000 | NO | 0 | 0 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
