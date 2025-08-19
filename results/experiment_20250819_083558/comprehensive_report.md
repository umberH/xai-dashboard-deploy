# Comprehensive XAI Benchmarking Report

Generated on: 2025-08-19 10:06:52

## Summary

- **Datasets**: 4
- **Models**: 8
- **Explanation Methods**: 17
- **Evaluation Metrics**: 16
- **Total Combinations**: 96

### Datasets
- **adult_income** (tabular)
- **compas** (tabular)
- **imdb** (text)
- **mnist** (image)

### Models
- **bert** (bert)
- **cnn** (cnn)
- **decision_tree** (decision_tree)
- **gradient_boosting** (gradient_boosting)
- **lstm** (lstm)
- **mlp** (mlp)
- **random_forest** (random_forest)
- **vit** (vit)

### Explanation Methods
- **attention_visualization**
- **bayesian_rule_list**
- **causal_shap**
- **concept_bottleneck**
- **corels**
- **counterfactual**
- **feature_ablation**
- **influence_functions**
- **integrated_gradients**
- **lime**
- **occlusion**
- **prototype**
- **shap**
- **shap_interactive**
- **shapley_flow**
- **tcav**
- **text_occlusion**

## Model Performance Summary

Training and test set performance for each model on each dataset.

| Dataset | Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss | Other Metrics |
|---------|-------|----------------|---------------|------------|-----------|---------------|
| adult_income | decision_tree | 0.8405 | 0.8326 | N/A | N/A | train_f1: 0.8247; test_f1: 0.8159; train_precision: 0.8365; test_precision: 0.8264; train_recall: 0.8405; test_recall: 0.8326; overfitting_gap: 0.0079; overfitting_severity: low; class_accuracies: [0.957845950121386, 0.45472703062583225]; n_classes: 2.0000; n_train_samples: 24129.0000; n_test_samples: 6033.0000; training_time: 0.0275; model_complexity: {'n_parameters': 13, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| adult_income | random_forest | 0.8425 | 0.8333 | N/A | N/A | train_f1: 0.8267; test_f1: 0.8160; train_precision: 0.8392; test_precision: 0.8278; train_recall: 0.8425; test_recall: 0.8333; overfitting_gap: 0.0092; overfitting_severity: low; class_accuracies: [0.9602736702714633, 0.45006657789613846]; n_classes: 2.0000; n_train_samples: 24129.0000; n_test_samples: 6033.0000; training_time: 0.6678; model_complexity: {'n_parameters': 19, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| adult_income | gradient_boosting | 0.8387 | 0.8356 | N/A | N/A | train_f1: 0.8229; test_f1: 0.8189; train_precision: 0.8340; test_precision: 0.8305; train_recall: 0.8387; test_recall: 0.8356; overfitting_gap: 0.0031; overfitting_severity: low; class_accuracies: [0.9607150739351137, 0.4580559254327563]; n_classes: 2.0000; n_train_samples: 24129.0000; n_test_samples: 6033.0000; training_time: 1.1447; model_complexity: {'n_parameters': 20, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| adult_income | mlp | 0.8257 | 0.8236 | N/A | N/A | train_f1: 0.8112; test_f1: 0.8083; train_precision: 0.8161; test_precision: 0.8137; train_recall: 0.8257; test_recall: 0.8236; overfitting_gap: 0.0021; overfitting_severity: low; class_accuracies: [0.9452659457073493, 0.4567243675099867]; n_classes: 2.0000; n_train_samples: 24129.0000; n_test_samples: 6033.0000; training_time: 8.5389; model_complexity: {'n_parameters': 23, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| compas | decision_tree | 0.7375 | 0.6736 | N/A | N/A | train_f1: 0.7347; test_f1: 0.6706; train_precision: 0.7381; test_precision: 0.6721; train_recall: 0.7375; test_recall: 0.6736; overfitting_gap: 0.0639; overfitting_severity: low; class_accuracies: [0.755359394703657, 0.5738461538461539]; n_classes: 2.0000; n_train_samples: 5771.0000; n_test_samples: 1443.0000; training_time: 0.0059; model_complexity: {'n_parameters': 13, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| compas | random_forest | 0.7538 | 0.6826 | N/A | N/A | train_f1: 0.7516; test_f1: 0.6797; train_precision: 0.7543; test_precision: 0.6813; train_recall: 0.7538; test_recall: 0.6826; overfitting_gap: 0.0712; overfitting_severity: low; class_accuracies: [0.7629255989911727, 0.5846153846153846]; n_classes: 2.0000; n_train_samples: 5771.0000; n_test_samples: 1443.0000; training_time: 0.2903; model_complexity: {'n_parameters': 19, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| compas | gradient_boosting | 0.7054 | 0.6951 | N/A | N/A | train_f1: 0.7025; test_f1: 0.6924; train_precision: 0.7049; test_precision: 0.6941; train_recall: 0.7054; test_recall: 0.6951; overfitting_gap: 0.0103; overfitting_severity: low; class_accuracies: [0.7730138713745272, 0.6]; n_classes: 2.0000; n_train_samples: 5771.0000; n_test_samples: 1443.0000; training_time: 0.2799; model_complexity: {'n_parameters': 20, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| compas | mlp | 0.6881 | 0.6854 | N/A | N/A | train_f1: 0.6862; test_f1: 0.6837; train_precision: 0.6868; test_precision: 0.6840; train_recall: 0.6881; test_recall: 0.6854; overfitting_gap: 0.0027; overfitting_severity: low; class_accuracies: [0.7490542244640606, 0.6076923076923076]; n_classes: 2.0000; n_train_samples: 5771.0000; n_test_samples: 1443.0000; training_time: 1.8534; model_complexity: {'n_parameters': 23, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| mnist | cnn | 0.9940 | 0.9800 | N/A | N/A | train_f1: 0.9940; test_f1: 0.9797; train_precision: 0.9942; test_precision: 0.9811; train_recall: 0.9940; test_recall: 0.9800; overfitting_gap: 0.0140; overfitting_severity: low; class_accuracies: [1.0, 1.0, 0.9375, 0.9375, 1.0, 1.0, 1.0, 1.0, 0.8, 1.0]; n_classes: 10.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 6.4886; model_complexity: {'n_parameters': 688138, 'model_size_bytes': 2752552, 'model_size_mb': 2.6250381469726562, 'complexity_level': 'complex'} |
| mnist | vit | 0.7800 | 0.7000 | N/A | N/A | train_f1: 0.7748; test_f1: 0.6862; train_precision: 0.7974; test_precision: 0.7076; train_recall: 0.7800; test_recall: 0.7000; overfitting_gap: 0.0800; overfitting_severity: low; class_accuracies: [1.0, 0.8928571428571429, 0.5, 0.5625, 0.8928571428571429, 0.35, 0.35, 0.875, 0.7, 0.6666666666666666]; n_classes: 10.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 9.8344; model_complexity: {'n_parameters': 3231242, 'model_size_bytes': 12924968, 'model_size_mb': 12.326210021972656, 'complexity_level': 'complex'} |
| imdb | bert | 0.9180 | 0.8100 | N/A | N/A | train_f1: 0.9180; test_f1: 0.8099; train_precision: 0.9180; test_precision: 0.8105; train_recall: 0.9180; test_recall: 0.8100; overfitting_gap: 0.1080; overfitting_severity: moderate; class_accuracies: [0.79, 0.83]; n_classes: 2.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 0.5902; model_complexity: {'n_parameters': 15, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| imdb | lstm | 0.8870 | 0.8150 | N/A | N/A | train_f1: 0.8870; test_f1: 0.8149; train_precision: 0.8870; test_precision: 0.8158; train_recall: 0.8870; test_recall: 0.8150; overfitting_gap: 0.0720; overfitting_severity: low; class_accuracies: [0.84, 0.79]; n_classes: 2.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 1.0073; model_complexity: {'n_parameters': 4, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |

## XAI Evaluation Results Table

Each row represents a unique combination of Dataset, Model, and Explanation Method with their evaluation metrics.

| Dataset | Model | Explanation Method | Detailed Report | Time Complexity | Faithfulness | Monotonicity | Completeness | Stability | Consistency | Sparsity | Simplicity | Advanced Identity | Advanced Separability | Advanced Non Sensitivity | Advanced Compactness | Advanced Correctness | Advanced Entropy | Advanced Gini Coefficient | Advanced Kl Divergence |
|---------|-------|-------------------|-----------------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|
| adult_income | decision_tree | shap | [View Details](#) | 0.0007 | 0.1900 | 0.0200 | 0.0100 | 0.0000 | 0.4651 | 0.0300 | 0.9520 | 0.9432 | 0.1706 | 1.0000 | 0.1775 | 0.6240 | 0.0215 | 0.1420 | 0.1685 |
| adult_income | decision_tree | lime | [View Details](#) | 0.0096 | 0.0600 | 0.0267 | 0.0000 | 0.0000 | 0.5203 | 0.0600 | 0.9404 | 0.8696 | 0.2186 | 1.0000 | 0.2238 | 0.5943 | 0.0279 | 0.1804 | 0.2121 |
| adult_income | decision_tree | causal_shap | [View Details](#) | 0.0161 | 0.2400 | 0.0200 | 0.0200 | 0.0000 | 0.5514 | 0.0360 | 0.9491 | 1.0000 | 0.1772 | 1.0000 | 0.1855 | 0.5809 | 0.0255 | 0.1491 | 0.1745 |
| adult_income | decision_tree | shapley_flow | [View Details](#) | 0.0068 | 0.1000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | shap_interactive | [View Details](#) | 0.0177 | 0.3000 | 0.0333 | 0.0190 | 0.0000 | 0.3736 | 0.1000 | 0.9404 | 0.9073 | 0.2791 | 1.0000 | 0.2800 | 0.6270 | 0.0863 | 0.2270 | 0.2471 |
| adult_income | decision_tree | prototype | [View Details](#) | 0.0008 | 0.6900 | 0.8369 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | counterfactual | [View Details](#) | 0.0005 | 0.7200 | 0.1868 | 1.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | bayesian_rule_list | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5670 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | corels | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5670 | 1.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | feature_ablation | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4632 | 0.0240 | 0.9440 | 1.0000 | 0.2245 | 1.0000 | 0.2300 | 0.6040 | 0.0172 | 0.1840 | 0.2228 |
| adult_income | random_forest | shap | [View Details](#) | 0.0323 | 0.1900 | 0.0200 | 0.0000 | 0.0000 | 0.4696 | 0.0140 | 0.9440 | 0.9438 | 0.1647 | 1.0000 | 0.1675 | 0.6170 | 0.0291 | 0.1340 | 0.1609 |
| adult_income | random_forest | lime | [View Details](#) | 0.0184 | 0.1000 | 0.0200 | 0.0000 | 0.0000 | 0.3842 | 0.0240 | 0.9659 | 0.9091 | 0.1562 | 1.0000 | 0.1583 | 0.5779 | 0.0080 | 0.1259 | 0.1520 |
| adult_income | random_forest | causal_shap | [View Details](#) | 0.6472 | 0.2400 | 0.0200 | 0.0000 | 0.0000 | 0.5620 | 0.0360 | 0.9495 | 1.0000 | 0.1772 | 1.0000 | 0.1849 | 0.5810 | 0.0278 | 0.1495 | 0.1722 |
| adult_income | random_forest | shapley_flow | [View Details](#) | 0.2995 | 0.1333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | shap_interactive | [View Details](#) | 0.7332 | 0.3000 | 0.0333 | 0.0000 | 0.0000 | 0.4052 | 0.0800 | 0.9290 | 0.9127 | 0.2683 | 1.0000 | 0.2654 | 0.6262 | 0.1044 | 0.2146 | 0.2290 |
| adult_income | random_forest | prototype | [View Details](#) | 0.0042 | 0.6850 | 0.8065 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | counterfactual | [View Details](#) | 0.0055 | 0.6800 | 0.1849 | 1.0000 | 0.6432 | 0.6142 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | bayesian_rule_list | [View Details](#) | 0.0059 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | corels | [View Details](#) | 0.0047 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 1.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | feature_ablation | [View Details](#) | 0.0279 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4509 | 0.0120 | 0.9320 | 1.0000 | 0.2132 | 1.0000 | 0.2150 | 0.6040 | 0.0309 | 0.1720 | 0.2091 |
| adult_income | gradient_boosting | shap | [View Details](#) | 0.0023 | 0.2100 | 0.0300 | 0.0000 | 0.0000 | 0.4896 | 0.0220 | 0.9400 | 0.9432 | 0.1825 | 1.0000 | 0.1875 | 0.6440 | 0.0316 | 0.1500 | 0.1784 |
| adult_income | gradient_boosting | lime | [View Details](#) | 0.0155 | 0.1200 | 0.0400 | 0.0000 | 0.0000 | 0.4557 | 0.0360 | 0.9538 | 0.9091 | 0.1873 | 1.0000 | 0.1926 | 0.6135 | 0.0182 | 0.1538 | 0.1818 |
| adult_income | gradient_boosting | causal_shap | [View Details](#) | 0.0507 | 0.2600 | 0.0200 | 0.0000 | 0.0000 | 0.6393 | 0.0280 | 0.9572 | 1.0000 | 0.1847 | 1.0000 | 0.1904 | 0.6138 | 0.0259 | 0.1514 | 0.1741 |
| adult_income | gradient_boosting | shap_interactive | [View Details](#) | 0.0610 | 0.3000 | 0.0333 | 0.0140 | 0.0000 | 0.5203 | 0.0933 | 0.9370 | 0.9607 | 0.2754 | 1.0000 | 0.2834 | 0.6507 | 0.0993 | 0.2277 | 0.2340 |
| adult_income | gradient_boosting | prototype | [View Details](#) | 0.0012 | 0.7100 | 0.8096 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | gradient_boosting | counterfactual | [View Details](#) | 0.0010 | 0.7200 | 0.1808 | 1.0000 | 0.8024 | 0.2903 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | gradient_boosting | bayesian_rule_list | [View Details](#) | 0.0009 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5810 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | gradient_boosting | corels | [View Details](#) | 0.0008 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5810 | 1.0000 | 0.0000 | 0.0000 |
| adult_income | gradient_boosting | feature_ablation | [View Details](#) | 0.0013 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4954 | 0.0200 | 0.9360 | 1.0000 | 0.2404 | 1.0000 | 0.2450 | 0.6380 | 0.0223 | 0.1960 | 0.2377 |
| adult_income | mlp | shap | [View Details](#) | 0.0010 | 0.2200 | 0.0250 | 0.0000 | 0.0000 | 0.4396 | 0.0260 | 0.9420 | 0.9032 | 0.1970 | 1.0000 | 0.2025 | 0.6400 | 0.0258 | 0.1620 | 0.1942 |
| adult_income | mlp | lime | [View Details](#) | 0.0142 | 0.0800 | 0.0233 | 0.0000 | 0.0000 | 0.6496 | 0.0720 | 0.9650 | 0.8913 | 0.0947 | 1.0000 | 0.1052 | 0.5691 | 0.0383 | 0.0850 | 0.0817 |
| adult_income | mlp | integrated_gradients | [View Details](#) | 0.0610 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5833 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | causal_shap | [View Details](#) | 0.0266 | 0.2400 | 0.0090 | 0.0000 | 0.0000 | 0.5502 | 0.0360 | 0.9659 | 1.0000 | 0.1617 | 1.0000 | 0.1662 | 0.5957 | 0.0312 | 0.1320 | 0.1488 |
| adult_income | mlp | shapley_flow | [View Details](#) | 0.0107 | 0.1000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5833 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | shap_interactive | [View Details](#) | 0.0324 | 0.3333 | 0.0178 | 0.0064 | 0.0000 | 0.3857 | 0.1267 | 0.9609 | 0.8939 | 0.2946 | 1.0000 | 0.2845 | 0.6486 | 0.1393 | 0.2330 | 0.2273 |
| adult_income | mlp | prototype | [View Details](#) | 0.0011 | 0.7050 | 0.8031 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | counterfactual | [View Details](#) | 0.0008 | 0.7400 | 0.1976 | 1.0000 | 0.7957 | 0.7817 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | influence_functions | [View Details](#) | 0.0342 | 0.0000 | 0.0000 | 0.0000 | 0.2615 | 0.4384 | 0.6000 | 0.4358 | 1.0000 | 0.4254 | 1.0000 | 0.5102 | 0.7454 | 0.7768 | 0.4358 | 0.2232 |
| adult_income | mlp | bayesian_rule_list | [View Details](#) | 0.0007 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5740 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | corels | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5740 | 1.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | feature_ablation | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4377 | 0.0240 | 0.9320 | 1.0000 | 0.2845 | 1.0000 | 0.2900 | 0.6360 | 0.0172 | 0.2320 | 0.2828 |
| compas | decision_tree | shap | [View Details](#) | 0.0006 | 0.6500 | 0.0300 | 0.0000 | 0.0000 | 0.6861 | 0.3500 | 0.7000 | 0.6292 | 0.3712 | 0.9999 | 0.5250 | 0.6090 | 0.1525 | 0.3500 | 0.4975 |
| compas | decision_tree | lime | [View Details](#) | 0.0155 | 0.3000 | 0.0800 | 0.0000 | 0.0000 | 0.6991 | 0.6267 | 0.6797 | 0.5000 | 0.6541 | 1.0000 | 0.9284 | 0.5958 | 0.0305 | 0.6197 | 0.9095 |
| compas | decision_tree | causal_shap | [View Details](#) | 0.0125 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.6130 | 0.3000 | 0.7603 | 1.0000 | 0.2295 | 1.0000 | 0.3185 | 0.3997 | 0.2245 | 0.2215 | 0.2555 |
| compas | decision_tree | shapley_flow | [View Details](#) | 0.0051 | 0.3333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.3733 | 0.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | shap_interactive | [View Details](#) | 0.0178 | 0.6667 | 0.0111 | 0.0716 | 0.0000 | 0.6505 | 0.5444 | 0.6931 | 0.6838 | 0.4380 | 1.0000 | 0.4790 | 0.5052 | 0.5006 | 0.3426 | 0.3661 |
| compas | decision_tree | prototype | [View Details](#) | 0.0003 | 0.6550 | 0.7320 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | counterfactual | [View Details](#) | 0.0002 | 0.6300 | 0.2618 | 1.0000 | 0.8343 | 0.9754 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | bayesian_rule_list | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 0.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | corels | [View Details](#) | 0.0002 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 1.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | feature_ablation | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.6747 | 0.3667 | 0.6667 | 1.0000 | 0.3889 | 1.0000 | 0.5500 | 0.5260 | 0.1840 | 0.3667 | 0.5160 |
| compas | random_forest | shap | [View Details](#) | 0.0273 | 0.6300 | 0.0383 | 0.0000 | 0.0000 | 0.7164 | 0.3233 | 0.6933 | 0.6548 | 0.3429 | 1.0000 | 0.4850 | 0.6240 | 0.1777 | 0.3233 | 0.4523 |
| compas | random_forest | lime | [View Details](#) | 0.0274 | 0.3200 | 0.0867 | 0.0000 | 0.0000 | 0.7949 | 0.4933 | 0.6940 | 0.6216 | 0.4458 | 1.0000 | 0.6386 | 0.5475 | 0.1680 | 0.4340 | 0.5720 |
| compas | random_forest | causal_shap | [View Details](#) | 0.5443 | 0.4800 | 0.0300 | 0.0000 | 0.0000 | 0.6366 | 0.3200 | 0.7403 | 1.0000 | 0.2109 | 0.9996 | 0.2786 | 0.4479 | 0.2842 | 0.2021 | 0.2158 |
| compas | random_forest | shapley_flow | [View Details](#) | 0.2809 | 0.4333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.3733 | 0.0000 | 0.0000 | 0.0000 |
| compas | random_forest | shap_interactive | [View Details](#) | 0.6092 | 0.6333 | 0.0556 | 0.0358 | 0.0000 | 0.6707 | 0.4889 | 0.6391 | 0.8108 | 0.3285 | 0.9999 | 0.3809 | 0.4536 | 0.4920 | 0.2802 | 0.2747 |
| compas | random_forest | prototype | [View Details](#) | 0.0042 | 0.7200 | 0.6803 | 1.0000 | 0.9783 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | random_forest | counterfactual | [View Details](#) | 0.0052 | 0.6850 | 0.3126 | 1.0000 | 0.8405 | 0.7841 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | random_forest | bayesian_rule_list | [View Details](#) | 0.0045 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4410 | 0.0000 | 0.0000 | 0.0000 |
| compas | random_forest | corels | [View Details](#) | 0.0049 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4410 | 1.0000 | 0.0000 | 0.0000 |
| compas | random_forest | feature_ablation | [View Details](#) | 0.0202 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.7118 | 0.2933 | 0.6333 | 1.0000 | 0.3111 | 0.9999 | 0.4400 | 0.5640 | 0.2671 | 0.2933 | 0.3929 |
| compas | gradient_boosting | shap | [View Details](#) | 0.0013 | 0.6100 | 0.0250 | 0.0000 | 0.0000 | 0.7096 | 0.3233 | 0.7133 | 0.6705 | 0.3429 | 0.9999 | 0.4850 | 0.6490 | 0.1551 | 0.3233 | 0.4549 |
| compas | gradient_boosting | lime | [View Details](#) | 0.0163 | 0.4000 | 0.1400 | 0.0000 | 0.3665 | 0.9617 | 0.5600 | 0.7133 | 0.5682 | 0.5839 | 1.0000 | 0.8292 | 0.6500 | 0.0307 | 0.5533 | 0.8093 |
| compas | gradient_boosting | causal_shap | [View Details](#) | 0.0307 | 0.4600 | 0.0300 | 0.0000 | 0.0000 | 0.6156 | 0.3133 | 0.6738 | 1.0000 | 0.1721 | 0.9999 | 0.2337 | 0.4502 | 0.3297 | 0.1738 | 0.1703 |
| compas | gradient_boosting | shap_interactive | [View Details](#) | 0.0326 | 0.6667 | 0.0611 | 0.0352 | 0.0000 | 0.6118 | 0.5000 | 0.6608 | 0.7493 | 0.3400 | 1.0000 | 0.3777 | 0.4833 | 0.4946 | 0.2744 | 0.2721 |
| compas | gradient_boosting | prototype | [View Details](#) | 0.0004 | 0.7500 | 0.6892 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | gradient_boosting | counterfactual | [View Details](#) | 0.0004 | 0.6650 | 0.3223 | 1.0000 | 0.9948 | 0.3208 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | gradient_boosting | bayesian_rule_list | [View Details](#) | 0.0008 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 0.0000 | 0.0000 | 0.0000 |
| compas | gradient_boosting | corels | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 1.0000 | 0.0000 | 0.0000 |
| compas | gradient_boosting | feature_ablation | [View Details](#) | 0.0011 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.6815 | 0.3333 | 0.6933 | 1.0000 | 0.3536 | 0.9999 | 0.5000 | 0.5980 | 0.1767 | 0.3333 | 0.4633 |
| compas | mlp | shap | [View Details](#) | 0.0009 | 0.5800 | 0.0100 | 0.0000 | 0.0000 | 0.7432 | 0.3800 | 0.8000 | 0.6556 | 0.4031 | 1.0000 | 0.5700 | 0.6430 | 0.0126 | 0.3800 | 0.5674 |
| compas | mlp | lime | [View Details](#) | 0.0126 | 0.0400 | 0.0000 | 0.0000 | 0.0000 | 0.7909 | 0.3600 | 0.7900 | 0.6136 | 0.3422 | 1.0000 | 0.4877 | 0.5413 | 0.0847 | 0.3300 | 0.4553 |
| compas | mlp | integrated_gradients | [View Details](#) | 0.0336 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | causal_shap | [View Details](#) | 0.0153 | 0.3400 | 0.0000 | 0.0000 | 0.0000 | 0.5885 | 0.3067 | 0.8046 | 1.0000 | 0.2568 | 1.0000 | 0.3432 | 0.5058 | 0.1481 | 0.2366 | 0.3119 |
| compas | mlp | shapley_flow | [View Details](#) | 0.0074 | 0.2333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | shap_interactive | [View Details](#) | 0.0165 | 0.5000 | 0.0111 | 0.0327 | 0.0000 | 0.6456 | 0.5111 | 0.8059 | 0.6015 | 0.4634 | 1.0000 | 0.5193 | 0.6008 | 0.3694 | 0.3600 | 0.4306 |
| compas | mlp | prototype | [View Details](#) | 0.0003 | 0.7150 | 0.7000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | counterfactual | [View Details](#) | 0.0004 | 0.7250 | 0.3166 | 1.0000 | 0.8997 | 0.5523 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | influence_functions | [View Details](#) | 0.0245 | 0.0000 | 0.0000 | 0.0000 | 0.3834 | 0.7184 | 0.6667 | 0.4325 | 1.0000 | 0.4194 | 1.0000 | 0.6078 | 0.6356 | 0.6415 | 0.4325 | 0.3585 |
| compas | mlp | bayesian_rule_list | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | corels | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 1.0000 | 0.0000 | 0.0000 |
| compas | mlp | feature_ablation | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.7167 | 0.3800 | 0.8000 | 1.0000 | 0.4031 | 1.0000 | 0.5700 | 0.5800 | 0.0126 | 0.3800 | 0.5674 |
| mnist | cnn | prototype | [View Details](#) | 0.0019 | 0.9800 | 0.66179883 | 1.0000 | 0.8955 | 0.1336 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| mnist | cnn | counterfactual | [View Details](#) | 0.0035 | 0.9800 | 0.4679225 | 1.0000 | 0.7809 | 0.8833 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| mnist | cnn | tcav | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| mnist | cnn | concept_bottleneck | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| mnist | cnn | occlusion | [View Details](#) | 0.0219 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| mnist | vit | tcav | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| mnist | vit | concept_bottleneck | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| mnist | vit | occlusion | [View Details](#) | 0.0900 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| imdb | bert | lime | [View Details](#) | 0.0888 | 0.8400 | 0.0000 | 0.0000 | 0.0769 | 0.1526 | 0.7400 | 0.4506 | 1.0000 | 0.4687 | 0.0000 | 0.4594 | 0.5942 | 0.9038 | 0.4506 | 0.0962 |
| imdb | bert | text_occlusion | [View Details](#) | 0.0493 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0552 | 0.0046 | 0.8016 | 1.0000 | 0.0890 | 0.0000 | 0.0824 | 0.6360 | 0.2137 | 0.0816 | 0.0663 |
| imdb | bert | attention_visualization | [View Details](#) | 0.1220 | 0.0000 | 0.0000 | 0.0000 | 0.7141 | 0.0947 | 0.7005 | 0.0381 | 1.0000 | 0.0360 | 0.0000 | 0.0055 | 0.5880 | 0.9994 | 0.0381 | 0.0006 |
| imdb | lstm | lime | [View Details](#) | 0.0847 | 0.8000 | 0.0000 | 0.0000 | 0.0000 | 0.1255 | 0.7400 | 0.4763 | 1.0000 | 0.5240 | 0.0000 | 0.5058 | 0.5677 | 0.8899 | 0.4763 | 0.1101 |
| imdb | lstm | text_occlusion | [View Details](#) | 0.0501 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0627 | 0.0062 | 0.7822 | 1.0000 | 0.1734 | 0.0000 | 0.1638 | 0.6500 | 0.2449 | 0.1622 | 0.1351 |
| imdb | lstm | attention_visualization | [View Details](#) | 0.1300 | 0.0000 | 0.0000 | 0.0000 | 0.7135 | 0.0924 | 0.6971 | 0.0385 | 1.0000 | 0.0371 | 0.0000 | 0.0059 | 0.5600 | 0.9994 | 0.0385 | 0.0006 |

## Detailed Explanation Analysis

Summary of detailed explanations generated for the entire test set.

| Dataset | Model | Method | Test Instances | Valid Explanations | Accuracy | Avg Feature Importance | Detailed Files |
|---------|-------|--------|----------------|-------------------|----------|----------------------|----------------|
| adult_income | decision_tree | shap | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\shap_detailed_explanations.json) |
| adult_income | decision_tree | lime | 6033 | 6033 | 0.833 | 0.0356 | [JSON](detailed_explanations\adult_income\decision_tree\lime_detailed_explanations.json) |
| adult_income | decision_tree | causal_shap | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\causal_shap_detailed_explanations.json) |
| adult_income | decision_tree | shapley_flow | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\shapley_flow_detailed_explanations.json) |
| adult_income | decision_tree | shap_interactive | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\shap_interactive_detailed_explanations.json) |
| adult_income | decision_tree | prototype | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\prototype_detailed_explanations.json) |
| adult_income | decision_tree | counterfactual | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\counterfactual_detailed_explanations.json) |
| adult_income | decision_tree | bayesian_rule_list | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\bayesian_rule_list_detailed_explanations.json) |
| adult_income | decision_tree | corels | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\corels_detailed_explanations.json) |
| adult_income | decision_tree | feature_ablation | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\feature_ablation_detailed_explanations.json) |
| adult_income | random_forest | shap | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\shap_detailed_explanations.json) |
| adult_income | random_forest | lime | 6033 | 6033 | 0.833 | 0.0299 | [JSON](detailed_explanations\adult_income\random_forest\lime_detailed_explanations.json) |
| adult_income | random_forest | causal_shap | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\causal_shap_detailed_explanations.json) |
| adult_income | random_forest | shapley_flow | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\shapley_flow_detailed_explanations.json) |
| adult_income | random_forest | shap_interactive | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\shap_interactive_detailed_explanations.json) |
| adult_income | random_forest | prototype | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\prototype_detailed_explanations.json) |
| adult_income | random_forest | counterfactual | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\counterfactual_detailed_explanations.json) |
| adult_income | random_forest | bayesian_rule_list | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\bayesian_rule_list_detailed_explanations.json) |
| adult_income | random_forest | corels | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\corels_detailed_explanations.json) |
| adult_income | random_forest | feature_ablation | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\feature_ablation_detailed_explanations.json) |
| adult_income | gradient_boosting | shap | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\shap_detailed_explanations.json) |
| adult_income | gradient_boosting | lime | 6033 | 6033 | 0.836 | 0.0271 | [JSON](detailed_explanations\adult_income\gradient_boosting\lime_detailed_explanations.json) |
| adult_income | gradient_boosting | causal_shap | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\causal_shap_detailed_explanations.json) |
| adult_income | gradient_boosting | shap_interactive | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\shap_interactive_detailed_explanations.json) |
| adult_income | gradient_boosting | prototype | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\prototype_detailed_explanations.json) |
| adult_income | gradient_boosting | counterfactual | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\counterfactual_detailed_explanations.json) |
| adult_income | gradient_boosting | bayesian_rule_list | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\bayesian_rule_list_detailed_explanations.json) |
| adult_income | gradient_boosting | corels | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\corels_detailed_explanations.json) |
| adult_income | gradient_boosting | feature_ablation | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\feature_ablation_detailed_explanations.json) |
| adult_income | mlp | shap | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\shap_detailed_explanations.json) |
| adult_income | mlp | lime | 6033 | 6033 | 0.824 | 0.0209 | [JSON](detailed_explanations\adult_income\mlp\lime_detailed_explanations.json) |
| adult_income | mlp | integrated_gradients | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\integrated_gradients_detailed_explanations.json) |
| adult_income | mlp | causal_shap | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\causal_shap_detailed_explanations.json) |
| adult_income | mlp | shapley_flow | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\shapley_flow_detailed_explanations.json) |
| adult_income | mlp | shap_interactive | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\shap_interactive_detailed_explanations.json) |
| adult_income | mlp | prototype | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\prototype_detailed_explanations.json) |
| adult_income | mlp | counterfactual | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\counterfactual_detailed_explanations.json) |
| adult_income | mlp | influence_functions | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\influence_functions_detailed_explanations.json) |
| adult_income | mlp | bayesian_rule_list | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\bayesian_rule_list_detailed_explanations.json) |
| adult_income | mlp | corels | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\corels_detailed_explanations.json) |
| adult_income | mlp | feature_ablation | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\feature_ablation_detailed_explanations.json) |
| compas | decision_tree | shap | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\shap_detailed_explanations.json) |
| compas | decision_tree | lime | 1443 | 1443 | 0.674 | 0.2657 | [JSON](detailed_explanations\compas\decision_tree\lime_detailed_explanations.json) |
| compas | decision_tree | causal_shap | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\causal_shap_detailed_explanations.json) |
| compas | decision_tree | shapley_flow | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\shapley_flow_detailed_explanations.json) |
| compas | decision_tree | shap_interactive | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\shap_interactive_detailed_explanations.json) |
| compas | decision_tree | prototype | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\prototype_detailed_explanations.json) |
| compas | decision_tree | counterfactual | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\counterfactual_detailed_explanations.json) |
| compas | decision_tree | bayesian_rule_list | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\bayesian_rule_list_detailed_explanations.json) |
| compas | decision_tree | corels | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\corels_detailed_explanations.json) |
| compas | decision_tree | feature_ablation | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\feature_ablation_detailed_explanations.json) |
| compas | random_forest | shap | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\shap_detailed_explanations.json) |
| compas | random_forest | lime | 1443 | 1443 | 0.683 | 0.0651 | [JSON](detailed_explanations\compas\random_forest\lime_detailed_explanations.json) |
| compas | random_forest | causal_shap | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\causal_shap_detailed_explanations.json) |
| compas | random_forest | shapley_flow | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\shapley_flow_detailed_explanations.json) |
| compas | random_forest | shap_interactive | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\shap_interactive_detailed_explanations.json) |
| compas | random_forest | prototype | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\prototype_detailed_explanations.json) |
| compas | random_forest | counterfactual | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\counterfactual_detailed_explanations.json) |
| compas | random_forest | bayesian_rule_list | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\bayesian_rule_list_detailed_explanations.json) |
| compas | random_forest | corels | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\corels_detailed_explanations.json) |
| compas | random_forest | feature_ablation | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\feature_ablation_detailed_explanations.json) |
| compas | gradient_boosting | shap | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\shap_detailed_explanations.json) |
| compas | gradient_boosting | lime | 1443 | 1443 | 0.695 | 0.2287 | [JSON](detailed_explanations\compas\gradient_boosting\lime_detailed_explanations.json) |
| compas | gradient_boosting | causal_shap | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\causal_shap_detailed_explanations.json) |
| compas | gradient_boosting | shap_interactive | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\shap_interactive_detailed_explanations.json) |
| compas | gradient_boosting | prototype | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\prototype_detailed_explanations.json) |
| compas | gradient_boosting | counterfactual | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\counterfactual_detailed_explanations.json) |
| compas | gradient_boosting | bayesian_rule_list | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\bayesian_rule_list_detailed_explanations.json) |
| compas | gradient_boosting | corels | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\corels_detailed_explanations.json) |
| compas | gradient_boosting | feature_ablation | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\feature_ablation_detailed_explanations.json) |
| compas | mlp | shap | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\shap_detailed_explanations.json) |
| compas | mlp | lime | 1443 | 1443 | 0.685 | 0.1127 | [JSON](detailed_explanations\compas\mlp\lime_detailed_explanations.json) |
| compas | mlp | integrated_gradients | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\integrated_gradients_detailed_explanations.json) |
| compas | mlp | causal_shap | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\causal_shap_detailed_explanations.json) |
| compas | mlp | shapley_flow | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\shapley_flow_detailed_explanations.json) |
| compas | mlp | shap_interactive | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\shap_interactive_detailed_explanations.json) |
| compas | mlp | prototype | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\prototype_detailed_explanations.json) |
| compas | mlp | counterfactual | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\counterfactual_detailed_explanations.json) |
| compas | mlp | influence_functions | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\influence_functions_detailed_explanations.json) |
| compas | mlp | bayesian_rule_list | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\bayesian_rule_list_detailed_explanations.json) |
| compas | mlp | corels | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\corels_detailed_explanations.json) |
| compas | mlp | feature_ablation | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\feature_ablation_detailed_explanations.json) |
| mnist | cnn | prototype | 200 | 200 | 0.980 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\prototype_detailed_explanations.json) |
| mnist | cnn | counterfactual | 200 | 200 | 0.980 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\counterfactual_detailed_explanations.json) |
| mnist | cnn | tcav | 200 | 200 | 0.980 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\tcav_detailed_explanations.json) |
| mnist | cnn | concept_bottleneck | 200 | 200 | 0.980 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\concept_bottleneck_detailed_explanations.json) |
| mnist | cnn | occlusion | 200 | 200 | 0.980 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\occlusion_detailed_explanations.json) |
| mnist | vit | tcav | 200 | 200 | 0.700 | 0.0000 | [JSON](detailed_explanations\mnist\vit\tcav_detailed_explanations.json) |
| mnist | vit | concept_bottleneck | 200 | 200 | 0.700 | 0.0000 | [JSON](detailed_explanations\mnist\vit\concept_bottleneck_detailed_explanations.json) |
| mnist | vit | occlusion | 200 | 200 | 0.700 | 0.0000 | [JSON](detailed_explanations\mnist\vit\occlusion_detailed_explanations.json) |
| imdb | bert | lime | 200 | 200 | 0.810 | 0.0200 | [JSON](detailed_explanations\imdb\bert\lime_detailed_explanations.json) |
| imdb | bert | text_occlusion | 200 | 200 | 0.810 | 0.0000 | [JSON](detailed_explanations\imdb\bert\text_occlusion_detailed_explanations.json) |
| imdb | bert | attention_visualization | 200 | 200 | 0.810 | 0.0104 | [JSON](detailed_explanations\imdb\bert\attention_visualization_detailed_explanations.json) |
| imdb | lstm | lime | 200 | 200 | 0.815 | 0.0200 | [JSON](detailed_explanations\imdb\lstm\lime_detailed_explanations.json) |
| imdb | lstm | text_occlusion | 200 | 200 | 0.815 | 0.0000 | [JSON](detailed_explanations\imdb\lstm\text_occlusion_detailed_explanations.json) |
| imdb | lstm | attention_visualization | 200 | 200 | 0.815 | 0.0104 | [JSON](detailed_explanations\imdb\lstm\attention_visualization_detailed_explanations.json) |

