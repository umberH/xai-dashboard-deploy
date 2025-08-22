# Detailed Explanation Report

**Dataset:** wine_classification  
**Model:** linear_regression  
**Explanation Method:** lime  
**Generated:** 2025-08-22 14:32:08  

## Summary Statistics

- **Total Instances:** 36
- **Valid Explanations:** 36
- **Errors:** 0
- **Model Accuracy:** 0.8611
- **Average Feature Importance:** 0.0769
- **Feature Importance Std:** 0.1912
- **Max Feature Importance:** 0.9468

## Prediction Analysis

- **Correct Predictions:** 31 (86.1%)
- **Incorrect Predictions:** 5 (13.9%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 6 | 23 | 0.6918 | 63.9% |
| 11 | 22 | 0.0795 | 61.1% |
| 9 | 18 | 0.2521 | 50.0% |
| 5 | 17 | 0.0388 | 47.2% |
| 12 | 16 | 0.1257 | 44.4% |
| 3 | 14 | 0.2749 | 38.9% |
| 7 | 13 | 0.1648 | 36.1% |
| 1 | 13 | 0.0288 | 36.1% |
| 0 | 12 | 0.1617 | 33.3% |
| 2 | 10 | 0.0300 | 27.8% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** -0.28420640024809407
- **Prediction Probabilities:** ['-0.284']
- **Top Features:**
  - Feature 6: 0.7681
  - Feature 12: 0.0596
  - Feature 11: 0.0570

#### Instance 1

- **True Label:** 2.0
- **Prediction:** 1.788989754333345
- **Prediction Probabilities:** ['1.789']
- **Top Features:**
  - Feature 9: 0.9234
  - Feature 7: 0.0766
  - Feature 0: 0.0000

#### Instance 2

- **True Label:** 0.0
- **Prediction:** 0.05887020624168804
- **Prediction Probabilities:** ['0.059']
- **Top Features:**
  - Feature 6: 0.6910
  - Feature 12: 0.1112
  - Feature 5: 0.0478

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 0.8408169627178115
- **Prediction Probabilities:** ['0.841']
- **Top Features:**
  - Feature 0: 0.9255
  - Feature 10: 0.0672
  - Feature 6: 0.0073

#### Instance 5

- **True Label:** 0.0
- **Prediction:** -0.14959092579272137
- **Prediction Probabilities:** ['-0.150']
- **Top Features:**
  - Feature 6: 0.6930
  - Feature 12: 0.1005
  - Feature 9: 0.0582

### Incorrect Predictions (Sample)

#### Instance 3

- **True Label:** 1.0
- **Prediction:** -0.1582246007544169
- **Prediction Probabilities:** ['-0.158']
- **Top Features:**
  - Feature 6: 0.7587
  - Feature 11: 0.0943
  - Feature 5: 0.0392

#### Instance 7

- **True Label:** 1.0
- **Prediction:** 0.4844156137852371
- **Prediction Probabilities:** ['0.484']
- **Top Features:**
  - Feature 6: 0.7260
  - Feature 9: 0.1131
  - Feature 5: 0.0637

#### Instance 13

- **True Label:** 2.0
- **Prediction:** 1.401781527466775
- **Prediction Probabilities:** ['1.402']
- **Top Features:**
  - Feature 4: 0.7305
  - Feature 0: 0.2695
  - Feature 2: 0.0000

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | -0.284 | YES | 6 | 0.7681178524890278 |
| 1 | 2.0 | 1.789 | YES | 9 | 0.9234015916769609 |
| 2 | 0.0 | 0.059 | YES | 6 | 0.6909522679569796 |
| 3 | 1.0 | -0.158 | NO | 6 | 0.7587380549674194 |
| 4 | 1.0 | 0.841 | YES | 0 | 0.9255244636769524 |
| 5 | 0.0 | -0.150 | YES | 6 | 0.6930017720312208 |
| 6 | 0.0 | -0.131 | YES | 6 | 0.7093207358383263 |
| 7 | 1.0 | 0.484 | NO | 6 | 0.7259508785613595 |
| 8 | 1.0 | 1.202 | YES | 3 | 0.7276100307923496 |
| 9 | 2.0 | 2.068 | YES | 9 | 0.4936380681276481 |
| 10 | 1.0 | 0.907 | YES | 6 | 0.783478347389704 |
| 11 | 2.0 | 1.668 | YES | 3 | 0.5676493194899518 |
| 12 | 0.0 | -0.308 | YES | 6 | 0.67083870912549 |
| 13 | 2.0 | 1.402 | NO | 4 | 0.7304507345667149 |
| 14 | 0.0 | -0.475 | YES | 6 | 0.5776648896762291 |
| 15 | 1.0 | 1.083 | YES | 6 | 0.7563219489818997 |
| 16 | 1.0 | 0.905 | YES | 11 | 0.4716570682530842 |
| 17 | 0.0 | 0.047 | YES | 6 | 0.6572420170842689 |
| 18 | 1.0 | 0.710 | YES | 6 | 0.9468317465839544 |
| 19 | 0.0 | 0.159 | YES | 6 | 0.7393618144264303 |
| 20 | 1.0 | 0.911 | YES | 6 | 0.8687165831367576 |
| 21 | 1.0 | 1.126 | YES | 7 | 0.779396089973217 |
| 22 | 0.0 | -0.225 | YES | 6 | 0.7153840768306672 |
| 23 | 0.0 | -0.568 | NO | 6 | 0.5848963001220499 |
| 24 | 1.0 | 0.356 | NO | 6 | 0.911487508225249 |
| 25 | 1.0 | 1.057 | YES | 7 | 0.6837485220588507 |
| 26 | 0.0 | -0.129 | YES | 6 | 0.725592241176209 |
| 27 | 2.0 | 1.799 | YES | 9 | 0.6048255546127642 |
| 28 | 1.0 | 0.730 | YES | 6 | 0.9299942245730959 |
| 29 | 2.0 | 2.085 | YES | 3 | 0.3937816972155145 |
| 30 | 0.0 | 0.318 | YES | 6 | 0.7724216428226338 |
| 31 | 2.0 | 1.847 | YES | 12 | 0.5413975938523049 |
| 32 | 1.0 | 1.109 | YES | 6 | 0.8976193920997687 |
| 33 | 2.0 | 2.184 | YES | 9 | 0.5656162307893372 |
| 34 | 2.0 | 2.021 | YES | 3 | 0.5340675758345192 |
| 35 | 2.0 | 1.882 | YES | 9 | 0.40412511073881163 |
