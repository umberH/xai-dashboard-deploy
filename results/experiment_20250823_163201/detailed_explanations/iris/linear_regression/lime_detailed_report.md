# Detailed Explanation Report

**Dataset:** iris  
**Model:** linear_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:29:21  

## Summary Statistics

- **Total Instances:** 30
- **Valid Explanations:** 30
- **Errors:** 0
- **Model Accuracy:** 1.0000
- **Average Feature Importance:** 0.2417
- **Feature Importance Std:** 0.3338
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 30 (100.0%)
- **Incorrect Predictions:** 0 (0.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 30 | 0.3066 | 100.0% |
| 0 | 30 | 0.0421 | 100.0% |
| 2 | 30 | 0.2547 | 100.0% |
| 3 | 30 | 0.3633 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** -0.021802036940573255
- **Prediction Probabilities:** ['-0.022']
- **Top Features:**
  - Feature 1: 1.0000
  - Feature 0: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 1.594678905525389
- **Prediction Probabilities:** ['1.595']
- **Top Features:**
  - Feature 3: 0.5534
  - Feature 2: 0.4233
  - Feature 0: 0.0223

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.8918912024316553
- **Prediction Probabilities:** ['0.892']
- **Top Features:**
  - Feature 2: 1.0000
  - Feature 0: 0.0000
  - Feature 1: 0.0000

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 0.8863871812290878
- **Prediction Probabilities:** ['0.886']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 4

- **True Label:** 0.0
- **Prediction:** -0.030704953543304048
- **Prediction Probabilities:** ['-0.031']
- **Top Features:**
  - Feature 1: 1.0000
  - Feature 0: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | -0.022 | YES | 1 | 1.0 |
| 1 | 2.0 | 1.595 | YES | 3 | 0.5533845345660143 |
| 2 | 1.0 | 0.892 | YES | 2 | 1.0 |
| 3 | 1.0 | 0.886 | YES | 0 | 0.0 |
| 4 | 0.0 | -0.031 | YES | 1 | 1.0 |
| 5 | 1.0 | 1.393 | YES | 3 | 0.6813475173341574 |
| 6 | 0.0 | -0.134 | YES | 1 | 1.0 |
| 7 | 0.0 | -0.051 | YES | 1 | 1.0 |
| 8 | 2.0 | 1.745 | YES | 3 | 0.6700440751358147 |
| 9 | 1.0 | 1.390 | YES | 3 | 0.6952638760164291 |
| 10 | 2.0 | 1.787 | YES | 3 | 0.6006824762773202 |
| 11 | 2.0 | 1.866 | YES | 2 | 0.5299761560496167 |
| 12 | 2.0 | 2.001 | YES | 3 | 0.5817738439619741 |
| 13 | 1.0 | 1.281 | YES | 3 | 0.6599266268557994 |
| 14 | 0.0 | -0.055 | YES | 1 | 1.0 |
| 15 | 0.0 | -0.073 | YES | 1 | 1.0 |
| 16 | 0.0 | -0.228 | YES | 0 | 0.7202286812128441 |
| 17 | 1.0 | 1.012 | YES | 2 | 0.9549697123322 |
| 18 | 1.0 | 1.306 | YES | 3 | 0.6310925076478711 |
| 19 | 2.0 | 1.583 | YES | 3 | 0.6672898158602065 |
| 20 | 0.0 | -0.109 | YES | 1 | 1.0 |
| 21 | 2.0 | 2.057 | YES | 3 | 0.6725190990778732 |
| 22 | 1.0 | 1.172 | YES | 3 | 0.49403168906350936 |
| 23 | 2.0 | 1.517 | YES | 3 | 0.6172081370603626 |
| 24 | 2.0 | 1.976 | YES | 3 | 0.650296819104846 |
| 25 | 1.0 | 1.495 | YES | 3 | 0.6220867163991592 |
| 26 | 1.0 | 1.186 | YES | 3 | 0.8010721675275632 |
| 27 | 0.0 | -0.037 | YES | 1 | 0.8396244834823868 |
| 28 | 2.0 | 1.687 | YES | 3 | 0.8213228938691133 |
| 29 | 0.0 | -0.097 | YES | 1 | 1.0 |
