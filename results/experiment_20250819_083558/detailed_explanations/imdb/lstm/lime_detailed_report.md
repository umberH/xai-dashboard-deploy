# Detailed Explanation Report

**Dataset:** imdb  
**Model:** lstm  
**Explanation Method:** lime  
**Generated:** 2025-08-19 10:06:05  

## Summary Statistics

- **Total Instances:** 200
- **Valid Explanations:** 200
- **Errors:** 0
- **Model Accuracy:** 0.8150
- **Average Feature Importance:** 0.0200
- **Feature Importance Std:** 0.0234
- **Max Feature Importance:** 0.5593

## Prediction Analysis

- **Correct Predictions:** 163 (81.5%)
- **Incorrect Predictions:** 37 (18.5%)

## Feature Importance Analysis

### Most Frequently Important Features

| Feature Index | Frequency | Avg Importance | Percentage |
|---------------|-----------|----------------|------------|
| 4 | 36 | 0.0662 | 18.0% |
| 1 | 33 | 0.0637 | 16.5% |
| 2 | 29 | 0.0582 | 14.5% |
| 3 | 28 | 0.0696 | 14.0% |
| 13 | 28 | 0.0692 | 14.0% |
| 35 | 26 | 0.0569 | 13.0% |
| 8 | 26 | 0.0704 | 13.0% |
| 15 | 26 | 0.0746 | 13.0% |
| 16 | 25 | 0.0902 | 12.5% |
| 17 | 25 | 0.0750 | 12.5% |

## Sample Explanations

### Correct Predictions (Sample)

#### Instance 0

- **True Label:** 0.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.781', '0.219']
- **Top Features:**
  - Feature 46: 0.0612
  - Feature 39: 0.0545
  - Feature 31: 0.0512

#### Instance 1

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.356', '0.644']
- **Top Features:**
  - Feature 47: 0.0607
  - Feature 24: 0.0497
  - Feature 14: 0.0476

#### Instance 3

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.397', '0.603']
- **Top Features:**
  - Feature 43: 0.0688
  - Feature 6: 0.0631
  - Feature 39: 0.0569

#### Instance 4

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.323', '0.677']
- **Top Features:**
  - Feature 26: 0.0473
  - Feature 29: 0.0436
  - Feature 16: 0.0400

#### Instance 5

- **True Label:** 1.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.341', '0.659']
- **Top Features:**
  - Feature 3: 0.0824
  - Feature 44: 0.0766
  - Feature 48: 0.0700

### Incorrect Predictions (Sample)

#### Instance 2

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.503', '0.497']
- **Top Features:**
  - Feature 23: 0.1328
  - Feature 35: 0.1013
  - Feature 24: 0.0843

#### Instance 7

- **True Label:** 0.0
- **Prediction:** 1.0
- **Prediction Probabilities:** ['0.413', '0.587']
- **Top Features:**
  - Feature 2: 0.0873
  - Feature 5: 0.0868
  - Feature 46: 0.0772

#### Instance 8

- **True Label:** 1.0
- **Prediction:** 0.0
- **Prediction Probabilities:** ['0.656', '0.344']
- **Top Features:**
  - Feature 49: 0.0670
  - Feature 11: 0.0569
  - Feature 15: 0.0491

## Detailed Results Table