## Model Performance Analysis by Dataset

### adult_income

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| decision_tree | 0.8405 | 0.8326 | N/A | N/A |
| random_forest | 0.8425 | 0.8333 | N/A | N/A |
| gradient_boosting | 0.8387 | 0.8356 | N/A | N/A |
| mlp | 0.8257 | 0.8236 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| decision_tree | shap | 0.0007 | 0.1900 | 0.0200 |
| decision_tree | lime | 0.0096 | 0.0600 | 0.0267 |
| decision_tree | causal_shap | 0.0161 | 0.2400 | 0.0200 |
| decision_tree | shapley_flow | 0.0068 | 0.1000 | 0.0000 |
| decision_tree | shap_interactive | 0.0177 | 0.3000 | 0.0333 |
| decision_tree | prototype | 0.0008 | 0.6900 | 0.8369 |
| decision_tree | counterfactual | 0.0005 | 0.7200 | 0.1868 |
| decision_tree | bayesian_rule_list | 0.0005 | 0.0000 | 0.0000 |
| decision_tree | corels | 0.0003 | 0.0000 | 0.0000 |
| decision_tree | feature_ablation | 0.0004 | 0.0000 | 0.0000 |
| random_forest | shap | 0.0323 | 0.1900 | 0.0200 |
| random_forest | lime | 0.0184 | 0.1000 | 0.0200 |
| random_forest | causal_shap | 0.6472 | 0.2400 | 0.0200 |
| random_forest | shapley_flow | 0.2995 | 0.1333 | 0.0000 |
| random_forest | shap_interactive | 0.7332 | 0.3000 | 0.0333 |
| random_forest | prototype | 0.0042 | 0.6850 | 0.8065 |
| random_forest | counterfactual | 0.0055 | 0.6800 | 0.1849 |
| random_forest | bayesian_rule_list | 0.0059 | 0.0000 | 0.0000 |
| random_forest | corels | 0.0047 | 0.0000 | 0.0000 |
| random_forest | feature_ablation | 0.0279 | 0.0000 | 0.0000 |
| gradient_boosting | shap | 0.0023 | 0.2100 | 0.0300 |
| gradient_boosting | lime | 0.0155 | 0.1200 | 0.0400 |
| gradient_boosting | causal_shap | 0.0507 | 0.2600 | 0.0200 |
| gradient_boosting | shap_interactive | 0.0610 | 0.3000 | 0.0333 |
| gradient_boosting | prototype | 0.0012 | 0.7100 | 0.8096 |
| gradient_boosting | counterfactual | 0.0010 | 0.7200 | 0.1808 |
| gradient_boosting | bayesian_rule_list | 0.0009 | 0.0000 | 0.0000 |
| gradient_boosting | corels | 0.0008 | 0.0000 | 0.0000 |
| gradient_boosting | feature_ablation | 0.0013 | 0.0000 | 0.0000 |
| mlp | shap | 0.0010 | 0.2200 | 0.0250 |
| mlp | lime | 0.0142 | 0.0800 | 0.0233 |
| mlp | integrated_gradients | 0.0610 | 0.0000 | 0.0000 |
| mlp | causal_shap | 0.0266 | 0.2400 | 0.0090 |
| mlp | shapley_flow | 0.0107 | 0.1000 | 0.0000 |
| mlp | shap_interactive | 0.0324 | 0.3333 | 0.0178 |
| mlp | prototype | 0.0011 | 0.7050 | 0.8031 |
| mlp | counterfactual | 0.0008 | 0.7400 | 0.1976 |
| mlp | influence_functions | 0.0342 | 0.0000 | 0.0000 |
| mlp | bayesian_rule_list | 0.0007 | 0.0000 | 0.0000 |
| mlp | corels | 0.0005 | 0.0000 | 0.0000 |
| mlp | feature_ablation | 0.0005 | 0.0000 | 0.0000 |

