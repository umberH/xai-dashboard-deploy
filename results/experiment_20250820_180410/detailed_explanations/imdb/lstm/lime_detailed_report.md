# Detailed Explanation Report

**Dataset:** imdb  
**Model:** lstm  
**Explanation Method:** lime  
**Generated:** 2025-08-20 18:45:57  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8150
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0235
- **Max Feature Importance:** 0.5270

## Prediction Analysis

- **Correct Predictions:** 163 (81.5%)
- **Incorrect Predictions:** 37 (18.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 2 | 37 | 0.0558 | 18.5% |
| 4 | 35 | 0.0661 | 17.5% |
| 1 | 34 | 0.0624 | 17.0% |
| 3 | 30 | 0.0701 | 15.0% |
| 7 | 30 | 0.0686 | 15.0% |
| 13 | 28 | 0.0687 | 14.0% |
| 20 | 27 | 0.0675 | 13.5% |
| 15 | 27 | 0.0706 | 13.5% |
| 8 | 26 | 0.0721 | 13.0% |
| 0 | 25 | 0.0486 | 12.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.781', '0.219']
- **Top Features:**
  - Feature 38: 0.0634
  - Feature 12: 0.0617
  - Feature 43: 0.0479

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.356', '0.644']
- **Top Features:**
  - Feature 23: 0.0525
  - Feature 20: 0.0513
  - Feature 25: 0.0508

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.397', '0.603']
- **Top Features:**
  - Feature 43: 0.0786
  - Feature 35: 0.0615
  - Feature 38: 0.0566

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
  - Feature 44: 0.0980
  - Feature 48: 0.0671
  - Feature 3: 0.0613

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.503', '0.497']
- **Top Features:**
  - Feature 23: 0.1283
  - Feature 4: 0.0707
  - Feature 35: 0.0694

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.413', '0.587']
- **Top Features:**
  - Feature 46: 0.0927
  - Feature 2: 0.0889
  - Feature 5: 0.0768

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.656', '0.344']
- **Top Features:**
  - Feature 5: 0.0675
  - Feature 49: 0.0638
  - Feature 16: 0.0545

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 38 | 0.0634050608482252 |
| 1 | 1.0 | 1.000 | YES | 23 | 0.05250740976739328 |
| 2 | 1.0 | 0.000 | NO | 23 | 0.12831493269564573 |
| 3 | 1.0 | 1.000 | YES | 43 | 0.07858847989903453 |
| 4 | 1.0 | 1.000 | YES | 0 | 0.044444444444444446 |
| 5 | 1.0 | 1.000 | YES | 44 | 0.09795827785354554 |
| 6 | 1.0 | 1.000 | YES | 48 | 0.04156344021665004 |
| 7 | 0.0 | 1.000 | NO | 46 | 0.09273724205425761 |
| 8 | 1.0 | 0.000 | NO | 5 | 0.06754590620282284 |
| 9 | 1.0 | 1.000 | YES | 13 | 0.05499269835859907 |
| 10 | 0.0 | 0.000 | YES | 30 | 0.12935515554541055 |
| 11 | 0.0 | 1.000 | NO | 9 | 0.20140046727483774 |
| 12 | 1.0 | 1.000 | YES | 20 | 0.13816962356765272 |
| 13 | 1.0 | 1.000 | YES | 43 | 0.08385000940121558 |
| 14 | 0.0 | 0.000 | YES | 28 | 0.04838645282804473 |
| 15 | 0.0 | 0.000 | YES | 28 | 0.09313802906495922 |
| 16 | 1.0 | 1.000 | YES | 21 | 0.2878346475053904 |
| 17 | 0.0 | 1.000 | NO | 15 | 0.057657721185944234 |
| 18 | 1.0 | 1.000 | YES | 29 | 0.22011627656980454 |
| 19 | 0.0 | 1.000 | NO | 16 | 0.14269336674649713 |
| 20 | 1.0 | 1.000 | YES | 3 | 0.36462886907198677 |
| 21 | 0.0 | 0.000 | YES | 38 | 0.10271590627422365 |
| 22 | 1.0 | 1.000 | YES | 15 | 0.09148956709240481 |
| 23 | 1.0 | 0.000 | NO | 15 | 0.10571932749539917 |
| 24 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 25 | 1.0 | 1.000 | YES | 22 | 0.0883301023735891 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 27 | 0.0 | 0.000 | YES | 30 | 0.08715822244545715 |
| 28 | 0.0 | 1.000 | NO | 6 | 0.05608863889968293 |
| 29 | 1.0 | 1.000 | YES | 4 | 0.15404399357740525 |
| 30 | 0.0 | 0.000 | YES | 7 | 0.047482373544127786 |
| 31 | 0.0 | 0.000 | YES | 17 | 0.20795410641868572 |
| 32 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 33 | 0.0 | 1.000 | NO | 23 | 0.12427933155443781 |
| 34 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 35 | 0.0 | 0.000 | YES | 23 | 0.15094394116448936 |
| 36 | 1.0 | 1.000 | YES | 19 | 0.14483132459395748 |
| 37 | 1.0 | 1.000 | YES | 33 | 0.10249327881297254 |
| 38 | 1.0 | 1.000 | YES | 38 | 0.10843438409210725 |
| 39 | 0.0 | 0.000 | YES | 24 | 0.17641493458813984 |
| 40 | 0.0 | 0.000 | YES | 43 | 0.24853087455971304 |
| 41 | 0.0 | 1.000 | NO | 17 | 0.12601381041154627 |
| 42 | 1.0 | 1.000 | YES | 33 | 0.07358497558676076 |
| 43 | 1.0 | 1.000 | YES | 22 | 0.08559085585313224 |
| 44 | 0.0 | 0.000 | YES | 23 | 0.05776008895027343 |
| 45 | 0.0 | 0.000 | YES | 34 | 0.09547267307698147 |
| 46 | 1.0 | 1.000 | YES | 25 | 0.12701726421424145 |
| 47 | 1.0 | 1.000 | YES | 43 | 0.13469036534235374 |
| 48 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 49 | 0.0 | 0.000 | YES | 9 | 0.13266357470492016 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
