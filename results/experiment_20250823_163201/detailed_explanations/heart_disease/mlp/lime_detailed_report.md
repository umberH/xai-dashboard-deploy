# Detailed Explanation Report

**Dataset:** heart_disease  
**Model:** mlp  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:25:48  

## Summary Statistics

- **Total Instances:** 60
- **Valid Explanations:** 60
- **Errors:** 0
- **Model Accuracy:** 0.8000
- **Average Feature Importance:** 0.0667
- **Feature Importance Std:** 0.1910
- **Max Feature Importance:** 1.0000

## Prediction Analysis

- **Correct Predictions:** 48 (80.0%)
- **Incorrect Predictions:** 12 (20.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 60 | 0.1341 | 100.0% |
| 1 | 60 | 0.0376 | 100.0% |
| 2 | 60 | 0.0241 | 100.0% |
| 3 | 60 | 0.0284 | 100.0% |
| 4 | 60 | 0.1091 | 100.0% |

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
  - Feature 3: 0.8645
  - Feature 2: 0.1158
  - Feature 0: 0.0197

#### Instance 3

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.688', '0.312']
- **Top Features:**
  - Feature 0: 0.5567
  - Feature 2: 0.2261
  - Feature 3: 0.2173

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
  - Feature 2: 0.6418
  - Feature 4: 0.1976
  - Feature 0: 0.1605

#### Instance 19

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.704', '0.296']
- **Top Features:**
  - Feature 0: 0.9045
  - Feature 4: 0.0893
  - Feature 1: 0.0062

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
| 2 | 0.0 | 0.000 | YES | 3 | 0.8644837541621575 |
| 3 | 0.0 | 0.000 | YES | 0 | 0.5566584602944455 |
| 4 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 5 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 7 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 8 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 9 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 10 | 1.0 | 0.000 | NO | 2 | 0.6418301461938442 |
| 11 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 12 | 0.0 | 0.000 | YES | 0 | 0.6724416142664633 |
| 13 | 1.0 | 1.000 | YES | 4 | 1.0 |
| 14 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 15 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 16 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 17 | 0.0 | 0.000 | YES | 4 | 0.5307663020156304 |
| 18 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 19 | 1.0 | 0.000 | NO | 0 | 0.9045324300200045 |
| 20 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 21 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 22 | 1.0 | 1.000 | YES | 1 | 0.562941065466709 |
| 23 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 24 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 25 | 0.0 | 0.000 | YES | 0 | 0.6113451003030238 |
| 26 | 0.0 | 0.000 | YES | 4 | 0.5770063675988263 |
| 27 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 28 | 0.0 | 1.000 | NO | 0 | 0.0 |
| 29 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 30 | 0.0 | 0.000 | YES | 0 | 0.49578187563729437 |
| 31 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 32 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 33 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 35 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 36 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 37 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 38 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 39 | 1.0 | 1.000 | YES | 4 | 0.5251012066512939 |
| 40 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 41 | 1.0 | 1.000 | YES | 0 | 0.0 |
| 42 | 1.0 | 1.000 | YES | 4 | 1.0 |
| 43 | 1.0 | 0.000 | NO | 0 | 0.9281561202063756 |
| 44 | 0.0 | 0.000 | YES | 0 | 0.6141177773480179 |
| 45 | 0.0 | 0.000 | YES | 0 | 0.0 |
| 46 | 1.0 | 1.000 | YES | 4 | 0.7939693150916359 |
| 47 | 0.0 | 1.000 | NO | 0 | 0.9607305898556797 |
| 48 | 1.0 | 0.000 | NO | 0 | 0.0 |
| 49 | 0.0 | 1.000 | NO | 0 | 0.0 |

*Showing first 50 of 60 instances. See JSON file for complete data.*