### compas

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| decision_tree | 0.7375 | 0.6736 | N/A | N/A |
| random_forest | 0.7538 | 0.6826 | N/A | N/A |
| gradient_boosting | 0.7054 | 0.6951 | N/A | N/A |
| mlp | 0.6881 | 0.6854 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| decision_tree | shap | 0.0006 | 0.6500 | 0.0300 |
| decision_tree | lime | 0.0155 | 0.3000 | 0.0800 |
| decision_tree | causal_shap | 0.0125 | 0.5000 | 0.0000 |
| decision_tree | shapley_flow | 0.0051 | 0.3333 | 0.0000 |
| decision_tree | shap_interactive | 0.0178 | 0.6667 | 0.0111 |
| decision_tree | prototype | 0.0003 | 0.6550 | 0.7320 |
| decision_tree | counterfactual | 0.0002 | 0.6300 | 0.2618 |
| decision_tree | bayesian_rule_list | 0.0004 | 0.0000 | 0.0000 |
| decision_tree | corels | 0.0002 | 0.0000 | 0.0000 |
| decision_tree | feature_ablation | 0.0004 | 0.0000 | 0.0000 |
| random_forest | shap | 0.0273 | 0.6300 | 0.0383 |
| random_forest | lime | 0.0274 | 0.3200 | 0.0867 |
| random_forest | causal_shap | 0.5443 | 0.4800 | 0.0300 |
| random_forest | shapley_flow | 0.2809 | 0.4333 | 0.0000 |
| random_forest | shap_interactive | 0.6092 | 0.6333 | 0.0556 |
| random_forest | prototype | 0.0042 | 0.7200 | 0.6803 |
| random_forest | counterfactual | 0.0052 | 0.6850 | 0.3126 |
| random_forest | bayesian_rule_list | 0.0045 | 0.0000 | 0.0000 |
| random_forest | corels | 0.0049 | 0.0000 | 0.0000 |
| random_forest | feature_ablation | 0.0202 | 0.0000 | 0.0000 |
| gradient_boosting | shap | 0.0013 | 0.6100 | 0.0250 |
| gradient_boosting | lime | 0.0163 | 0.4000 | 0.1400 |
| gradient_boosting | causal_shap | 0.0307 | 0.4600 | 0.0300 |
| gradient_boosting | shap_interactive | 0.0326 | 0.6667 | 0.0611 |
| gradient_boosting | prototype | 0.0004 | 0.7500 | 0.6892 |
| gradient_boosting | counterfactual | 0.0004 | 0.6650 | 0.3223 |
| gradient_boosting | bayesian_rule_list | 0.0008 | 0.0000 | 0.0000 |
| gradient_boosting | corels | 0.0004 | 0.0000 | 0.0000 |
| gradient_boosting | feature_ablation | 0.0011 | 0.0000 | 0.0000 |
| mlp | shap | 0.0009 | 0.5800 | 0.0100 |
| mlp | lime | 0.0126 | 0.0400 | 0.0000 |
| mlp | integrated_gradients | 0.0336 | 0.0000 | 0.0000 |
| mlp | causal_shap | 0.0153 | 0.3400 | 0.0000 |
| mlp | shapley_flow | 0.0074 | 0.2333 | 0.0000 |
| mlp | shap_interactive | 0.0165 | 0.5000 | 0.0111 |
| mlp | prototype | 0.0003 | 0.7150 | 0.7000 |
| mlp | counterfactual | 0.0004 | 0.7250 | 0.3166 |
| mlp | influence_functions | 0.0245 | 0.0000 | 0.0000 |
| mlp | bayesian_rule_list | 0.0005 | 0.0000 | 0.0000 |
| mlp | corels | 0.0005 | 0.0000 | 0.0000 |
| mlp | feature_ablation | 0.0004 | 0.0000 | 0.0000 |

