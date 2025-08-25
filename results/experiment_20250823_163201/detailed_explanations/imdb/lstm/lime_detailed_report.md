# Detailed Explanation Report

**Dataset:** imdb  
**Model:** lstm  
**Explanation Method:** lime  
**Generated:** 2025-08-23 19:06:01  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8150
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0233
- **Max Feature Importance:** 0.5357

## Prediction Analysis

- **Correct Predictions:** 163 (81.5%)
- **Incorrect Predictions:** 37 (18.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 4 | 42 | 0.0642 | 21.0% |
| 1 | 35 | 0.0622 | 17.5% |
| 2 | 34 | 0.0578 | 17.0% |
| 3 | 32 | 0.0658 | 16.0% |
| 13 | 29 | 0.0708 | 14.5% |
| 17 | 28 | 0.0716 | 14.0% |
| 0 | 27 | 0.0497 | 13.5% |
| 7 | 26 | 0.0712 | 13.0% |
| 12 | 25 | 0.0697 | 12.5% |
| 43 | 25 | 0.0804 | 12.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.781', '0.219']
- **Top Features:**
  - Feature 0: 0.0392
  - Feature 1: 0.0384
  - Feature 2: 0.0376

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.356', '0.644']
- **Top Features:**
  - Feature 0: 0.0399
  - Feature 25: 0.0398
  - Feature 12: 0.0360

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.397', '0.603']
- **Top Features:**
  - Feature 43: 0.0558
  - Feature 27: 0.0529
  - Feature 30: 0.0520

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.323', '0.677']
- **Top Features:**
  - Feature 0: 0.0444
  - Feature 1: 0.0434
  - Feature 2: 0.0424

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.341', '0.659']
- **Top Features:**
  - Feature 44: 0.0877
  - Feature 3: 0.0872
  - Feature 48: 0.0849

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.503', '0.497']
- **Top Features:**
  - Feature 23: 0.1563
  - Feature 35: 0.0893
  - Feature 1: 0.0665

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.413', '0.587']
- **Top Features:**
  - Feature 46: 0.0910
  - Feature 37: 0.0711
  - Feature 5: 0.0635

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.656', '0.344']
- **Top Features:**
  - Feature 49: 0.0691
  - Feature 5: 0.0573
  - Feature 17: 0.0521

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 1 | 1.0 | 1.000 | YES | 0 | 0.03994173705367393 |
| 2 | 1.0 | 0.000 | NO | 23 | 0.156343187966859 |
| 3 | 1.0 | 1.000 | YES | 43 | 0.0558069644883831 |
| 4 | 1.0 | 1.000 | YES | 0 | 0.044444444444444446 |
| 5 | 1.0 | 1.000 | YES | 44 | 0.08765486140407593 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 7 | 0.0 | 1.000 | NO | 46 | 0.09101431681317922 |
| 8 | 1.0 | 0.000 | NO | 49 | 0.06909431207377714 |
| 9 | 1.0 | 1.000 | YES | 38 | 0.06107489586107698 |
| 10 | 0.0 | 0.000 | YES | 30 | 0.12853105094400732 |
| 11 | 0.0 | 1.000 | NO | 9 | 0.1970082079087752 |
| 12 | 1.0 | 1.000 | YES | 44 | 0.12223423988902594 |
| 13 | 1.0 | 1.000 | YES | 43 | 0.11132466137755506 |
| 14 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 15 | 0.0 | 0.000 | YES | 28 | 0.10514904299249206 |
| 16 | 1.0 | 1.000 | YES | 21 | 0.2928396615673735 |
| 17 | 0.0 | 1.000 | NO | 10 | 0.06065823466490426 |
| 18 | 1.0 | 1.000 | YES | 29 | 0.22098493386582255 |
| 19 | 0.0 | 1.000 | NO | 16 | 0.12828879323401135 |
| 20 | 1.0 | 1.000 | YES | 3 | 0.33866497538478935 |
| 21 | 0.0 | 0.000 | YES | 38 | 0.09546794599699397 |
| 22 | 1.0 | 1.000 | YES | 15 | 0.10034377996742859 |
| 23 | 1.0 | 0.000 | NO | 15 | 0.10350835666733373 |
| 24 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 25 | 1.0 | 1.000 | YES | 49 | 0.1079377493114224 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 27 | 0.0 | 0.000 | YES | 30 | 0.08810863937692065 |
| 28 | 0.0 | 1.000 | NO | 29 | 0.07519077109502847 |
| 29 | 1.0 | 1.000 | YES | 4 | 0.15553832585598437 |
| 30 | 0.0 | 0.000 | YES | 30 | 0.04638371321587289 |
| 31 | 0.0 | 0.000 | YES | 17 | 0.20220587722152872 |
| 32 | 0.0 | 0.000 | YES | 23 | 0.03846095957596002 |
| 33 | 0.0 | 1.000 | NO | 23 | 0.1259825293905539 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 35 | 0.0 | 0.000 | YES | 23 | 0.159017558596055 |
| 36 | 1.0 | 1.000 | YES | 17 | 0.14414459838090063 |
| 37 | 1.0 | 1.000 | YES | 33 | 0.07847869679004577 |
| 38 | 1.0 | 1.000 | YES | 17 | 0.10183325097733134 |
| 39 | 0.0 | 0.000 | YES | 24 | 0.1604031234791046 |
| 40 | 0.0 | 0.000 | YES | 43 | 0.24649066090620106 |
| 41 | 0.0 | 1.000 | NO | 48 | 0.15037186835373406 |
| 42 | 1.0 | 1.000 | YES | 23 | 0.060936876449307564 |
| 43 | 1.0 | 1.000 | YES | 22 | 0.0704729980312148 |
| 44 | 0.0 | 0.000 | YES | 23 | 0.06156802930351146 |
| 45 | 0.0 | 0.000 | YES | 34 | 0.09350646261643615 |
| 46 | 1.0 | 1.000 | YES | 6 | 0.15048291563043573 |
| 47 | 1.0 | 1.000 | YES | 43 | 0.12284601482986209 |
| 48 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 49 | 0.0 | 0.000 | YES | 2 | 0.10810545145928069 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
