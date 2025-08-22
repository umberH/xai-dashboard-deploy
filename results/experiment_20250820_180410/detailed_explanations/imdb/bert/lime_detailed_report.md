# Detailed Explanation Report

**Dataset:** imdb  
**Model:** bert  
**Explanation Method:** lime  
**Generated:** 2025-08-20 18:44:46  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8100
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0214
- **Max Feature Importance:** 0.3618

## Prediction Analysis

- **Correct Predictions:** 162 (81.0%)
- **Incorrect Predictions:** 38 (19.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 4 | 53 | 0.0622 | 26.5% |
| 1 | 50 | 0.0536 | 25.0% |
| 2 | 47 | 0.0498 | 23.5% |
| 3 | 42 | 0.0573 | 21.0% |
| 0 | 39 | 0.0496 | 19.5% |
| 38 | 24 | 0.0612 | 12.0% |
| 13 | 24 | 0.0813 | 12.0% |
| 8 | 23 | 0.0720 | 11.5% |
| 18 | 23 | 0.0526 | 11.5% |
| 39 | 22 | 0.0714 | 11.0% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.753', '0.247']
- **Top Features:**
  - Feature 39: 0.1217
  - Feature 4: 0.0741
  - Feature 35: 0.0638

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.320', '0.680']
- **Top Features:**
  - Feature 0: 0.0392
  - Feature 1: 0.0384
  - Feature 2: 0.0376

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.350', '0.650']
- **Top Features:**
  - Feature 43: 0.0849
  - Feature 1: 0.0845
  - Feature 30: 0.0730

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.259', '0.741']
- **Top Features:**
  - Feature 0: 0.0444
  - Feature 1: 0.0434
  - Feature 2: 0.0424

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.371', '0.629']
- **Top Features:**
  - Feature 48: 0.0774
  - Feature 47: 0.0727
  - Feature 20: 0.0564

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.510', '0.490']
- **Top Features:**
  - Feature 4: 0.1035
  - Feature 23: 0.0980
  - Feature 46: 0.0481

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.405', '0.595']
- **Top Features:**
  - Feature 38: 0.0518
  - Feature 37: 0.0517
  - Feature 42: 0.0437

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.656', '0.344']
- **Top Features:**
  - Feature 7: 0.1477
  - Feature 49: 0.1359
  - Feature 1: 0.0487

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 39 | 0.1216810457778469 |
| 1 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 2 | 1.0 | 0.000 | NO | 4 | 0.10346410617243715 |
| 3 | 1.0 | 1.000 | YES | 43 | 0.08485467691009857 |
| 4 | 1.0 | 1.000 | YES | 0 | 0.044444444444444446 |
| 5 | 1.0 | 1.000 | YES | 48 | 0.07737701515378227 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 7 | 0.0 | 1.000 | NO | 38 | 0.051815407042236264 |
| 8 | 1.0 | 0.000 | NO | 7 | 0.14765956915985118 |
| 9 | 1.0 | 1.000 | YES | 2 | 0.04577771724185279 |
| 10 | 0.0 | 0.000 | YES | 30 | 0.10922681611246962 |
| 11 | 0.0 | 0.000 | YES | 46 | 0.19091135492494393 |
| 12 | 1.0 | 1.000 | YES | 44 | 0.05922627918541454 |
| 13 | 1.0 | 1.000 | YES | 3 | 0.1324214369814439 |
| 14 | 0.0 | 0.000 | YES | 43 | 0.07960634903793895 |
| 15 | 0.0 | 0.000 | YES | 23 | 0.11167414953599637 |
| 16 | 1.0 | 1.000 | YES | 21 | 0.11565660001689833 |
| 17 | 0.0 | 1.000 | NO | 0 | 0.0392156862745098 |
| 18 | 1.0 | 1.000 | YES | 26 | 0.1587568195023725 |
| 19 | 0.0 | 1.000 | NO | 3 | 0.09321379849696239 |
| 20 | 1.0 | 1.000 | YES | 3 | 0.2036829063494492 |
| 21 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 22 | 1.0 | 1.000 | YES | 37 | 0.07135414817517305 |
| 23 | 1.0 | 1.000 | YES | 7 | 0.07347788527090765 |
| 24 | 0.0 | 0.000 | YES | 32 | 0.04352849037358868 |
| 25 | 1.0 | 1.000 | YES | 7 | 0.10496781707232847 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 27 | 0.0 | 0.000 | YES | 8 | 0.10827809055298647 |
| 28 | 0.0 | 1.000 | NO | 0 | 0.0392156862745098 |
| 29 | 1.0 | 1.000 | YES | 14 | 0.09434155953383143 |
| 30 | 0.0 | 0.000 | YES | 27 | 0.07528626733922694 |
| 31 | 0.0 | 0.000 | YES | 17 | 0.36181302160240547 |
| 32 | 0.0 | 0.000 | YES | 4 | 0.057071314568845524 |
| 33 | 0.0 | 1.000 | NO | 16 | 0.11696112188642242 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 35 | 0.0 | 0.000 | YES | 23 | 0.20320050409122317 |
| 36 | 1.0 | 1.000 | YES | 17 | 0.13661121645217902 |
| 37 | 1.0 | 1.000 | YES | 15 | 0.059613531597068066 |
| 38 | 1.0 | 1.000 | YES | 38 | 0.08839222023547372 |
| 39 | 0.0 | 0.000 | YES | 24 | 0.07938701915369781 |
| 40 | 0.0 | 0.000 | YES | 43 | 0.1687479939254161 |
| 41 | 0.0 | 1.000 | NO | 48 | 0.16721513518395112 |
| 42 | 1.0 | 1.000 | YES | 45 | 0.09084058216734825 |
| 43 | 1.0 | 1.000 | YES | 45 | 0.06062568666592952 |
| 44 | 0.0 | 0.000 | YES | 39 | 0.10893001167231908 |
| 45 | 0.0 | 0.000 | YES | 34 | 0.11289736024243155 |
| 46 | 1.0 | 1.000 | YES | 25 | 0.08765912762728405 |
| 47 | 1.0 | 1.000 | YES | 41 | 0.07689266705141867 |
| 48 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 49 | 0.0 | 0.000 | YES | 22 | 0.06457597295681686 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