### imdb

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| bert | 0.9180 | 0.8100 | N/A | N/A |
| lstm | 0.8870 | 0.8150 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| bert | lime | 0.0888 | 0.8400 | 0.0000 |
| bert | text_occlusion | 0.0493 | 0.0000 | 0.0000 |
| bert | attention_visualization | 0.1220 | 0.0000 | 0.0000 |
| lstm | lime | 0.0847 | 0.8000 | 0.0000 |
| lstm | text_occlusion | 0.0501 | 0.0000 | 0.0000 |
| lstm | attention_visualization | 0.1300 | 0.0000 | 0.0000 |

### mnist

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| cnn | 0.9940 | 0.9800 | N/A | N/A |
| vit | 0.7800 | 0.7000 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| cnn | prototype | 0.0019 | 0.9800 | 0.66179883 |
| cnn | counterfactual | 0.0035 | 0.9800 | 0.4679225 |
| cnn | tcav | 0.0000 | 0.0000 | 0.0000 |
| cnn | concept_bottleneck | 0.0000 | 0.0000 | 0.0000 |
| cnn | occlusion | 0.0219 | 0.0000 | 0.0000 |
| vit | tcav | 0.0000 | 0.0000 | 0.0000 |
| vit | concept_bottleneck | 0.0000 | 0.0000 | 0.0000 |
| vit | occlusion | 0.0900 | 0.0000 | 0.0000 |

