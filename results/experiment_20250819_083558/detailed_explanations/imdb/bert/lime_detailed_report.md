# Detailed Explanation Report

**Dataset:** imdb  
**Model:** bert  
**Explanation Method:** lime  
**Generated:** 2025-08-19 10:04:57  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8100
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0210
- **Max Feature Importance:** 0.3046

## Prediction Analysis

- **Correct Predictions:** 162 (81.0%)
- **Incorrect Predictions:** 38 (19.0%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 4 | 51 | 0.0618 | 25.5% |
| 1 | 46 | 0.0540 | 23.0% |
| 3 | 43 | 0.0574 | 21.5% |
| 0 | 36 | 0.0537 | 18.0% |
| 2 | 35 | 0.0523 | 17.5% |
| 8 | 27 | 0.0684 | 13.5% |
| 15 | 27 | 0.0631 | 13.5% |
| 12 | 27 | 0.0750 | 13.5% |
| 13 | 24 | 0.0774 | 12.0% |
| 43 | 23 | 0.0740 | 11.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.753', '0.247']
- **Top Features:**
  - Feature 4: 0.0794
  - Feature 39: 0.0762
  - Feature 21: 0.0519

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
  - Feature 43: 0.0904
  - Feature 6: 0.0605
  - Feature 30: 0.0602

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
  - Feature 48: 0.0709
  - Feature 35: 0.0622
  - Feature 3: 0.0562

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.510', '0.490']
- **Top Features:**
  - Feature 23: 0.1204
  - Feature 4: 0.1079
  - Feature 35: 0.0611

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.405', '0.595']
- **Top Features:**
  - Feature 0: 0.0392
  - Feature 1: 0.0384
  - Feature 2: 0.0376

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.656', '0.344']
- **Top Features:**
  - Feature 49: 0.1693
  - Feature 7: 0.1553
  - Feature 1: 0.0573

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 4 | 0.0794252431796376 |
| 1 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 2 | 1.0 | 0.000 | NO | 23 | 0.12037303821534598 |
| 3 | 1.0 | 1.000 | YES | 43 | 0.09037785789093866 |
| 4 | 1.0 | 1.000 | YES | 0 | 0.044444444444444446 |
| 5 | 1.0 | 1.000 | YES | 48 | 0.07089544944877611 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 7 | 0.0 | 1.000 | NO | 0 | 0.0392156862745098 |
| 8 | 1.0 | 0.000 | NO | 49 | 0.16931112284036098 |
| 9 | 1.0 | 1.000 | YES | 0 | 0.053688711779573586 |
| 10 | 0.0 | 0.000 | YES | 30 | 0.10965199465413841 |
| 11 | 0.0 | 0.000 | YES | 46 | 0.1585960334472001 |
| 12 | 1.0 | 1.000 | YES | 20 | 0.06670116322254645 |
| 13 | 1.0 | 1.000 | YES | 3 | 0.1122131072346523 |
| 14 | 0.0 | 0.000 | YES | 21 | 0.062368039940030984 |
| 15 | 0.0 | 0.000 | YES | 23 | 0.08920759880339824 |
| 16 | 1.0 | 1.000 | YES | 21 | 0.12840398852010715 |
| 17 | 0.0 | 1.000 | NO | 1 | 0.04647924075045089 |
| 18 | 1.0 | 1.000 | YES | 26 | 0.13628932256880366 |
| 19 | 0.0 | 1.000 | NO | 16 | 0.10435570680925928 |
| 20 | 1.0 | 1.000 | YES | 3 | 0.1659672607832377 |
| 21 | 0.0 | 0.000 | YES | 9 | 0.03821082998771225 |
| 22 | 1.0 | 1.000 | YES | 23 | 0.08955399638788186 |
| 23 | 1.0 | 1.000 | YES | 20 | 0.07339970034699492 |
| 24 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 25 | 1.0 | 1.000 | YES | 22 | 0.08935192093924789 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 27 | 0.0 | 0.000 | YES | 8 | 0.11751995125532132 |
| 28 | 0.0 | 1.000 | NO | 0 | 0.0392156862745098 |
| 29 | 1.0 | 1.000 | YES | 24 | 0.08865327182731791 |
| 30 | 0.0 | 0.000 | YES | 34 | 0.07956018008743466 |
| 31 | 0.0 | 0.000 | YES | 17 | 0.30459948175538654 |
| 32 | 0.0 | 0.000 | YES | 7 | 0.04540411739750857 |
| 33 | 0.0 | 1.000 | NO | 16 | 0.13270230518356632 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 35 | 0.0 | 0.000 | YES | 23 | 0.1631476331330548 |
| 36 | 1.0 | 1.000 | YES | 17 | 0.10330499023821965 |
| 37 | 1.0 | 1.000 | YES | 20 | 0.045808779582105025 |
| 38 | 1.0 | 1.000 | YES | 41 | 0.0722473595828021 |
| 39 | 0.0 | 0.000 | YES | 36 | 0.06608453887444776 |
| 40 | 0.0 | 0.000 | YES | 43 | 0.13263595497666358 |
| 41 | 0.0 | 1.000 | NO | 48 | 0.1778301367859507 |
| 42 | 1.0 | 1.000 | YES | 45 | 0.11535916703964469 |
| 43 | 1.0 | 1.000 | YES | 47 | 0.05818178662872248 |
| 44 | 0.0 | 0.000 | YES | 39 | 0.09312568679957695 |
| 45 | 0.0 | 0.000 | YES | 34 | 0.11326983355744777 |
| 46 | 1.0 | 1.000 | YES | 25 | 0.08853613100753868 |
| 47 | 1.0 | 1.000 | YES | 33 | 0.08755143468880297 |
| 48 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 49 | 0.0 | 0.000 | YES | 9 | 0.06712048762571157 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
