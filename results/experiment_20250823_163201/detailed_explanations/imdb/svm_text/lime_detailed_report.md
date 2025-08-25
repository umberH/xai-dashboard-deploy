# Detailed Explanation Report

**Dataset:** imdb  
**Model:** svm_text  
**Explanation Method:** lime  
**Generated:** 2025-08-24 05:09:55  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8050
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0202
- **Max Feature Importance:** 0.5699

## Prediction Analysis

- **Correct Predictions:** 161 (80.5%)
- **Incorrect Predictions:** 39 (19.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 1 | 43 | 0.0644 | 21.5% |
| 2 | 42 | 0.0494 | 21.0% |
| 4 | 41 | 0.0547 | 20.5% |
| 3 | 41 | 0.0556 | 20.5% |
| 0 | 30 | 0.0476 | 15.0% |
| 35 | 30 | 0.0616 | 15.0% |
| 45 | 30 | 0.0627 | 15.0% |
| 13 | 27 | 0.0738 | 13.5% |
| 17 | 27 | 0.0693 | 13.5% |
| 5 | 25 | 0.0763 | 12.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.986', '0.014']
- **Top Features:**
  - Feature 39: 0.0983
  - Feature 4: 0.0862
  - Feature 13: 0.0827

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.078', '0.922']
- **Top Features:**
  - Feature 0: 0.0392
  - Feature 1: 0.0384
  - Feature 2: 0.0376

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.067', '0.933']
- **Top Features:**
  - Feature 17: 0.0540
  - Feature 30: 0.0514
  - Feature 6: 0.0487

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.009', '0.991']
- **Top Features:**
  - Feature 0: 0.0444
  - Feature 1: 0.0434
  - Feature 2: 0.0424

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.044', '0.956']
- **Top Features:**
  - Feature 48: 0.0786
  - Feature 40: 0.0730
  - Feature 22: 0.0656

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.706', '0.294']
- **Top Features:**
  - Feature 23: 0.1297
  - Feature 4: 0.1224
  - Feature 32: 0.0714

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.322', '0.678']
- **Top Features:**
  - Feature 0: 0.0392
  - Feature 1: 0.0384
  - Feature 2: 0.0376

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.829', '0.171']
- **Top Features:**
  - Feature 7: 0.0981
  - Feature 15: 0.0655
  - Feature 21: 0.0609

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 39 | 0.09832248623850263 |
| 1 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 2 | 1.0 | 0.000 | NO | 23 | 0.12968611151260867 |
| 3 | 1.0 | 1.000 | YES | 17 | 0.05401338334978712 |
| 4 | 1.0 | 1.000 | YES | 0 | 0.044444444444444446 |
| 5 | 1.0 | 1.000 | YES | 48 | 0.07857111747930898 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 7 | 0.0 | 1.000 | NO | 0 | 0.0392156862745098 |
| 8 | 1.0 | 0.000 | NO | 7 | 0.09805288885743045 |
| 9 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 10 | 0.0 | 0.000 | YES | 27 | 0.10051718692375207 |
| 11 | 0.0 | 0.000 | YES | 6 | 0.09053628753555858 |
| 12 | 1.0 | 1.000 | YES | 44 | 0.09554683517071363 |
| 13 | 1.0 | 1.000 | YES | 20 | 0.06727092976240492 |
| 14 | 0.0 | 0.000 | YES | 18 | 0.061530173955869634 |
| 15 | 0.0 | 0.000 | YES | 11 | 0.09037685964801294 |
| 16 | 1.0 | 1.000 | YES | 21 | 0.13512003074247475 |
| 17 | 0.0 | 1.000 | NO | 0 | 0.0392156862745098 |
| 18 | 1.0 | 0.000 | NO | 26 | 0.1045167932167084 |
| 19 | 0.0 | 1.000 | NO | 3 | 0.09616801090637528 |
| 20 | 1.0 | 1.000 | YES | 3 | 0.1145720594919814 |
| 21 | 0.0 | 0.000 | YES | 11 | 0.07506893375351427 |
| 22 | 1.0 | 1.000 | YES | 25 | 0.07793799829142341 |
| 23 | 1.0 | 0.000 | NO | 20 | 0.10969571399444225 |
| 24 | 0.0 | 0.000 | YES | 20 | 0.05822268488508948 |
| 25 | 1.0 | 1.000 | YES | 22 | 0.08284968462473033 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 27 | 0.0 | 0.000 | YES | 8 | 0.10118538295757414 |
| 28 | 0.0 | 1.000 | NO | 29 | 0.06908943842754658 |
| 29 | 1.0 | 1.000 | YES | 24 | 0.10830613062743276 |
| 30 | 0.0 | 0.000 | YES | 26 | 0.08926790508905773 |
| 31 | 0.0 | 0.000 | YES | 17 | 0.2168143199605575 |
| 32 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 33 | 0.0 | 1.000 | NO | 16 | 0.06543617230953264 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 35 | 0.0 | 0.000 | YES | 23 | 0.14697934326389073 |
| 36 | 1.0 | 0.000 | NO | 17 | 0.13930947463022816 |
| 37 | 1.0 | 1.000 | YES | 35 | 0.0611208030514103 |
| 38 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 39 | 0.0 | 0.000 | YES | 19 | 0.09746371473498008 |
| 40 | 0.0 | 0.000 | YES | 43 | 0.14989339130290658 |
| 41 | 0.0 | 1.000 | NO | 48 | 0.11543692789985638 |
| 42 | 1.0 | 1.000 | YES | 23 | 0.05979749507049687 |
| 43 | 1.0 | 1.000 | YES | 45 | 0.07410954616367815 |
| 44 | 0.0 | 0.000 | YES | 39 | 0.07910239024566247 |
| 45 | 0.0 | 1.000 | NO | 7 | 0.13351103141881365 |
| 46 | 1.0 | 1.000 | YES | 11 | 0.06604488035083318 |
| 47 | 1.0 | 1.000 | YES | 40 | 0.050656466500964496 |
| 48 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 49 | 0.0 | 0.000 | YES | 3 | 0.07781551615235924 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