## Best Performing Models by Dataset

Ranking models by test accuracy on each dataset.

### adult_income - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | gradient_boosting | 0.8356 |
| 2 | random_forest | 0.8333 |
| 3 | decision_tree | 0.8326 |
| 4 | mlp | 0.8236 |

### compas - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | gradient_boosting | 0.6951 |
| 2 | mlp | 0.6854 |
| 3 | random_forest | 0.6826 |
| 4 | decision_tree | 0.6736 |

### imdb - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | lstm | 0.8150 |
| 2 | bert | 0.8100 |

### mnist - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | cnn | 0.9800 |
| 2 | vit | 0.7000 |

## Top Performing XAI Combinations

### Best Time Complexity

| Rank | Dataset | Model | Explanation | Score |
|------|---------|-------|-------------|-------|
| 1 | adult_income | random_forest | shap_interactive | 0.7332 |
| 2 | adult_income | random_forest | causal_shap | 0.6472 |
| 3 | compas | random_forest | shap_interactive | 0.6092 |
| 4 | compas | random_forest | causal_shap | 0.5443 |
| 5 | adult_income | random_forest | shapley_flow | 0.2995 |
| 6 | compas | random_forest | shapley_flow | 0.2809 |
| 7 | imdb | lstm | attention_visualization | 0.1300 |
| 8 | imdb | bert | attention_visualization | 0.1220 |
| 9 | mnist | vit | occlusion | 0.0900 |
| 10 | imdb | bert | lime | 0.0888 |

