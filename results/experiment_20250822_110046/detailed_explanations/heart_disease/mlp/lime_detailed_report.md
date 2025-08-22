# Detailed Explanation Report

**Dataset:** heart_disease  
**Model:** mlp  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:01:23  

## Summary Statistics

- **Total Instances:** 60
- **Valid Explanations:** 60
- **Errors:** 0
- **Model Accuracy:** 0.8000
- **Average Feature Importance:** 0.0733
- **Feature Importance Std:** 0.2022
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 48 (80.0%)
- **Incorrect Predictions:** 12 (20.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 60 | 0.1595 | 100.0% |
| 1 | 60 | 0.0486 | 100.0% |
| 2 | 60 | 0.0287 | 100.0% |
| 3 | 60 | 0.0221 | 100.0% |
| 4 | 60 | 0.1078 | 100.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.958', '0.042']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 1

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.845', '0.155']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.502', '0.498']
- **Top Features:**
  - Feature 3: 0.7359
  - Feature 0: 0.1530
  - Feature 2: 0.1111

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.688', '0.312']
- **Top Features:**
  - Feature 0: 0.7097
  - Feature 2: 0.2569
  - Feature 3: 0.0335

#### Instance 4

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.785', '0.215']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

### Incorrect Predictions (Sample)

#### Instance 10

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.665', '0.335']
- **Top Features:**
  - Feature 2: 0.6865
  - Feature 0: 0.2685
  - Feature 4: 0.0451

#### Instance 19

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.704', '0.296']
- **Top Features:**
  - Feature 0: 0.9170
  - Feature 4: 0.0830
  - Feature 1: 0.0000

#### Instance 28

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.187', '0.813']
- **Top Features:**
  - Feature 0: 0.0000
  - Feature 1: 0.0000
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 1 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 2 | 0.0 | 0.000 | YES | 3 | 0.7359360034302529 |
| 3 | 0.0 | 0.000 | YES | 0 | 0.7096700589804046 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 0.000 | NO | 2 | 0.686452377250202 |
| 11 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 0.000 | YES | 1 | 0.4726726475914029 |
| 13 | 1.0 | 1.000 | YES | 4 | 1.0 |
| 14 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 15 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 16 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 17 | 0.0 | 0.000 | YES | 4 | 0.7331185080078134 |
| 18 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 19 | 1.0 | 0.000 | NO | 0 | 0.9170265783345117 |
| 20 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 21 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 22 | 1.0 | 1.000 | YES | 4 | 0.4146855747066724 |
| 23 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 24 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 25 | 0.0 | 0.000 | YES | 1 | 0.5847764145279315 |
| 26 | 0.0 | 0.000 | YES | 4 | 0.7421240289460227 |
| 27 | 1.0 | 1.000 | YES | 4 | 1.0 |
| 28 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 29 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 30 | 0.0 | 0.000 | YES | 1 | 0.5559584011707628 |
| 31 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 32 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 33 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 35 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 36 | 0.0 | 0.000 | YES | 0 | 1.0 |
| 37 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 1.0 | 1.000 | YES | 0 | 0.5583833547097082 |
| 40 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 41 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 1.000 | YES | 0 | 0.5519645614965529 |
| 43 | 1.0 | 0.000 | NO | 0 | 0.8454302323732696 |
| 44 | 0.0 | 0.000 | YES | 0 | 1.0 |
| 45 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 46 | 1.0 | 1.000 | YES | 4 | 0.6449197671168602 |
| 47 | 0.0 | 1.000 | NO | 0 | 0.85706805719256 |
| 48 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 49 | 0.0 | 1.000 | NO | 0 | 0.0 |

*Showing first 50 of 60 instances. See JSON file for complete data.*
