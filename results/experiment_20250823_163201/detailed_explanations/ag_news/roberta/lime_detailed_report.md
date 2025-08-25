# Detailed Explanation Report

**Dataset:** ag_news  
**Model:** roberta  
**Explanation Method:** lime  
**Generated:** 2025-08-24 17:42:56  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.9000
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0220
- **Max Feature Importance:** 0.3659

## Prediction Analysis

- **Correct Predictions:** 180 (90.0%)
- **Incorrect Predictions:** 20 (10.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 0 | 101 | 0.0604 | 50.5% |
| 1 | 96 | 0.0566 | 48.0% |
| 3 | 91 | 0.0537 | 45.5% |
| 2 | 89 | 0.0538 | 44.5% |
| 4 | 83 | 0.0527 | 41.5% |
| 11 | 33 | 0.0744 | 16.5% |
| 7 | 26 | 0.0737 | 13.0% |
| 8 | 24 | 0.0676 | 12.0% |
| 19 | 22 | 0.0665 | 11.0% |
| 5 | 22 | 0.0735 | 11.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.050', '0.942', '0.003', '0.005']
- **Top Features:**
  - Feature 12: 0.0802
  - Feature 29: 0.0796
  - Feature 19: 0.0639

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.004', '0.992', '0.002', '0.002']
- **Top Features:**
  - Feature 0: 0.0444
  - Feature 1: 0.0434
  - Feature 2: 0.0424

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.991', '0.003', '0.003', '0.003']
- **Top Features:**
  - Feature 0: 0.0513
  - Feature 1: 0.0499
  - Feature 2: 0.0486

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.005', '0.992', '0.002', '0.002']
- **Top Features:**
  - Feature 0: 0.0606
  - Feature 1: 0.0587
  - Feature 2: 0.0568

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.003', '0.993', '0.002', '0.002']
- **Top Features:**
  - Feature 30: 0.0508
  - Feature 0: 0.0500
  - Feature 1: 0.0483

### Incorrect Predictions (Sample)

#### Instance 6

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.002', '0.002', '0.009', '0.987']
- **Top Features:**
  - Feature 23: 0.0607
  - Feature 27: 0.0556
  - Feature 2: 0.0536

#### Instance 22

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.037', '0.027', '0.236', '0.700']
- **Top Features:**
  - Feature 3: 0.1039
  - Feature 6: 0.0975
  - Feature 10: 0.0892

#### Instance 32

- **True Label:** 2.0
- **Prediction:** 3.0
- **Prediction Probabilities:** ['0.003', '0.002', '0.045', '0.949']
- **Top Features:**
  - Feature 0: 0.0689
  - Feature 21: 0.0592
  - Feature 28: 0.0520

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 1.0 | 1.000 | YES | 12 | 0.0802136966721728 |
| 1 | 1.0 | 1.000 | YES | 0 | 0.044444444444444446 |
| 2 | 0.0 | 0.000 | YES | 0 | 0.05128205128205128 |
| 3 | 1.0 | 1.000 | YES | 0 | 0.06060606060606061 |
| 4 | 1.0 | 1.000 | YES | 30 | 0.050780658555330885 |
| 5 | 1.0 | 1.000 | YES | 0 | 0.05405405405405406 |
| 6 | 2.0 | 3.000 | NO | 23 | 0.06072411675676111 |
| 7 | 1.0 | 1.000 | YES | 29 | 0.1081954106771367 |
| 8 | 0.0 | 0.000 | YES | 0 | 0.1612805567136888 |
| 9 | 3.0 | 3.000 | YES | 14 | 0.05442290570545018 |
| 10 | 3.0 | 3.000 | YES | 0 | 0.04878048780487805 |
| 11 | 3.0 | 3.000 | YES | 3 | 0.06711174543051603 |
| 12 | 1.0 | 1.000 | YES | 31 | 0.06692396445933571 |
| 13 | 2.0 | 2.000 | YES | 0 | 0.047619047619047616 |
| 14 | 3.0 | 3.000 | YES | 16 | 0.0774639063800639 |
| 15 | 3.0 | 3.000 | YES | 25 | 0.07774611017885044 |
| 16 | 2.0 | 2.000 | YES | 22 | 0.11076733068876328 |
| 17 | 0.0 | 0.000 | YES | 0 | 0.06531695342451224 |
| 18 | 1.0 | 1.000 | YES | 0 | 0.06451612903225806 |
| 19 | 2.0 | 2.000 | YES | 0 | 0.058823529411764705 |
| 20 | 1.0 | 1.000 | YES | 24 | 0.06140189608840913 |
| 21 | 2.0 | 2.000 | YES | 0 | 0.04081632653061224 |
| 22 | 2.0 | 3.000 | NO | 3 | 0.10392391029925775 |
| 23 | 3.0 | 3.000 | YES | 15 | 0.1123746720937595 |
| 24 | 0.0 | 0.000 | YES | 13 | 0.1889370807647046 |
| 25 | 2.0 | 2.000 | YES | 26 | 0.08252726926463008 |
| 26 | 0.0 | 0.000 | YES | 10 | 0.05370224662074398 |
| 27 | 2.0 | 2.000 | YES | 19 | 0.043270650989396725 |
| 28 | 3.0 | 3.000 | YES | 1 | 0.09901718862119531 |
| 29 | 2.0 | 2.000 | YES | 0 | 0.04081632653061224 |
| 30 | 3.0 | 3.000 | YES | 24 | 0.10359976126764348 |
| 31 | 0.0 | 0.000 | YES | 20 | 0.06447412300635566 |
| 32 | 2.0 | 3.000 | NO | 0 | 0.0688862966165161 |
| 33 | 3.0 | 3.000 | YES | 8 | 0.06971475243562437 |
| 34 | 0.0 | 1.000 | NO | 20 | 0.06529308023889979 |
| 35 | 1.0 | 1.000 | YES | 0 | 0.05263157894736842 |
| 36 | 3.0 | 3.000 | YES | 24 | 0.06953223886325119 |
| 37 | 2.0 | 2.000 | YES | 0 | 0.0625 |
| 38 | 3.0 | 3.000 | YES | 15 | 0.07651643380399743 |
| 39 | 3.0 | 0.000 | NO | 13 | 0.2550089301379964 |
| 40 | 2.0 | 2.000 | YES | 15 | 0.07797122246809739 |
| 41 | 2.0 | 2.000 | YES | 40 | 0.07491999617218405 |
| 42 | 2.0 | 2.000 | YES | 28 | 0.08023625469777657 |
| 43 | 2.0 | 2.000 | YES | 0 | 0.047619047619047616 |
| 44 | 2.0 | 2.000 | YES | 0 | 0.05263157894736842 |
| 45 | 1.0 | 1.000 | YES | 0 | 0.04878048780487805 |
| 46 | 2.0 | 2.000 | YES | 35 | 0.06657638729943718 |
| 47 | 1.0 | 1.000 | YES | 9 | 0.0672596678733008 |
| 48 | 1.0 | 1.000 | YES | 0 | 0.05555555555555555 |
| 49 | 0.0 | 1.000 | NO | 34 | 0.06860596698293116 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