### Best Faithfulness

| Rank | Dataset | Model | Explanation | Score |
|------|---------|-------|-------------|-------|
| 1 | mnist | cnn | prototype | 0.9800 |
| 2 | mnist | cnn | counterfactual | 0.9800 |
| 3 | imdb | bert | lime | 0.8400 |
| 4 | imdb | lstm | lime | 0.8000 |
| 5 | compas | gradient_boosting | prototype | 0.7500 |
| 6 | adult_income | mlp | counterfactual | 0.7400 |
| 7 | compas | mlp | counterfactual | 0.7250 |
| 8 | adult_income | decision_tree | counterfactual | 0.7200 |
| 9 | adult_income | gradient_boosting | counterfactual | 0.7200 |
| 10 | compas | random_forest | prototype | 0.7200 |

### Best Monotonicity

| Rank | Dataset | Model | Explanation | Score |
|------|---------|-------|-------------|-------|
| 1 | adult_income | decision_tree | prototype | 0.8369 |
| 2 | adult_income | gradient_boosting | prototype | 0.8096 |
| 3 | adult_income | random_forest | prototype | 0.8065 |
| 4 | adult_income | mlp | prototype | 0.8031 |
| 5 | compas | decision_tree | prototype | 0.7320 |
| 6 | compas | mlp | prototype | 0.7000 |
| 7 | compas | gradient_boosting | prototype | 0.6892 |
| 8 | compas | random_forest | prototype | 0.6803 |
| 9 | compas | gradient_boosting | counterfactual | 0.3223 |
| 10 | compas | mlp | counterfactual | 0.3166 |

