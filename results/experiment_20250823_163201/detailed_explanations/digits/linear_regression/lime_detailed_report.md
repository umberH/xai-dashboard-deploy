# Detailed Explanation Report

**Dataset:** digits  
**Model:** linear_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-23 18:53:17  

## Summary Statistics

- **Total Instances:** 360
- **Valid Explanations:** 360
- **Errors:** 0
- **Model Accuracy:** 0.2417
- **Average Feature Importance:** 0.0156
- **Feature Importance Std:** 0.0429
- **Max Feature Importance:** 0.5462

## Prediction Analysis

- **Correct Predictions:** 87 (24.2%)
- **Incorrect Predictions:** 273 (75.8%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 52 | 192 | 0.2735 | 53.3% |
| 35 | 183 | 0.2130 | 50.8% |
| 44 | 131 | 0.1252 | 36.4% |
| 10 | 126 | 0.1056 | 35.0% |
| 29 | 102 | 0.1134 | 28.3% |
| 27 | 100 | 0.1057 | 27.8% |
| 13 | 95 | 0.1107 | 26.4% |
| 18 | 82 | 0.1038 | 22.8% |
| 28 | 74 | 0.0833 | 20.6% |
| 33 | 73 | 0.1140 | 20.3% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 9

- **True Label:** 5.0
- **Prediction:** 5.26569554436196
- **Prediction Probabilities:** ['5.266']
- **Top Features:**
  - Feature 52: 0.3271
  - Feature 35: 0.2391
  - Feature 10: 0.0694

#### Instance 12

- **True Label:** 9.0
- **Prediction:** 9.071233027754028
- **Prediction Probabilities:** ['9.071']
- **Top Features:**
  - Feature 27: 0.1705
  - Feature 29: 0.1399
  - Feature 45: 0.1276

#### Instance 18

- **True Label:** 9.0
- **Prediction:** 9.197009382487266
- **Prediction Probabilities:** ['9.197']
- **Top Features:**
  - Feature 35: 0.1914
  - Feature 36: 0.1149
  - Feature 15: 0.0863

#### Instance 30

- **True Label:** 6.0
- **Prediction:** 6.101614175230673
- **Prediction Probabilities:** ['6.102']
- **Top Features:**
  - Feature 35: 0.3002
  - Feature 36: 0.1285
  - Feature 12: 0.0678

#### Instance 33

- **True Label:** 6.0
- **Prediction:** 6.029276218170434
- **Prediction Probabilities:** ['6.029']
- **Top Features:**
  - Feature 35: 0.3352
  - Feature 51: 0.1592
  - Feature 54: 0.0791

### Incorrect Predictions (Sample)

#### Instance 0

- **True Label:** 5.0
- **Prediction:** 8.119061342909566
- **Prediction Probabilities:** ['8.119']
- **Top Features:**
  - Feature 18: 0.2848
  - Feature 29: 0.1706
  - Feature 10: 0.1108

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 4.1780723389942915
- **Prediction Probabilities:** ['4.178']
- **Top Features:**
  - Feature 52: 0.2483
  - Feature 54: 0.1288
  - Feature 20: 0.0745

#### Instance 2

- **True Label:** 8.0
- **Prediction:** 5.096404556107999
- **Prediction Probabilities:** ['5.096']
- **Top Features:**
  - Feature 52: 0.1784
  - Feature 29: 0.1427
  - Feature 35: 0.1426

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 5.0 | 8.119 | NO | 18 | 0.284767781543468 |
| 1 | 2.0 | 4.178 | NO | 52 | 0.24834939179165816 |
| 2 | 8.0 | 5.096 | NO | 52 | 0.17840178794909262 |
| 3 | 1.0 | 5.720 | NO | 35 | 0.4925046112571736 |
| 4 | 7.0 | 5.972 | NO | 10 | 0.3240862970065793 |
| 5 | 2.0 | 2.549 | NO | 35 | 0.16514615897301183 |
| 6 | 6.0 | 5.393 | NO | 35 | 0.25766506319305094 |
| 7 | 2.0 | 3.027 | NO | 52 | 0.3391812367191177 |
| 8 | 6.0 | 5.393 | NO | 27 | 0.2653730777222003 |
| 9 | 5.0 | 5.266 | YES | 52 | 0.3271297799020962 |
| 10 | 0.0 | -0.612 | NO | 52 | 0.4519981180236715 |
| 11 | 5.0 | 6.276 | NO | 52 | 0.33208256892011023 |
| 12 | 9.0 | 9.071 | YES | 27 | 0.17046971041066952 |
| 13 | 3.0 | 7.123 | NO | 35 | 0.2646499842397449 |
| 14 | 4.0 | 4.675 | NO | 35 | 0.2507942515497682 |
| 15 | 4.0 | 5.385 | NO | 52 | 0.1377908617157047 |
| 16 | 2.0 | 2.792 | NO | 44 | 0.26078419713072354 |
| 17 | 4.0 | 5.703 | NO | 52 | 0.2515211472022425 |
| 18 | 9.0 | 9.197 | YES | 35 | 0.19141086151745898 |
| 19 | 9.0 | 3.881 | NO | 20 | 0.26363372781239636 |
| 20 | 6.0 | 5.384 | NO | 61 | 0.2496960691116103 |
| 21 | 3.0 | 1.133 | NO | 52 | 0.4124702144634244 |
| 22 | 8.0 | 8.720 | NO | 10 | 0.19925089110753272 |
| 23 | 1.0 | 3.676 | NO | 35 | 0.1694358248464241 |
| 24 | 2.0 | 3.530 | NO | 35 | 0.3053208822596902 |
| 25 | 5.0 | 6.537 | NO | 52 | 0.195743002127093 |
| 26 | 6.0 | 3.489 | NO | 54 | 0.2963222569410303 |
| 27 | 0.0 | 0.589 | NO | 52 | 0.41545783684781556 |
| 28 | 3.0 | 5.078 | NO | 10 | 0.20857111491603053 |
| 29 | 4.0 | 4.936 | NO | 35 | 0.17256565637636412 |
| 30 | 6.0 | 6.102 | YES | 35 | 0.30018102012569037 |
| 31 | 7.0 | 6.120 | NO | 35 | 0.46443442514843314 |
| 32 | 2.0 | 3.080 | NO | 21 | 0.18809906902677825 |
| 33 | 6.0 | 6.029 | YES | 35 | 0.335172749580967 |
| 34 | 6.0 | 4.188 | NO | 35 | 0.2841971903338038 |
| 35 | 6.0 | 4.020 | NO | 61 | 0.23477891871294493 |
| 36 | 6.0 | 2.335 | NO | 52 | 0.22733694454528913 |
| 37 | 5.0 | 6.681 | NO | 29 | 0.1409207446734803 |
| 38 | 0.0 | 0.191 | YES | 52 | 0.48439959238584535 |
| 39 | 9.0 | 6.963 | NO | 51 | 0.13191455213053777 |
| 40 | 1.0 | 4.899 | NO | 35 | 0.3040248472130368 |
| 41 | 7.0 | 4.822 | NO | 35 | 0.22397894728836548 |
| 42 | 9.0 | 4.957 | NO | 29 | 0.1607893732618921 |
| 43 | 6.0 | 6.009 | YES | 35 | 0.2657161171456202 |
| 44 | 5.0 | 4.071 | NO | 52 | 0.35964784154687657 |
| 45 | 7.0 | 4.649 | NO | 35 | 0.3412124942601279 |
| 46 | 5.0 | 5.056 | YES | 44 | 0.30317514234556564 |
| 47 | 2.0 | 0.880 | NO | 54 | 0.1944210898707439 |
| 48 | 7.0 | 7.776 | NO | 13 | 0.25049807857714357 |
| 49 | 5.0 | 4.079 | NO | 52 | 0.24875541113116267 |

*Showing first 50 of 360 instances. See JSON file for complete data.*
