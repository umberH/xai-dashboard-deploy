# Detailed Explanation Report

**Dataset:** ag_news  
**Model:** naive_bayes_text  
**Explanation Method:** lime  
**Generated:** 2025-08-24 19:01:11  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8150
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0238
- **Max Feature Importance:** 0.3284

## Prediction Analysis

- **Correct Predictions:** 163 (81.5%)
- **Incorrect Predictions:** 37 (18.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 72 | 0.0587 | 36.0% |
| 1 | 72 | 0.0614 | 36.0% |
| 3 | 71 | 0.0623 | 35.5% |
| 2 | 69 | 0.0611 | 34.5% |
| 4 | 68 | 0.0630 | 34.0% |
| 11 | 28 | 0.0803 | 14.0% |
| 6 | 26 | 0.0790 | 13.0% |
| 9 | 24 | 0.0722 | 12.0% |
| 23 | 23 | 0.0691 | 11.5% |
| 7 | 23 | 0.0814 | 11.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.175', '0.344', '0.210', '0.271']
- **Top Features:**
  - Feature 15: 0.1924
  - Feature 23: 0.0685
  - Feature 8: 0.0630

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.075', '0.760', '0.088', '0.077']
- **Top Features:**
  - Feature 0: 0.0444
  - Feature 1: 0.0434
  - Feature 2: 0.0424

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.629', '0.106', '0.147', '0.119']
- **Top Features:**
  - Feature 0: 0.0513
  - Feature 1: 0.0499
  - Feature 2: 0.0486

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.108', '0.756', '0.074', '0.063']
- **Top Features:**
  - Feature 0: 0.0606
  - Feature 1: 0.0587
  - Feature 2: 0.0568

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.128', '0.509', '0.203', '0.160']
- **Top Features:**
  - Feature 7: 0.0948
  - Feature 33: 0.0845
  - Feature 3: 0.0721

### Incorrect Predictions (Sample)

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.061', '0.059', '0.098', '0.782']
- **Top Features:**
  - Feature 0: 0.0513
  - Feature 1: 0.0499
  - Feature 2: 0.0486

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.320', '0.282', '0.231', '0.167']
- **Top Features:**
  - Feature 7: 0.1286
  - Feature 11: 0.1264
  - Feature 5: 0.1231

#### Instance 22

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.217', '0.183', '0.243', '0.358']
- **Top Features:**
  - Feature 28: 0.1370
  - Feature 17: 0.1173
  - Feature 9: 0.0928

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 15 | 0.1923561093064054 |
| 1 | 1.0 | 1.000 | YES | 0 | 0.044444444444444446 |
| 2 | 0.0 | 0.000 | YES | 0 | 0.05128205128205128 |
| 3 | 1.0 | 1.000 | YES | 0 | 0.06060606060606061 |
| 4 | 1.0 | 1.000 | YES | 7 | 0.0948065333444031 |
| 5 | 1.0 | 1.000 | YES | 25 | 0.09726307079563401 |
| 6 | 2.0 | 3.000 | NO | 0 | 0.05128205128205128 |
| 7 | 1.0 | 0.000 | NO | 7 | 0.12859165978907228 |
| 8 | 0.0 | 0.000 | YES | 26 | 0.07228026486565804 |
| 9 | 3.0 | 3.000 | YES | 14 | 0.10913725109947858 |
| 10 | 3.0 | 3.000 | YES | 29 | 0.07382463934121133 |
| 11 | 3.0 | 3.000 | YES | 25 | 0.11611900303886154 |
| 12 | 1.0 | 1.000 | YES | 1 | 0.06539505461980441 |
| 13 | 2.0 | 2.000 | YES | 0 | 0.047619047619047616 |
| 14 | 3.0 | 3.000 | YES | 32 | 0.04924190139109577 |
| 15 | 3.0 | 3.000 | YES | 6 | 0.13637602769370705 |
| 16 | 2.0 | 2.000 | YES | 19 | 0.17038030367383294 |
| 17 | 0.0 | 0.000 | YES | 19 | 0.1302609043248688 |
| 18 | 1.0 | 1.000 | YES | 12 | 0.20451987431961932 |
| 19 | 2.0 | 2.000 | YES | 0 | 0.058823529411764705 |
| 20 | 1.0 | 1.000 | YES | 27 | 0.07188274430723911 |
| 21 | 2.0 | 2.000 | YES | 10 | 0.08782857095903004 |
| 22 | 2.0 | 3.000 | NO | 28 | 0.13700820794497073 |
| 23 | 3.0 | 3.000 | YES | 1 | 0.1263082141409185 |
| 24 | 0.0 | 0.000 | YES | 1 | 0.15715063177399638 |
| 25 | 2.0 | 3.000 | NO | 21 | 0.14587176895138523 |
| 26 | 0.0 | 0.000 | YES | 0 | 0.046511627906976744 |
| 27 | 2.0 | 2.000 | YES | 13 | 0.054692620309288204 |
| 28 | 3.0 | 3.000 | YES | 17 | 0.10204332124043923 |
| 29 | 2.0 | 2.000 | YES | 32 | 0.05846631587212995 |
| 30 | 3.0 | 3.000 | YES | 0 | 0.06985171490335293 |
| 31 | 0.0 | 0.000 | YES | 21 | 0.10333098074461369 |
| 32 | 2.0 | 3.000 | NO | 49 | 0.03782570416439091 |
| 33 | 3.0 | 3.000 | YES | 9 | 0.10072804082899417 |
| 34 | 0.0 | 1.000 | NO | 0 | 0.07407407407407407 |
| 35 | 1.0 | 1.000 | YES | 33 | 0.07424301322576299 |
| 36 | 3.0 | 3.000 | YES | 0 | 0.10834187822222147 |
| 37 | 2.0 | 2.000 | YES | 28 | 0.07308693310644696 |
| 38 | 3.0 | 3.000 | YES | 10 | 0.17857037504603915 |
| 39 | 3.0 | 0.000 | NO | 21 | 0.10342876846091288 |
| 40 | 2.0 | 2.000 | YES | 24 | 0.09433675741701562 |
| 41 | 2.0 | 2.000 | YES | 7 | 0.09751086077094534 |
| 42 | 2.0 | 2.000 | YES | 3 | 0.07336165385254932 |
| 43 | 2.0 | 2.000 | YES | 16 | 0.05410879463733569 |
| 44 | 2.0 | 2.000 | YES | 0 | 0.05263157894736842 |
| 45 | 1.0 | 1.000 | YES | 8 | 0.07806279478045602 |
| 46 | 2.0 | 2.000 | YES | 0 | 0.0425531914893617 |
| 47 | 1.0 | 1.000 | YES | 33 | 0.09861415387786832 |
| 48 | 1.0 | 1.000 | YES | 0 | 0.05555555555555555 |
| 49 | 0.0 | 0.000 | YES | 11 | 0.11427994083517969 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