### Best Completeness

| Rank | Dataset | Model | Explanation | Score |
|------|---------|-------|-------------|-------|
| 1 | adult_income | decision_tree | prototype | 1.0000 |
| 2 | adult_income | decision_tree | counterfactual | 1.0000 |
| 3 | adult_income | random_forest | prototype | 1.0000 |
| 4 | adult_income | random_forest | counterfactual | 1.0000 |
| 5 | adult_income | gradient_boosting | prototype | 1.0000 |
| 6 | adult_income | gradient_boosting | counterfactual | 1.0000 |
| 7 | adult_income | mlp | prototype | 1.0000 |
| 8 | adult_income | mlp | counterfactual | 1.0000 |
| 9 | compas | decision_tree | prototype | 1.0000 |
| 10 | compas | decision_tree | counterfactual | 1.0000 |

### Best Stability

| Rank | Dataset | Model | Explanation | Score |
|------|---------|-------|-------------|-------|
| 1 | adult_income | decision_tree | shapley_flow | 1.0000 |
| 2 | adult_income | decision_tree | counterfactual | 1.0000 |
| 3 | adult_income | decision_tree | bayesian_rule_list | 1.0000 |
| 4 | adult_income | random_forest | shapley_flow | 1.0000 |
| 5 | adult_income | random_forest | bayesian_rule_list | 1.0000 |
| 6 | adult_income | gradient_boosting | bayesian_rule_list | 1.0000 |
| 7 | adult_income | mlp | integrated_gradients | 1.0000 |
| 8 | adult_income | mlp | shapley_flow | 1.0000 |
| 9 | adult_income | mlp | bayesian_rule_list | 1.0000 |
| 10 | compas | decision_tree | shapley_flow | 1.0000 |