| Instance ID | True Label | Prediction | Correct | Top Feature | Top Importance |
|-------------|------------|------------|---------|-------------|----------------|
| 0 | 0.0 | 0.000 | YES | 46 | 0.06120661946147844 |
| 1 | 1.0 | 1.000 | YES | 47 | 0.060661192410788545 |
| 2 | 1.0 | 0.000 | NO | 23 | 0.1328194972282961 |
| 3 | 1.0 | 1.000 | YES | 43 | 0.06884995788512618 |
| 4 | 1.0 | 1.000 | YES | 26 | 0.0473471561822172 |
| 5 | 1.0 | 1.000 | YES | 3 | 0.0823734985976051 |
| 6 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 7 | 0.0 | 1.000 | NO | 2 | 0.0873476092197728 |
| 8 | 1.0 | 0.000 | NO | 49 | 0.06702965800507929 |
| 9 | 1.0 | 1.000 | YES | 2 | 0.07060340883309353 |
| 10 | 0.0 | 0.000 | YES | 30 | 0.13112174500648127 |
| 11 | 0.0 | 1.000 | NO | 9 | 0.20781888828923958 |
| 12 | 1.0 | 1.000 | YES | 44 | 0.13085129276318078 |
| 13 | 1.0 | 1.000 | YES | 43 | 0.0963081385438482 |
| 14 | 0.0 | 0.000 | YES | 49 | 0.05459428913544632 |
| 15 | 0.0 | 0.000 | YES | 28 | 0.09671486934531688 |
| 16 | 1.0 | 1.000 | YES | 21 | 0.21677412602885635 |
| 17 | 0.0 | 1.000 | NO | 27 | 0.0461433847234323 |
| 18 | 1.0 | 1.000 | YES | 29 | 0.14786912057683477 |
| 19 | 0.0 | 1.000 | NO | 16 | 0.1345143556237966 |
| 20 | 1.0 | 1.000 | YES | 3 | 0.31896031658860113 |
| 21 | 0.0 | 0.000 | YES | 19 | 0.08180863854932877 |
| 22 | 1.0 | 1.000 | YES | 23 | 0.10840516279125723 |
| 23 | 1.0 | 0.000 | NO | 11 | 0.10531226330240159 |
| 24 | 0.0 | 0.000 | YES | 0 | 0.0392156862745098 |
| 25 | 1.0 | 1.000 | YES | 39 | 0.0881971777512081 |
| 26 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 27 | 0.0 | 0.000 | YES | 30 | 0.07972148762415038 |
| 28 | 0.0 | 1.000 | NO | 7 | 0.07102389725028226 |
| 29 | 1.0 | 1.000 | YES | 4 | 0.13417336521863846 |
| 30 | 0.0 | 0.000 | YES | 27 | 0.04911008216232824 |
| 31 | 0.0 | 0.000 | YES | 17 | 0.22325774517786734 |
| 32 | 0.0 | 0.000 | YES | 19 | 0.04216570228519561 |
| 33 | 0.0 | 1.000 | NO | 23 | 0.09946515167177693 |
| 34 | 0.0 | 0.000 | YES | 42 | 0.03903019688826594 |
| 35 | 0.0 | 0.000 | YES | 23 | 0.18687179232147644 |
| 36 | 1.0 | 1.000 | YES | 19 | 0.1313285585880724 |
| 37 | 1.0 | 1.000 | YES | 33 | 0.0818613676306196 |
| 38 | 1.0 | 1.000 | YES | 38 | 0.10306349192945723 |
| 39 | 0.0 | 0.000 | YES | 24 | 0.16439896882386576 |
| 40 | 0.0 | 0.000 | YES | 43 | 0.21539174856563667 |
| 41 | 0.0 | 1.000 | NO | 48 | 0.12886850224273338 |
| 42 | 1.0 | 1.000 | YES | 7 | 0.0549484903238879 |
| 43 | 1.0 | 1.000 | YES | 22 | 0.07457575687638317 |
| 44 | 0.0 | 0.000 | YES | 39 | 0.09004197963920131 |
| 45 | 0.0 | 0.000 | YES | 27 | 0.09191367156475948 |
| 46 | 1.0 | 1.000 | YES | 6 | 0.1351643238261909 |
| 47 | 1.0 | 1.000 | YES | 43 | 0.11772468919307688 |
| 48 | 1.0 | 1.000 | YES | 0 | 0.0392156862745098 |
| 49 | 0.0 | 0.000 | YES | 3 | 0.09608031549529371 |

*Showing first 50 of 200 instances. See JSON file for complete data.*
