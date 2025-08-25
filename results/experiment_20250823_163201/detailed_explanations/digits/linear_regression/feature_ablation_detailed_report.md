# Detailed Explanation Report

**Dataset:** digits  
**Model:** linear_regression  
**Explanation Method:** feature_ablation  
**Generated:** 2025-08-23 18:53:39  

## Summary Statistics

- **Total Instances:** 360
- **Valid Explanations:** 360
- **Errors:** 0
- **Model Accuracy:** 0.2417
- **Average Feature Importance:** 0.1842
- **Feature Importance Std:** 0.2613
- **Max Feature Importance:** 3.4612

## Prediction Analysis

- **Correct Predictions:** 87 (24.2%)
- **Incorrect Predictions:** 273 (75.8%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 52 | 267 | 1.2473 | 74.2% |
| 35 | 251 | 0.9324 | 69.7% |
| 44 | 193 | 0.7664 | 53.6% |
| 13 | 148 | 0.6953 | 41.1% |
| 29 | 142 | 0.6904 | 39.4% |
| 10 | 106 | 0.7759 | 29.4% |
| 27 | 88 | 0.6495 | 24.4% |
| 18 | 77 | 0.7373 | 21.4% |
| 54 | 74 | 0.9651 | 20.6% |
| 61 | 68 | 0.6077 | 18.9% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 9

- **True Label:** 5.0
- **Prediction:** 5.26569554436196
- **Prediction Probabilities:** ['5.266']
- **Top Features:**
  - Feature 44: 0.8553
  - Feature 29: 0.6899
  - Feature 6: 0.6275

#### Instance 12

- **True Label:** 9.0
- **Prediction:** 9.071233027754028
- **Prediction Probabilities:** ['9.071']
- **Top Features:**
  - Feature 29: 0.7667
  - Feature 14: 0.7214
  - Feature 52: 0.7150

#### Instance 18

- **True Label:** 9.0
- **Prediction:** 9.197009382487266
- **Prediction Probabilities:** ['9.197']
- **Top Features:**
  - Feature 14: 1.1675
  - Feature 10: 1.0479
  - Feature 52: 0.9224

#### Instance 30

- **True Label:** 6.0
- **Prediction:** 6.101614175230673
- **Prediction Probabilities:** ['6.102']
- **Top Features:**
  - Feature 52: 1.1297
  - Feature 54: 0.8978
  - Feature 35: 0.7662

#### Instance 33

- **True Label:** 6.0
- **Prediction:** 6.029276218170434
- **Prediction Probabilities:** ['6.029']
- **Top Features:**
  - Feature 52: 1.9590
  - Feature 10: 1.0479
  - Feature 54: 1.0060

### Incorrect Predictions (Sample)

#### Instance 0

- **True Label:** 5.0
- **Prediction:** 8.119061342909566
- **Prediction Probabilities:** ['8.119']
- **Top Features:**
  - Feature 52: 1.5444
  - Feature 35: 1.1787
  - Feature 44: 0.8009

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 4.1780723389942915
- **Prediction Probabilities:** ['4.178']
- **Top Features:**
  - Feature 52: 1.3582
  - Feature 54: 1.3309
  - Feature 35: 0.7662

#### Instance 2

- **True Label:** 8.0
- **Prediction:** 5.096404556107999
- **Prediction Probabilities:** ['5.096']
- **Top Features:**
  - Feature 44: 0.7518
  - Feature 52: 0.7363
  - Feature 27: 0.5839

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 5.0 | 8.119 | NO | 52 | 1.5443523974586313 |
| 1 | 2.0 | 4.178 | NO | 52 | 1.3582336948501075 |
| 2 | 8.0 | 5.096 | NO | 44 | 0.7518145709332797 |
| 3 | 1.0 | 5.720 | NO | 52 | 1.7516799754806844 |
| 4 | 7.0 | 5.972 | NO | 52 | 1.9590075535027367 |
| 5 | 2.0 | 2.549 | NO | 52 | 1.3582336948501084 |
| 6 | 6.0 | 5.393 | NO | 54 | 0.8977558621234234 |
| 7 | 2.0 | 3.027 | NO | 52 | 1.3582336948501084 |
| 8 | 6.0 | 5.393 | NO | 54 | 1.114338616068081 |
| 9 | 5.0 | 5.266 | YES | 44 | 0.8553268386760333 |
| 10 | 0.0 | -0.612 | NO | 52 | 1.3582336948501084 |
| 11 | 5.0 | 6.276 | NO | 52 | 1.3582336948501075 |
| 12 | 9.0 | 9.071 | YES | 29 | 0.7667177230999709 |
| 13 | 3.0 | 7.123 | NO | 52 | 1.7516799754806849 |
| 14 | 4.0 | 4.675 | NO | 10 | 1.0479256752226682 |
| 15 | 4.0 | 5.385 | NO | 25 | 1.5172554061212935 |
| 16 | 2.0 | 2.792 | NO | 35 | 0.7896957774393822 |
| 17 | 4.0 | 5.703 | NO | 52 | 1.3582336948501075 |
| 18 | 9.0 | 9.197 | YES | 14 | 1.167458188562815 |
| 19 | 9.0 | 3.881 | NO | 35 | 1.1786786952343058 |
| 20 | 6.0 | 5.384 | NO | 52 | 1.1296972414145259 |
| 21 | 3.0 | 1.133 | NO | 18 | 0.8154021379058642 |
| 22 | 8.0 | 8.720 | NO | 52 | 1.9590075535027367 |
| 23 | 1.0 | 3.676 | NO | 35 | 0.8958968663386222 |
| 24 | 2.0 | 3.530 | NO | 52 | 1.1296972414145263 |
| 25 | 5.0 | 6.537 | NO | 44 | 0.8008694452080309 |
| 26 | 6.0 | 3.489 | NO | 52 | 0.9435785388060021 |
| 27 | 0.0 | 0.589 | NO | 35 | 1.1786786952343058 |
| 28 | 3.0 | 5.078 | NO | 54 | 1.114338616068081 |
| 29 | 4.0 | 4.936 | NO | 33 | 1.1845588205431987 |
| 30 | 6.0 | 6.102 | YES | 52 | 1.1296972414145259 |
| 31 | 7.0 | 6.120 | NO | 52 | 1.5443523974586322 |
| 32 | 2.0 | 3.080 | NO | 27 | 0.7172848400287575 |
| 33 | 6.0 | 6.029 | YES | 52 | 1.9590075535027367 |
| 34 | 6.0 | 4.188 | NO | 33 | 1.1845588205431987 |
| 35 | 6.0 | 4.020 | NO | 52 | 1.5443523974586317 |
| 36 | 6.0 | 2.335 | NO | 52 | 1.358233694850108 |
| 37 | 5.0 | 6.681 | NO | 25 | 1.040270934759163 |
| 38 | 0.0 | 0.191 | YES | 52 | 1.3582336948501075 |
| 39 | 9.0 | 6.963 | NO | 52 | 1.751679975480684 |
| 40 | 1.0 | 4.899 | NO | 52 | 1.3582336948501075 |
| 41 | 7.0 | 4.822 | NO | 52 | 1.7516799754806844 |
| 42 | 9.0 | 4.957 | NO | 54 | 1.3309213700127396 |
| 43 | 6.0 | 6.009 | YES | 52 | 1.5443523974586322 |
| 44 | 5.0 | 4.071 | NO | 35 | 1.1786786952343054 |
| 45 | 7.0 | 4.649 | NO | 18 | 0.8154021379058642 |
| 46 | 5.0 | 5.056 | YES | 52 | 1.3582336948501084 |
| 47 | 2.0 | 0.880 | NO | 52 | 1.3582336948501075 |
| 48 | 7.0 | 7.776 | NO | 52 | 1.1296972414145259 |
| 49 | 5.0 | 4.079 | NO | 25 | 1.5172554061212935 |

*Showing first 50 of 360 instances. See JSON file for complete data.*
