# Comprehensive XAI Benchmarking Report

Generated on: 2025-08-24 19:04:47

## Summary

- **Datasets**: 16
- **Models**: 15
- **Explanation Methods**: 17
- **Evaluation Metrics**: 16
- **Total Combinations**: 666

### Datasets
- **20newsgroups** (text)
- **adult_income** (tabular)
- **ag_news** (text)
- **breast_cancer** (tabular)
- **cifar10** (image)
- **compas** (tabular)
- **diabetes** (tabular)
- **digits** (tabular)
- **fashion_mnist** (image)
- **german_credit** (tabular)
- **heart_disease** (tabular)
- **imdb** (text)
- **iris** (tabular)
- **mnist** (image)
- **wine_classification** (tabular)
- **wine_quality** (tabular)

### Models
- **bert** (bert)
- **cnn** (cnn)
- **decision_tree** (decision_tree)
- **gradient_boosting** (gradient_boosting)
- **linear_regression** (linear_regression)
- **logistic_regression** (logistic_regression)
- **lstm** (lstm)
- **mlp** (mlp)
- **naive_bayes_text** (naive_bayes_text)
- **random_forest** (random_forest)
- **resnet** (resnet)
- **roberta** (roberta)
- **svm_text** (svm_text)
- **vit** (vit)
- **xgboost_text** (xgboost_text)

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
| adult_income | decision_tree | 0.8405 | 0.8326 | N/A | N/A | train_f1: 0.8247; test_f1: 0.8159; train_precision: 0.8365; test_precision: 0.8264; train_recall: 0.8405; test_recall: 0.8326; overfitting_gap: 0.0079; overfitting_severity: low; class_accuracies: [0.957845950121386, 0.45472703062583225]; n_classes: 2.0000; n_train_samples: 24129.0000; n_test_samples: 6033.0000; training_time: 0.0379; model_complexity: {'n_parameters': 13, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| adult_income | random_forest | 0.8425 | 0.8333 | N/A | N/A | train_f1: 0.8267; test_f1: 0.8160; train_precision: 0.8392; test_precision: 0.8278; train_recall: 0.8425; test_recall: 0.8333; overfitting_gap: 0.0092; overfitting_severity: low; class_accuracies: [0.9602736702714633, 0.45006657789613846]; n_classes: 2.0000; n_train_samples: 24129.0000; n_test_samples: 6033.0000; training_time: 0.8299; model_complexity: {'n_parameters': 19, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| adult_income | gradient_boosting | 0.8387 | 0.8356 | N/A | N/A | train_f1: 0.8229; test_f1: 0.8189; train_precision: 0.8340; test_precision: 0.8305; train_recall: 0.8387; test_recall: 0.8356; overfitting_gap: 0.0031; overfitting_severity: low; class_accuracies: [0.9607150739351137, 0.4580559254327563]; n_classes: 2.0000; n_train_samples: 24129.0000; n_test_samples: 6033.0000; training_time: 0.8993; model_complexity: {'n_parameters': 20, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| adult_income | mlp | 0.8257 | 0.8236 | N/A | N/A | train_f1: 0.8112; test_f1: 0.8083; train_precision: 0.8161; test_precision: 0.8137; train_recall: 0.8257; test_recall: 0.8236; overfitting_gap: 0.0021; overfitting_severity: low; class_accuracies: [0.9452659457073493, 0.4567243675099867]; n_classes: 2.0000; n_train_samples: 24129.0000; n_test_samples: 6033.0000; training_time: 10.8726; model_complexity: {'n_parameters': 23, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| adult_income | linear_regression | 0.7913 | 0.7915 | N/A | N/A | train_f1: 0.7528; test_f1: 0.7517; train_precision: 0.7790; test_precision: 0.7807; train_recall: 0.7913; test_recall: 0.7915; overfitting_gap: -0.0002; overfitting_severity: low; class_accuracies: [0.9684396380489958, 0.2576564580559254]; n_classes: 2.0000; n_train_samples: 24129.0000; n_test_samples: 6033.0000; training_time: 0.0296; model_complexity: {'n_parameters': 5, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| adult_income | logistic_regression | 0.8089 | 0.8087 | N/A | N/A | train_f1: 0.7886; test_f1: 0.7876; train_precision: 0.7959; test_precision: 0.7960; train_recall: 0.8089; test_recall: 0.8087; overfitting_gap: 0.0001; overfitting_severity: low; class_accuracies: [0.9472522621937762, 0.39081225033288947]; n_classes: 2.0000; n_train_samples: 24129.0000; n_test_samples: 6033.0000; training_time: 0.0406; model_complexity: {'n_parameters': 15, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| compas | decision_tree | 0.7375 | 0.6736 | N/A | N/A | train_f1: 0.7347; test_f1: 0.6706; train_precision: 0.7381; test_precision: 0.6721; train_recall: 0.7375; test_recall: 0.6736; overfitting_gap: 0.0639; overfitting_severity: low; class_accuracies: [0.755359394703657, 0.5738461538461539]; n_classes: 2.0000; n_train_samples: 5771.0000; n_test_samples: 1443.0000; training_time: 0.0073; model_complexity: {'n_parameters': 13, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| compas | random_forest | 0.7538 | 0.6826 | N/A | N/A | train_f1: 0.7516; test_f1: 0.6797; train_precision: 0.7543; test_precision: 0.6813; train_recall: 0.7538; test_recall: 0.6826; overfitting_gap: 0.0712; overfitting_severity: low; class_accuracies: [0.7629255989911727, 0.5846153846153846]; n_classes: 2.0000; n_train_samples: 5771.0000; n_test_samples: 1443.0000; training_time: 0.2047; model_complexity: {'n_parameters': 19, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| compas | gradient_boosting | 0.7054 | 0.6951 | N/A | N/A | train_f1: 0.7025; test_f1: 0.6924; train_precision: 0.7049; test_precision: 0.6941; train_recall: 0.7054; test_recall: 0.6951; overfitting_gap: 0.0103; overfitting_severity: low; class_accuracies: [0.7730138713745272, 0.6]; n_classes: 2.0000; n_train_samples: 5771.0000; n_test_samples: 1443.0000; training_time: 0.3245; model_complexity: {'n_parameters': 20, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| compas | mlp | 0.6881 | 0.6854 | N/A | N/A | train_f1: 0.6862; test_f1: 0.6837; train_precision: 0.6868; test_precision: 0.6840; train_recall: 0.6881; test_recall: 0.6854; overfitting_gap: 0.0027; overfitting_severity: low; class_accuracies: [0.7490542244640606, 0.6076923076923076]; n_classes: 2.0000; n_train_samples: 5771.0000; n_test_samples: 1443.0000; training_time: 1.4766; model_complexity: {'n_parameters': 23, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| compas | linear_regression | 0.6749 | 0.6868 | N/A | N/A | train_f1: 0.6651; test_f1: 0.6776; train_precision: 0.6785; test_precision: 0.6912; train_recall: 0.6749; test_recall: 0.6868; overfitting_gap: -0.0118; overfitting_severity: low; class_accuracies: [0.8284993694829761, 0.5138461538461538]; n_classes: 2.0000; n_train_samples: 5771.0000; n_test_samples: 1443.0000; training_time: 0.0011; model_complexity: {'n_parameters': 5, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| compas | logistic_regression | 0.6767 | 0.6854 | N/A | N/A | train_f1: 0.6694; test_f1: 0.6779; train_precision: 0.6779; test_precision: 0.6877; train_recall: 0.6767; test_recall: 0.6854; overfitting_gap: -0.0087; overfitting_severity: low; class_accuracies: [0.8133669609079445, 0.5292307692307693]; n_classes: 2.0000; n_train_samples: 5771.0000; n_test_samples: 1443.0000; training_time: 0.0031; model_complexity: {'n_parameters': 15, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| breast_cancer | decision_tree | 1.0000 | 0.9123 | N/A | N/A | train_f1: 1.0000; test_f1: 0.9130; train_precision: 1.0000; test_precision: 0.9161; train_recall: 1.0000; test_recall: 0.9123; overfitting_gap: 0.0877; overfitting_severity: low; class_accuracies: [0.9285714285714286, 0.9027777777777778]; n_classes: 2.0000; n_train_samples: 455.0000; n_test_samples: 114.0000; training_time: 0.0070; model_complexity: {'n_parameters': 13, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| breast_cancer | random_forest | 1.0000 | 0.9561 | N/A | N/A | train_f1: 1.0000; test_f1: 0.9560; train_precision: 1.0000; test_precision: 0.9561; train_recall: 1.0000; test_recall: 0.9561; overfitting_gap: 0.0439; overfitting_severity: low; class_accuracies: [0.9285714285714286, 0.9722222222222222]; n_classes: 2.0000; n_train_samples: 455.0000; n_test_samples: 114.0000; training_time: 0.1364; model_complexity: {'n_parameters': 19, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| breast_cancer | gradient_boosting | 1.0000 | 0.9561 | N/A | N/A | train_f1: 1.0000; test_f1: 0.9558; train_precision: 1.0000; test_precision: 0.9569; train_recall: 1.0000; test_recall: 0.9561; overfitting_gap: 0.0439; overfitting_severity: low; class_accuracies: [0.9047619047619048, 0.9861111111111112]; n_classes: 2.0000; n_train_samples: 455.0000; n_test_samples: 114.0000; training_time: 0.4393; model_complexity: {'n_parameters': 20, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| breast_cancer | mlp | 1.0000 | 0.9474 | N/A | N/A | train_f1: 1.0000; test_f1: 0.9478; train_precision: 1.0000; test_precision: 0.9507; train_recall: 1.0000; test_recall: 0.9474; overfitting_gap: 0.0526; overfitting_severity: low; class_accuracies: [0.9761904761904762, 0.9305555555555556]; n_classes: 2.0000; n_train_samples: 455.0000; n_test_samples: 114.0000; training_time: 0.3218; model_complexity: {'n_parameters': 23, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| breast_cancer | linear_regression | 0.9692 | 0.9561 | N/A | N/A | train_f1: 0.9690; test_f1: 0.9558; train_precision: 0.9702; test_precision: 0.9569; train_recall: 0.9692; test_recall: 0.9561; overfitting_gap: 0.0131; overfitting_severity: low; class_accuracies: [0.9047619047619048, 0.9861111111111112]; n_classes: 2.0000; n_train_samples: 455.0000; n_test_samples: 114.0000; training_time: 0.0057; model_complexity: {'n_parameters': 5, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| breast_cancer | logistic_regression | 0.9890 | 0.9825 | N/A | N/A | train_f1: 0.9890; test_f1: 0.9825; train_precision: 0.9891; test_precision: 0.9825; train_recall: 0.9890; test_recall: 0.9825; overfitting_gap: 0.0066; overfitting_severity: low; class_accuracies: [0.9761904761904762, 0.9861111111111112]; n_classes: 2.0000; n_train_samples: 455.0000; n_test_samples: 114.0000; training_time: 0.0089; model_complexity: {'n_parameters': 15, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| heart_disease | decision_tree | 0.9916 | 0.7333 | N/A | N/A | train_f1: 0.9916; test_f1: 0.7336; train_precision: 0.9917; test_precision: 0.7356; train_recall: 0.9916; test_recall: 0.7333; overfitting_gap: 0.2582; overfitting_severity: high; class_accuracies: [0.71875, 0.75]; n_classes: 2.0000; n_train_samples: 237.0000; n_test_samples: 60.0000; training_time: 0.0040; model_complexity: {'n_parameters': 13, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| heart_disease | random_forest | 1.0000 | 0.7333 | N/A | N/A | train_f1: 1.0000; test_f1: 0.7336; train_precision: 1.0000; test_precision: 0.7356; train_recall: 1.0000; test_recall: 0.7333; overfitting_gap: 0.2667; overfitting_severity: high; class_accuracies: [0.71875, 0.75]; n_classes: 2.0000; n_train_samples: 237.0000; n_test_samples: 60.0000; training_time: 0.1105; model_complexity: {'n_parameters': 19, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| heart_disease | gradient_boosting | 0.9451 | 0.7000 | N/A | N/A | train_f1: 0.9450; test_f1: 0.7003; train_precision: 0.9465; test_precision: 0.7022; train_recall: 0.9451; test_recall: 0.7000; overfitting_gap: 0.2451; overfitting_severity: high; class_accuracies: [0.6875, 0.7142857142857143]; n_classes: 2.0000; n_train_samples: 237.0000; n_test_samples: 60.0000; training_time: 0.0873; model_complexity: {'n_parameters': 20, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| heart_disease | mlp | 0.8186 | 0.8000 | N/A | N/A | train_f1: 0.8165; test_f1: 0.7966; train_precision: 0.8233; test_precision: 0.8100; train_recall: 0.8186; test_recall: 0.8000; overfitting_gap: 0.0186; overfitting_severity: low; class_accuracies: [0.90625, 0.6785714285714286]; n_classes: 2.0000; n_train_samples: 237.0000; n_test_samples: 60.0000; training_time: 0.2826; model_complexity: {'n_parameters': 23, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| heart_disease | linear_regression | 0.7089 | 0.8167 | N/A | N/A | train_f1: 0.7062; test_f1: 0.8156; train_precision: 0.7093; test_precision: 0.8187; train_recall: 0.7089; test_recall: 0.8167; overfitting_gap: -0.1078; overfitting_severity: low; class_accuracies: [0.875, 0.75]; n_classes: 2.0000; n_train_samples: 237.0000; n_test_samples: 60.0000; training_time: 0.0000; model_complexity: {'n_parameters': 5, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| heart_disease | logistic_regression | 0.7131 | 0.8000 | N/A | N/A | train_f1: 0.7107; test_f1: 0.7993; train_precision: 0.7133; test_precision: 0.8005; train_recall: 0.7131; test_recall: 0.8000; overfitting_gap: -0.0869; overfitting_severity: low; class_accuracies: [0.84375, 0.75]; n_classes: 2.0000; n_train_samples: 237.0000; n_test_samples: 60.0000; training_time: 0.0020; model_complexity: {'n_parameters': 15, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| german_credit | decision_tree | 0.8950 | 0.6450 | N/A | N/A | train_f1: 0.8917; test_f1: 0.6361; train_precision: 0.8952; test_precision: 0.6297; train_recall: 0.8950; test_recall: 0.6450; overfitting_gap: 0.2500; overfitting_severity: high; class_accuracies: [0.7785714285714286, 0.3333333333333333]; n_classes: 2.0000; n_train_samples: 800.0000; n_test_samples: 200.0000; training_time: 0.0061; model_complexity: {'n_parameters': 13, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| german_credit | random_forest | 0.9287 | 0.7050 | N/A | N/A | train_f1: 0.9257; test_f1: 0.6718; train_precision: 0.9353; test_precision: 0.6726; train_recall: 0.9287; test_recall: 0.7050; overfitting_gap: 0.2238; overfitting_severity: high; class_accuracies: [0.8928571428571429, 0.26666666666666666]; n_classes: 2.0000; n_train_samples: 800.0000; n_test_samples: 200.0000; training_time: 0.1419; model_complexity: {'n_parameters': 19, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| german_credit | gradient_boosting | 0.8387 | 0.7150 | N/A | N/A | train_f1: 0.8204; test_f1: 0.6892; train_precision: 0.8582; test_precision: 0.6889; train_recall: 0.8387; test_recall: 0.7150; overfitting_gap: 0.1238; overfitting_severity: moderate; class_accuracies: [0.8857142857142857, 0.31666666666666665]; n_classes: 2.0000; n_train_samples: 800.0000; n_test_samples: 200.0000; training_time: 0.1280; model_complexity: {'n_parameters': 20, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| german_credit | mlp | 0.8425 | 0.7150 | N/A | N/A | train_f1: 0.8330; test_f1: 0.6972; train_precision: 0.8426; test_precision: 0.6937; train_recall: 0.8425; test_recall: 0.7150; overfitting_gap: 0.1275; overfitting_severity: moderate; class_accuracies: [0.8642857142857143, 0.36666666666666664]; n_classes: 2.0000; n_train_samples: 800.0000; n_test_samples: 200.0000; training_time: 0.6504; model_complexity: {'n_parameters': 23, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| german_credit | linear_regression | 0.7037 | 0.7250 | N/A | N/A | train_f1: 0.6179; test_f1: 0.6615; train_precision: 0.6603; test_precision: 0.7108; train_recall: 0.7037; test_recall: 0.7250; overfitting_gap: -0.0212; overfitting_severity: low; class_accuracies: [0.9642857142857143, 0.16666666666666666]; n_classes: 2.0000; n_train_samples: 800.0000; n_test_samples: 200.0000; training_time: 0.0006; model_complexity: {'n_parameters': 5, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| german_credit | logistic_regression | 0.7013 | 0.7350 | N/A | N/A | train_f1: 0.6243; test_f1: 0.6786; train_precision: 0.6527; test_precision: 0.7282; train_recall: 0.7013; test_recall: 0.7350; overfitting_gap: -0.0337; overfitting_severity: low; class_accuracies: [0.9642857142857143, 0.2]; n_classes: 2.0000; n_train_samples: 800.0000; n_test_samples: 200.0000; training_time: 0.0036; model_complexity: {'n_parameters': 15, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| iris | decision_tree | 1.0000 | 0.9333 | N/A | N/A | train_f1: 1.0000; test_f1: 0.9333; train_precision: 1.0000; test_precision: 0.9333; train_recall: 1.0000; test_recall: 0.9333; overfitting_gap: 0.0667; overfitting_severity: low; class_accuracies: [1.0, 0.9, 0.9]; n_classes: 3.0000; n_train_samples: 120.0000; n_test_samples: 30.0000; training_time: 0.0000; model_complexity: {'n_parameters': 13, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| iris | random_forest | 1.0000 | 0.9000 | N/A | N/A | train_f1: 1.0000; test_f1: 0.8997; train_precision: 1.0000; test_precision: 0.9024; train_recall: 1.0000; test_recall: 0.9000; overfitting_gap: 0.1000; overfitting_severity: low; class_accuracies: [1.0, 0.9, 0.8]; n_classes: 3.0000; n_train_samples: 120.0000; n_test_samples: 30.0000; training_time: 0.1018; model_complexity: {'n_parameters': 19, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| iris | gradient_boosting | 1.0000 | 0.9667 | N/A | N/A | train_f1: 1.0000; test_f1: 0.9666; train_precision: 1.0000; test_precision: 0.9697; train_recall: 1.0000; test_recall: 0.9667; overfitting_gap: 0.0333; overfitting_severity: low; class_accuracies: [1.0, 0.9, 1.0]; n_classes: 3.0000; n_train_samples: 120.0000; n_test_samples: 30.0000; training_time: 0.1620; model_complexity: {'n_parameters': 20, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| iris | mlp | 0.9833 | 0.9667 | N/A | N/A | train_f1: 0.9833; test_f1: 0.9666; train_precision: 0.9833; test_precision: 0.9697; train_recall: 0.9833; test_recall: 0.9667; overfitting_gap: 0.0167; overfitting_severity: low; class_accuracies: [1.0, 0.9, 1.0]; n_classes: 3.0000; n_train_samples: 120.0000; n_test_samples: 30.0000; training_time: 0.1506; model_complexity: {'n_parameters': 23, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| iris | linear_regression | 0.0000 | 0.0000 | N/A | N/A | error: Classification metrics can't handle a mix of multiclass and continuous targets; training_time: 0.0014; model_complexity: {'n_parameters': 5, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| iris | logistic_regression | 0.9583 | 0.9333 | N/A | N/A | train_f1: 0.9583; test_f1: 0.9333; train_precision: 0.9585; test_precision: 0.9333; train_recall: 0.9583; test_recall: 0.9333; overfitting_gap: 0.0250; overfitting_severity: low; class_accuracies: [1.0, 0.9, 0.9]; n_classes: 3.0000; n_train_samples: 120.0000; n_test_samples: 30.0000; training_time: 0.0090; model_complexity: {'n_parameters': 15, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| wine_quality | decision_tree | 0.8874 | 0.6406 | N/A | N/A | train_f1: 0.8871; test_f1: 0.6405; train_precision: 0.8904; test_precision: 0.6406; train_recall: 0.8874; test_recall: 0.6406; overfitting_gap: 0.2468; overfitting_severity: high; class_accuracies: [0.697986577181208, 0.5859375, 0.6046511627906976]; n_classes: 3.0000; n_train_samples: 1279.0000; n_test_samples: 320.0000; training_time: 0.0061; model_complexity: {'n_parameters': 13, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| wine_quality | random_forest | 0.9679 | 0.7063 | N/A | N/A | train_f1: 0.9678; test_f1: 0.7044; train_precision: 0.9685; test_precision: 0.7043; train_recall: 0.9679; test_recall: 0.7063; overfitting_gap: 0.2617; overfitting_severity: high; class_accuracies: [0.8053691275167785, 0.6328125, 0.5813953488372093]; n_classes: 3.0000; n_train_samples: 1279.0000; n_test_samples: 320.0000; training_time: 0.2078; model_complexity: {'n_parameters': 19, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| wine_quality | gradient_boosting | 0.8694 | 0.7000 | N/A | N/A | train_f1: 0.8692; test_f1: 0.6968; train_precision: 0.8705; test_precision: 0.6952; train_recall: 0.8694; test_recall: 0.7000; overfitting_gap: 0.1694; overfitting_severity: moderate; class_accuracies: [0.825503355704698, 0.6015625, 0.5581395348837209]; n_classes: 3.0000; n_train_samples: 1279.0000; n_test_samples: 320.0000; training_time: 0.6586; model_complexity: {'n_parameters': 20, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| wine_quality | mlp | 0.9124 | 0.6906 | N/A | N/A | train_f1: 0.9122; test_f1: 0.6869; train_precision: 0.9122; test_precision: 0.6876; train_recall: 0.9124; test_recall: 0.6906; overfitting_gap: 0.2218; overfitting_severity: high; class_accuracies: [0.8053691275167785, 0.5859375, 0.6046511627906976]; n_classes: 3.0000; n_train_samples: 1279.0000; n_test_samples: 320.0000; training_time: 1.0717; model_complexity: {'n_parameters': 23, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| wine_quality | linear_regression | 0.0000 | 0.0000 | N/A | N/A | error: Classification metrics can't handle a mix of multiclass and continuous targets; training_time: 0.0020; model_complexity: {'n_parameters': 5, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| wine_quality | logistic_regression | 0.6302 | 0.6531 | N/A | N/A | train_f1: 0.6225; test_f1: 0.6432; train_precision: 0.6240; test_precision: 0.6508; train_recall: 0.6302; test_recall: 0.6531; overfitting_gap: -0.0229; overfitting_severity: low; class_accuracies: [0.8187919463087249, 0.5546875, 0.37209302325581395]; n_classes: 3.0000; n_train_samples: 1279.0000; n_test_samples: 320.0000; training_time: 0.0116; model_complexity: {'n_parameters': 15, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| diabetes | decision_tree | 0.9858 | 0.4944 | N/A | N/A | train_f1: 0.9858; test_f1: 0.4901; train_precision: 0.9861; test_precision: 0.4879; train_recall: 0.9858; test_recall: 0.4944; overfitting_gap: 0.4915; overfitting_severity: high; class_accuracies: [0.6190476190476191, 0.41935483870967744, 0.3125]; n_classes: 3.0000; n_train_samples: 353.0000; n_test_samples: 89.0000; training_time: 0.0034; model_complexity: {'n_parameters': 13, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| diabetes | random_forest | 0.9972 | 0.5843 | N/A | N/A | train_f1: 0.9972; test_f1: 0.5792; train_precision: 0.9972; test_precision: 0.5879; train_recall: 0.9972; test_recall: 0.5843; overfitting_gap: 0.4129; overfitting_severity: high; class_accuracies: [0.7380952380952381, 0.45161290322580644, 0.4375]; n_classes: 3.0000; n_train_samples: 353.0000; n_test_samples: 89.0000; training_time: 0.1300; model_complexity: {'n_parameters': 19, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| diabetes | gradient_boosting | 0.9830 | 0.5393 | N/A | N/A | train_f1: 0.9830; test_f1: 0.5235; train_precision: 0.9832; test_precision: 0.5184; train_recall: 0.9830; test_recall: 0.5393; overfitting_gap: 0.4437; overfitting_severity: high; class_accuracies: [0.7619047619047619, 0.3225806451612903, 0.375]; n_classes: 3.0000; n_train_samples: 353.0000; n_test_samples: 89.0000; training_time: 0.3754; model_complexity: {'n_parameters': 20, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| diabetes | mlp | 0.9575 | 0.4494 | N/A | N/A | train_f1: 0.9574; test_f1: 0.4528; train_precision: 0.9576; test_precision: 0.4605; train_recall: 0.9575; test_recall: 0.4494; overfitting_gap: 0.5081; overfitting_severity: high; class_accuracies: [0.5714285714285714, 0.2903225806451613, 0.4375]; n_classes: 3.0000; n_train_samples: 353.0000; n_test_samples: 89.0000; training_time: 0.3076; model_complexity: {'n_parameters': 23, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| diabetes | linear_regression | 0.0000 | 0.0000 | N/A | N/A | error: Classification metrics can't handle a mix of multiclass and continuous targets; training_time: 0.0015; model_complexity: {'n_parameters': 5, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| diabetes | logistic_regression | 0.6459 | 0.6517 | N/A | N/A | train_f1: 0.6458; test_f1: 0.6528; train_precision: 0.6474; test_precision: 0.6572; train_recall: 0.6459; test_recall: 0.6517; overfitting_gap: -0.0058; overfitting_severity: low; class_accuracies: [0.7380952380952381, 0.5806451612903226, 0.5625]; n_classes: 3.0000; n_train_samples: 353.0000; n_test_samples: 89.0000; training_time: 0.0107; model_complexity: {'n_parameters': 15, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| wine_classification | decision_tree | 1.0000 | 0.9444 | N/A | N/A | train_f1: 1.0000; test_f1: 0.9450; train_precision: 1.0000; test_precision: 0.9514; train_recall: 1.0000; test_recall: 0.9444; overfitting_gap: 0.0556; overfitting_severity: low; class_accuracies: [0.9166666666666666, 1.0, 0.9]; n_classes: 3.0000; n_train_samples: 142.0000; n_test_samples: 36.0000; training_time: 0.0020; model_complexity: {'n_parameters': 13, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| wine_classification | random_forest | 1.0000 | 1.0000 | N/A | N/A | train_f1: 1.0000; test_f1: 1.0000; train_precision: 1.0000; test_precision: 1.0000; train_recall: 1.0000; test_recall: 1.0000; overfitting_gap: 0.0000; overfitting_severity: low; class_accuracies: [1.0, 1.0, 1.0]; n_classes: 3.0000; n_train_samples: 142.0000; n_test_samples: 36.0000; training_time: 0.0873; model_complexity: {'n_parameters': 19, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| wine_classification | gradient_boosting | 1.0000 | 0.9444 | N/A | N/A | train_f1: 1.0000; test_f1: 0.9443; train_precision: 1.0000; test_precision: 0.9466; train_recall: 1.0000; test_recall: 0.9444; overfitting_gap: 0.0556; overfitting_severity: low; class_accuracies: [1.0, 0.9285714285714286, 0.9]; n_classes: 3.0000; n_train_samples: 142.0000; n_test_samples: 36.0000; training_time: 0.2650; model_complexity: {'n_parameters': 20, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| wine_classification | mlp | 1.0000 | 1.0000 | N/A | N/A | train_f1: 1.0000; test_f1: 1.0000; train_precision: 1.0000; test_precision: 1.0000; train_recall: 1.0000; test_recall: 1.0000; overfitting_gap: 0.0000; overfitting_severity: low; class_accuracies: [1.0, 1.0, 1.0]; n_classes: 3.0000; n_train_samples: 142.0000; n_test_samples: 36.0000; training_time: 0.0962; model_complexity: {'n_parameters': 23, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| wine_classification | linear_regression | 0.0000 | 0.0000 | N/A | N/A | error: Classification metrics can't handle a mix of multiclass and continuous targets; training_time: 0.0010; model_complexity: {'n_parameters': 5, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| wine_classification | logistic_regression | 1.0000 | 0.9722 | N/A | N/A | train_f1: 1.0000; test_f1: 0.9720; train_precision: 1.0000; test_precision: 0.9741; train_recall: 1.0000; test_recall: 0.9722; overfitting_gap: 0.0278; overfitting_severity: low; class_accuracies: [1.0, 1.0, 0.9]; n_classes: 3.0000; n_train_samples: 142.0000; n_test_samples: 36.0000; training_time: 0.0070; model_complexity: {'n_parameters': 15, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| digits | decision_tree | 0.9875 | 0.8083 | N/A | N/A | train_f1: 0.9875; test_f1: 0.8091; train_precision: 0.9878; test_precision: 0.8125; train_recall: 0.9875; test_recall: 0.8083; overfitting_gap: 0.1791; overfitting_severity: moderate; class_accuracies: [0.9444444444444444, 0.7222222222222222, 0.7714285714285715, 0.8108108108108109, 0.8055555555555556, 0.9459459459459459, 0.8333333333333334, 0.8333333333333334, 0.6857142857142857, 0.7222222222222222]; n_classes: 10.0000; n_train_samples: 1437.0000; n_test_samples: 360.0000; training_time: 0.0165; model_complexity: {'n_parameters': 13, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| digits | random_forest | 1.0000 | 0.9611 | N/A | N/A | train_f1: 1.0000; test_f1: 0.9609; train_precision: 1.0000; test_precision: 0.9620; train_recall: 1.0000; test_recall: 0.9611; overfitting_gap: 0.0389; overfitting_severity: low; class_accuracies: [0.9722222222222222, 0.9722222222222222, 0.9714285714285714, 0.972972972972973, 0.9722222222222222, 1.0, 0.9722222222222222, 1.0, 0.8571428571428571, 0.9166666666666666]; n_classes: 10.0000; n_train_samples: 1437.0000; n_test_samples: 360.0000; training_time: 0.2570; model_complexity: {'n_parameters': 19, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| digits | gradient_boosting | 1.0000 | 0.9528 | N/A | N/A | train_f1: 1.0000; test_f1: 0.9523; train_precision: 1.0000; test_precision: 0.9531; train_recall: 1.0000; test_recall: 0.9528; overfitting_gap: 0.0472; overfitting_severity: low; class_accuracies: [0.9722222222222222, 0.8333333333333334, 0.9714285714285714, 1.0, 0.9722222222222222, 1.0, 0.9444444444444444, 1.0, 0.9142857142857143, 0.9166666666666666]; n_classes: 10.0000; n_train_samples: 1437.0000; n_test_samples: 360.0000; training_time: 5.1146; model_complexity: {'n_parameters': 20, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| digits | mlp | 1.0000 | 0.9778 | N/A | N/A | train_f1: 1.0000; test_f1: 0.9775; train_precision: 1.0000; test_precision: 0.9779; train_recall: 1.0000; test_recall: 0.9778; overfitting_gap: 0.0222; overfitting_severity: low; class_accuracies: [1.0, 0.9722222222222222, 1.0, 1.0, 1.0, 1.0, 0.9722222222222222, 1.0, 0.8571428571428571, 0.9722222222222222]; n_classes: 10.0000; n_train_samples: 1437.0000; n_test_samples: 360.0000; training_time: 0.7398; model_complexity: {'n_parameters': 23, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| digits | linear_regression | 0.0000 | 0.0000 | N/A | N/A | error: Classification metrics can't handle a mix of multiclass and continuous targets; training_time: 0.0129; model_complexity: {'n_parameters': 5, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| digits | logistic_regression | 0.9993 | 0.9722 | N/A | N/A | train_f1: 0.9993; test_f1: 0.9722; train_precision: 0.9993; test_precision: 0.9724; train_recall: 0.9993; test_recall: 0.9722; overfitting_gap: 0.0271; overfitting_severity: low; class_accuracies: [1.0, 0.8888888888888888, 1.0, 1.0, 1.0, 1.0, 0.9722222222222222, 1.0, 0.8857142857142857, 0.9722222222222222]; n_classes: 10.0000; n_train_samples: 1437.0000; n_test_samples: 360.0000; training_time: 0.0307; model_complexity: {'n_parameters': 15, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| mnist | cnn | 0.9970 | 0.9750 | N/A | N/A | train_f1: 0.9970; test_f1: 0.9748; train_precision: 0.9970; test_precision: 0.9759; train_recall: 0.9970; test_recall: 0.9750; overfitting_gap: 0.0220; overfitting_severity: low; class_accuracies: [1.0, 1.0, 1.0, 1.0, 0.8928571428571429, 1.0, 1.0, 1.0, 1.0, 0.9047619047619048]; n_classes: 10.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 7.2236; model_complexity: {'n_parameters': 688138, 'model_size_bytes': 2752552, 'model_size_mb': 2.6250381469726562, 'complexity_level': 'complex'} |
| mnist | vit | 0.7790 | 0.7100 | N/A | N/A | train_f1: 0.7716; test_f1: 0.6908; train_precision: 0.7937; test_precision: 0.7139; train_recall: 0.7790; test_recall: 0.7100; overfitting_gap: 0.0690; overfitting_severity: low; class_accuracies: [0.8823529411764706, 1.0, 0.5, 0.625, 0.7857142857142857, 0.2, 0.45, 0.875, 0.8, 0.8095238095238095]; n_classes: 10.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 9.7024; model_complexity: {'n_parameters': 3231242, 'model_size_bytes': 12924968, 'model_size_mb': 12.326210021972656, 'complexity_level': 'complex'} |
| mnist | resnet | 0.9790 | 0.9300 | N/A | N/A | train_f1: 0.9789; test_f1: 0.9276; train_precision: 0.9799; test_precision: 0.9388; train_recall: 0.9790; test_recall: 0.9300; overfitting_gap: 0.0490; overfitting_severity: low; class_accuracies: [0.9411764705882353, 1.0, 0.875, 1.0, 1.0, 0.85, 1.0, 1.0, 1.0, 0.6190476190476191]; n_classes: 10.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 38.0068; model_complexity: {'n_parameters': 11175370, 'model_size_bytes': 44701480, 'model_size_mb': 42.630653381347656, 'complexity_level': 'complex'} |
| cifar10 | cnn | 0.8715 | 0.5125 | N/A | N/A | train_f1: 0.8716; test_f1: 0.5091; train_precision: 0.8777; test_precision: 0.5206; train_recall: 0.8715; test_recall: 0.5125; overfitting_gap: 0.3590; overfitting_severity: high; class_accuracies: [0.4666666666666667, 0.696969696969697, 0.38095238095238093, 0.42105263157894735, 0.3, 0.2222222222222222, 0.625, 0.5833333333333334, 0.7021276595744681, 0.6222222222222222]; n_classes: 10.0000; n_train_samples: 2000.0000; n_test_samples: 400.0000; training_time: 15.8214; model_complexity: {'n_parameters': 1147466, 'model_size_bytes': 4589864, 'model_size_mb': 4.377235412597656, 'complexity_level': 'complex'} |
| cifar10 | vit | 0.3250 | 0.2525 | N/A | N/A | train_f1: 0.3206; test_f1: 0.2541; train_precision: 0.3881; test_precision: 0.3114; train_recall: 0.3250; test_recall: 0.2525; overfitting_gap: 0.0725; overfitting_severity: low; class_accuracies: [0.26666666666666666, 0.24242424242424243, 0.42857142857142855, 0.0, 0.1, 0.3888888888888889, 0.3125, 0.1388888888888889, 0.19148936170212766, 0.37777777777777777]; n_classes: 10.0000; n_train_samples: 2000.0000; n_test_samples: 400.0000; training_time: 22.8699; model_complexity: {'n_parameters': 3363082, 'model_size_bytes': 13452328, 'model_size_mb': 12.829139709472656, 'complexity_level': 'complex'} |
| cifar10 | resnet | 0.9010 | 0.3950 | N/A | N/A | train_f1: 0.8991; test_f1: 0.3934; train_precision: 0.9066; test_precision: 0.4101; train_recall: 0.9010; test_recall: 0.3950; overfitting_gap: 0.5060; overfitting_severity: high; class_accuracies: [0.2222222222222222, 0.2727272727272727, 0.3333333333333333, 0.18421052631578946, 0.3333333333333333, 0.2777777777777778, 0.6041666666666666, 0.4444444444444444, 0.5957446808510638, 0.5555555555555556]; n_classes: 10.0000; n_train_samples: 2000.0000; n_test_samples: 400.0000; training_time: 72.2992; model_complexity: {'n_parameters': 11181642, 'model_size_bytes': 44726568, 'model_size_mb': 42.654579162597656, 'complexity_level': 'complex'} |
| fashion_mnist | cnn | 0.9440 | 0.8450 | N/A | N/A | train_f1: 0.9438; test_f1: 0.8430; train_precision: 0.9444; test_precision: 0.8474; train_recall: 0.9440; test_recall: 0.8450; overfitting_gap: 0.0990; overfitting_severity: low; class_accuracies: [0.9047619047619048, 1.0, 0.6851851851851852, 0.9444444444444444, 0.5348837209302325, 0.9375, 0.717948717948718, 1.0, 0.9117647058823529, 0.9166666666666666]; n_classes: 10.0000; n_train_samples: 2000.0000; n_test_samples: 400.0000; training_time: 12.3959; model_complexity: {'n_parameters': 688138, 'model_size_bytes': 2752552, 'model_size_mb': 2.6250381469726562, 'complexity_level': 'complex'} |
| fashion_mnist | vit | 0.7290 | 0.7100 | N/A | N/A | train_f1: 0.7220; test_f1: 0.7088; train_precision: 0.7550; test_precision: 0.7486; train_recall: 0.7290; test_recall: 0.7100; overfitting_gap: 0.0190; overfitting_severity: low; class_accuracies: [0.7380952380952381, 0.9090909090909091, 0.8148148148148148, 0.7222222222222222, 0.5348837209302325, 0.90625, 0.2564102564102564, 0.85, 0.7647058823529411, 0.5833333333333334]; n_classes: 10.0000; n_train_samples: 2000.0000; n_test_samples: 400.0000; training_time: 17.1894; model_complexity: {'n_parameters': 3231242, 'model_size_bytes': 12924968, 'model_size_mb': 12.326210021972656, 'complexity_level': 'complex'} |
| fashion_mnist | resnet | 0.9055 | 0.7575 | N/A | N/A | train_f1: 0.9068; test_f1: 0.7519; train_precision: 0.9377; test_precision: 0.8112; train_recall: 0.9055; test_recall: 0.7575; overfitting_gap: 0.1480; overfitting_severity: moderate; class_accuracies: [0.8333333333333334, 1.0, 0.3148148148148148, 0.8055555555555556, 0.8837209302325582, 0.96875, 0.358974358974359, 0.925, 0.8235294117647058, 0.8333333333333334]; n_classes: 10.0000; n_train_samples: 2000.0000; n_test_samples: 400.0000; training_time: 70.0636; model_complexity: {'n_parameters': 11175370, 'model_size_bytes': 44701480, 'model_size_mb': 42.630653381347656, 'complexity_level': 'complex'} |
| imdb | bert | 0.9180 | 0.8100 | N/A | N/A | train_f1: 0.9180; test_f1: 0.8099; train_precision: 0.9180; test_precision: 0.8105; train_recall: 0.9180; test_recall: 0.8100; overfitting_gap: 0.1080; overfitting_severity: moderate; class_accuracies: [0.79, 0.83]; n_classes: 2.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 0.4252; model_complexity: {'n_parameters': 15, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| imdb | lstm | 0.8870 | 0.8150 | N/A | N/A | train_f1: 0.8870; test_f1: 0.8149; train_precision: 0.8870; test_precision: 0.8158; train_recall: 0.8870; test_recall: 0.8150; overfitting_gap: 0.0720; overfitting_severity: low; class_accuracies: [0.84, 0.79]; n_classes: 2.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 0.6745; model_complexity: {'n_parameters': 4, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| imdb | roberta | 0.9240 | 0.8700 | N/A | N/A | train_f1: 0.9239; test_f1: 0.8684; train_precision: 0.9267; test_precision: 0.8888; train_recall: 0.9240; test_recall: 0.8700; overfitting_gap: 0.0540; overfitting_severity: low; class_accuracies: [0.98, 0.76]; n_classes: 2.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 15215.2777; model_complexity: {'n_parameters': 124647170, 'model_size_bytes': 498588680, 'model_size_mb': 475.49121856689453, 'complexity_level': 'complex'} |
| imdb | naive_bayes_text | 0.9850 | 0.8050 | N/A | N/A | train_f1: 0.9850; test_f1: 0.8036; train_precision: 0.9853; test_precision: 0.8141; train_recall: 0.9850; test_recall: 0.8050; overfitting_gap: 0.1800; overfitting_severity: moderate; class_accuracies: [0.89, 0.72]; n_classes: 2.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 1.1157; model_complexity: {'n_parameters': 4, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| imdb | svm_text | 0.9970 | 0.8050 | N/A | N/A | train_f1: 0.9970; test_f1: 0.8050; train_precision: 0.9970; test_precision: 0.8053; train_recall: 0.9970; test_recall: 0.8050; overfitting_gap: 0.1920; overfitting_severity: moderate; class_accuracies: [0.79, 0.82]; n_classes: 2.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 5.1057; model_complexity: {'n_parameters': 15, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| imdb | xgboost_text | 0.9890 | 0.7900 | N/A | N/A | train_f1: 0.9890; test_f1: 0.7899; train_precision: 0.9892; test_precision: 0.7905; train_recall: 0.9890; test_recall: 0.7900; overfitting_gap: 0.1990; overfitting_severity: moderate; class_accuracies: [0.77, 0.81]; n_classes: 2.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 2.5840; model_complexity: {'n_parameters': 40, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| 20newsgroups | bert | 0.9380 | 0.7150 | N/A | N/A | train_f1: 0.9378; test_f1: 0.7073; train_precision: 0.9416; test_precision: 0.7299; train_recall: 0.9380; test_recall: 0.7150; overfitting_gap: 0.2230; overfitting_severity: high; class_accuracies: [0.45454545454545453, 0.8260869565217391, 0.6984126984126984, 0.8723404255319149]; n_classes: 4.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 0.8115; model_complexity: {'n_parameters': 15, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| 20newsgroups | lstm | 0.8950 | 0.7100 | N/A | N/A | train_f1: 0.8936; test_f1: 0.7041; train_precision: 0.8975; test_precision: 0.7642; train_recall: 0.8950; test_recall: 0.7100; overfitting_gap: 0.1850; overfitting_severity: moderate; class_accuracies: [0.38636363636363635, 0.8913043478260869, 0.6666666666666666, 0.8936170212765957]; n_classes: 4.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 0.9408; model_complexity: {'n_parameters': 4, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| 20newsgroups | roberta | 0.9790 | 0.8400 | N/A | N/A | train_f1: 0.9791; test_f1: 0.8384; train_precision: 0.9800; test_precision: 0.8397; train_recall: 0.9790; test_recall: 0.8400; overfitting_gap: 0.1390; overfitting_severity: moderate; class_accuracies: [0.6818181818181818, 0.9130434782608695, 0.8571428571428571, 0.8936170212765957]; n_classes: 4.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 13048.7038; model_complexity: {'n_parameters': 124648708, 'model_size_bytes': 498594832, 'model_size_mb': 475.49708557128906, 'complexity_level': 'complex'} |
| 20newsgroups | naive_bayes_text | 0.9370 | 0.7350 | N/A | N/A | train_f1: 0.9360; test_f1: 0.7124; train_precision: 0.9412; test_precision: 0.8285; train_recall: 0.9370; test_recall: 0.7350; overfitting_gap: 0.2020; overfitting_severity: high; class_accuracies: [0.22727272727272727, 0.8695652173913043, 0.8253968253968254, 0.9574468085106383]; n_classes: 4.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 1.0485; model_complexity: {'n_parameters': 4, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| 20newsgroups | svm_text | 0.9800 | 0.7950 | N/A | N/A | train_f1: 0.9802; test_f1: 0.7927; train_precision: 0.9814; test_precision: 0.7976; train_recall: 0.9800; test_recall: 0.7950; overfitting_gap: 0.1850; overfitting_severity: moderate; class_accuracies: [0.5909090909090909, 0.8260869565217391, 0.8888888888888888, 0.8297872340425532]; n_classes: 4.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 4.6601; model_complexity: {'n_parameters': 15, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| 20newsgroups | xgboost_text | 0.9480 | 0.7050 | N/A | N/A | train_f1: 0.9487; test_f1: 0.7029; train_precision: 0.9527; test_precision: 0.7022; train_recall: 0.9480; test_recall: 0.7050; overfitting_gap: 0.2430; overfitting_severity: high; class_accuracies: [0.5227272727272727, 0.7391304347826086, 0.7301587301587301, 0.8085106382978723]; n_classes: 4.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 4.4885; model_complexity: {'n_parameters': 40, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| ag_news | bert | 0.9640 | 0.7900 | N/A | N/A | train_f1: 0.9640; test_f1: 0.7896; train_precision: 0.9641; test_precision: 0.7896; train_recall: 0.9640; test_recall: 0.7900; overfitting_gap: 0.1740; overfitting_severity: moderate; class_accuracies: [0.82, 0.84, 0.7, 0.8]; n_classes: 4.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 0.2042; model_complexity: {'n_parameters': 15, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| ag_news | lstm | 0.9350 | 0.7800 | N/A | N/A | train_f1: 0.9349; test_f1: 0.7779; train_precision: 0.9354; test_precision: 0.7790; train_recall: 0.9350; test_recall: 0.7800; overfitting_gap: 0.1550; overfitting_severity: moderate; class_accuracies: [0.84, 0.88, 0.66, 0.74]; n_classes: 4.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 0.1827; model_complexity: {'n_parameters': 4, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| ag_news | roberta | 0.9770 | 0.9000 | N/A | N/A | train_f1: 0.9769; test_f1: 0.9007; train_precision: 0.9774; test_precision: 0.9039; train_recall: 0.9770; test_recall: 0.9000; overfitting_gap: 0.0770; overfitting_severity: low; class_accuracies: [0.86, 0.98, 0.88, 0.88]; n_classes: 4.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 3064.3737; model_complexity: {'n_parameters': 124648708, 'model_size_bytes': 498594832, 'model_size_mb': 475.49708557128906, 'complexity_level': 'complex'} |
| ag_news | naive_bayes_text | 0.9710 | 0.8150 | N/A | N/A | train_f1: 0.9710; test_f1: 0.8140; train_precision: 0.9711; test_precision: 0.8169; train_recall: 0.9710; test_recall: 0.8150; overfitting_gap: 0.1560; overfitting_severity: moderate; class_accuracies: [0.88, 0.88, 0.7, 0.8]; n_classes: 4.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 0.5256; model_complexity: {'n_parameters': 4, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| ag_news | svm_text | 0.9930 | 0.7900 | N/A | N/A | train_f1: 0.9930; test_f1: 0.7895; train_precision: 0.9930; test_precision: 0.7899; train_recall: 0.9930; test_recall: 0.7900; overfitting_gap: 0.2030; overfitting_severity: high; class_accuracies: [0.84, 0.88, 0.68, 0.76]; n_classes: 4.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 1.6506; model_complexity: {'n_parameters': 15, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |
| ag_news | xgboost_text | 0.9750 | 0.7100 | N/A | N/A | train_f1: 0.9750; test_f1: 0.7118; train_precision: 0.9753; test_precision: 0.7152; train_recall: 0.9750; test_recall: 0.7100; overfitting_gap: 0.2650; overfitting_severity: high; class_accuracies: [0.74, 0.76, 0.64, 0.7]; n_classes: 4.0000; n_train_samples: 1000.0000; n_test_samples: 200.0000; training_time: 2.0474; model_complexity: {'n_parameters': 40, 'model_size_bytes': 48, 'model_size_mb': 4.57763671875e-05, 'complexity_level': 'simple'} |

## XAI Evaluation Results Table

Each row represents a unique combination of Dataset, Model, and Explanation Method with their evaluation metrics.

| Dataset | Model | Explanation Method | Detailed Report | Time Complexity | Faithfulness | Monotonicity | Completeness | Stability | Consistency | Sparsity | Simplicity | Advanced Identity | Advanced Separability | Advanced Non Sensitivity | Advanced Compactness | Advanced Correctness | Advanced Entropy | Advanced Gini Coefficient | Advanced Kl Divergence |
|---------|-------|-------------------|-----------------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|
| adult_income | decision_tree | shap | [View Details](#) | 0.0011 | 0.1900 | 0.0200 | 0.0100 | 0.0000 | 0.4651 | 0.0300 | 0.9520 | 0.9432 | 0.1706 | 1.0000 | 0.1775 | 0.6240 | 0.0215 | 0.1420 | 0.1685 |
| adult_income | decision_tree | lime | [View Details](#) | 0.0230 | 0.1000 | 0.0300 | 0.0000 | 0.0000 | 0.5060 | 0.0240 | 0.9497 | 0.8696 | 0.2352 | 1.0000 | 0.2375 | 0.6015 | 0.0086 | 0.1897 | 0.2314 |
| adult_income | decision_tree | causal_shap | [View Details](#) | 0.0179 | 0.2400 | 0.0200 | 0.0200 | 0.0000 | 0.5050 | 0.0480 | 0.9495 | 0.9877 | 0.1919 | 1.0000 | 0.1987 | 0.5818 | 0.0372 | 0.1607 | 0.1828 |
| adult_income | decision_tree | shapley_flow | [View Details](#) | 0.0088 | 0.1000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | shap_interactive | [View Details](#) | 0.0039 | 0.4000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.9600 | 1.0000 | 0.2000 | 1.0000 | 0.2000 | 0.3400 | -0.0000 | 0.1600 | 0.2000 |
| adult_income | decision_tree | prototype | [View Details](#) | 0.0010 | 0.6900 | 0.8228 | 1.0000 | 1.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | counterfactual | [View Details](#) | 0.0006 | 0.6700 | 0.1743 | 1.0000 | 0.8432 | 0.6718 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | bayesian_rule_list | [View Details](#) | 0.0007 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5670 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | corels | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5670 | 1.0000 | 0.0000 | 0.0000 |
| adult_income | decision_tree | feature_ablation | [View Details](#) | 0.0007 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4632 | 0.0240 | 0.9440 | 1.0000 | 0.2245 | 1.0000 | 0.2300 | 0.6040 | 0.0172 | 0.1840 | 0.2228 |
| adult_income | random_forest | shap | [View Details](#) | 0.0309 | 0.1900 | 0.0200 | 0.0000 | 0.0000 | 0.4696 | 0.0140 | 0.9440 | 0.9438 | 0.1647 | 1.0000 | 0.1675 | 0.6170 | 0.0291 | 0.1340 | 0.1609 |
| adult_income | random_forest | lime | [View Details](#) | 0.0305 | 0.1000 | 0.0200 | 0.0000 | 0.0000 | 0.4066 | 0.0120 | 0.9627 | 0.8889 | 0.1770 | 1.0000 | 0.1786 | 0.5843 | 0.0057 | 0.1427 | 0.1743 |
| adult_income | random_forest | causal_shap | [View Details](#) | 0.6718 | 0.2400 | 0.0200 | 0.0000 | 0.0000 | 0.5218 | 0.0320 | 0.9438 | 1.0000 | 0.1711 | 1.0000 | 0.1783 | 0.5790 | 0.0339 | 0.1438 | 0.1661 |
| adult_income | random_forest | shapley_flow | [View Details](#) | 0.3408 | 0.1333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | shap_interactive | [View Details](#) | 0.1759 | 0.6000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.9600 | 1.0000 | 0.2000 | 1.0000 | 0.2000 | 0.3400 | -0.0000 | 0.1600 | 0.2000 |
| adult_income | random_forest | prototype | [View Details](#) | 0.0045 | 0.7150 | 0.8098 | 1.0000 | 1.0000 | 0.9126 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | counterfactual | [View Details](#) | 0.0036 | 0.6850 | 0.1959 | 1.0000 | 0.8035 | 0.4857 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | bayesian_rule_list | [View Details](#) | 0.0036 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | corels | [View Details](#) | 0.0030 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 1.0000 | 0.0000 | 0.0000 |
| adult_income | random_forest | feature_ablation | [View Details](#) | 0.0171 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4509 | 0.0120 | 0.9320 | 1.0000 | 0.2132 | 1.0000 | 0.2150 | 0.6040 | 0.0309 | 0.1720 | 0.2091 |
| adult_income | gradient_boosting | shap | [View Details](#) | 0.0019 | 0.2100 | 0.0300 | 0.0000 | 0.0000 | 0.4896 | 0.0220 | 0.9400 | 0.9432 | 0.1825 | 1.0000 | 0.1875 | 0.6440 | 0.0316 | 0.1500 | 0.1784 |
| adult_income | gradient_boosting | lime | [View Details](#) | 0.0090 | 0.1400 | 0.0300 | 0.0000 | 0.0000 | 0.5266 | 0.0360 | 0.9583 | 0.9302 | 0.1700 | 1.0000 | 0.1739 | 0.6090 | 0.0170 | 0.1383 | 0.1630 |
| adult_income | gradient_boosting | causal_shap | [View Details](#) | 0.0401 | 0.2600 | 0.0200 | 0.0000 | 0.0000 | 0.5848 | 0.0320 | 0.9561 | 1.0000 | 0.1821 | 1.0000 | 0.1878 | 0.6127 | 0.0283 | 0.1498 | 0.1717 |
| adult_income | gradient_boosting | shap_interactive | [View Details](#) | 0.0069 | 0.4000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.9600 | 1.0000 | 0.2000 | 1.0000 | 0.2000 | 0.3400 | -0.0000 | 0.1600 | 0.2000 |
| adult_income | gradient_boosting | prototype | [View Details](#) | 0.0008 | 0.6900 | 0.8163 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | gradient_boosting | counterfactual | [View Details](#) | 0.0006 | 0.7250 | 0.2130 | 1.0000 | 0.7659 | 0.8036 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | gradient_boosting | bayesian_rule_list | [View Details](#) | 0.0007 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5810 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | gradient_boosting | corels | [View Details](#) | 0.0006 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5810 | 1.0000 | 0.0000 | 0.0000 |
| adult_income | gradient_boosting | feature_ablation | [View Details](#) | 0.0009 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4954 | 0.0200 | 0.9360 | 1.0000 | 0.2404 | 1.0000 | 0.2450 | 0.6380 | 0.0223 | 0.1960 | 0.2377 |
| adult_income | mlp | shap | [View Details](#) | 0.0023 | 0.2200 | 0.0250 | 0.0000 | 0.0000 | 0.4396 | 0.0260 | 0.9420 | 0.9032 | 0.1970 | 1.0000 | 0.2025 | 0.6400 | 0.0258 | 0.1620 | 0.1942 |
| adult_income | mlp | lime | [View Details](#) | 0.0188 | 0.0800 | 0.0317 | 0.0000 | 0.0000 | 0.6105 | 0.0720 | 0.9549 | 0.8723 | 0.1028 | 1.0000 | 0.1164 | 0.5697 | 0.0522 | 0.0949 | 0.0878 |
| adult_income | mlp | integrated_gradients | [View Details](#) | 0.0432 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5833 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | causal_shap | [View Details](#) | 0.0178 | 0.2400 | 0.0090 | 0.0000 | 0.0000 | 0.6256 | 0.0360 | 0.9661 | 1.0000 | 0.1591 | 1.0000 | 0.1625 | 0.5953 | 0.0349 | 0.1298 | 0.1451 |
| adult_income | mlp | shapley_flow | [View Details](#) | 0.0075 | 0.1000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5833 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | shap_interactive | [View Details](#) | 0.0041 | 0.4000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.9600 | 1.0000 | 0.2000 | 1.0000 | 0.2000 | 0.4800 | -0.0000 | 0.1600 | 0.2000 |
| adult_income | mlp | prototype | [View Details](#) | 0.0008 | 0.7000 | 0.7951 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | counterfactual | [View Details](#) | 0.0005 | 0.6950 | 0.1871 | 1.0000 | 0.9424 | 0.5030 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | influence_functions | [View Details](#) | 0.0183 | 0.0000 | 0.0000 | 0.0000 | 0.2615 | 0.4384 | 0.6000 | 0.4358 | 1.0000 | 0.4254 | 1.0000 | 0.5102 | 0.7454 | 0.7768 | 0.4358 | 0.2232 |
| adult_income | mlp | bayesian_rule_list | [View Details](#) | 0.0007 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5740 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | corels | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5740 | 1.0000 | 0.0000 | 0.0000 |
| adult_income | mlp | feature_ablation | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4377 | 0.0240 | 0.9320 | 1.0000 | 0.2845 | 1.0000 | 0.2900 | 0.6360 | 0.0172 | 0.2320 | 0.2828 |
| adult_income | linear_regression | lime | [View Details](#) | 0.0096 | 0.0600 | 0.0000 | 0.0000 | 0.0000 | 0.4799 | 0.0960 | 0.9424 | 0.8491 | 0.1026 | 1.0000 | 0.1233 | 0.5100 | 0.0746 | 0.1024 | 0.0854 |
| adult_income | linear_regression | causal_shap | [View Details](#) | 0.0206 | 0.1000 | 0.0100 | 0.0000 | 0.0000 | 0.5381 | 0.0600 | 0.9696 | 1.0000 | 0.0611 | 1.0000 | 0.0690 | 0.5052 | 0.0499 | 0.0576 | 0.0501 |
| adult_income | linear_regression | shap_interactive | [View Details](#) | 0.0042 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.9600 | 0.8000 | 0.2000 | 1.0000 | 0.2000 | 0.4800 | -0.0000 | 0.1600 | 0.2000 |
| adult_income | linear_regression | prototype | [View Details](#) | 0.0008 | 0.5850 | 0.5725 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | linear_regression | counterfactual | [View Details](#) | 0.0005 | 0.6000 | 0.4333 | 1.0000 | 0.7504 | 0.5312 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | linear_regression | bayesian_rule_list | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5320 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | linear_regression | corels | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5320 | 1.0000 | 0.0000 | 0.0000 |
| adult_income | linear_regression | feature_ablation | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.3667 | 0.0560 | 0.9560 | 1.0000 | 0.0572 | 1.0000 | 0.0700 | 0.5200 | 0.0481 | 0.0560 | 0.0519 |
| adult_income | logistic_regression | lime | [View Details](#) | 0.0087 | 0.0400 | 0.0000 | 0.0000 | 0.0000 | 0.5275 | 0.0480 | 0.9599 | 0.8511 | 0.1133 | 0.5000 | 0.1233 | 0.5328 | 0.0335 | 0.0999 | 0.1065 |
| adult_income | logistic_regression | causal_shap | [View Details](#) | 0.0169 | 0.1400 | 0.0400 | 0.0000 | 0.0000 | 0.5518 | 0.0920 | 0.9509 | 0.9901 | 0.1575 | 1.0000 | 0.1623 | 0.5456 | 0.0953 | 0.1346 | 0.1247 |
| adult_income | logistic_regression | shap_interactive | [View Details](#) | 0.0038 | 0.2000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.9600 | 1.0000 | 0.2000 | 1.0000 | 0.2000 | 0.3400 | -0.0000 | 0.1600 | 0.2000 |
| adult_income | logistic_regression | prototype | [View Details](#) | 0.0007 | 0.6550 | 0.7932 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | logistic_regression | counterfactual | [View Details](#) | 0.0005 | 0.6850 | 0.1945 | 1.0000 | 0.9117 | 0.8593 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | logistic_regression | influence_functions | [View Details](#) | 0.0141 | 0.0000 | 0.0000 | 0.0000 | 0.2615 | 0.4384 | 0.6000 | 0.4358 | 1.0000 | 0.4254 | 1.0000 | 0.5102 | 0.6404 | 0.7768 | 0.4358 | 0.2232 |
| adult_income | logistic_regression | bayesian_rule_list | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| adult_income | logistic_regression | corels | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 1.0000 | 0.0000 | 0.0000 |
| adult_income | logistic_regression | feature_ablation | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.5190 | 0.0360 | 0.9560 | 1.0000 | 0.1367 | 1.0000 | 0.1450 | 0.5520 | 0.0258 | 0.1160 | 0.1342 |
| compas | decision_tree | shap | [View Details](#) | 0.0006 | 0.6500 | 0.0300 | 0.0000 | 0.0000 | 0.6861 | 0.3500 | 0.7000 | 0.6292 | 0.3712 | 0.9999 | 0.5250 | 0.6090 | 0.1525 | 0.3500 | 0.4975 |
| compas | decision_tree | lime | [View Details](#) | 0.0091 | 0.3200 | 0.0800 | 0.0000 | 0.0000 | 0.7302 | 0.6133 | 0.6847 | 0.5208 | 0.6376 | 1.0000 | 0.9053 | 0.5882 | 0.0341 | 0.6047 | 0.8859 |
| compas | decision_tree | causal_shap | [View Details](#) | 0.0093 | 0.4800 | 0.0000 | 0.0000 | 0.0000 | 0.6367 | 0.3067 | 0.7633 | 1.0000 | 0.2331 | 1.0000 | 0.3215 | 0.4030 | 0.2163 | 0.2237 | 0.2637 |
| compas | decision_tree | shapley_flow | [View Details](#) | 0.0043 | 0.3333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.3733 | 0.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | shap_interactive | [View Details](#) | 0.0015 | 0.4000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1333 | 0.9333 | 1.0000 | 0.1414 | 1.0000 | 0.2000 | 0.4800 | -0.0000 | 0.1333 | 0.2000 |
| compas | decision_tree | prototype | [View Details](#) | 0.0002 | 0.6550 | 0.7376 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | counterfactual | [View Details](#) | 0.0002 | 0.6250 | 0.2716 | 1.0000 | 0.9775 | 0.4835 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | bayesian_rule_list | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 0.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | corels | [View Details](#) | 0.0002 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 1.0000 | 0.0000 | 0.0000 |
| compas | decision_tree | feature_ablation | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.6747 | 0.3667 | 0.6667 | 1.0000 | 0.3889 | 1.0000 | 0.5500 | 0.5260 | 0.1840 | 0.3667 | 0.5160 |
| compas | random_forest | shap | [View Details](#) | 0.0174 | 0.6300 | 0.0383 | 0.0000 | 0.0000 | 0.7164 | 0.3233 | 0.6933 | 0.6548 | 0.3429 | 1.0000 | 0.4850 | 0.6240 | 0.1777 | 0.3233 | 0.4523 |
| compas | random_forest | lime | [View Details](#) | 0.0180 | 0.3600 | 0.0300 | 0.0000 | 0.0000 | 0.7762 | 0.4733 | 0.6972 | 0.6053 | 0.4305 | 1.0000 | 0.6152 | 0.5415 | 0.1664 | 0.4172 | 0.5536 |
| compas | random_forest | causal_shap | [View Details](#) | 0.3482 | 0.4800 | 0.0300 | 0.0000 | 0.0000 | 0.6486 | 0.3200 | 0.7558 | 1.0000 | 0.2283 | 1.0000 | 0.3074 | 0.4556 | 0.2659 | 0.2168 | 0.2341 |
| compas | random_forest | shapley_flow | [View Details](#) | 0.1854 | 0.4333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.3733 | 0.0000 | 0.0000 | 0.0000 |
| compas | random_forest | shap_interactive | [View Details](#) | 0.0540 | 0.4000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| compas | random_forest | prototype | [View Details](#) | 0.0035 | 0.6150 | 0.6974 | 1.0000 | 0.9706 | 0.3587 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | random_forest | counterfactual | [View Details](#) | 0.0055 | 0.6950 | 0.2975 | 1.0000 | 0.9270 | 0.5698 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | random_forest | bayesian_rule_list | [View Details](#) | 0.0051 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4410 | 0.0000 | 0.0000 | 0.0000 |
| compas | random_forest | corels | [View Details](#) | 0.0039 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4410 | 1.0000 | 0.0000 | 0.0000 |
| compas | random_forest | feature_ablation | [View Details](#) | 0.0200 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.7118 | 0.2933 | 0.6333 | 1.0000 | 0.3111 | 0.9999 | 0.4400 | 0.5640 | 0.2671 | 0.2933 | 0.3929 |
| compas | gradient_boosting | shap | [View Details](#) | 0.0013 | 0.6100 | 0.0250 | 0.0000 | 0.0000 | 0.7096 | 0.3233 | 0.7133 | 0.6705 | 0.3429 | 0.9999 | 0.4850 | 0.6490 | 0.1551 | 0.3233 | 0.4549 |
| compas | gradient_boosting | lime | [View Details](#) | 0.0125 | 0.4000 | 0.1400 | 0.0000 | 0.3990 | 0.9124 | 0.5600 | 0.7096 | 0.5682 | 0.5795 | 1.0000 | 0.8239 | 0.6469 | 0.0427 | 0.5496 | 0.7973 |
| compas | gradient_boosting | causal_shap | [View Details](#) | 0.0284 | 0.4600 | 0.0300 | 0.0000 | 0.0000 | 0.6326 | 0.3267 | 0.6734 | 1.0000 | 0.1700 | 0.9990 | 0.2302 | 0.4518 | 0.3271 | 0.1734 | 0.1729 |
| compas | gradient_boosting | shap_interactive | [View Details](#) | 0.0063 | 0.2000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| compas | gradient_boosting | prototype | [View Details](#) | 0.0005 | 0.6950 | 0.6932 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | gradient_boosting | counterfactual | [View Details](#) | 0.0005 | 0.6450 | 0.3075 | 1.0000 | 0.9896 | 0.9178 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | gradient_boosting | bayesian_rule_list | [View Details](#) | 0.0011 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 0.0000 | 0.0000 | 0.0000 |
| compas | gradient_boosting | corels | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 1.0000 | 0.0000 | 0.0000 |
| compas | gradient_boosting | feature_ablation | [View Details](#) | 0.0007 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.6815 | 0.3333 | 0.6933 | 1.0000 | 0.3536 | 1.0000 | 0.5000 | 0.5980 | 0.1767 | 0.3333 | 0.4633 |
| compas | mlp | shap | [View Details](#) | 0.0024 | 0.5800 | 0.0100 | 0.0000 | 0.0000 | 0.7432 | 0.3800 | 0.8000 | 0.6556 | 0.4031 | 1.0000 | 0.5700 | 0.6430 | 0.0126 | 0.3800 | 0.5674 |
| compas | mlp | lime | [View Details](#) | 0.0091 | 0.0400 | 0.0000 | 0.0000 | 0.0000 | 0.7970 | 0.3333 | 0.8101 | 0.6429 | 0.3209 | 1.0000 | 0.4590 | 0.5330 | 0.0738 | 0.3101 | 0.4262 |
| compas | mlp | integrated_gradients | [View Details](#) | 0.0250 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | causal_shap | [View Details](#) | 0.0109 | 0.3400 | 0.0000 | 0.0000 | 0.0000 | 0.5817 | 0.2933 | 0.8030 | 1.0000 | 0.2567 | 1.0000 | 0.3456 | 0.5052 | 0.1462 | 0.2365 | 0.3138 |
| compas | mlp | shapley_flow | [View Details](#) | 0.0066 | 0.2333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | shap_interactive | [View Details](#) | 0.0017 | 0.0000 | 0.0000 | 0.0000 | 0.0202 | 0.6667 | 0.2667 | 0.6667 | 0.7500 | 0.2828 | 1.0000 | 0.4000 | 0.6000 | 0.2524 | 0.2667 | 0.3476 |
| compas | mlp | prototype | [View Details](#) | 0.0002 | 0.6700 | 0.6845 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | counterfactual | [View Details](#) | 0.0004 | 0.6750 | 0.3109 | 1.0000 | 0.9559 | 0.6168 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | influence_functions | [View Details](#) | 0.0174 | 0.0000 | 0.0000 | 0.0000 | 0.3834 | 0.7184 | 0.6667 | 0.4325 | 1.0000 | 0.4194 | 1.0000 | 0.6078 | 0.6356 | 0.6415 | 0.4325 | 0.3585 |
| compas | mlp | bayesian_rule_list | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 0.0000 | 0.0000 | 0.0000 |
| compas | mlp | corels | [View Details](#) | 0.0002 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 1.0000 | 0.0000 | 0.0000 |
| compas | mlp | feature_ablation | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.7167 | 0.3800 | 0.8000 | 1.0000 | 0.4031 | 1.0000 | 0.5700 | 0.5800 | 0.0126 | 0.3800 | 0.5674 |
| compas | linear_regression | lime | [View Details](#) | 0.0092 | 0.1400 | 0.0100 | 0.0000 | 0.0000 | 0.6464 | 0.0800 | 0.9423 | 0.9688 | 0.0650 | 1.0000 | 0.0908 | 0.4585 | 0.0368 | 0.0623 | 0.0832 |
| compas | linear_regression | causal_shap | [View Details](#) | 0.0087 | 0.2800 | 0.0100 | 0.0000 | 0.0000 | 0.6014 | 0.2400 | 0.8238 | 1.0000 | 0.2129 | 1.0000 | 0.3014 | 0.5123 | 0.1003 | 0.2038 | 0.2797 |
| compas | linear_regression | shap_interactive | [View Details](#) | 0.0012 | 0.0000 | 0.0000 | 0.0000 | 0.0202 | 0.6667 | 0.2667 | 0.6667 | 0.7500 | 0.2828 | 1.0000 | 0.4000 | 0.6000 | 0.2524 | 0.2667 | 0.3476 |
| compas | linear_regression | prototype | [View Details](#) | 0.0002 | 0.6500 | 0.6079 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | linear_regression | counterfactual | [View Details](#) | 0.0002 | 0.7100 | 0.3879 | 1.0000 | 0.9664 | 0.2209 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | linear_regression | bayesian_rule_list | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4830 | 0.0000 | 0.0000 | 0.0000 |
| compas | linear_regression | corels | [View Details](#) | 0.0002 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4830 | 1.0000 | 0.0000 | 0.0000 |
| compas | linear_regression | feature_ablation | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.7617 | 0.3267 | 0.8267 | 1.0000 | 0.3465 | 1.0000 | 0.4900 | 0.5840 | 0.0126 | 0.3267 | 0.4874 |
| compas | logistic_regression | lime | [View Details](#) | 0.0078 | 0.1600 | 0.0000 | 0.0000 | 0.0000 | 0.4553 | 0.0400 | 0.9721 | 0.9688 | 0.0330 | 0.5000 | 0.0475 | 0.4457 | 0.0191 | 0.0321 | 0.0409 |
| compas | logistic_regression | causal_shap | [View Details](#) | 0.0079 | 0.3000 | 0.0000 | 0.0000 | 0.0000 | 0.5981 | 0.2400 | 0.8292 | 1.0000 | 0.2196 | 1.0000 | 0.3107 | 0.5167 | 0.0880 | 0.2092 | 0.2920 |
| compas | logistic_regression | shap_interactive | [View Details](#) | 0.0035 | 0.0000 | 0.0000 | 0.0000 | 0.0202 | 0.6667 | 0.2667 | 0.6667 | 0.7500 | 0.2828 | 1.0000 | 0.4000 | 0.6000 | 0.2524 | 0.2667 | 0.3476 |
| compas | logistic_regression | prototype | [View Details](#) | 0.0002 | 0.6900 | 0.6496 | 1.0000 | 0.9274 | 0.9993 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | logistic_regression | counterfactual | [View Details](#) | 0.0002 | 0.6500 | 0.3619 | 1.0000 | 0.9922 | 0.3111 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| compas | logistic_regression | influence_functions | [View Details](#) | 0.0145 | 0.0000 | 0.0000 | 0.0000 | 0.3834 | 0.7184 | 0.6667 | 0.4325 | 1.0000 | 0.4194 | 1.0000 | 0.6078 | 0.6706 | 0.6415 | 0.4325 | 0.3585 |
| compas | logistic_regression | bayesian_rule_list | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 0.0000 | 0.0000 | 0.0000 |
| compas | logistic_regression | corels | [View Details](#) | 0.0002 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 1.0000 | 0.0000 | 0.0000 |
| compas | logistic_regression | feature_ablation | [View Details](#) | 0.0002 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.7835 | 0.3600 | 0.8200 | 1.0000 | 0.3818 | 1.0000 | 0.5400 | 0.5960 | -0.0000 | 0.3600 | 0.5400 |
| breast_cancer | decision_tree | shap | [View Details](#) | 0.0022 | 0.1900 | 0.0000 | 0.0000 | 0.0000 | 0.2048 | 0.0000 | 0.9913 | 0.8611 | 0.1900 | 1.0000 | 0.1876 | 0.6870 | 0.0143 | 0.1813 | 0.1757 |
| breast_cancer | decision_tree | lime | [View Details](#) | 0.0082 | 0.0800 | 0.0000 | 0.0000 | 0.0000 | 0.2823 | 0.0147 | 0.9910 | 0.8182 | 0.2000 | 0.5000 | 0.1975 | 0.6769 | 0.0210 | 0.1910 | 0.1790 |
| breast_cancer | decision_tree | causal_shap | [View Details](#) | 0.0911 | 0.4000 | 0.0067 | 0.0000 | 1.0000 | 0.5200 | 0.0000 | 1.0000 | 1.0000 | 0.4600 | 1.0000 | 0.4527 | 0.7345 | 0.0617 | 0.4380 | 0.3983 |
| breast_cancer | decision_tree | shapley_flow | [View Details](#) | 0.0389 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6767 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | decision_tree | shap_interactive | [View Details](#) | 0.0047 | 0.6000 | 0.0000 | 0.0000 | 1.0000 | 0.5438 | 0.0000 | 1.0000 | 0.6667 | 0.8000 | 1.0000 | 0.7724 | 0.9400 | 0.1292 | 0.7467 | 0.6708 |
| breast_cancer | decision_tree | prototype | [View Details](#) | 0.0001 | 0.9123 | 0.9518 | 1.0000 | 0.8603 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | decision_tree | counterfactual | [View Details](#) | 0.0001 | 0.9123 | 0.0798 | 1.0000 | 0.1355 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | decision_tree | bayesian_rule_list | [View Details](#) | 0.0018 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6300 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | decision_tree | corels | [View Details](#) | 0.0010 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1511 | 0.0000 | 0.9358 | 1.0000 | 1.0000 | 1.0000 | 0.9663 | 0.7747 | 0.2021 | 0.9358 | 0.7979 |
| breast_cancer | decision_tree | feature_ablation | [View Details](#) | 0.0019 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1757 | 0.0000 | 0.9900 | 1.0000 | 0.2200 | 1.0000 | 0.2172 | 0.6960 | 0.0163 | 0.2100 | 0.2037 |
| breast_cancer | random_forest | shap | [View Details](#) | 0.0946 | 0.0200 | 0.0000 | 0.0000 | 0.0000 | 0.1961 | 0.0000 | 0.9977 | 0.9054 | 0.0200 | 0.5000 | 0.0183 | 0.6710 | 0.0073 | 0.0177 | 0.0127 |
| breast_cancer | random_forest | lime | [View Details](#) | 0.0177 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1613 | 0.0733 | 0.9766 | 0.8158 | 0.1327 | 0.5000 | 0.1206 | 0.6704 | 0.0673 | 0.1166 | 0.0727 |
| breast_cancer | random_forest | causal_shap | [View Details](#) | 4.0582 | 0.0400 | 0.0000 | 0.0000 | 1.0000 | 0.3561 | 0.1307 | 1.0000 | 0.9968 | 0.3930 | 1.0000 | 0.3407 | 0.6975 | 0.2074 | 0.3313 | 0.1926 |
| breast_cancer | random_forest | shapley_flow | [View Details](#) | 1.9812 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.9989 | 1.0000 | 0.0333 | 0.5000 | 0.0333 | 0.6633 | -0.0000 | 0.0322 | 0.0333 |
| breast_cancer | random_forest | shap_interactive | [View Details](#) | 0.2541 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 1.0000 | 1.0000 | 0.6000 | 1.0000 | 0.6000 | 0.7400 | -0.0000 | 0.5800 | 0.6000 |
| breast_cancer | random_forest | prototype | [View Details](#) | 0.0033 | 0.9561 | 0.9240 | 1.0000 | 0.5944 | 0.5820 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | random_forest | counterfactual | [View Details](#) | 0.0035 | 0.9561 | 0.1490 | 1.0000 | 0.7399 | 0.9293 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | random_forest | bayesian_rule_list | [View Details](#) | 0.0058 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6650 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | random_forest | corels | [View Details](#) | 0.0052 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1511 | 0.0000 | 0.9358 | 1.0000 | 1.0000 | 1.0000 | 0.9663 | 0.8097 | 0.2021 | 0.9358 | 0.7979 |
| breast_cancer | random_forest | feature_ablation | [View Details](#) | 0.1065 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1961 | 0.0000 | 0.9953 | 1.0000 | 0.0400 | 0.5000 | 0.0366 | 0.6700 | 0.0146 | 0.0353 | 0.0254 |
| breast_cancer | gradient_boosting | shap | [View Details](#) | 0.0063 | 0.0800 | 0.0000 | 0.0000 | 0.0000 | 0.1904 | 0.0000 | 0.9960 | 0.9688 | 0.0900 | 1.0000 | 0.0890 | 0.6920 | 0.0061 | 0.0860 | 0.0839 |
| breast_cancer | gradient_boosting | lime | [View Details](#) | 0.0094 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1164 | 0.0147 | 0.9947 | 1.0000 | 0.0400 | 0.5000 | 0.0372 | 0.6757 | 0.0180 | 0.0347 | 0.0220 |
| breast_cancer | gradient_boosting | causal_shap | [View Details](#) | 0.2261 | 0.0800 | 0.0000 | 0.0000 | 0.0000 | 0.3785 | 0.0727 | 0.9912 | 1.0000 | 0.6400 | 1.0000 | 0.5733 | 0.8073 | 0.2767 | 0.5587 | 0.3633 |
| breast_cancer | gradient_boosting | shap_interactive | [View Details](#) | 0.0168 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.2917 | 0.1267 | 0.8600 | 0.2857 | 0.9314 | 1.0000 | 0.8897 | 0.8600 | 0.3172 | 0.8600 | 0.6828 |
| breast_cancer | gradient_boosting | prototype | [View Details](#) | 0.0002 | 0.9561 | 0.9511 | 1.0000 | 0.9152 | 0.0686 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | gradient_boosting | counterfactual | [View Details](#) | 0.0003 | 0.9561 | 0.0961 | 1.0000 | 0.6046 | 0.8487 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | gradient_boosting | bayesian_rule_list | [View Details](#) | 0.0022 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6650 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | gradient_boosting | corels | [View Details](#) | 0.0016 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1511 | 0.0000 | 0.9358 | 1.0000 | 1.0000 | 1.0000 | 0.9663 | 0.8097 | 0.2021 | 0.9358 | 0.7979 |
| breast_cancer | gradient_boosting | feature_ablation | [View Details](#) | 0.0053 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1632 | 0.0000 | 0.9940 | 1.0000 | 0.1200 | 1.0000 | 0.1179 | 0.7080 | 0.0122 | 0.1140 | 0.1078 |
| breast_cancer | mlp | shap | [View Details](#) | 0.0034 | 0.0600 | 0.0000 | 0.0000 | 0.0000 | 0.2640 | 0.0127 | 0.9907 | 0.9538 | 0.0634 | 0.5000 | 0.0628 | 0.6790 | 0.0160 | 0.0607 | 0.0540 |
| breast_cancer | mlp | lime | [View Details](#) | 0.0095 | 0.0400 | 0.0000 | 0.0000 | 0.0000 | 0.2390 | 0.0147 | 0.9923 | 0.8750 | 0.0800 | 0.5000 | 0.0745 | 0.6536 | 0.0283 | 0.0723 | 0.0517 |
| breast_cancer | mlp | integrated_gradients | [View Details](#) | 0.2721 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6533 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | mlp | causal_shap | [View Details](#) | 0.1250 | 0.1000 | 0.0057 | 0.0000 | 1.0000 | 0.2289 | 0.1660 | 1.0000 | 0.9722 | 0.4359 | 1.0000 | 0.3818 | 0.7447 | 0.2180 | 0.3684 | 0.2420 |
| breast_cancer | mlp | shapley_flow | [View Details](#) | 0.0519 | 0.0333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6533 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | mlp | shap_interactive | [View Details](#) | 0.0063 | 0.2000 | 0.0000 | 0.0000 | 1.0000 | 0.2417 | 0.1933 | 1.0000 | 0.1667 | 0.7756 | 1.0000 | 0.7034 | 0.8600 | 0.6255 | 0.6800 | 0.3745 |
| breast_cancer | mlp | prototype | [View Details](#) | 0.0002 | 0.9474 | 0.9459 | 1.0000 | 0.9607 | 0.3784 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | mlp | counterfactual | [View Details](#) | 0.0002 | 0.9474 | 0.0956 | 1.0000 | 0.5583 | 0.9812 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | mlp | influence_functions | [View Details](#) | 0.0198 | 0.0000 | 0.0000 | 0.0000 | 0.3591 | 0.2532 | 0.7333 | 0.3526 | 1.0000 | 0.3210 | 1.0000 | 0.3001 | 0.9300 | 0.9333 | 0.3526 | 0.0667 |
| breast_cancer | mlp | bayesian_rule_list | [View Details](#) | 0.0021 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6580 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | mlp | corels | [View Details](#) | 0.0012 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1511 | 0.0000 | 0.9358 | 1.0000 | 1.0000 | 1.0000 | 0.9663 | 0.8027 | 0.2021 | 0.9358 | 0.7979 |
| breast_cancer | mlp | feature_ablation | [View Details](#) | 0.0030 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.2673 | 0.0253 | 0.9827 | 1.0000 | 0.0867 | 0.5000 | 0.0855 | 0.6740 | 0.0321 | 0.0827 | 0.0679 |
| breast_cancer | linear_regression | lime | [View Details](#) | 0.0123 | 0.0000 | 0.0017 | 0.0000 | 0.0000 | 0.2392 | 0.1320 | 0.9596 | 0.7174 | 0.2997 | 0.9980 | 0.2729 | 0.6885 | 0.1280 | 0.2596 | 0.1720 |
| breast_cancer | linear_regression | causal_shap | [View Details](#) | 0.0988 | 0.2400 | 0.0013 | 0.0000 | 1.0000 | 0.4483 | 0.2533 | 1.0000 | 0.8777 | 0.3692 | 1.0000 | 0.3089 | 0.7503 | 0.2338 | 0.2950 | 0.1462 |
| breast_cancer | linear_regression | shap_interactive | [View Details](#) | 0.0051 | 0.4000 | 0.0000 | 0.0000 | 1.0000 | 0.4157 | 0.0000 | 1.0000 | 0.2857 | 0.8000 | 1.0000 | 0.7379 | 0.9400 | 0.2646 | 0.7133 | 0.5354 |
| breast_cancer | linear_regression | prototype | [View Details](#) | 0.0002 | 0.9561 | 0.6966 | 1.0000 | 0.8736 | 0.4718 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | linear_regression | counterfactual | [View Details](#) | 0.0002 | 0.9561 | 0.4314 | 1.0000 | 0.1716 | 0.3418 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | linear_regression | bayesian_rule_list | [View Details](#) | 0.0021 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6650 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | linear_regression | corels | [View Details](#) | 0.0018 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1511 | 0.0000 | 0.9358 | 1.0000 | 1.0000 | 1.0000 | 0.9663 | 0.8097 | 0.2021 | 0.9358 | 0.7979 |
| breast_cancer | linear_regression | feature_ablation | [View Details](#) | 0.0019 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.6612 | 0.0127 | 0.9393 | 1.0000 | 0.8113 | 1.0000 | 0.7855 | 0.9040 | 0.1526 | 0.7593 | 0.6674 |
| breast_cancer | logistic_regression | lime | [View Details](#) | 0.0105 | 0.0200 | 0.0000 | 0.0000 | 0.0000 | 0.2806 | 0.0147 | 0.9948 | 0.9118 | 0.0600 | 0.5000 | 0.0566 | 0.6938 | 0.0194 | 0.0548 | 0.0406 |
| breast_cancer | logistic_regression | causal_shap | [View Details](#) | 0.0972 | 0.0400 | 0.0000 | 0.0000 | 1.0000 | 0.2209 | 0.1113 | 1.0000 | 0.9394 | 0.4203 | 1.0000 | 0.3706 | 0.7694 | 0.2100 | 0.3580 | 0.2300 |
| breast_cancer | logistic_regression | shap_interactive | [View Details](#) | 0.0062 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.2438 | 0.3200 | 1.0000 | 0.3333 | 0.7250 | 1.0000 | 0.7172 | 1.0000 | 0.5448 | 0.6933 | 0.4552 |
| breast_cancer | logistic_regression | prototype | [View Details](#) | 0.0001 | 0.9825 | 0.9331 | 1.0000 | 0.7366 | 0.4174 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | logistic_regression | counterfactual | [View Details](#) | 0.0001 | 0.9825 | 0.1252 | 1.0000 | 0.9065 | 0.2318 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | logistic_regression | influence_functions | [View Details](#) | 0.0233 | 0.0000 | 0.0000 | 0.0000 | 0.3591 | 0.2532 | 0.7333 | 0.3526 | 1.0000 | 0.3210 | 1.0000 | 0.3001 | 0.9650 | 0.9333 | 0.3526 | 0.0667 |
| breast_cancer | logistic_regression | bayesian_rule_list | [View Details](#) | 0.0019 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6860 | 0.0000 | 0.0000 | 0.0000 |
| breast_cancer | logistic_regression | corels | [View Details](#) | 0.0011 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1511 | 0.0000 | 0.9358 | 1.0000 | 1.0000 | 1.0000 | 0.9663 | 0.8307 | 0.2021 | 0.9358 | 0.7979 |
| breast_cancer | logistic_regression | feature_ablation | [View Details](#) | 0.0020 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1784 | 0.0000 | 0.9913 | 1.0000 | 0.0781 | 1.0000 | 0.0738 | 0.7100 | 0.0237 | 0.0713 | 0.0563 |
| heart_disease | decision_tree | shap | [View Details](#) | 0.0006 | 0.6667 | 0.0083 | 0.0000 | 0.0000 | 0.4715 | 0.0867 | 0.8200 | 0.5085 | 0.5892 | 1.0000 | 0.6083 | 0.7133 | 0.0874 | 0.4867 | 0.5793 |
| heart_disease | decision_tree | lime | [View Details](#) | 0.0095 | 0.2000 | 0.0200 | 0.0000 | 0.0000 | 0.5457 | 0.0120 | 0.9579 | 0.7941 | 0.1943 | 1.0000 | 0.1968 | 0.5891 | 0.0072 | 0.1579 | 0.1928 |
| heart_disease | decision_tree | causal_shap | [View Details](#) | 0.0158 | 0.4400 | 0.0067 | 0.0000 | 1.0000 | 0.5578 | 0.1560 | 1.0000 | 1.0000 | 0.3624 | 1.0000 | 0.3735 | 0.6408 | 0.1461 | 0.3062 | 0.3139 |
| heart_disease | decision_tree | shapley_flow | [View Details](#) | 0.0073 | 0.2000 | 0.0333 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.9933 | 1.0000 | 0.0333 | 0.5000 | 0.0333 | 0.5700 | -0.0000 | 0.0267 | 0.0333 |
| heart_disease | decision_tree | shap_interactive | [View Details](#) | 0.0047 | 0.8000 | 0.0000 | 0.0000 | 1.0000 | 0.8062 | 0.1200 | 1.0000 | 1.0000 | 0.7225 | 1.0000 | 0.7500 | 0.9400 | 0.0861 | 0.6000 | 0.7139 |
| heart_disease | decision_tree | prototype | [View Details](#) | 0.0001 | 0.7333 | 0.9831 | 1.0000 | 0.9307 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | decision_tree | counterfactual | [View Details](#) | 0.0003 | 0.7333 | 0.0205 | 1.0000 | 0.9299 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | decision_tree | bayesian_rule_list | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5133 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | decision_tree | corels | [View Details](#) | 0.0002 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5133 | 1.0000 | 0.0000 | 0.0000 |
| heart_disease | decision_tree | feature_ablation | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4627 | 0.0920 | 0.8200 | 1.0000 | 0.5548 | 1.0000 | 0.5750 | 0.7240 | 0.0962 | 0.4600 | 0.5438 |
| heart_disease | random_forest | shap | [View Details](#) | 0.0272 | 0.5167 | 0.0056 | 0.0000 | 0.0000 | 0.4958 | 0.0667 | 0.8700 | 0.5455 | 0.4680 | 1.0000 | 0.4833 | 0.6683 | 0.0544 | 0.3867 | 0.4622 |
| heart_disease | random_forest | lime | [View Details](#) | 0.0228 | 0.1800 | 0.0000 | 0.0000 | 0.0000 | 0.4506 | 0.1680 | 0.8976 | 0.7879 | 0.2126 | 1.0000 | 0.2418 | 0.5659 | 0.1177 | 0.1976 | 0.1823 |
| heart_disease | random_forest | causal_shap | [View Details](#) | 0.6725 | 0.2800 | 0.0040 | 0.0000 | 1.0000 | 0.4357 | 0.2960 | 1.0000 | 0.8935 | 0.2673 | 1.0000 | 0.2395 | 0.6110 | 0.3946 | 0.2121 | 0.1254 |
| heart_disease | random_forest | shapley_flow | [View Details](#) | 0.3348 | 0.1667 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | random_forest | shap_interactive | [View Details](#) | 0.1562 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.6055 | 0.2000 | 1.0000 | 0.2500 | 0.2133 | 1.0000 | 0.2500 | 0.7400 | 0.8453 | 0.2000 | 0.1547 |
| heart_disease | random_forest | prototype | [View Details](#) | 0.0039 | 0.7333 | 0.7346 | 1.0000 | 0.8886 | 0.5473 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | random_forest | counterfactual | [View Details](#) | 0.0036 | 0.7333 | 0.3022 | 1.0000 | 0.7818 | 0.7012 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | random_forest | bayesian_rule_list | [View Details](#) | 0.0038 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5133 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | random_forest | corels | [View Details](#) | 0.0035 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5133 | 1.0000 | 0.0000 | 0.0000 |
| heart_disease | random_forest | feature_ablation | [View Details](#) | 0.0191 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4859 | 0.0560 | 0.8680 | 1.0000 | 0.4972 | 1.0000 | 0.5100 | 0.6800 | 0.0481 | 0.4080 | 0.4919 |
| heart_disease | gradient_boosting | shap | [View Details](#) | 0.0019 | 0.5500 | 0.0333 | 0.0000 | 0.0000 | 0.4630 | 0.0600 | 0.8700 | 0.6000 | 0.5112 | 1.0000 | 0.5250 | 0.6550 | 0.0431 | 0.4200 | 0.5069 |
| heart_disease | gradient_boosting | lime | [View Details](#) | 0.0100 | 0.1000 | 0.0000 | 0.0000 | 0.0000 | 0.4875 | 0.1680 | 0.8891 | 0.8387 | 0.2768 | 1.0000 | 0.3078 | 0.5569 | 0.1145 | 0.2491 | 0.2455 |
| heart_disease | gradient_boosting | causal_shap | [View Details](#) | 0.0359 | 0.3200 | 0.0200 | 0.0000 | 1.0000 | 0.4986 | 0.2200 | 1.0000 | 1.0000 | 0.3103 | 1.0000 | 0.3248 | 0.5748 | 0.2491 | 0.2703 | 0.2309 |
| heart_disease | gradient_boosting | shap_interactive | [View Details](#) | 0.0103 | 0.4000 | 0.0000 | 0.0000 | 1.0000 | 0.6124 | 0.1200 | 1.0000 | 1.0000 | 0.3225 | 1.0000 | 0.3500 | 0.6800 | 0.0861 | 0.2800 | 0.3139 |
| heart_disease | gradient_boosting | prototype | [View Details](#) | 0.0003 | 0.7000 | 0.8027 | 1.0000 | 0.9211 | 0.1824 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | gradient_boosting | counterfactual | [View Details](#) | 0.0003 | 0.7000 | 0.2336 | 1.0000 | 0.9194 | 0.4206 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | gradient_boosting | bayesian_rule_list | [View Details](#) | 0.0009 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4900 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | gradient_boosting | corels | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4900 | 1.0000 | 0.0000 | 0.0000 |
| heart_disease | gradient_boosting | feature_ablation | [View Details](#) | 0.0017 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4540 | 0.0600 | 0.8760 | 1.0000 | 0.4812 | 1.0000 | 0.4950 | 0.6460 | 0.0431 | 0.3960 | 0.4769 |
| heart_disease | mlp | shap | [View Details](#) | 0.0008 | 0.3833 | 0.0167 | 0.0000 | 0.0000 | 0.4875 | 0.0800 | 0.8967 | 0.7308 | 0.3316 | 1.0000 | 0.3500 | 0.6750 | 0.0574 | 0.2800 | 0.3259 |
| heart_disease | mlp | lime | [View Details](#) | 0.0101 | 0.0600 | 0.0400 | 0.0000 | 0.0000 | 0.4085 | 0.1800 | 0.8742 | 0.7381 | 0.2285 | 1.0000 | 0.2616 | 0.6098 | 0.1464 | 0.2142 | 0.1936 |
| heart_disease | mlp | integrated_gradients | [View Details](#) | 0.0427 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6300 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | mlp | causal_shap | [View Details](#) | 0.0202 | 0.2600 | 0.0050 | 0.0000 | 0.0000 | 0.4438 | 0.2120 | 0.9238 | 0.9904 | 0.2668 | 1.0000 | 0.2755 | 0.6389 | 0.2228 | 0.2281 | 0.1772 |
| heart_disease | mlp | shapley_flow | [View Details](#) | 0.0087 | 0.1000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6300 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | mlp | shap_interactive | [View Details](#) | 0.0042 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.7000 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | mlp | prototype | [View Details](#) | 0.0001 | 0.8000 | 0.7834 | 1.0000 | 0.8538 | 0.6663 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | mlp | counterfactual | [View Details](#) | 0.0001 | 0.8000 | 0.2512 | 1.0000 | 0.9016 | 0.2578 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | mlp | influence_functions | [View Details](#) | 0.0197 | 0.0000 | 0.0000 | 0.0000 | 0.4416 | 0.4279 | 0.6000 | 0.3049 | 1.0000 | 0.2816 | 1.0000 | 0.3018 | 0.8010 | 0.8819 | 0.3049 | 0.1181 |
| heart_disease | mlp | bayesian_rule_list | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | mlp | corels | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 1.0000 | 0.0000 | 0.0000 |
| heart_disease | mlp | feature_ablation | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4592 | 0.0840 | 0.8920 | 1.0000 | 0.3457 | 1.0000 | 0.3650 | 0.6800 | 0.0603 | 0.2920 | 0.3397 |
| heart_disease | linear_regression | lime | [View Details](#) | 0.0133 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.5421 | 0.1080 | 0.9295 | 0.8485 | 0.1891 | 1.0000 | 0.2095 | 0.6204 | 0.0711 | 0.1695 | 0.1689 |
| heart_disease | linear_regression | causal_shap | [View Details](#) | 0.0153 | 0.2600 | 0.0000 | 0.0000 | 0.0000 | 0.5295 | 0.1480 | 0.9197 | 0.9964 | 0.3863 | 1.0000 | 0.3902 | 0.6894 | 0.1299 | 0.3147 | 0.3301 |
| heart_disease | linear_regression | shap_interactive | [View Details](#) | 0.0042 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.9600 | 0.8333 | 0.2000 | 1.0000 | 0.2000 | 0.7600 | -0.0000 | 0.1600 | 0.2000 |
| heart_disease | linear_regression | prototype | [View Details](#) | 0.0001 | 0.8167 | 0.6256 | 1.0000 | 0.8775 | 0.1641 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | linear_regression | counterfactual | [View Details](#) | 0.0001 | 0.8167 | 0.4117 | 1.0000 | 0.8074 | 0.5538 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | linear_regression | bayesian_rule_list | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5717 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | linear_regression | corels | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5717 | 1.0000 | 0.0000 | 0.0000 |
| heart_disease | linear_regression | feature_ablation | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.5937 | 0.0240 | 0.9160 | 1.0000 | 0.3645 | 1.0000 | 0.3700 | 0.6880 | 0.0172 | 0.2960 | 0.3628 |
| heart_disease | logistic_regression | lime | [View Details](#) | 0.0107 | 0.0200 | 0.0100 | 0.0000 | 0.0000 | 0.6408 | 0.0840 | 0.9364 | 0.8710 | 0.1515 | 1.0000 | 0.1675 | 0.5968 | 0.0643 | 0.1364 | 0.1357 |
| heart_disease | logistic_regression | causal_shap | [View Details](#) | 0.0157 | 0.2400 | 0.0200 | 0.0000 | 0.0000 | 0.5309 | 0.2120 | 0.9004 | 0.9278 | 0.3916 | 1.0000 | 0.3970 | 0.6764 | 0.1812 | 0.3245 | 0.3188 |
| heart_disease | logistic_regression | shap_interactive | [View Details](#) | 0.0030 | 0.2000 | 0.2000 | 0.0000 | 0.0000 | 0.4082 | 0.1200 | 0.8800 | 0.8000 | 0.3225 | 1.0000 | 0.3500 | 0.6800 | 0.0861 | 0.2800 | 0.3139 |
| heart_disease | logistic_regression | prototype | [View Details](#) | 0.0001 | 0.8000 | 0.7513 | 1.0000 | 0.8847 | 0.9785 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | logistic_regression | counterfactual | [View Details](#) | 0.0002 | 0.8000 | 0.2860 | 1.0000 | 0.9646 | 0.0165 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | logistic_regression | influence_functions | [View Details](#) | 0.0160 | 0.0000 | 0.0000 | 0.0000 | 0.4416 | 0.4279 | 0.6000 | 0.3049 | 1.0000 | 0.2816 | 1.0000 | 0.3018 | 0.8360 | 0.8819 | 0.3049 | 0.1181 |
| heart_disease | logistic_regression | bayesian_rule_list | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| heart_disease | logistic_regression | corels | [View Details](#) | 0.0002 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 1.0000 | 0.0000 | 0.0000 |
| heart_disease | logistic_regression | feature_ablation | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.5733 | 0.0360 | 0.9080 | 1.0000 | 0.3767 | 1.0000 | 0.3850 | 0.6800 | 0.0258 | 0.3080 | 0.3742 |
| german_credit | decision_tree | shap | [View Details](#) | 0.0009 | 0.5300 | 0.0450 | 0.0000 | 0.0000 | 0.4091 | 0.1714 | 0.8814 | 0.6827 | 0.4670 | 1.0000 | 0.4800 | 0.5860 | 0.0995 | 0.4114 | 0.4305 |
| german_credit | decision_tree | lime | [View Details](#) | 0.0099 | 0.2000 | 0.0200 | 0.0000 | 0.0000 | 0.2852 | 0.0143 | 0.9850 | 0.9459 | 0.1000 | 0.5000 | 0.0991 | 0.4905 | 0.0039 | 0.0850 | 0.0961 |
| german_credit | decision_tree | causal_shap | [View Details](#) | 0.0224 | 0.4000 | 0.0267 | 0.0000 | 0.0000 | 0.4547 | 0.1114 | 0.9487 | 1.0000 | 0.2652 | 1.0000 | 0.2671 | 0.5311 | 0.0713 | 0.2302 | 0.2287 |
| german_credit | decision_tree | shapley_flow | [View Details](#) | 0.0105 | 0.1667 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | decision_tree | shap_interactive | [View Details](#) | 0.0034 | 0.4000 | 0.0000 | 0.0000 | 0.0000 | 0.4444 | 0.0000 | 0.9143 | 0.7500 | 0.6000 | 1.0000 | 0.6000 | 0.8800 | -0.0000 | 0.5143 | 0.6000 |
| german_credit | decision_tree | prototype | [View Details](#) | 0.0001 | 0.6450 | 0.9130 | 1.0000 | 0.7909 | 0.3620 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | decision_tree | counterfactual | [View Details](#) | 0.0001 | 0.6450 | 0.1025 | 1.0000 | 0.8366 | 0.0348 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | decision_tree | bayesian_rule_list | [View Details](#) | 0.0006 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.8571 | 1.0000 | 1.0000 | 1.0000 | 1.0000 | 0.5020 | -0.0000 | 0.8571 | 1.0000 |
| german_credit | decision_tree | corels | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4270 | 1.0000 | 0.0000 | 0.0000 |
| german_credit | decision_tree | feature_ablation | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.3921 | 0.1629 | 0.8800 | 1.0000 | 0.4769 | 1.0000 | 0.4900 | 0.6240 | 0.0980 | 0.4200 | 0.4420 |
| german_credit | random_forest | shap | [View Details](#) | 0.0312 | 0.2500 | 0.0103 | 0.0000 | 0.0000 | 0.3844 | 0.0914 | 0.9186 | 0.8817 | 0.1871 | 0.5000 | 0.1967 | 0.5370 | 0.0860 | 0.1686 | 0.1640 |
| german_credit | random_forest | lime | [View Details](#) | 0.0213 | 0.1400 | 0.0000 | 0.0000 | 0.0000 | 0.4237 | 0.0143 | 0.9926 | 0.9767 | 0.0386 | 0.5000 | 0.0381 | 0.5134 | 0.0070 | 0.0326 | 0.0330 |
| german_credit | random_forest | causal_shap | [View Details](#) | 0.9309 | 0.1800 | 0.0000 | 0.0000 | 0.0000 | 0.4268 | 0.0943 | 0.9613 | 1.0000 | 0.1086 | 0.5000 | 0.1111 | 0.5279 | 0.0886 | 0.0978 | 0.0714 |
| german_credit | random_forest | shapley_flow | [View Details](#) | 0.4802 | 0.1000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5367 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | random_forest | shap_interactive | [View Details](#) | 0.1743 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | random_forest | prototype | [View Details](#) | 0.0036 | 0.7050 | 0.7289 | 1.0000 | 0.9131 | 0.4507 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | random_forest | counterfactual | [View Details](#) | 0.0034 | 0.7050 | 0.3051 | 1.0000 | 0.7988 | 0.2438 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | random_forest | bayesian_rule_list | [View Details](#) | 0.0043 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.8571 | 1.0000 | 1.0000 | 1.0000 | 1.0000 | 0.5370 | -0.0000 | 0.8571 | 1.0000 |
| german_credit | random_forest | corels | [View Details](#) | 0.0045 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4620 | 1.0000 | 0.0000 | 0.0000 |
| german_credit | random_forest | feature_ablation | [View Details](#) | 0.0265 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.3842 | 0.1029 | 0.9343 | 1.0000 | 0.1694 | 0.5000 | 0.1800 | 0.5700 | 0.0737 | 0.1543 | 0.1463 |
| german_credit | gradient_boosting | shap | [View Details](#) | 0.0021 | 0.2600 | 0.0508 | 0.0000 | 0.0000 | 0.4589 | 0.0843 | 0.9357 | 0.9186 | 0.2207 | 0.5000 | 0.2283 | 0.5610 | 0.0582 | 0.1957 | 0.2018 |
| german_credit | gradient_boosting | lime | [View Details](#) | 0.0101 | 0.1000 | 0.0207 | 0.0000 | 0.0000 | 0.5187 | 0.0857 | 0.9675 | 0.9091 | 0.1500 | 0.5000 | 0.1482 | 0.5411 | 0.0315 | 0.1275 | 0.1285 |
| german_credit | gradient_boosting | causal_shap | [View Details](#) | 0.0526 | 0.2000 | 0.0250 | 0.0000 | 0.0000 | 0.6679 | 0.1257 | 0.9471 | 1.0000 | 0.1527 | 0.5000 | 0.1623 | 0.5306 | 0.0808 | 0.1424 | 0.1192 |
| german_credit | gradient_boosting | shap_interactive | [View Details](#) | 0.0098 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | gradient_boosting | prototype | [View Details](#) | 0.0004 | 0.7150 | 0.7451 | 1.0000 | 0.6025 | 0.3993 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | gradient_boosting | counterfactual | [View Details](#) | 0.0006 | 0.7150 | 0.2889 | 1.0000 | 0.8465 | 0.5559 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | gradient_boosting | bayesian_rule_list | [View Details](#) | 0.0009 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.8571 | 1.0000 | 1.0000 | 1.0000 | 1.0000 | 0.5580 | -0.0000 | 0.8571 | 1.0000 |
| german_credit | gradient_boosting | corels | [View Details](#) | 0.0006 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4830 | 1.0000 | 0.0000 | 0.0000 |
| german_credit | gradient_boosting | feature_ablation | [View Details](#) | 0.0019 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4511 | 0.0714 | 0.9514 | 1.0000 | 0.2191 | 0.5000 | 0.2233 | 0.5760 | 0.0356 | 0.1914 | 0.2044 |
| german_credit | mlp | shap | [View Details](#) | 0.0009 | 0.5100 | 0.0348 | 0.0000 | 0.0000 | 0.3950 | 0.1400 | 0.8700 | 0.6190 | 0.4304 | 0.5000 | 0.4433 | 0.6400 | 0.1116 | 0.3800 | 0.3984 |
| german_credit | mlp | lime | [View Details](#) | 0.0098 | 0.2600 | 0.0000 | 0.0000 | 0.0000 | 0.4477 | 0.0429 | 0.9814 | 0.9750 | 0.0712 | 0.5000 | 0.0721 | 0.5328 | 0.0249 | 0.0614 | 0.0551 |
| german_credit | mlp | integrated_gradients | [View Details](#) | 0.0593 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4900 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | mlp | causal_shap | [View Details](#) | 0.0294 | 0.3600 | 0.0117 | 0.0000 | 0.0000 | 0.3693 | 0.1971 | 0.9757 | 0.9606 | 0.2186 | 1.0000 | 0.1860 | 0.5611 | 0.1865 | 0.1639 | 0.1135 |
| german_credit | mlp | shapley_flow | [View Details](#) | 0.0130 | 0.2000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4900 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | mlp | shap_interactive | [View Details](#) | 0.0044 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | mlp | prototype | [View Details](#) | 0.0002 | 0.7150 | 0.8110 | 1.0000 | 0.9366 | 0.3733 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | mlp | counterfactual | [View Details](#) | 0.0002 | 0.7150 | 0.2207 | 1.0000 | 0.8961 | 0.8452 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | mlp | influence_functions | [View Details](#) | 0.0220 | 0.0000 | 0.0000 | 0.0000 | 0.4662 | 0.3583 | 0.7143 | 0.3179 | 1.0000 | 0.2946 | 1.0000 | 0.2993 | 0.7303 | 0.8992 | 0.3179 | 0.1008 |
| german_credit | mlp | bayesian_rule_list | [View Details](#) | 0.0006 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.8571 | 1.0000 | 1.0000 | 1.0000 | 1.0000 | 0.5650 | -0.0000 | 0.8571 | 1.0000 |
| german_credit | mlp | corels | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4900 | 1.0000 | 0.0000 | 0.0000 |
| german_credit | mlp | feature_ablation | [View Details](#) | 0.0006 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4046 | 0.1057 | 0.8686 | 1.0000 | 0.3723 | 0.5000 | 0.3833 | 0.6500 | 0.1138 | 0.3286 | 0.3462 |
| german_credit | linear_regression | lime | [View Details](#) | 0.0095 | 0.0600 | 0.0167 | 0.0000 | 0.0000 | 0.1474 | 0.0286 | 0.9914 | 0.9592 | 0.0367 | 0.5000 | 0.0362 | 0.5252 | 0.0111 | 0.0314 | 0.0289 |
| german_credit | linear_regression | causal_shap | [View Details](#) | 0.0260 | 0.0800 | 0.0050 | 0.0000 | 0.0000 | 0.2704 | 0.0514 | 0.9854 | 0.9874 | 0.0488 | 0.5000 | 0.0475 | 0.5259 | 0.0557 | 0.0429 | 0.0243 |
| german_credit | linear_regression | shap_interactive | [View Details](#) | 0.0054 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | linear_regression | prototype | [View Details](#) | 0.0001 | 0.7250 | 0.5913 | 1.0000 | 0.9608 | 0.9169 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | linear_regression | counterfactual | [View Details](#) | 0.0002 | 0.7250 | 0.4427 | 1.0000 | 0.8664 | 0.8549 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | linear_regression | bayesian_rule_list | [View Details](#) | 0.0010 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.8571 | 1.0000 | 1.0000 | 1.0000 | 1.0000 | 0.5510 | -0.0000 | 0.8571 | 1.0000 |
| german_credit | linear_regression | corels | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4760 | 1.0000 | 0.0000 | 0.0000 |
| german_credit | linear_regression | feature_ablation | [View Details](#) | 0.0007 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.3733 | 0.0571 | 0.9743 | 1.0000 | 0.0832 | 0.5000 | 0.0867 | 0.5480 | 0.0285 | 0.0743 | 0.0715 |
| german_credit | logistic_regression | lime | [View Details](#) | 0.0100 | 0.0800 | 0.0040 | 0.0000 | 0.0000 | 0.9349 | 0.0286 | 0.9853 | 1.0000 | 0.0254 | 0.5000 | 0.0287 | 0.5352 | 0.0233 | 0.0253 | 0.0167 |
| german_credit | logistic_regression | causal_shap | [View Details](#) | 0.0220 | 0.0600 | 0.0050 | 0.0000 | 0.0000 | 0.3429 | 0.0571 | 0.9856 | 1.0000 | 0.0566 | 0.5000 | 0.0557 | 0.5464 | 0.0460 | 0.0494 | 0.0340 |
| german_credit | logistic_regression | shap_interactive | [View Details](#) | 0.0038 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4200 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | logistic_regression | prototype | [View Details](#) | 0.0001 | 0.7350 | 0.7158 | 1.0000 | 0.7247 | 0.2189 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | logistic_regression | counterfactual | [View Details](#) | 0.0001 | 0.7350 | 0.3183 | 1.0000 | 0.8316 | 0.1461 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| german_credit | logistic_regression | influence_functions | [View Details](#) | 0.0179 | 0.0000 | 0.0000 | 0.0000 | 0.4662 | 0.3583 | 0.7143 | 0.3179 | 1.0000 | 0.2946 | 1.0000 | 0.2993 | 0.7303 | 0.8992 | 0.3179 | 0.1008 |
| german_credit | logistic_regression | bayesian_rule_list | [View Details](#) | 0.0006 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.8571 | 1.0000 | 1.0000 | 1.0000 | 1.0000 | 0.5650 | -0.0000 | 0.8571 | 1.0000 |
| german_credit | logistic_regression | corels | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4900 | 1.0000 | 0.0000 | 0.0000 |
| german_credit | logistic_regression | feature_ablation | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4733 | 0.0543 | 0.9714 | 1.0000 | 0.0790 | 0.5000 | 0.0833 | 0.5620 | 0.0327 | 0.0714 | 0.0673 |
| iris | decision_tree | shap | [View Details](#) | 0.0007 | 0.4000 | 0.0000 | 0.2167 | 0.0000 | 0.8517 | 0.3417 | 0.8750 | 1.0000 | 0.3919 | 1.0000 | 0.4556 | 0.7933 | 0.0167 | 0.3417 | 0.4500 |
| iris | decision_tree | lime | [View Details](#) | 0.0105 | 0.0167 | 0.0000 | 0.0000 | 0.0000 | 0.7184 | 0.2500 | 0.9009 | 0.6667 | 0.2614 | 1.0000 | 0.3102 | 0.7376 | 0.0527 | 0.2342 | 0.2807 |
| iris | decision_tree | causal_shap | [View Details](#) | 0.0152 | 0.4000 | 0.0000 | 0.1667 | 0.0000 | 0.7545 | 0.5000 | 0.8071 | 1.0000 | 0.4297 | 1.0000 | 0.5055 | 0.7824 | 0.2311 | 0.3904 | 0.4356 |
| iris | decision_tree | shapley_flow | [View Details](#) | 0.0056 | 0.0167 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0250 | 0.9917 | 1.0000 | 0.0289 | 0.5000 | 0.0333 | 0.6633 | -0.0000 | 0.0250 | 0.0333 |
| iris | decision_tree | shap_interactive | [View Details](#) | 0.0018 | 0.4000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.3000 | 1.0000 | 1.0000 | 0.3464 | 1.0000 | 0.4000 | 0.8200 | -0.0000 | 0.3000 | 0.4000 |
| iris | decision_tree | prototype | [View Details](#) | 0.0001 | 0.9333 | 0.9937 | 1.0000 | 0.9315 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| iris | decision_tree | counterfactual | [View Details](#) | 0.0001 | 0.9333 | 0.0272 | 1.0000 | 0.9758 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| iris | decision_tree | bayesian_rule_list | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6533 | 0.0000 | 0.0000 | 0.0000 |
| iris | decision_tree | corels | [View Details](#) | 0.0002 | 0.0000 | 0.0000 | 0.0000 | 0.0112 | 0.4858 | 0.7500 | 0.5320 | 1.0000 | 0.5139 | 1.0000 | 0.6841 | 0.6907 | 0.4891 | 0.5320 | 0.5109 |
| iris | decision_tree | feature_ablation | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.8517 | 0.3417 | 0.8750 | 1.0000 | 0.3919 | 1.0000 | 0.4556 | 0.7933 | 0.0167 | 0.3417 | 0.4500 |
| iris | random_forest | shap | [View Details](#) | 0.0242 | 0.2333 | 0.0167 | 0.0815 | 0.0000 | 0.7515 | 0.1917 | 0.9250 | 0.8462 | 0.2187 | 1.0000 | 0.2556 | 0.7100 | 0.0167 | 0.1917 | 0.2500 |
| iris | random_forest | lime | [View Details](#) | 0.0191 | 0.0500 | 0.0167 | 0.0000 | 0.0000 | 0.8367 | 0.2500 | 0.8868 | 0.6471 | 0.2376 | 1.0000 | 0.2894 | 0.7012 | 0.0846 | 0.2202 | 0.2487 |
| iris | random_forest | causal_shap | [View Details](#) | 0.5398 | 0.2000 | 0.0000 | 0.1212 | 1.0000 | 0.5540 | 0.5000 | 0.8790 | 0.9649 | 0.3880 | 1.0000 | 0.4815 | 0.7223 | 0.3460 | 0.3665 | 0.3206 |
| iris | random_forest | shapley_flow | [View Details](#) | 0.2766 | 0.0333 | 0.0333 | 0.0000 | 0.0000 | 0.0000 | 0.0250 | 0.9917 | 1.0000 | 0.0289 | 0.5000 | 0.0333 | 0.6400 | -0.0000 | 0.0250 | 0.0333 |
| iris | random_forest | shap_interactive | [View Details](#) | 0.1517 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.7000 | 0.0000 | 0.0000 | 0.0000 |
| iris | random_forest | prototype | [View Details](#) | 0.0044 | 0.9000 | 0.9382 | 1.0000 | 0.9215 | 0.8084 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| iris | random_forest | counterfactual | [View Details](#) | 0.0060 | 0.9000 | 0.0886 | 1.0000 | 0.9482 | 0.6627 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| iris | random_forest | bayesian_rule_list | [View Details](#) | 0.0051 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6300 | 0.0000 | 0.0000 | 0.0000 |
| iris | random_forest | corels | [View Details](#) | 0.0038 | 0.0000 | 0.0000 | 0.0000 | 0.0112 | 0.4858 | 0.7500 | 0.5320 | 1.0000 | 0.5139 | 1.0000 | 0.6841 | 0.6673 | 0.4891 | 0.5320 | 0.5109 |
| iris | random_forest | feature_ablation | [View Details](#) | 0.0150 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.7515 | 0.1917 | 0.9250 | 1.0000 | 0.2187 | 1.0000 | 0.2556 | 0.7100 | 0.0167 | 0.1917 | 0.2500 |
| iris | gradient_boosting | shap | [View Details](#) | 0.0036 | 0.3167 | 0.0000 | 0.1333 | 0.0000 | 0.7345 | 0.2667 | 0.8667 | 1.0000 | 0.2976 | 1.0000 | 0.3556 | 0.7967 | 0.0667 | 0.2667 | 0.3333 |
| iris | gradient_boosting | lime | [View Details](#) | 0.0117 | 0.0167 | 0.0000 | 0.0000 | 0.0000 | 0.7367 | 0.2250 | 0.9086 | 0.7500 | 0.2330 | 1.0000 | 0.2778 | 0.7511 | 0.0500 | 0.2086 | 0.2500 |
| iris | gradient_boosting | causal_shap | [View Details](#) | 0.0874 | 0.3167 | 0.0000 | 0.1822 | 0.0000 | 0.5740 | 0.5250 | 0.8585 | 1.0000 | 0.4133 | 1.0000 | 0.4840 | 0.8085 | 0.3868 | 0.3677 | 0.3132 |
| iris | gradient_boosting | shap_interactive | [View Details](#) | 0.0206 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.3000 | 1.0000 | 1.0000 | 0.3464 | 1.0000 | 0.4000 | 0.8200 | -0.0000 | 0.3000 | 0.4000 |
| iris | gradient_boosting | prototype | [View Details](#) | 0.0008 | 0.9667 | 0.9939 | 1.0000 | 0.9215 | 0.9369 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| iris | gradient_boosting | counterfactual | [View Details](#) | 0.0010 | 0.9667 | 0.0276 | 1.0000 | 0.9924 | 0.4836 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| iris | gradient_boosting | bayesian_rule_list | [View Details](#) | 0.0016 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6767 | 0.0000 | 0.0000 | 0.0000 |
| iris | gradient_boosting | corels | [View Details](#) | 0.0010 | 0.0000 | 0.0000 | 0.0000 | 0.0112 | 0.4858 | 0.7500 | 0.5320 | 1.0000 | 0.5139 | 1.0000 | 0.6841 | 0.7140 | 0.4891 | 0.5320 | 0.5109 |
| iris | gradient_boosting | feature_ablation | [View Details](#) | 0.0026 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.7345 | 0.2667 | 0.8667 | 1.0000 | 0.2976 | 0.9999 | 0.3556 | 0.7967 | 0.0667 | 0.2667 | 0.3333 |
| iris | mlp | shap | [View Details](#) | 0.0009 | 0.2167 | 0.0167 | 0.0977 | 0.0000 | 0.6244 | 0.2417 | 0.8417 | 0.9000 | 0.2662 | 1.0000 | 0.3222 | 0.7967 | 0.1097 | 0.2417 | 0.2903 |
| iris | mlp | lime | [View Details](#) | 0.0113 | 0.0667 | 0.0083 | 0.0000 | 0.0000 | 0.7309 | 0.1500 | 0.9178 | 1.0000 | 0.1212 | 1.0000 | 0.1509 | 0.7088 | 0.0790 | 0.1178 | 0.1210 |
| iris | mlp | integrated_gradients | [View Details](#) | 0.0391 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6767 | 0.0000 | 0.0000 | 0.0000 |
| iris | mlp | causal_shap | [View Details](#) | 0.0150 | 0.1833 | 0.0083 | 0.1144 | 0.0000 | 0.5764 | 0.5250 | 0.8837 | 1.0000 | 0.4318 | 1.0000 | 0.5300 | 0.7956 | 0.3033 | 0.4010 | 0.3967 |
| iris | mlp | shapley_flow | [View Details](#) | 0.0067 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6767 | 0.0000 | 0.0000 | 0.0000 |
| iris | mlp | shap_interactive | [View Details](#) | 0.0030 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.3000 | 1.0000 | 1.0000 | 0.3464 | 1.0000 | 0.4000 | 0.8200 | -0.0000 | 0.3000 | 0.4000 |
| iris | mlp | prototype | [View Details](#) | 0.0001 | 0.9667 | 0.9526 | 1.0000 | 0.9464 | 0.1234 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| iris | mlp | counterfactual | [View Details](#) | 0.0001 | 0.9667 | 0.0760 | 1.0000 | 0.9913 | 0.4815 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| iris | mlp | influence_functions | [View Details](#) | 0.0110 | 0.0000 | 0.0000 | 0.0000 | 0.5329 | 0.5568 | 0.7500 | 0.2467 | 1.0000 | 0.2351 | 1.0000 | 0.2557 | 0.8401 | 0.8887 | 0.2467 | 0.1113 |
| iris | mlp | bayesian_rule_list | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6767 | 0.0000 | 0.0000 | 0.0000 |
| iris | mlp | corels | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 0.0112 | 0.4858 | 0.7500 | 0.5320 | 1.0000 | 0.5139 | 1.0000 | 0.6841 | 0.7140 | 0.4891 | 0.5320 | 0.5109 |
| iris | mlp | feature_ablation | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.6244 | 0.2417 | 0.8417 | 1.0000 | 0.2662 | 1.0000 | 0.3222 | 0.7967 | 0.1097 | 0.2417 | 0.2903 |
| iris | linear_regression | lime | [View Details](#) | 0.0104 | 0.2115 | 0.3833 | 0.0000 | 0.0000 | 0.8338 | 0.7250 | 0.6442 | 1.0000 | 0.6330 | 1.0000 | 0.7907 | 0.8747 | 0.3358 | 0.6109 | 0.6309 |
| iris | linear_regression | causal_shap | [View Details](#) | 0.0100 | 0.4779 | 0.5333 | 1.0000 | 1.0000 | 0.8736 | 0.7500 | 0.8306 | 1.0000 | 0.5105 | 1.0000 | 0.5307 | 0.7879 | 0.7003 | 0.4372 | 0.2997 |
| iris | linear_regression | shap_interactive | [View Details](#) | 0.0022 | 0.5038 | 0.2000 | 1.0000 | 1.0000 | 1.0000 | 0.7500 | 0.9205 | 1.0000 | 0.5116 | 1.0000 | 0.4087 | 0.7849 | 0.7751 | 0.3612 | 0.2249 |
| iris | linear_regression | prototype | [View Details](#) | 0.0003 | 0.6667 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| iris | linear_regression | counterfactual | [View Details](#) | 0.0001 | 0.6667 | 0.3115 | 1.0000 | 0.9316 | 0.6780 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| iris | linear_regression | bayesian_rule_list | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.7000 | 0.0000 | 0.0000 | 0.0000 |
| iris | linear_regression | corels | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 0.0112 | 0.4858 | 0.7500 | 0.5320 | 1.0000 | 0.5139 | 1.0000 | 0.6841 | 0.7373 | 0.4891 | 0.5320 | 0.5109 |
| iris | linear_regression | feature_ablation | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 0.4785 | 0.8708 | 0.7500 | 0.4372 | 1.0000 | 0.4099 | 1.0000 | 0.5307 | 0.7653 | 0.7003 | 0.4372 | 0.2997 |
| iris | logistic_regression | lime | [View Details](#) | 0.0125 | 0.0500 | 0.0222 | 0.0000 | 0.0000 | 0.9254 | 0.1750 | 0.9042 | 0.8333 | 0.1386 | 1.0000 | 0.1771 | 0.6881 | 0.1062 | 0.1375 | 0.1271 |
| iris | logistic_regression | causal_shap | [View Details](#) | 0.0109 | 0.1667 | 0.0000 | 0.0678 | 0.0000 | 0.6058 | 0.4833 | 0.9068 | 1.0000 | 0.4303 | 1.0000 | 0.5245 | 0.7753 | 0.2504 | 0.4034 | 0.4163 |
| iris | logistic_regression | shap_interactive | [View Details](#) | 0.0031 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.2000 | 1.0000 | 1.0000 | 0.2000 | 1.0000 | 0.2667 | 0.8200 | 0.2000 | 0.2000 | 0.2000 |
| iris | logistic_regression | prototype | [View Details](#) | 0.0002 | 0.9333 | 0.8678 | 1.0000 | 0.9727 | 0.4862 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| iris | logistic_regression | counterfactual | [View Details](#) | 0.0002 | 0.9333 | 0.1653 | 1.0000 | 0.9678 | 0.6293 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| iris | logistic_regression | influence_functions | [View Details](#) | 0.0093 | 0.0000 | 0.0000 | 0.0000 | 0.5329 | 0.5568 | 0.7500 | 0.2467 | 1.0000 | 0.2351 | 1.0000 | 0.2557 | 0.8401 | 0.8887 | 0.2467 | 0.1113 |
| iris | logistic_regression | bayesian_rule_list | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6533 | 0.0000 | 0.0000 | 0.0000 |
| iris | logistic_regression | corels | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 0.0112 | 0.4858 | 0.7500 | 0.5320 | 1.0000 | 0.5139 | 1.0000 | 0.6841 | 0.6907 | 0.4891 | 0.5320 | 0.5109 |
| iris | logistic_regression | feature_ablation | [View Details](#) | 0.0003 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.6887 | 0.2500 | 0.8500 | 1.0000 | 0.2732 | 1.0000 | 0.3333 | 0.7733 | 0.1000 | 0.2500 | 0.3000 |
| wine_quality | decision_tree | shap | [View Details](#) | 0.0010 | 0.7200 | 0.0237 | 0.0635 | 0.0000 | 0.3582 | 0.0836 | 0.8765 | 0.4098 | 0.7253 | 1.0000 | 0.6881 | 0.6870 | 0.1622 | 0.6265 | 0.5878 |
| wine_quality | decision_tree | lime | [View Details](#) | 0.0091 | 0.1300 | 0.0200 | 0.0000 | 0.0000 | 0.2764 | 0.0436 | 0.9615 | 0.7714 | 0.3800 | 1.0000 | 0.3760 | 0.5957 | 0.0198 | 0.3415 | 0.3602 |
| wine_quality | decision_tree | causal_shap | [View Details](#) | 0.0337 | 0.1600 | 0.0050 | 0.1019 | 0.0000 | 0.3646 | 0.2982 | 0.9602 | 0.9507 | 0.4026 | 1.0000 | 0.3645 | 0.5952 | 0.2539 | 0.3398 | 0.2261 |
| wine_quality | decision_tree | shapley_flow | [View Details](#) | 0.0159 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5133 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | decision_tree | shap_interactive | [View Details](#) | 0.0069 | 0.2000 | 0.0000 | 0.1000 | 0.0000 | 0.3654 | 0.4182 | 0.7836 | 0.3000 | 0.8843 | 1.0000 | 0.8552 | 0.7200 | 0.3473 | 0.7836 | 0.6527 |
| wine_quality | decision_tree | prototype | [View Details](#) | 0.0001 | 0.6500 | 0.8927 | 1.0000 | 0.7183 | 0.8470 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | decision_tree | counterfactual | [View Details](#) | 0.0002 | 0.5900 | 0.1392 | 1.0000 | 0.7887 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | decision_tree | bayesian_rule_list | [View Details](#) | 0.0010 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4620 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | decision_tree | corels | [View Details](#) | 0.0006 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4620 | 1.0000 | 0.0000 | 0.0000 |
| wine_quality | decision_tree | feature_ablation | [View Details](#) | 0.0008 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4023 | 0.0855 | 0.8827 | 1.0000 | 0.6989 | 1.0000 | 0.6620 | 0.7060 | 0.1542 | 0.6027 | 0.5658 |
| wine_quality | random_forest | shap | [View Details](#) | 0.0431 | 0.3550 | 0.0175 | 0.0025 | 0.0000 | 0.2971 | 0.0955 | 0.9164 | 0.5797 | 0.3427 | 1.0000 | 0.3370 | 0.6280 | 0.1075 | 0.3064 | 0.2825 |
| wine_quality | random_forest | lime | [View Details](#) | 0.0233 | 0.0400 | 0.0025 | 0.0000 | 0.0000 | 0.3222 | 0.2182 | 0.9335 | 0.8696 | 0.2662 | 1.0000 | 0.2549 | 0.5698 | 0.1269 | 0.2335 | 0.1731 |
| wine_quality | random_forest | causal_shap | [View Details](#) | 1.2929 | 0.2000 | 0.0000 | 0.0050 | 1.0000 | 0.3235 | 0.4327 | 0.9864 | 0.9804 | 0.4788 | 1.0000 | 0.4420 | 0.6109 | 0.3898 | 0.4045 | 0.2302 |
| wine_quality | random_forest | shapley_flow | [View Details](#) | 0.6594 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5133 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | random_forest | shap_interactive | [View Details](#) | 0.1732 | 0.2000 | 0.0000 | 0.0000 | 1.0000 | 0.4000 | 0.0000 | 1.0000 | 0.7500 | 0.6000 | 1.0000 | 0.6000 | 0.7400 | -0.0000 | 0.5455 | 0.6000 |
| wine_quality | random_forest | prototype | [View Details](#) | 0.0032 | 0.6600 | 0.6658 | 1.0000 | 0.7201 | 0.0362 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | random_forest | counterfactual | [View Details](#) | 0.0034 | 0.7100 | 0.3748 | 1.0000 | 0.8236 | 0.2153 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | random_forest | bayesian_rule_list | [View Details](#) | 0.0039 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5110 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | random_forest | corels | [View Details](#) | 0.0038 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5110 | 1.0000 | 0.0000 | 0.0000 |
| wine_quality | random_forest | feature_ablation | [View Details](#) | 0.0369 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.3313 | 0.0709 | 0.9382 | 1.0000 | 0.3585 | 1.0000 | 0.3500 | 0.6460 | 0.0713 | 0.3182 | 0.3087 |
| wine_quality | gradient_boosting | shap | [View Details](#) | 0.0073 | 0.4050 | 0.0175 | 0.0011 | 0.0000 | 0.3164 | 0.0836 | 0.9148 | 0.6094 | 0.3891 | 1.0000 | 0.3788 | 0.6190 | 0.1082 | 0.3448 | 0.3218 |
| wine_quality | gradient_boosting | lime | [View Details](#) | 0.0110 | 0.0500 | 0.0029 | 0.0000 | 0.0000 | 0.3154 | 0.1891 | 0.9295 | 0.6897 | 0.4647 | 1.0000 | 0.4495 | 0.6319 | 0.1025 | 0.4095 | 0.3775 |
| wine_quality | gradient_boosting | causal_shap | [View Details](#) | 0.2263 | 0.1500 | 0.0050 | 0.0014 | 1.0000 | 0.3848 | 0.4036 | 0.9827 | 1.0000 | 0.4680 | 1.0000 | 0.4491 | 0.5900 | 0.3499 | 0.4125 | 0.2501 |
| wine_quality | gradient_boosting | shap_interactive | [View Details](#) | 0.0256 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.2000 | 1.0000 | 0.2000 | 0.6200 | -0.0000 | 0.1818 | 0.2000 |
| wine_quality | gradient_boosting | prototype | [View Details](#) | 0.0006 | 0.7050 | 0.7148 | 1.0000 | 0.8918 | 0.8213 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | gradient_boosting | counterfactual | [View Details](#) | 0.0007 | 0.6950 | 0.3426 | 1.0000 | 0.9750 | 0.0054 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | gradient_boosting | bayesian_rule_list | [View Details](#) | 0.0016 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4900 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | gradient_boosting | corels | [View Details](#) | 0.0010 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4900 | 1.0000 | 0.0000 | 0.0000 |
| wine_quality | gradient_boosting | feature_ablation | [View Details](#) | 0.0053 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.3749 | 0.0673 | 0.9345 | 1.0000 | 0.2923 | 1.0000 | 0.2800 | 0.6280 | 0.0935 | 0.2545 | 0.2265 |
| wine_quality | mlp | shap | [View Details](#) | 0.0013 | 0.6600 | 0.0053 | 0.0590 | 0.0000 | 0.2634 | 0.1209 | 0.8696 | 0.3694 | 0.6334 | 1.0000 | 0.6144 | 0.7110 | 0.1654 | 0.5596 | 0.5246 |
| wine_quality | mlp | lime | [View Details](#) | 0.0098 | 0.0400 | 0.0000 | 0.0000 | 0.0000 | 0.2755 | 0.1891 | 0.9313 | 0.7143 | 0.2641 | 0.5000 | 0.2512 | 0.5717 | 0.1236 | 0.2313 | 0.1764 |
| wine_quality | mlp | integrated_gradients | [View Details](#) | 0.0955 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | mlp | causal_shap | [View Details](#) | 0.0467 | 0.2600 | 0.0000 | 0.0077 | 1.0000 | 0.3211 | 0.4309 | 0.9972 | 0.9524 | 0.4454 | 1.0000 | 0.3854 | 0.6424 | 0.4505 | 0.3539 | 0.1695 |
| wine_quality | mlp | shapley_flow | [View Details](#) | 0.0214 | 0.0833 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5600 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | mlp | shap_interactive | [View Details](#) | 0.0066 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.3975 | 0.1273 | 1.0000 | 0.4000 | 0.7581 | 1.0000 | 0.7000 | 0.9400 | 0.2313 | 0.6364 | 0.5687 |
| wine_quality | mlp | prototype | [View Details](#) | 0.0002 | 0.6700 | 0.8188 | 1.0000 | 0.7931 | 0.1500 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | mlp | counterfactual | [View Details](#) | 0.0003 | 0.6800 | 0.2288 | 1.0000 | 0.7711 | 0.8838 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | mlp | influence_functions | [View Details](#) | 0.0206 | 0.0000 | 0.0000 | 0.0000 | 0.3948 | 0.2805 | 0.7273 | 0.3701 | 1.0000 | 0.3433 | 1.0000 | 0.3493 | 0.8278 | 0.8981 | 0.3701 | 0.1019 |
| wine_quality | mlp | bayesian_rule_list | [View Details](#) | 0.0011 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5040 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | mlp | corels | [View Details](#) | 0.0006 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5040 | 1.0000 | 0.0000 | 0.0000 |
| wine_quality | mlp | feature_ablation | [View Details](#) | 0.0012 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.2690 | 0.1145 | 0.8652 | 1.0000 | 0.6867 | 1.0000 | 0.6645 | 0.7540 | 0.1687 | 0.6052 | 0.5713 |
| wine_quality | linear_regression | lime | [View Details](#) | 0.0110 | 0.4046 | 0.3646 | 0.0000 | 0.0000 | 0.3379 | 0.7273 | 0.8032 | 1.0000 | 0.9450 | 0.9999 | 0.8878 | 0.6471 | 0.3855 | 0.8032 | 0.6145 |
| wine_quality | linear_regression | causal_shap | [View Details](#) | 0.0422 | 0.5872 | 0.4127 | 0.3609 | 1.0000 | 0.3542 | 0.7273 | 0.9753 | 1.0000 | 0.6914 | 1.0000 | 0.5991 | 0.5417 | 0.7755 | 0.5343 | 0.2245 |
| wine_quality | linear_regression | shap_interactive | [View Details](#) | 0.0035 | 0.5430 | 0.3636 | 0.3220 | 1.0000 | 0.3100 | 0.7273 | 1.0000 | 1.0000 | 0.7492 | 1.0000 | 0.6384 | 0.4594 | 0.7551 | 0.5565 | 0.2449 |
| wine_quality | linear_regression | prototype | [View Details](#) | 0.0003 | 0.4850 | 0.0000 | 0.6667 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | linear_regression | counterfactual | [View Details](#) | 0.0003 | 0.5250 | 0.3794 | 0.6667 | 0.6862 | 0.2995 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | linear_regression | bayesian_rule_list | [View Details](#) | 0.0015 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4900 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | linear_regression | corels | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4900 | 1.0000 | 0.0000 | 0.0000 |
| wine_quality | linear_regression | feature_ablation | [View Details](#) | 0.0008 | 0.0000 | 0.0000 | 0.0000 | 0.2425 | 0.5147 | 0.7273 | 0.5343 | 1.0000 | 0.5680 | 1.0000 | 0.5991 | 0.5312 | 0.7755 | 0.5343 | 0.2245 |
| wine_quality | logistic_regression | lime | [View Details](#) | 0.0166 | 0.0300 | 0.0000 | 0.0000 | 0.0000 | 0.2561 | 0.1455 | 0.9534 | 0.7778 | 0.1733 | 1.0000 | 0.1670 | 0.5545 | 0.0906 | 0.1534 | 0.1094 |
| wine_quality | logistic_regression | causal_shap | [View Details](#) | 0.0363 | 0.2700 | 0.0100 | 0.0000 | 1.0000 | 0.3850 | 0.5036 | 0.9867 | 1.0000 | 0.4982 | 1.0000 | 0.4364 | 0.6679 | 0.5092 | 0.4192 | 0.2108 |
| wine_quality | logistic_regression | shap_interactive | [View Details](#) | 0.0035 | 0.2000 | 0.0000 | 0.0000 | 1.0000 | 0.4015 | 0.6545 | 1.0000 | 0.2500 | 0.7007 | 1.0000 | 0.7200 | 0.8600 | 0.5488 | 0.6545 | 0.4512 |
| wine_quality | logistic_regression | prototype | [View Details](#) | 0.0002 | 0.5900 | 0.6465 | 1.0000 | 0.9308 | 0.1812 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | logistic_regression | counterfactual | [View Details](#) | 0.0003 | 0.6250 | 0.4019 | 1.0000 | 0.8218 | 0.5780 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | logistic_regression | influence_functions | [View Details](#) | 0.0240 | 0.0000 | 0.0000 | 0.0000 | 0.3948 | 0.2805 | 0.7273 | 0.3701 | 1.0000 | 0.3433 | 1.0000 | 0.3493 | 0.8278 | 0.8981 | 0.3701 | 0.1019 |
| wine_quality | logistic_regression | bayesian_rule_list | [View Details](#) | 0.0009 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 0.0000 | 0.0000 | 0.0000 |
| wine_quality | logistic_regression | corels | [View Details](#) | 0.0006 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4690 | 1.0000 | 0.0000 | 0.0000 |
| wine_quality | logistic_regression | feature_ablation | [View Details](#) | 0.0008 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4875 | 0.0582 | 0.9182 | 1.0000 | 0.4026 | 1.0000 | 0.3940 | 0.6640 | 0.0900 | 0.3582 | 0.3500 |
| diabetes | decision_tree | shap | [View Details](#) | 0.0010 | 0.7584 | 0.0375 | 0.1461 | 0.0000 | 0.3220 | 0.0315 | 0.8769 | 0.4133 | 0.7651 | 1.0000 | 0.7239 | 0.5787 | 0.1354 | 0.6521 | 0.6399 |
| diabetes | decision_tree | lime | [View Details](#) | 0.0090 | 0.2200 | 0.0467 | 0.0000 | 0.0000 | 0.4677 | 0.0700 | 0.9429 | 0.6522 | 0.5000 | 1.0000 | 0.4912 | 0.4693 | 0.0361 | 0.4429 | 0.4639 |
| diabetes | decision_tree | causal_shap | [View Details](#) | 0.0398 | 0.3900 | 0.0250 | 0.1000 | 1.0000 | 0.4044 | 0.3460 | 0.9919 | 1.0000 | 0.6214 | 1.0000 | 0.5815 | 0.4782 | 0.2860 | 0.5297 | 0.4140 |
| diabetes | decision_tree | shapley_flow | [View Details](#) | 0.0141 | 0.1333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.3967 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | decision_tree | shap_interactive | [View Details](#) | 0.0039 | 0.6000 | 0.0000 | 0.0000 | 1.0000 | 0.5131 | 0.4200 | 1.0000 | 1.0000 | 0.8850 | 1.0000 | 0.8667 | 0.5800 | 0.2863 | 0.7800 | 0.7137 |
| diabetes | decision_tree | prototype | [View Details](#) | 0.0001 | 0.4944 | 0.9553 | 1.0000 | 0.9159 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | decision_tree | counterfactual | [View Details](#) | 0.0001 | 0.4944 | 0.0500 | 1.0000 | 0.9141 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | decision_tree | bayesian_rule_list | [View Details](#) | 0.0009 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.3461 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | decision_tree | corels | [View Details](#) | 0.0006 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.3461 | 1.0000 | 0.0000 | 0.0000 |
| diabetes | decision_tree | feature_ablation | [View Details](#) | 0.0008 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.3372 | 0.0420 | 0.8620 | 1.0000 | 0.8258 | 1.0000 | 0.7791 | 0.5880 | 0.1596 | 0.7020 | 0.6804 |
| diabetes | random_forest | shap | [View Details](#) | 0.0425 | 0.4270 | 0.0135 | 0.0000 | 0.0000 | 0.3045 | 0.0787 | 0.9124 | 0.5926 | 0.4211 | 1.0000 | 0.4145 | 0.5472 | 0.0947 | 0.3730 | 0.3660 |
| diabetes | random_forest | lime | [View Details](#) | 0.0250 | 0.0700 | 0.0000 | 0.0000 | 0.0000 | 0.3633 | 0.1120 | 0.9415 | 0.8125 | 0.2306 | 0.5000 | 0.2261 | 0.4776 | 0.0910 | 0.2015 | 0.1690 |
| diabetes | random_forest | causal_shap | [View Details](#) | 1.4198 | 0.1200 | 0.0022 | 0.0000 | 0.0000 | 0.2915 | 0.3540 | 0.9634 | 0.9630 | 0.3818 | 1.0000 | 0.3302 | 0.5451 | 0.3776 | 0.3096 | 0.1624 |
| diabetes | random_forest | shapley_flow | [View Details](#) | 0.6845 | 0.0667 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.3733 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | random_forest | shap_interactive | [View Details](#) | 0.1771 | 0.1000 | 0.0000 | 0.0000 | 0.0000 | 0.4076 | 0.3800 | 0.7067 | 0.2857 | 0.7977 | 1.0000 | 0.7822 | 0.7200 | 0.4517 | 0.7067 | 0.5483 |
| diabetes | random_forest | prototype | [View Details](#) | 0.0032 | 0.5843 | 0.6618 | 1.0000 | 0.9780 | 0.4376 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | random_forest | counterfactual | [View Details](#) | 0.0033 | 0.5843 | 0.4042 | 1.0000 | 0.7579 | 0.3749 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | random_forest | bayesian_rule_list | [View Details](#) | 0.0037 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4090 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | random_forest | corels | [View Details](#) | 0.0035 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4090 | 1.0000 | 0.0000 | 0.0000 |
| diabetes | random_forest | feature_ablation | [View Details](#) | 0.0392 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.3092 | 0.0740 | 0.9140 | 1.0000 | 0.3585 | 1.0000 | 0.3489 | 0.5540 | 0.1044 | 0.3140 | 0.2956 |
| diabetes | gradient_boosting | shap | [View Details](#) | 0.0065 | 0.4831 | 0.0328 | 0.0074 | 0.0000 | 0.3109 | 0.0742 | 0.9040 | 0.4167 | 0.4842 | 1.0000 | 0.4675 | 0.5326 | 0.1131 | 0.4209 | 0.4038 |
| diabetes | gradient_boosting | lime | [View Details](#) | 0.0111 | 0.1100 | 0.0210 | 0.0000 | 0.0000 | 0.3428 | 0.2660 | 0.8928 | 0.6429 | 0.4846 | 1.0000 | 0.4640 | 0.4775 | 0.1827 | 0.4128 | 0.3373 |
| diabetes | gradient_boosting | causal_shap | [View Details](#) | 0.2039 | 0.3700 | 0.0133 | 0.0300 | 1.0000 | 0.3293 | 0.5740 | 0.9975 | 0.9000 | 0.6764 | 1.0000 | 0.5949 | 0.5706 | 0.5072 | 0.5507 | 0.3328 |
| diabetes | gradient_boosting | shap_interactive | [View Details](#) | 0.0270 | 0.2000 | 0.0000 | 0.0000 | 1.0000 | 0.3668 | 0.4000 | 1.0000 | 1.0000 | 0.8547 | 1.0000 | 0.8000 | 0.5800 | 0.4317 | 0.7200 | 0.5683 |
| diabetes | gradient_boosting | prototype | [View Details](#) | 0.0006 | 0.5393 | 0.7733 | 1.0000 | 0.8100 | 0.7077 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | gradient_boosting | counterfactual | [View Details](#) | 0.0007 | 0.5393 | 0.2912 | 1.0000 | 0.9428 | 0.6844 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | gradient_boosting | bayesian_rule_list | [View Details](#) | 0.0013 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.3775 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | gradient_boosting | corels | [View Details](#) | 0.0009 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.3775 | 1.0000 | 0.0000 | 0.0000 |
| diabetes | gradient_boosting | feature_ablation | [View Details](#) | 0.0052 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.3052 | 0.0800 | 0.9072 | 1.0000 | 0.4468 | 1.0000 | 0.4298 | 0.5360 | 0.1160 | 0.3872 | 0.3640 |
| diabetes | mlp | shap | [View Details](#) | 0.0013 | 0.6854 | 0.0094 | 0.0525 | 0.0000 | 0.2801 | 0.1820 | 0.8485 | 0.3238 | 0.6361 | 1.0000 | 0.6292 | 0.5303 | 0.1865 | 0.5676 | 0.5326 |
| diabetes | mlp | lime | [View Details](#) | 0.0091 | 0.1400 | 0.0022 | 0.0000 | 0.0000 | 0.3110 | 0.2660 | 0.8587 | 0.7083 | 0.3464 | 1.0000 | 0.3488 | 0.3840 | 0.2389 | 0.3187 | 0.2211 |
| diabetes | mlp | integrated_gradients | [View Details](#) | 0.0830 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.3267 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | mlp | causal_shap | [View Details](#) | 0.0379 | 0.3900 | 0.0069 | 0.0379 | 1.0000 | 0.3361 | 0.4380 | 0.9981 | 1.0000 | 0.4515 | 1.0000 | 0.3845 | 0.4674 | 0.4851 | 0.3606 | 0.1749 |
| diabetes | mlp | shapley_flow | [View Details](#) | 0.0182 | 0.1000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.3267 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | mlp | shap_interactive | [View Details](#) | 0.0052 | 0.2000 | 0.0000 | 0.0000 | 1.0000 | 0.5029 | 0.3800 | 1.0000 | 0.2000 | 0.6138 | 1.0000 | 0.6000 | 0.7200 | 0.6317 | 0.5400 | 0.3683 |
| diabetes | mlp | prototype | [View Details](#) | 0.0001 | 0.4494 | 0.8152 | 1.0000 | 0.9417 | 0.2186 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | mlp | counterfactual | [View Details](#) | 0.0002 | 0.4494 | 0.2412 | 1.0000 | 0.9083 | 0.8108 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | mlp | influence_functions | [View Details](#) | 0.0197 | 0.0000 | 0.0000 | 0.0000 | 0.3940 | 0.2887 | 0.7000 | 0.3343 | 1.0000 | 0.3082 | 1.0000 | 0.3050 | 0.5966 | 0.9068 | 0.3343 | 0.0932 |
| diabetes | mlp | bayesian_rule_list | [View Details](#) | 0.0009 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.3146 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | mlp | corels | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.3146 | 1.0000 | 0.0000 | 0.0000 |
| diabetes | mlp | feature_ablation | [View Details](#) | 0.0011 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.2853 | 0.1980 | 0.8553 | 1.0000 | 0.5974 | 1.0000 | 0.5925 | 0.5400 | 0.1849 | 0.5353 | 0.4951 |
| diabetes | linear_regression | lime | [View Details](#) | 0.0132 | 0.2881 | 0.7549 | 0.0000 | 0.0000 | 0.3727 | 0.5600 | 0.7504 | 1.0000 | 0.8296 | 1.0000 | 0.8280 | 0.5765 | 0.4164 | 0.7504 | 0.5836 |
| diabetes | linear_regression | causal_shap | [View Details](#) | 0.0270 | 0.5771 | 0.4460 | 0.3775 | 0.0000 | 0.4632 | 0.7000 | 0.9996 | 1.0000 | 0.6486 | 1.0000 | 0.5032 | 0.5393 | 0.8148 | 0.4832 | 0.1852 |
| diabetes | linear_regression | shap_interactive | [View Details](#) | 0.0030 | 0.6934 | 0.3600 | 0.4721 | 0.0000 | 0.4448 | 0.7000 | 0.9959 | 1.0000 | 0.6613 | 1.0000 | 0.5386 | 0.5823 | 0.7997 | 0.5018 | 0.2003 |
| diabetes | linear_regression | prototype | [View Details](#) | 0.0002 | 0.5506 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | linear_regression | counterfactual | [View Details](#) | 0.0001 | 0.5506 | 0.4054 | 1.0000 | 0.9544 | 0.4688 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | linear_regression | bayesian_rule_list | [View Details](#) | 0.0008 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4247 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | linear_regression | corels | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4247 | 1.0000 | 0.0000 | 0.0000 |
| diabetes | linear_regression | feature_ablation | [View Details](#) | 0.0006 | 0.0000 | 0.0000 | 0.0000 | 0.3513 | 0.5529 | 0.7000 | 0.4832 | 1.0000 | 0.4624 | 1.0000 | 0.5032 | 0.4901 | 0.8148 | 0.4832 | 0.1852 |
| diabetes | logistic_regression | lime | [View Details](#) | 0.0097 | 0.0600 | 0.0000 | 0.0000 | 0.0000 | 0.3436 | 0.1680 | 0.9080 | 0.9583 | 0.1973 | 1.0000 | 0.2007 | 0.4749 | 0.1503 | 0.1880 | 0.1297 |
| diabetes | logistic_regression | causal_shap | [View Details](#) | 0.0287 | 0.2600 | 0.0000 | 0.0000 | 0.0000 | 0.3533 | 0.3780 | 0.9864 | 0.9020 | 0.3801 | 1.0000 | 0.3099 | 0.6028 | 0.4279 | 0.2939 | 0.1321 |
| diabetes | logistic_regression | shap_interactive | [View Details](#) | 0.0033 | 0.1000 | 0.0000 | 0.0000 | 0.1888 | 0.4896 | 0.5000 | 0.5143 | 0.2000 | 0.5181 | 1.0000 | 0.5679 | 0.7200 | 0.6881 | 0.5143 | 0.3119 |
| diabetes | logistic_regression | prototype | [View Details](#) | 0.0001 | 0.6517 | 0.6880 | 1.0000 | 0.9551 | 0.3350 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | logistic_regression | counterfactual | [View Details](#) | 0.0001 | 0.6517 | 0.3780 | 1.0000 | 0.9761 | 0.7900 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | logistic_regression | influence_functions | [View Details](#) | 0.0144 | 0.0000 | 0.0000 | 0.0000 | 0.3940 | 0.2887 | 0.7000 | 0.3343 | 1.0000 | 0.3082 | 1.0000 | 0.3050 | 0.7016 | 0.9068 | 0.3343 | 0.0932 |
| diabetes | logistic_regression | bayesian_rule_list | [View Details](#) | 0.0007 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.4562 | 0.0000 | 0.0000 | 0.0000 |
| diabetes | logistic_regression | corels | [View Details](#) | 0.0004 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4562 | 1.0000 | 0.0000 | 0.0000 |
| diabetes | logistic_regression | feature_ablation | [View Details](#) | 0.0008 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.3171 | 0.0840 | 0.8970 | 1.0000 | 0.4294 | 1.0000 | 0.4185 | 0.5920 | 0.1242 | 0.3770 | 0.3558 |
| wine_classification | decision_tree | shap | [View Details](#) | 0.0014 | 0.3889 | 0.0278 | 0.1528 | 0.0000 | 0.3889 | 0.0000 | 0.9658 | 0.9167 | 0.4444 | 1.0000 | 0.4444 | 0.7944 | -0.0000 | 0.4103 | 0.4444 |
| wine_classification | decision_tree | lime | [View Details](#) | 0.0113 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6611 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | decision_tree | causal_shap | [View Details](#) | 0.0420 | 0.3333 | 0.0000 | 0.2222 | 0.0000 | 0.5630 | 0.0192 | 0.9363 | 1.0000 | 0.6944 | 1.0000 | 0.6621 | 0.8215 | 0.1214 | 0.6139 | 0.5731 |
| wine_classification | decision_tree | shapley_flow | [View Details](#) | 0.0165 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6533 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | decision_tree | shap_interactive | [View Details](#) | 0.0046 | 0.2000 | 0.0000 | 0.1000 | 0.0000 | 0.5509 | 0.0000 | 0.9282 | 1.0000 | 0.6000 | 1.0000 | 0.5700 | 0.7400 | 0.1037 | 0.5282 | 0.4963 |
| wine_classification | decision_tree | prototype | [View Details](#) | 0.0001 | 0.9444 | 0.9598 | 1.0000 | 0.9782 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | decision_tree | counterfactual | [View Details](#) | 0.0001 | 0.9444 | 0.0658 | 1.0000 | 0.9233 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | decision_tree | bayesian_rule_list | [View Details](#) | 0.0009 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6611 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | decision_tree | corels | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6611 | 1.0000 | 0.0000 | 0.0000 |
| wine_classification | decision_tree | feature_ablation | [View Details](#) | 0.0010 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.3889 | 0.0000 | 0.9658 | 1.0000 | 0.4444 | 1.0000 | 0.4444 | 0.7944 | -0.0000 | 0.4103 | 0.4444 |
| wine_classification | random_forest | shap | [View Details](#) | 0.0466 | 0.0972 | 0.0000 | 0.0000 | 0.0000 | 0.4296 | 0.0000 | 0.9872 | 1.0000 | 0.1389 | 1.0000 | 0.1366 | 0.7417 | 0.0075 | 0.1261 | 0.1314 |
| wine_classification | random_forest | lime | [View Details](#) | 0.0191 | 0.0278 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.7000 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | random_forest | causal_shap | [View Details](#) | 1.5310 | 0.0833 | 0.0000 | 0.1022 | 0.0000 | 0.3492 | 0.3568 | 0.9357 | 1.0000 | 0.6127 | 1.0000 | 0.5538 | 0.8363 | 0.3248 | 0.5099 | 0.3418 |
| wine_classification | random_forest | shapley_flow | [View Details](#) | 0.7512 | 0.0333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.7000 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | random_forest | shap_interactive | [View Details](#) | 0.1630 | 0.3000 | 0.0000 | 0.0000 | 0.0000 | 0.2909 | 0.0000 | 0.9000 | 1.0000 | 0.5969 | 1.0000 | 0.5389 | 0.8800 | 0.1892 | 0.5000 | 0.4108 |
| wine_classification | random_forest | prototype | [View Details](#) | 0.0052 | 1.0000 | 0.9266 | 1.0000 | 0.9811 | 0.4246 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | random_forest | counterfactual | [View Details](#) | 0.0037 | 1.0000 | 0.1585 | 1.0000 | 0.8713 | 0.7509 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | random_forest | bayesian_rule_list | [View Details](#) | 0.0040 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.7000 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | random_forest | corels | [View Details](#) | 0.0037 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.7000 | 1.0000 | 0.0000 | 0.0000 |
| wine_classification | random_forest | feature_ablation | [View Details](#) | 0.0446 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4296 | 0.0000 | 0.9872 | 1.0000 | 0.1389 | 1.0000 | 0.1366 | 0.7417 | 0.0075 | 0.1261 | 0.1314 |
| wine_classification | gradient_boosting | shap | [View Details](#) | 0.0071 | 0.1528 | 0.0000 | 0.1105 | 0.0000 | 0.4435 | 0.0000 | 0.9829 | 0.8750 | 0.2222 | 1.0000 | 0.2222 | 0.7278 | -0.0000 | 0.2051 | 0.2222 |
| wine_classification | gradient_boosting | lime | [View Details](#) | 0.0105 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.3822 | 0.0192 | 0.9808 | 0.7368 | 0.2222 | 0.5000 | 0.2196 | 0.7217 | 0.0119 | 0.2030 | 0.2103 |
| wine_classification | gradient_boosting | causal_shap | [View Details](#) | 0.2394 | 0.0694 | 0.0000 | 0.1244 | 1.0000 | 0.5969 | 0.0748 | 0.9813 | 0.9790 | 0.6389 | 1.0000 | 0.6086 | 0.7929 | 0.1298 | 0.5625 | 0.5091 |
| wine_classification | gradient_boosting | shap_interactive | [View Details](#) | 0.0257 | 0.1000 | 0.0000 | 0.0960 | 1.0000 | 0.6415 | 0.0000 | 0.9846 | 1.0000 | 0.8000 | 1.0000 | 0.7500 | 0.8000 | 0.1621 | 0.6923 | 0.6379 |
| wine_classification | gradient_boosting | prototype | [View Details](#) | 0.0006 | 0.9444 | 0.9610 | 1.0000 | 0.9438 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | gradient_boosting | counterfactual | [View Details](#) | 0.0009 | 0.9444 | 0.0670 | 1.0000 | 0.9506 | 0.5702 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | gradient_boosting | bayesian_rule_list | [View Details](#) | 0.0019 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6611 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | gradient_boosting | corels | [View Details](#) | 0.0013 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6611 | 1.0000 | 0.0000 | 0.0000 |
| wine_classification | gradient_boosting | feature_ablation | [View Details](#) | 0.0079 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.4435 | 0.0000 | 0.9829 | 1.0000 | 0.2222 | 1.0000 | 0.2222 | 0.7278 | -0.0000 | 0.2051 | 0.2222 |
| wine_classification | mlp | shap | [View Details](#) | 0.0017 | 0.1111 | 0.0000 | 0.0054 | 0.0000 | 0.3468 | 0.0321 | 0.9658 | 0.8235 | 0.1159 | 1.0000 | 0.1134 | 0.7417 | 0.0518 | 0.1047 | 0.0870 |
| wine_classification | mlp | lime | [View Details](#) | 0.0106 | 0.0278 | 0.0000 | 0.0000 | 0.0000 | 0.3288 | 0.0769 | 0.9730 | 0.7778 | 0.1600 | 1.0000 | 0.1509 | 0.7266 | 0.0544 | 0.1396 | 0.1123 |
| wine_classification | mlp | integrated_gradients | [View Details](#) | 0.1142 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.7000 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | mlp | causal_shap | [View Details](#) | 0.0497 | 0.0833 | 0.0000 | 0.1020 | 1.0000 | 0.3179 | 0.3868 | 0.9917 | 0.9655 | 0.5249 | 1.0000 | 0.4500 | 0.8385 | 0.4108 | 0.4198 | 0.2281 |
| wine_classification | mlp | shapley_flow | [View Details](#) | 0.0213 | 0.0333 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.7000 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | mlp | shap_interactive | [View Details](#) | 0.0050 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.3317 | 0.3846 | 1.0000 | 0.2500 | 0.8030 | 1.0000 | 0.7667 | 1.0000 | 0.4988 | 0.7077 | 0.5012 |
| wine_classification | mlp | prototype | [View Details](#) | 0.0001 | 1.0000 | 0.9422 | 1.0000 | 0.9834 | 0.6939 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | mlp | counterfactual | [View Details](#) | 0.0001 | 1.0000 | 0.1025 | 1.0000 | 0.9125 | 0.7783 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | mlp | influence_functions | [View Details](#) | 0.0166 | 0.0000 | 0.0000 | 0.0000 | 0.3421 | 0.2409 | 0.6923 | 0.3658 | 1.0000 | 0.3348 | 1.0000 | 0.3340 | 0.9837 | 0.9088 | 0.3658 | 0.0912 |
| wine_classification | mlp | bayesian_rule_list | [View Details](#) | 0.0009 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.7000 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | mlp | corels | [View Details](#) | 0.0007 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.7000 | 1.0000 | 0.0000 | 0.0000 |
| wine_classification | mlp | feature_ablation | [View Details](#) | 0.0025 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.3468 | 0.0321 | 0.9658 | 1.0000 | 0.1159 | 1.0000 | 0.1134 | 0.7417 | 0.0518 | 0.1047 | 0.0870 |
| wine_classification | linear_regression | lime | [View Details](#) | 0.0121 | 0.4623 | 0.3360 | 0.0000 | 0.0000 | 0.4356 | 0.6538 | 0.8280 | 1.0000 | 0.9905 | 1.0000 | 0.9249 | 0.7627 | 0.3619 | 0.8280 | 0.6381 |
| wine_classification | linear_regression | causal_shap | [View Details](#) | 0.0381 | 0.5794 | 0.4808 | 0.7820 | 1.0000 | 0.5083 | 0.6923 | 1.0000 | 1.0000 | 0.7616 | 1.0000 | 0.6420 | 0.7326 | 0.7604 | 0.5702 | 0.2396 |
| wine_classification | linear_regression | shap_interactive | [View Details](#) | 0.0035 | 0.7036 | 0.4923 | 0.8700 | 1.0000 | 0.5379 | 0.6923 | 1.0000 | 1.0000 | 0.8167 | 1.0000 | 0.6640 | 0.7219 | 0.7372 | 0.5746 | 0.2628 |
| wine_classification | linear_regression | prototype | [View Details](#) | 0.0002 | 0.5833 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | linear_regression | counterfactual | [View Details](#) | 0.0002 | 0.5833 | 0.3405 | 1.0000 | 0.9827 | 0.2556 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | linear_regression | bayesian_rule_list | [View Details](#) | 0.0009 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6028 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | linear_regression | corels | [View Details](#) | 0.0005 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6028 | 1.0000 | 0.0000 | 0.0000 |
| wine_classification | linear_regression | feature_ablation | [View Details](#) | 0.0008 | 0.0000 | 0.0000 | 0.0000 | 0.3168 | 0.5578 | 0.6923 | 0.5702 | 1.0000 | 0.6280 | 1.0000 | 0.6420 | 0.7031 | 0.7604 | 0.5702 | 0.2396 |
| wine_classification | logistic_regression | lime | [View Details](#) | 0.0086 | 0.0556 | 0.0000 | 0.0000 | 0.0000 | 0.3994 | 0.0769 | 0.9639 | 0.7895 | 0.1755 | 1.0000 | 0.1684 | 0.7069 | 0.0715 | 0.1583 | 0.1230 |
| wine_classification | logistic_regression | causal_shap | [View Details](#) | 0.0382 | 0.0972 | 0.0000 | 0.0968 | 1.0000 | 0.3149 | 0.3419 | 0.9947 | 1.0000 | 0.4883 | 1.0000 | 0.4222 | 0.8065 | 0.3659 | 0.3943 | 0.2174 |
| wine_classification | logistic_regression | shap_interactive | [View Details](#) | 0.0030 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.3588 | 0.2615 | 1.0000 | 0.3333 | 0.8591 | 1.0000 | 0.8333 | 0.8600 | 0.3733 | 0.7692 | 0.6267 |
| wine_classification | logistic_regression | prototype | [View Details](#) | 0.0002 | 0.9722 | 0.9369 | 1.0000 | 0.9594 | 0.7416 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | logistic_regression | counterfactual | [View Details](#) | 0.0003 | 0.9722 | 0.1235 | 1.0000 | 0.8771 | 0.7800 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | logistic_regression | influence_functions | [View Details](#) | 0.0096 | 0.0000 | 0.0000 | 0.0000 | 0.3421 | 0.2409 | 0.6923 | 0.3658 | 1.0000 | 0.3348 | 1.0000 | 0.3340 | 0.9487 | 0.9088 | 0.3658 | 0.0912 |
| wine_classification | logistic_regression | bayesian_rule_list | [View Details](#) | 0.0012 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6806 | 0.0000 | 0.0000 | 0.0000 |
| wine_classification | logistic_regression | corels | [View Details](#) | 0.0009 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6806 | 1.0000 | 0.0000 | 0.0000 |
| wine_classification | logistic_regression | feature_ablation | [View Details](#) | 0.0008 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.3089 | 0.0342 | 0.9658 | 1.0000 | 0.1167 | 1.0000 | 0.1134 | 0.7222 | 0.0538 | 0.1047 | 0.0851 |
| digits | decision_tree | shap | [View Details](#) | 0.0066 | 0.6845 | 0.1642 | 0.0178 | 0.0000 | 0.1505 | 0.0000 | 0.9769 | 0.2105 | 0.9300 | 1.0000 | 0.9204 | 0.8320 | 0.1032 | 0.9069 | 0.8268 |
| digits | decision_tree | lime | [View Details](#) | 0.0098 | 0.1770 | 0.0200 | 0.0000 | 0.0000 | 0.1662 | 0.0000 | 0.9927 | 0.7143 | 0.4000 | 1.0000 | 0.3994 | 0.6725 | 0.0132 | 0.3927 | 0.3868 |
| digits | decision_tree | causal_shap | [View Details](#) | 0.2125 | 0.5526 | 0.0569 | 0.0700 | 1.0000 | 0.1755 | 0.0000 | 1.0000 | 1.0000 | 0.9000 | 1.0000 | 0.8697 | 0.8300 | 0.2667 | 0.8575 | 0.6333 |
| digits | decision_tree | shapley_flow | [View Details](#) | 0.0831 | 0.1575 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5833 | 0.0000 | 0.0000 | 0.0000 |
| digits | decision_tree | shap_interactive | [View Details](#) | 0.0073 | 0.5886 | 0.2000 | 0.0000 | 1.0000 | 0.3560 | 0.0000 | 1.0000 | 1.0000 | 0.8000 | 1.0000 | 0.7935 | 0.9400 | 0.0710 | 0.7819 | 0.7290 |
| digits | decision_tree | prototype | [View Details](#) | 0.0003 | 0.8350 | 0.9091 | 1.0000 | 0.9297 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| digits | decision_tree | counterfactual | [View Details](#) | 0.0004 | 0.8400 | 0.1320 | 1.0000 | 0.9530 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| digits | decision_tree | bayesian_rule_list | [View Details](#) | 0.0039 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.5530 | 0.0000 | 0.0000 | 0.0000 |
| digits | decision_tree | corels | [View Details](#) | 0.0062 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.5530 | 1.0000 | 0.0000 | 0.0000 |
| digits | decision_tree | feature_ablation | [View Details](#) | 0.0039 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1624 | 0.0000 | 0.9755 | 1.0000 | 0.9400 | 1.0000 | 0.9291 | 0.8420 | 0.1121 | 0.9155 | 0.8279 |
| digits | random_forest | shap | [View Details](#) | 0.1970 | 0.0693 | 0.0167 | 0.0000 | 0.0000 | 0.1308 | 0.0000 | 0.9966 | 0.5455 | 0.1200 | 1.0000 | 0.1184 | 0.7010 | 0.0119 | 0.1166 | 0.1081 |
| digits | random_forest | lime | [View Details](#) | 0.0190 | 0.0533 | 0.0000 | 0.0000 | 0.0000 | 0.1648 | 0.0600 | 0.9852 | 1.0000 | 0.1376 | 1.0000 | 0.1300 | 0.6977 | 0.0636 | 0.1252 | 0.0764 |
| digits | random_forest | causal_shap | [View Details](#) | 8.1042 | 0.2587 | 0.0000 | 0.0102 | 1.0000 | 0.1462 | 0.5381 | 1.0000 | 1.0000 | 0.9387 | 1.0000 | 0.8059 | 0.9363 | 0.5785 | 0.7796 | 0.3615 |
| digits | random_forest | shapley_flow | [View Details](#) | 4.1689 | 0.0222 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.7000 | 0.0000 | 0.0000 | 0.0000 |
| digits | random_forest | shap_interactive | [View Details](#) | 0.4203 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.9969 | 1.0000 | 0.2000 | 1.0000 | 0.2000 | 0.7600 | -0.0000 | 0.1969 | 0.2000 |
| digits | random_forest | prototype | [View Details](#) | 0.0031 | 0.9650 | 0.8277 | 1.0000 | 0.9710 | 0.2780 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| digits | random_forest | counterfactual | [View Details](#) | 0.0039 | 0.9650 | 0.3689 | 1.0000 | 0.8926 | 0.9357 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| digits | random_forest | bayesian_rule_list | [View Details](#) | 0.0074 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6650 | 0.0000 | 0.0000 | 0.0000 |
| digits | random_forest | corels | [View Details](#) | 0.0102 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.6650 | 1.0000 | 0.0000 | 0.0000 |
| digits | random_forest | feature_ablation | [View Details](#) | 0.2030 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.2004 | 0.0000 | 0.9959 | 1.0000 | 0.1400 | 1.0000 | 0.1381 | 0.7280 | 0.0119 | 0.1359 | 0.1281 |
| digits | gradient_boosting | shap | [View Details](#) | 0.0448 | 0.2340 | 0.0210 | 0.0089 | 0.0000 | 0.2284 | 0.0070 | 0.9888 | 0.3636 | 0.3195 | 1.0000 | 0.3135 | 0.7540 | 0.0400 | 0.3088 | 0.2800 |
| digits | gradient_boosting | lime | [View Details](#) | 0.0140 | 0.0400 | 0.0000 | 0.0000 | 0.0000 | 0.1229 | 0.0750 | 0.9792 | 1.0000 | 0.1980 | 1.0000 | 0.1844 | 0.6872 | 0.0905 | 0.1792 | 0.1095 |
| digits | gradient_boosting | causal_shap | [View Details](#) | 1.7299 | 0.4628 | 0.0010 | 0.0873 | 1.0000 | 0.1452 | 0.3659 | 1.0000 | 1.0000 | 0.9183 | 1.0000 | 0.8217 | 0.9262 | 0.4913 | 0.8023 | 0.4287 |
| digits | gradient_boosting | shap_interactive | [View Details](#) | 0.0680 | 0.1600 | 0.0000 | 0.0000 | 1.0000 | 0.5079 | 0.0000 | 1.0000 | 1.0000 | 0.8000 | 1.0000 | 0.8000 | 0.9400 | -0.0000 | 0.7875 | 0.8000 |
| digits | gradient_boosting | prototype | [View Details](#) | 0.0009 | 0.9450 | 0.9111 | 1.0000 | 0.9314 | 0.7095 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| digits | gradient_boosting | counterfactual | [View Details](#) | 0.0011 | 0.9500 | 0.1655 | 1.0000 | 0.9850 | 0.2895 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| digits | gradient_boosting | bayesian_rule_list | [View Details](#) | 0.0049 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6580 | 0.0000 | 0.0000 | 0.0000 |
| digits | gradient_boosting | corels | [View Details](#) | 0.0081 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.6580 | 1.0000 | 0.0000 | 0.0000 |
| digits | gradient_boosting | feature_ablation | [View Details](#) | 0.0505 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.3245 | 0.0000 | 0.9935 | 1.0000 | 0.2800 | 1.0000 | 0.2778 | 0.7560 | 0.0186 | 0.2735 | 0.2614 |
| digits | mlp | shap | [View Details](#) | 0.0070 | 0.0373 | 0.0000 | 0.0000 | 0.0000 | 0.1451 | 0.0000 | 0.9970 | 0.4000 | 0.0600 | 0.5000 | 0.0579 | 0.6970 | 0.0136 | 0.0570 | 0.0464 |
| digits | mlp | lime | [View Details](#) | 0.0105 | 0.0050 | 0.0000 | 0.0000 | 0.0000 | 0.1223 | 0.0600 | 0.9862 | 1.0000 | 0.1200 | 0.5000 | 0.1087 | 0.6924 | 0.0606 | 0.1062 | 0.0594 |
| digits | mlp | integrated_gradients | [View Details](#) | 0.5421 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.7000 | 0.0000 | 0.0000 | 0.0000 |
| digits | mlp | causal_shap | [View Details](#) | 0.2778 | 0.0494 | 0.0000 | 0.0711 | 0.0000 | 0.1218 | 0.6847 | 1.0000 | 1.0000 | 0.8493 | 1.0000 | 0.6641 | 0.9652 | 0.7181 | 0.6611 | 0.2219 |
| digits | mlp | shapley_flow | [View Details](#) | 0.1235 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.7000 | 0.0000 | 0.0000 | 0.0000 |
| digits | mlp | shap_interactive | [View Details](#) | 0.0102 | 0.0000 | 0.0000 | 0.0000 | 0.1354 | 0.3770 | 0.6875 | 0.8011 | 1.0000 | 0.7449 | 1.0000 | 0.6810 | 1.0000 | 0.7483 | 0.6968 | 0.2517 |
| digits | mlp | prototype | [View Details](#) | 0.0002 | 0.9850 | 0.9231 | 1.0000 | 0.9709 | 0.8873 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| digits | mlp | counterfactual | [View Details](#) | 0.0004 | 0.9800 | 0.1478 | 1.0000 | 0.9753 | 0.6786 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| digits | mlp | influence_functions | [View Details](#) | 0.0205 | 0.0000 | 0.0000 | 0.0000 | 0.3555 | 0.5510 | 0.7500 | 0.4739 | 1.0000 | 0.4395 | 1.0000 | 0.4415 | 1.0000 | 0.9053 | 0.4739 | 0.0947 |
| digits | mlp | bayesian_rule_list | [View Details](#) | 0.0037 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6790 | 0.0000 | 0.0000 | 0.0000 |
| digits | mlp | corels | [View Details](#) | 0.0063 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.6790 | 1.0000 | 0.0000 | 0.0000 |
| digits | mlp | feature_ablation | [View Details](#) | 0.0062 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0226 | 0.0000 | 0.9991 | 1.0000 | 0.0400 | 0.5000 | 0.0397 | 0.6980 | 0.0033 | 0.0391 | 0.0367 |
| digits | linear_regression | lime | [View Details](#) | 0.0211 | 0.2141 | 0.4145 | 0.0000 | 0.0000 | 0.1860 | 0.7500 | 0.8163 | 1.0000 | 0.9907 | 1.0000 | 0.8775 | 0.1477 | 0.6355 | 0.8163 | 0.3645 |
| digits | linear_regression | causal_shap | [View Details](#) | 0.2384 | 0.3413 | 0.3577 | 0.1727 | 0.0000 | 0.1912 | 0.7500 | 1.0000 | 1.0000 | 0.8535 | 1.0000 | 0.6677 | 0.4120 | 0.8140 | 0.6518 | 0.1860 |
| digits | linear_regression | shap_interactive | [View Details](#) | 0.0071 | 0.2149 | 0.3443 | 0.2433 | 0.0000 | 0.1375 | 0.7500 | 1.0000 | 1.0000 | 0.8705 | 1.0000 | 0.6802 | 0.3000 | 0.8124 | 0.6518 | 0.1876 |
| digits | linear_regression | prototype | [View Details](#) | 0.0003 | 0.1850 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| digits | linear_regression | counterfactual | [View Details](#) | 0.0004 | 0.2150 | 0.0265 | 1.1000 | 0.9093 | 0.1720 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| digits | linear_regression | bayesian_rule_list | [View Details](#) | 0.0050 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.1330 | 0.0000 | 0.0000 | 0.0000 |
| digits | linear_regression | corels | [View Details](#) | 0.0082 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1330 | 1.0000 | 0.0000 | 0.0000 |
| digits | linear_regression | feature_ablation | [View Details](#) | 0.0046 | 0.0000 | 0.0000 | 0.0000 | 0.4326 | 0.8273 | 0.7500 | 0.6518 | 1.0000 | 0.6975 | 1.0000 | 0.6677 | 0.4120 | 0.8140 | 0.6518 | 0.1860 |
| digits | logistic_regression | lime | [View Details](#) | 0.0145 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1152 | 0.1350 | 0.9642 | 1.0000 | 0.2564 | 1.0000 | 0.2319 | 0.6882 | 0.1366 | 0.2242 | 0.1234 |
| digits | logistic_regression | causal_shap | [View Details](#) | 0.2161 | 0.1571 | 0.0005 | 0.0684 | 1.0000 | 0.1367 | 0.6641 | 1.0000 | 1.0000 | 0.8634 | 1.0000 | 0.6890 | 0.9349 | 0.6762 | 0.6752 | 0.2438 |
| digits | logistic_regression | shap_interactive | [View Details](#) | 0.0073 | 0.1886 | 0.0000 | 0.0000 | 1.0000 | 0.2486 | 0.0000 | 1.0000 | 0.1667 | 0.8000 | 1.0000 | 0.7781 | 0.8000 | 0.2094 | 0.7679 | 0.5906 |
| digits | logistic_regression | prototype | [View Details](#) | 0.0002 | 0.9650 | 0.9109 | 1.0000 | 0.9714 | 0.0118 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| digits | logistic_regression | counterfactual | [View Details](#) | 0.0004 | 0.9700 | 0.1742 | 1.0000 | 0.9885 | 0.5938 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| digits | logistic_regression | influence_functions | [View Details](#) | 0.0165 | 0.0000 | 0.0000 | 0.0000 | 0.3555 | 0.5510 | 0.7500 | 0.4739 | 1.0000 | 0.4395 | 1.0000 | 0.4415 | 0.9650 | 0.9053 | 0.4739 | 0.0947 |
| digits | logistic_regression | bayesian_rule_list | [View Details](#) | 0.0045 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 1.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.6650 | 0.0000 | 0.0000 | 0.0000 |
| digits | logistic_regression | corels | [View Details](#) | 0.0076 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.0000 | 0.0000 | 0.6650 | 1.0000 | 0.0000 | 0.0000 |
| digits | logistic_regression | feature_ablation | [View Details](#) | 0.0039 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0623 | 0.0144 | 0.9917 | 1.0000 | 0.1177 | 1.0000 | 0.1135 | 0.7080 | 0.0294 | 0.1117 | 0.0906 |
| mnist | cnn | prototype | [View Details](#) | 0.0015 | 0.9750 | 0.65870225 | 1.0000 | 0.8795 | 0.1330 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| mnist | cnn | counterfactual | [View Details](#) | 0.0039 | 0.9750 | 0.463766 | 1.0000 | 0.5276 | 0.6794 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| mnist | cnn | tcav | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| mnist | cnn | concept_bottleneck | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| mnist | cnn | occlusion | [View Details](#) | 0.0262 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| mnist | vit | tcav | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| mnist | vit | concept_bottleneck | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| mnist | vit | occlusion | [View Details](#) | 0.0940 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| mnist | resnet | prototype | [View Details](#) | 0.0072 | 0.9300 | 0.6776398 | 1.0000 | 0.8089 | 0.7729 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| mnist | resnet | counterfactual | [View Details](#) | 0.0076 | 0.9300 | 0.4899005 | 1.0000 | 0.8083 | 0.8015 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| cifar10 | cnn | prototype | [View Details](#) | 0.0038 | 0.4750 | 0.7854707 | 1.0000 | 0.5505 | 0.5929 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| cifar10 | cnn | counterfactual | [View Details](#) | 0.0467 | 0.4900 | 0.7617468 | 1.0000 | 0.9549 | 0.2132 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| cifar10 | cnn | tcav | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| cifar10 | cnn | concept_bottleneck | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| cifar10 | cnn | occlusion | [View Details](#) | 0.0914 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| cifar10 | vit | prototype | [View Details](#) | 0.0049 | 0.1450 | 0.7489129 | 0.8000 | 0.7000 | 0.1464 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| cifar10 | vit | counterfactual | [View Details](#) | 0.0484 | 0.1300 | 0.8460481 | 0.7000 | 0.8759 | 0.2046 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| cifar10 | vit | tcav | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| cifar10 | vit | concept_bottleneck | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| cifar10 | vit | occlusion | [View Details](#) | 0.2949 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| cifar10 | resnet | prototype | [View Details](#) | 0.0077 | 0.3950 | 0.74938685 | 1.0000 | 0.8725 | 0.9131 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| cifar10 | resnet | counterfactual | [View Details](#) | 0.0518 | 0.3950 | 0.66736954 | 1.0000 | 0.9192 | 0.0247 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| fashion_mnist | cnn | prototype | [View Details](#) | 0.0014 | 0.8700 | 0.8511568 | 1.0000 | 0.5060 | 0.9287 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| fashion_mnist | cnn | counterfactual | [View Details](#) | 0.0058 | 0.8750 | 0.3133816 | 1.0000 | 0.8910 | 0.2488 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| fashion_mnist | cnn | tcav | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| fashion_mnist | cnn | concept_bottleneck | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| fashion_mnist | cnn | occlusion | [View Details](#) | 0.0190 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| fashion_mnist | vit | tcav | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| fashion_mnist | vit | concept_bottleneck | [View Details](#) | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
| fashion_mnist | vit | occlusion | [View Details](#) | 0.0857 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| fashion_mnist | resnet | prototype | [View Details](#) | 0.0058 | 0.7750 | 0.8298211 | 1.0000 | 0.8729 | 0.7109 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| fashion_mnist | resnet | counterfactual | [View Details](#) | 0.0112 | 0.7700 | 0.3005286 | 1.0000 | 0.9114 | 0.5250 | 0.0000 | 0.0000 | 1.0000 | 0.0000 | 0.5000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |
| imdb | bert | lime | [View Details](#) | 0.0570 | 0.8400 | 0.0000 | 0.0000 | 0.0895 | 0.1339 | 0.7400 | 0.4488 | 1.0000 | 0.4613 | 0.0000 | 0.4507 | 0.5941 | 0.9048 | 0.4488 | 0.0952 |
| imdb | bert | text_occlusion | [View Details](#) | 0.0389 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0552 | 0.0046 | 0.8016 | 1.0000 | 0.0890 | 0.0000 | 0.0824 | 0.6360 | 0.2137 | 0.0816 | 0.0663 |
| imdb | bert | attention_visualization | [View Details](#) | 0.0803 | 0.0000 | 0.0000 | 0.0000 | 0.7141 | 0.0947 | 0.7005 | 0.0381 | 1.0000 | 0.0360 | 0.0000 | 0.0055 | 0.5880 | 0.9994 | 0.0381 | 0.0006 |
| imdb | lstm | lime | [View Details](#) | 0.0615 | 0.8000 | 0.0000 | 0.0000 | 0.0000 | 0.1176 | 0.7400 | 0.4750 | 1.0000 | 0.5223 | 0.0000 | 0.5016 | 0.5679 | 0.8890 | 0.4750 | 0.1110 |
| imdb | lstm | text_occlusion | [View Details](#) | 0.0350 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0627 | 0.0062 | 0.7822 | 1.0000 | 0.1734 | 0.0000 | 0.1638 | 0.6500 | 0.2449 | 0.1622 | 0.1351 |
| imdb | lstm | attention_visualization | [View Details](#) | 0.0864 | 0.0000 | 0.0000 | 0.0000 | 0.7135 | 0.0924 | 0.6971 | 0.0385 | 1.0000 | 0.0371 | 0.0000 | 0.0059 | 0.5600 | 0.9994 | 0.0385 | 0.0006 |
| imdb | roberta | lime | [View Details](#) | 17.0277 | 0.8800 | 0.0000 | 0.0000 | 0.1119 | 0.1283 | 0.7400 | 0.4386 | 1.0000 | 0.4476 | 0.0000 | 0.4412 | 0.6213 | 0.9113 | 0.4386 | 0.0887 |
| imdb | roberta | text_occlusion | [View Details](#) | 15.0937 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0465 | 0.0002 | 0.9161 | 1.0000 | 0.1010 | 0.0000 | 0.0971 | 0.6520 | 0.1059 | 0.0961 | 0.0741 |
| imdb | roberta | attention_visualization | [View Details](#) | 48.1745 | 0.0000 | 0.0000 | 0.0000 | 0.7142 | 0.0948 | 0.7047 | 0.0381 | 1.0000 | 0.0358 | 0.0000 | 0.0054 | 0.6160 | 0.9994 | 0.0381 | 0.0006 |
| imdb | naive_bayes_text | lime | [View Details](#) | 0.1148 | 0.8200 | 0.0000 | 0.0000 | 0.0968 | 0.1248 | 0.7400 | 0.4531 | 1.0000 | 0.4590 | 0.0000 | 0.4550 | 0.5795 | 0.9059 | 0.4531 | 0.0941 |
| imdb | naive_bayes_text | text_occlusion | [View Details](#) | 0.0598 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0715 | 0.0016 | 0.8699 | 1.0000 | 0.1841 | 0.0000 | 0.1717 | 0.6400 | 0.1769 | 0.1699 | 0.1231 |
| imdb | naive_bayes_text | attention_visualization | [View Details](#) | 0.1508 | 0.0000 | 0.0000 | 0.0000 | 0.7124 | 0.0943 | 0.6996 | 0.0399 | 1.0000 | 0.0379 | 0.0000 | 0.0063 | 0.5740 | 0.9993 | 0.0399 | 0.0007 |
| imdb | svm_text | lime | [View Details](#) | 0.2135 | 0.7600 | 0.0000 | 0.0000 | 0.1030 | 0.1328 | 0.7400 | 0.4555 | 1.0000 | 0.4600 | 0.0000 | 0.4530 | 0.5376 | 0.9044 | 0.4555 | 0.0956 |
| imdb | svm_text | text_occlusion | [View Details](#) | 0.1387 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0682 | 0.0040 | 0.8014 | 1.0000 | 0.0694 | 0.0000 | 0.0620 | 0.5800 | 0.2169 | 0.0614 | 0.0431 |
| imdb | svm_text | attention_visualization | [View Details](#) | 0.3299 | 0.0000 | 0.0000 | 0.0000 | 0.7133 | 0.0952 | 0.7037 | 0.0387 | 1.0000 | 0.0363 | 0.0000 | 0.0059 | 0.5320 | 0.9994 | 0.0387 | 0.0006 |
| imdb | xgboost_text | lime | [View Details](#) | 0.1981 | 0.7400 | 0.0000 | 0.0000 | 0.0463 | 0.5903 | 0.7400 | 0.4067 | 1.0000 | 0.4036 | 0.0000 | 0.3705 | 0.5396 | 0.8773 | 0.4067 | 0.1227 |
| imdb | xgboost_text | text_occlusion | [View Details](#) | 0.1066 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0297 | 0.0008 | 0.8376 | 1.0000 | 0.2234 | 0.0000 | 0.2198 | 0.6020 | 0.1719 | 0.2176 | 0.2081 |
| imdb | xgboost_text | attention_visualization | [View Details](#) | 0.2499 | 0.0000 | 0.0000 | 0.0000 | 0.7144 | 0.0951 | 0.7007 | 0.0376 | 1.0000 | 0.0359 | 0.0000 | 0.0054 | 0.5180 | 0.9994 | 0.0376 | 0.0006 |
| 20newsgroups | bert | lime | [View Details](#) | 0.1026 | 0.6400 | 0.0000 | 0.0000 | 0.0000 | 0.1277 | 0.6660 | 0.5701 | 1.0000 | 0.6203 | 0.0000 | 0.5891 | 0.4629 | 0.8034 | 0.5501 | 0.1766 |
| 20newsgroups | bert | text_occlusion | [View Details](#) | 0.0376 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0767 | 0.0041 | 0.8870 | 1.0000 | 0.2305 | 0.0000 | 0.2200 | 0.5429 | 0.1359 | 0.2136 | 0.1906 |
| 20newsgroups | bert | attention_visualization | [View Details](#) | 0.0988 | 0.0000 | 0.0000 | 0.0000 | 0.0621 | 0.1946 | 0.7042 | 0.0483 | 1.0000 | 0.0498 | 0.0000 | 0.0138 | 0.4584 | 0.9981 | 0.0483 | 0.0019 |
| 20newsgroups | lstm | lime | [View Details](#) | 0.0949 | 0.6800 | 0.0000 | 0.0000 | 0.0000 | 0.1427 | 0.6660 | 0.5511 | 1.0000 | 0.5818 | 0.0000 | 0.5561 | 0.4918 | 0.8080 | 0.5311 | 0.1720 |
| 20newsgroups | lstm | text_occlusion | [View Details](#) | 0.0409 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0519 | 0.0000 | 0.9093 | 1.0000 | 0.1660 | 0.0000 | 0.1580 | 0.5265 | 0.1193 | 0.1542 | 0.1255 |
| 20newsgroups | lstm | attention_visualization | [View Details](#) | 0.1040 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1942 | 0.7060 | 0.0472 | 1.0000 | 0.0477 | 0.0000 | 0.0126 | 0.4731 | 0.9984 | 0.0472 | 0.0016 |
| 20newsgroups | roberta | lime | [View Details](#) | 52.9093 | 0.7800 | 0.0000 | 0.0000 | 0.0000 | 0.2099 | 0.6660 | 0.4981 | 1.0000 | 0.4834 | 0.0000 | 0.4583 | 0.5577 | 0.8395 | 0.4781 | 0.1405 |
| 20newsgroups | roberta | text_occlusion | [View Details](#) | 10.3211 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1525 | 0.0142 | 0.9880 | 1.0000 | 0.0970 | 0.0000 | 0.0958 | 0.5878 | 0.0173 | 0.0900 | 0.0847 |
| 20newsgroups | roberta | attention_visualization | [View Details](#) | 33.8771 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1937 | 0.7056 | 0.0501 | 1.0000 | 0.0495 | 0.0000 | 0.0144 | 0.5592 | 0.9980 | 0.0501 | 0.0020 |
| 20newsgroups | naive_bayes_text | lime | [View Details](#) | 0.1124 | 0.6800 | 0.0000 | 0.0000 | 0.0000 | 0.1557 | 0.6660 | 0.5130 | 1.0000 | 0.5038 | 0.0000 | 0.4821 | 0.4875 | 0.8337 | 0.4930 | 0.1463 |
| 20newsgroups | naive_bayes_text | text_occlusion | [View Details](#) | 0.0508 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0915 | 0.0051 | 0.9577 | 1.0000 | 0.0684 | 0.0000 | 0.0613 | 0.5020 | 0.0598 | 0.0597 | 0.0423 |
| 20newsgroups | naive_bayes_text | attention_visualization | [View Details](#) | 0.1222 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1922 | 0.7040 | 0.0457 | 1.0000 | 0.0439 | 0.0000 | 0.0099 | 0.4727 | 0.9987 | 0.0457 | 0.0013 |
| 20newsgroups | svm_text | lime | [View Details](#) | 0.1893 | 0.8000 | 0.0000 | 0.0000 | 0.0000 | 0.1462 | 0.6660 | 0.5252 | 1.0000 | 0.5315 | 0.0000 | 0.5050 | 0.5728 | 0.8266 | 0.5052 | 0.1534 |
| 20newsgroups | svm_text | text_occlusion | [View Details](#) | 0.0810 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0430 | 0.0000 | 0.9863 | 1.0000 | 0.2449 | 0.0000 | 0.2374 | 0.6306 | 0.0398 | 0.2312 | 0.2051 |
| 20newsgroups | svm_text | attention_visualization | [View Details](#) | 0.2035 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1939 | 0.7047 | 0.0499 | 1.0000 | 0.0512 | 0.0000 | 0.0143 | 0.5585 | 0.9982 | 0.0499 | 0.0018 |
| 20newsgroups | xgboost_text | lime | [View Details](#) | 0.2105 | 0.7000 | 0.0000 | 0.0000 | 0.0000 | 0.1799 | 0.6660 | 0.6096 | 1.0000 | 0.6839 | 0.0000 | 0.6471 | 0.5492 | 0.6864 | 0.5896 | 0.2936 |
| 20newsgroups | xgboost_text | text_occlusion | [View Details](#) | 0.0772 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0277 | 0.0010 | 0.8447 | 1.0000 | 0.2904 | 0.0000 | 0.2818 | 0.6082 | 0.1644 | 0.2732 | 0.2642 |
| 20newsgroups | xgboost_text | attention_visualization | [View Details](#) | 0.1991 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.1940 | 0.7032 | 0.0475 | 1.0000 | 0.0501 | 0.0000 | 0.0138 | 0.4866 | 0.9982 | 0.0475 | 0.0018 |
| ag_news | bert | lime | [View Details](#) | 0.0879 | 0.8400 | 0.0000 | 0.0000 | 0.0000 | 0.4124 | 0.7400 | 0.5901 | 1.0000 | 0.6340 | 0.0000 | 0.5954 | 0.5992 | 0.8207 | 0.5901 | 0.1793 |
| ag_news | bert | text_occlusion | [View Details](#) | 0.0215 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0627 | 0.0000 | 0.9906 | 1.0000 | 0.1600 | 0.0000 | 0.1551 | 0.6360 | 0.0260 | 0.1506 | 0.1340 |
| ag_news | bert | attention_visualization | [View Details](#) | 0.0653 | 0.0000 | 0.0000 | 0.0000 | 0.1673 | 0.5230 | 0.7050 | 0.0483 | 1.0000 | 0.0458 | 0.0000 | 0.0098 | 0.5891 | 0.9987 | 0.0483 | 0.0013 |
| ag_news | lstm | lime | [View Details](#) | 0.0924 | 0.8200 | 0.0000 | 0.0000 | 0.0000 | 0.4161 | 0.7400 | 0.5920 | 1.0000 | 0.6219 | 0.0000 | 0.5928 | 0.5844 | 0.8236 | 0.5920 | 0.1764 |
| ag_news | lstm | text_occlusion | [View Details](#) | 0.0189 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0998 | 0.0000 | 0.9844 | 1.0000 | 0.1800 | 0.0000 | 0.1688 | 0.6280 | 0.0491 | 0.1644 | 0.1309 |
| ag_news | lstm | attention_visualization | [View Details](#) | 0.0758 | 0.0000 | 0.0000 | 0.0000 | 0.1524 | 0.5258 | 0.7081 | 0.0504 | 1.0000 | 0.0477 | 0.0000 | 0.0111 | 0.5748 | 0.9985 | 0.0504 | 0.0015 |
| ag_news | roberta | lime | [View Details](#) | 15.3733 | 0.8800 | 0.0000 | 0.0000 | 0.2692 | 0.5598 | 0.7400 | 0.5296 | 1.0000 | 0.4995 | 0.0000 | 0.4952 | 0.6225 | 0.8588 | 0.5296 | 0.1412 |
| ag_news | roberta | text_occlusion | [View Details](#) | 4.1286 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0182 | 0.0000 | 0.9989 | 1.0000 | 0.0400 | 0.0000 | 0.0400 | 0.6280 | -0.0000 | 0.0389 | 0.0400 |
| ag_news | roberta | attention_visualization | [View Details](#) | 13.8400 | 0.0000 | 0.0000 | 0.0000 | 0.1592 | 0.5235 | 0.7037 | 0.0452 | 1.0000 | 0.0417 | 0.0000 | 0.0077 | 0.6166 | 0.9990 | 0.0452 | 0.0010 |
| ag_news | naive_bayes_text | lime | [View Details](#) | 0.1088 | 0.8600 | 0.0000 | 0.0000 | 0.0692 | 0.4811 | 0.7400 | 0.5717 | 1.0000 | 0.5680 | 0.0000 | 0.5538 | 0.6105 | 0.8369 | 0.5717 | 0.1631 |
| ag_news | naive_bayes_text | text_occlusion | [View Details](#) | 0.0185 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0342 | 0.0000 | 0.9963 | 1.0000 | 0.0600 | 0.0000 | 0.0581 | 0.6200 | 0.0086 | 0.0563 | 0.0514 |
| ag_news | naive_bayes_text | attention_visualization | [View Details](#) | 0.0738 | 0.0000 | 0.0000 | 0.0000 | 0.1549 | 0.5226 | 0.7041 | 0.0459 | 1.0000 | 0.0425 | 0.0000 | 0.0079 | 0.6027 | 0.9990 | 0.0459 | 0.0010 |
| ag_news | svm_text | lime | [View Details](#) | 0.1527 | 0.8600 | 0.0000 | 0.0000 | 0.0000 | 0.4028 | 0.7400 | 0.5763 | 1.0000 | 0.5873 | 0.0000 | 0.5669 | 0.6111 | 0.8331 | 0.5763 | 0.1669 |
| ag_news | svm_text | text_occlusion | [View Details](#) | 0.0361 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0476 | 0.0000 | 0.9924 | 1.0000 | 0.1600 | 0.0000 | 0.1572 | 0.6500 | 0.0177 | 0.1524 | 0.1423 |
| ag_news | svm_text | attention_visualization | [View Details](#) | 0.1250 | 0.0000 | 0.0000 | 0.0000 | 0.1501 | 0.5231 | 0.7048 | 0.0494 | 1.0000 | 0.0486 | 0.0000 | 0.0121 | 0.6031 | 0.9985 | 0.0494 | 0.0015 |
| ag_news | xgboost_text | lime | [View Details](#) | 0.2081 | 0.7000 | 0.0000 | 0.0000 | 0.0000 | 0.4201 | 0.7400 | 0.6372 | 1.0000 | 0.7133 | 0.0000 | 0.6732 | 0.5229 | 0.7494 | 0.6372 | 0.2506 |
| ag_news | xgboost_text | text_occlusion | [View Details](#) | 0.0411 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0654 | 0.0141 | 0.9711 | 1.0000 | 0.3954 | 0.0000 | 0.3826 | 0.6100 | 0.0633 | 0.3711 | 0.3367 |
| ag_news | xgboost_text | attention_visualization | [View Details](#) | 0.1494 | 0.0000 | 0.0000 | 0.0000 | 0.2002 | 0.5216 | 0.7037 | 0.0555 | 1.0000 | 0.0568 | 0.0000 | 0.0158 | 0.4917 | 0.9980 | 0.0555 | 0.0020 |

## Detailed Explanation Analysis

Summary of detailed explanations generated for the entire test set.

| Dataset | Model | Method | Test Instances | Valid Explanations | Accuracy | Avg Feature Importance | Detailed Files |
|---------|-------|--------|----------------|-------------------|----------|----------------------|----------------|
| adult_income | decision_tree | shap | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\shap_detailed_explanations.json) |
| adult_income | decision_tree | lime | 6033 | 6033 | 0.833 | 0.0360 | [JSON](detailed_explanations\adult_income\decision_tree\lime_detailed_explanations.json) |
| adult_income | decision_tree | causal_shap | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\causal_shap_detailed_explanations.json) |
| adult_income | decision_tree | shapley_flow | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\shapley_flow_detailed_explanations.json) |
| adult_income | decision_tree | shap_interactive | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\shap_interactive_detailed_explanations.json) |
| adult_income | decision_tree | prototype | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\prototype_detailed_explanations.json) |
| adult_income | decision_tree | counterfactual | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\counterfactual_detailed_explanations.json) |
| adult_income | decision_tree | bayesian_rule_list | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\bayesian_rule_list_detailed_explanations.json) |
| adult_income | decision_tree | corels | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\corels_detailed_explanations.json) |
| adult_income | decision_tree | feature_ablation | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\decision_tree\feature_ablation_detailed_explanations.json) |
| adult_income | random_forest | shap | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\shap_detailed_explanations.json) |
| adult_income | random_forest | lime | 6033 | 6033 | 0.833 | 0.0305 | [JSON](detailed_explanations\adult_income\random_forest\lime_detailed_explanations.json) |
| adult_income | random_forest | causal_shap | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\causal_shap_detailed_explanations.json) |
| adult_income | random_forest | shapley_flow | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\shapley_flow_detailed_explanations.json) |
| adult_income | random_forest | shap_interactive | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\shap_interactive_detailed_explanations.json) |
| adult_income | random_forest | prototype | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\prototype_detailed_explanations.json) |
| adult_income | random_forest | counterfactual | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\counterfactual_detailed_explanations.json) |
| adult_income | random_forest | bayesian_rule_list | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\bayesian_rule_list_detailed_explanations.json) |
| adult_income | random_forest | corels | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\corels_detailed_explanations.json) |
| adult_income | random_forest | feature_ablation | 6033 | 6033 | 0.833 | 0.0000 | [JSON](detailed_explanations\adult_income\random_forest\feature_ablation_detailed_explanations.json) |
| adult_income | gradient_boosting | shap | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\shap_detailed_explanations.json) |
| adult_income | gradient_boosting | lime | 6033 | 6033 | 0.836 | 0.0269 | [JSON](detailed_explanations\adult_income\gradient_boosting\lime_detailed_explanations.json) |
| adult_income | gradient_boosting | causal_shap | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\causal_shap_detailed_explanations.json) |
| adult_income | gradient_boosting | shap_interactive | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\shap_interactive_detailed_explanations.json) |
| adult_income | gradient_boosting | prototype | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\prototype_detailed_explanations.json) |
| adult_income | gradient_boosting | counterfactual | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\counterfactual_detailed_explanations.json) |
| adult_income | gradient_boosting | bayesian_rule_list | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\bayesian_rule_list_detailed_explanations.json) |
| adult_income | gradient_boosting | corels | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\corels_detailed_explanations.json) |
| adult_income | gradient_boosting | feature_ablation | 6033 | 6033 | 0.836 | 0.0000 | [JSON](detailed_explanations\adult_income\gradient_boosting\feature_ablation_detailed_explanations.json) |
| adult_income | mlp | shap | 6033 | 6033 | 0.824 | 0.0000 | [JSON](detailed_explanations\adult_income\mlp\shap_detailed_explanations.json) |
| adult_income | mlp | lime | 6033 | 6033 | 0.824 | 0.0211 | [JSON](detailed_explanations\adult_income\mlp\lime_detailed_explanations.json) |
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
| adult_income | linear_regression | lime | 6033 | 6033 | 0.791 | 0.0157 | [JSON](detailed_explanations\adult_income\linear_regression\lime_detailed_explanations.json) |
| adult_income | linear_regression | causal_shap | 6033 | 6033 | 0.791 | 0.0000 | [JSON](detailed_explanations\adult_income\linear_regression\causal_shap_detailed_explanations.json) |
| adult_income | linear_regression | shap_interactive | 6033 | 6033 | 0.791 | 0.0000 | [JSON](detailed_explanations\adult_income\linear_regression\shap_interactive_detailed_explanations.json) |
| adult_income | linear_regression | prototype | 6033 | 6033 | 0.791 | 0.0000 | [JSON](detailed_explanations\adult_income\linear_regression\prototype_detailed_explanations.json) |
| adult_income | linear_regression | counterfactual | 6033 | 6033 | 0.791 | 0.0000 | [JSON](detailed_explanations\adult_income\linear_regression\counterfactual_detailed_explanations.json) |
| adult_income | linear_regression | bayesian_rule_list | 6033 | 6033 | 0.791 | 0.0000 | [JSON](detailed_explanations\adult_income\linear_regression\bayesian_rule_list_detailed_explanations.json) |
| adult_income | linear_regression | corels | 6033 | 6033 | 0.791 | 0.0000 | [JSON](detailed_explanations\adult_income\linear_regression\corels_detailed_explanations.json) |
| adult_income | linear_regression | feature_ablation | 6033 | 6033 | 0.791 | 0.0000 | [JSON](detailed_explanations\adult_income\linear_regression\feature_ablation_detailed_explanations.json) |
| adult_income | logistic_regression | lime | 6033 | 6033 | 0.809 | 0.0232 | [JSON](detailed_explanations\adult_income\logistic_regression\lime_detailed_explanations.json) |
| adult_income | logistic_regression | causal_shap | 6033 | 6033 | 0.809 | 0.0000 | [JSON](detailed_explanations\adult_income\logistic_regression\causal_shap_detailed_explanations.json) |
| adult_income | logistic_regression | shap_interactive | 6033 | 6033 | 0.809 | 0.0000 | [JSON](detailed_explanations\adult_income\logistic_regression\shap_interactive_detailed_explanations.json) |
| adult_income | logistic_regression | prototype | 6033 | 6033 | 0.809 | 0.0000 | [JSON](detailed_explanations\adult_income\logistic_regression\prototype_detailed_explanations.json) |
| adult_income | logistic_regression | counterfactual | 6033 | 6033 | 0.809 | 0.0000 | [JSON](detailed_explanations\adult_income\logistic_regression\counterfactual_detailed_explanations.json) |
| adult_income | logistic_regression | influence_functions | 6033 | 6033 | 0.809 | 0.0000 | [JSON](detailed_explanations\adult_income\logistic_regression\influence_functions_detailed_explanations.json) |
| adult_income | logistic_regression | bayesian_rule_list | 6033 | 6033 | 0.809 | 0.0000 | [JSON](detailed_explanations\adult_income\logistic_regression\bayesian_rule_list_detailed_explanations.json) |
| adult_income | logistic_regression | corels | 6033 | 6033 | 0.809 | 0.0000 | [JSON](detailed_explanations\adult_income\logistic_regression\corels_detailed_explanations.json) |
| adult_income | logistic_regression | feature_ablation | 6033 | 6033 | 0.809 | 0.0000 | [JSON](detailed_explanations\adult_income\logistic_regression\feature_ablation_detailed_explanations.json) |
| compas | decision_tree | shap | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\shap_detailed_explanations.json) |
| compas | decision_tree | lime | 1443 | 1443 | 0.674 | 0.2675 | [JSON](detailed_explanations\compas\decision_tree\lime_detailed_explanations.json) |
| compas | decision_tree | causal_shap | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\causal_shap_detailed_explanations.json) |
| compas | decision_tree | shapley_flow | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\shapley_flow_detailed_explanations.json) |
| compas | decision_tree | shap_interactive | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\shap_interactive_detailed_explanations.json) |
| compas | decision_tree | prototype | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\prototype_detailed_explanations.json) |
| compas | decision_tree | counterfactual | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\counterfactual_detailed_explanations.json) |
| compas | decision_tree | bayesian_rule_list | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\bayesian_rule_list_detailed_explanations.json) |
| compas | decision_tree | corels | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\corels_detailed_explanations.json) |
| compas | decision_tree | feature_ablation | 1443 | 1443 | 0.674 | 0.0000 | [JSON](detailed_explanations\compas\decision_tree\feature_ablation_detailed_explanations.json) |
| compas | random_forest | shap | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\shap_detailed_explanations.json) |
| compas | random_forest | lime | 1443 | 1443 | 0.683 | 0.0702 | [JSON](detailed_explanations\compas\random_forest\lime_detailed_explanations.json) |
| compas | random_forest | causal_shap | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\causal_shap_detailed_explanations.json) |
| compas | random_forest | shapley_flow | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\shapley_flow_detailed_explanations.json) |
| compas | random_forest | shap_interactive | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\shap_interactive_detailed_explanations.json) |
| compas | random_forest | prototype | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\prototype_detailed_explanations.json) |
| compas | random_forest | counterfactual | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\counterfactual_detailed_explanations.json) |
| compas | random_forest | bayesian_rule_list | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\bayesian_rule_list_detailed_explanations.json) |
| compas | random_forest | corels | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\corels_detailed_explanations.json) |
| compas | random_forest | feature_ablation | 1443 | 1443 | 0.683 | 0.0000 | [JSON](detailed_explanations\compas\random_forest\feature_ablation_detailed_explanations.json) |
| compas | gradient_boosting | shap | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\shap_detailed_explanations.json) |
| compas | gradient_boosting | lime | 1443 | 1443 | 0.695 | 0.2266 | [JSON](detailed_explanations\compas\gradient_boosting\lime_detailed_explanations.json) |
| compas | gradient_boosting | causal_shap | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\causal_shap_detailed_explanations.json) |
| compas | gradient_boosting | shap_interactive | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\shap_interactive_detailed_explanations.json) |
| compas | gradient_boosting | prototype | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\prototype_detailed_explanations.json) |
| compas | gradient_boosting | counterfactual | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\counterfactual_detailed_explanations.json) |
| compas | gradient_boosting | bayesian_rule_list | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\bayesian_rule_list_detailed_explanations.json) |
| compas | gradient_boosting | corels | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\corels_detailed_explanations.json) |
| compas | gradient_boosting | feature_ablation | 1443 | 1443 | 0.695 | 0.0000 | [JSON](detailed_explanations\compas\gradient_boosting\feature_ablation_detailed_explanations.json) |
| compas | mlp | shap | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\mlp\shap_detailed_explanations.json) |
| compas | mlp | lime | 1443 | 1443 | 0.685 | 0.1130 | [JSON](detailed_explanations\compas\mlp\lime_detailed_explanations.json) |
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
| compas | linear_regression | lime | 1443 | 1443 | 0.687 | 0.0363 | [JSON](detailed_explanations\compas\linear_regression\lime_detailed_explanations.json) |
| compas | linear_regression | causal_shap | 1443 | 1443 | 0.687 | 0.0000 | [JSON](detailed_explanations\compas\linear_regression\causal_shap_detailed_explanations.json) |
| compas | linear_regression | shap_interactive | 1443 | 1443 | 0.687 | 0.0000 | [JSON](detailed_explanations\compas\linear_regression\shap_interactive_detailed_explanations.json) |
| compas | linear_regression | prototype | 1443 | 1443 | 0.687 | 0.0000 | [JSON](detailed_explanations\compas\linear_regression\prototype_detailed_explanations.json) |
| compas | linear_regression | counterfactual | 1443 | 1443 | 0.687 | 0.0000 | [JSON](detailed_explanations\compas\linear_regression\counterfactual_detailed_explanations.json) |
| compas | linear_regression | bayesian_rule_list | 1443 | 1443 | 0.687 | 0.0000 | [JSON](detailed_explanations\compas\linear_regression\bayesian_rule_list_detailed_explanations.json) |
| compas | linear_regression | corels | 1443 | 1443 | 0.687 | 0.0000 | [JSON](detailed_explanations\compas\linear_regression\corels_detailed_explanations.json) |
| compas | linear_regression | feature_ablation | 1443 | 1443 | 0.687 | 0.0000 | [JSON](detailed_explanations\compas\linear_regression\feature_ablation_detailed_explanations.json) |
| compas | logistic_regression | lime | 1443 | 1443 | 0.685 | 0.0351 | [JSON](detailed_explanations\compas\logistic_regression\lime_detailed_explanations.json) |
| compas | logistic_regression | causal_shap | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\logistic_regression\causal_shap_detailed_explanations.json) |
| compas | logistic_regression | shap_interactive | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\logistic_regression\shap_interactive_detailed_explanations.json) |
| compas | logistic_regression | prototype | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\logistic_regression\prototype_detailed_explanations.json) |
| compas | logistic_regression | counterfactual | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\logistic_regression\counterfactual_detailed_explanations.json) |
| compas | logistic_regression | influence_functions | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\logistic_regression\influence_functions_detailed_explanations.json) |
| compas | logistic_regression | bayesian_rule_list | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\logistic_regression\bayesian_rule_list_detailed_explanations.json) |
| compas | logistic_regression | corels | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\logistic_regression\corels_detailed_explanations.json) |
| compas | logistic_regression | feature_ablation | 1443 | 1443 | 0.685 | 0.0000 | [JSON](detailed_explanations\compas\logistic_regression\feature_ablation_detailed_explanations.json) |
| breast_cancer | decision_tree | shap | 114 | 114 | 0.912 | 0.0000 | [JSON](detailed_explanations\breast_cancer\decision_tree\shap_detailed_explanations.json) |
| breast_cancer | decision_tree | lime | 114 | 114 | 0.912 | 0.0067 | [JSON](detailed_explanations\breast_cancer\decision_tree\lime_detailed_explanations.json) |
| breast_cancer | decision_tree | causal_shap | 114 | 114 | 0.912 | 0.0000 | [JSON](detailed_explanations\breast_cancer\decision_tree\causal_shap_detailed_explanations.json) |
| breast_cancer | decision_tree | shapley_flow | 114 | 114 | 0.912 | 0.0000 | [JSON](detailed_explanations\breast_cancer\decision_tree\shapley_flow_detailed_explanations.json) |
| breast_cancer | decision_tree | shap_interactive | 114 | 114 | 0.912 | 0.0000 | [JSON](detailed_explanations\breast_cancer\decision_tree\shap_interactive_detailed_explanations.json) |
| breast_cancer | decision_tree | prototype | 114 | 114 | 0.912 | 0.0000 | [JSON](detailed_explanations\breast_cancer\decision_tree\prototype_detailed_explanations.json) |
| breast_cancer | decision_tree | counterfactual | 114 | 114 | 0.912 | 0.0000 | [JSON](detailed_explanations\breast_cancer\decision_tree\counterfactual_detailed_explanations.json) |
| breast_cancer | decision_tree | bayesian_rule_list | 114 | 114 | 0.912 | 0.0000 | [JSON](detailed_explanations\breast_cancer\decision_tree\bayesian_rule_list_detailed_explanations.json) |
| breast_cancer | decision_tree | corels | 114 | 114 | 0.912 | 0.0000 | [JSON](detailed_explanations\breast_cancer\decision_tree\corels_detailed_explanations.json) |
| breast_cancer | decision_tree | feature_ablation | 114 | 114 | 0.912 | 0.0000 | [JSON](detailed_explanations\breast_cancer\decision_tree\feature_ablation_detailed_explanations.json) |
| breast_cancer | random_forest | shap | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\random_forest\shap_detailed_explanations.json) |
| breast_cancer | random_forest | lime | 114 | 114 | 0.956 | 0.0056 | [JSON](detailed_explanations\breast_cancer\random_forest\lime_detailed_explanations.json) |
| breast_cancer | random_forest | causal_shap | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\random_forest\causal_shap_detailed_explanations.json) |
| breast_cancer | random_forest | shapley_flow | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\random_forest\shapley_flow_detailed_explanations.json) |
| breast_cancer | random_forest | shap_interactive | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\random_forest\shap_interactive_detailed_explanations.json) |
| breast_cancer | random_forest | prototype | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\random_forest\prototype_detailed_explanations.json) |
| breast_cancer | random_forest | counterfactual | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\random_forest\counterfactual_detailed_explanations.json) |
| breast_cancer | random_forest | bayesian_rule_list | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\random_forest\bayesian_rule_list_detailed_explanations.json) |
| breast_cancer | random_forest | corels | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\random_forest\corels_detailed_explanations.json) |
| breast_cancer | random_forest | feature_ablation | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\random_forest\feature_ablation_detailed_explanations.json) |
| breast_cancer | gradient_boosting | shap | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\gradient_boosting\shap_detailed_explanations.json) |
| breast_cancer | gradient_boosting | lime | 114 | 114 | 0.956 | 0.0023 | [JSON](detailed_explanations\breast_cancer\gradient_boosting\lime_detailed_explanations.json) |
| breast_cancer | gradient_boosting | causal_shap | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\gradient_boosting\causal_shap_detailed_explanations.json) |
| breast_cancer | gradient_boosting | shap_interactive | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\gradient_boosting\shap_interactive_detailed_explanations.json) |
| breast_cancer | gradient_boosting | prototype | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\gradient_boosting\prototype_detailed_explanations.json) |
| breast_cancer | gradient_boosting | counterfactual | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\gradient_boosting\counterfactual_detailed_explanations.json) |
| breast_cancer | gradient_boosting | bayesian_rule_list | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\gradient_boosting\bayesian_rule_list_detailed_explanations.json) |
| breast_cancer | gradient_boosting | corels | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\gradient_boosting\corels_detailed_explanations.json) |
| breast_cancer | gradient_boosting | feature_ablation | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\gradient_boosting\feature_ablation_detailed_explanations.json) |
| breast_cancer | mlp | shap | 114 | 114 | 0.947 | 0.0000 | [JSON](detailed_explanations\breast_cancer\mlp\shap_detailed_explanations.json) |
| breast_cancer | mlp | lime | 114 | 114 | 0.947 | 0.0041 | [JSON](detailed_explanations\breast_cancer\mlp\lime_detailed_explanations.json) |
| breast_cancer | mlp | integrated_gradients | 114 | 114 | 0.947 | 0.0000 | [JSON](detailed_explanations\breast_cancer\mlp\integrated_gradients_detailed_explanations.json) |
| breast_cancer | mlp | causal_shap | 114 | 114 | 0.947 | 0.0000 | [JSON](detailed_explanations\breast_cancer\mlp\causal_shap_detailed_explanations.json) |
| breast_cancer | mlp | shapley_flow | 114 | 114 | 0.947 | 0.0000 | [JSON](detailed_explanations\breast_cancer\mlp\shapley_flow_detailed_explanations.json) |
| breast_cancer | mlp | shap_interactive | 114 | 114 | 0.947 | 0.0000 | [JSON](detailed_explanations\breast_cancer\mlp\shap_interactive_detailed_explanations.json) |
| breast_cancer | mlp | prototype | 114 | 114 | 0.947 | 0.0000 | [JSON](detailed_explanations\breast_cancer\mlp\prototype_detailed_explanations.json) |
| breast_cancer | mlp | counterfactual | 114 | 114 | 0.947 | 0.0000 | [JSON](detailed_explanations\breast_cancer\mlp\counterfactual_detailed_explanations.json) |
| breast_cancer | mlp | influence_functions | 114 | 114 | 0.947 | 0.0000 | [JSON](detailed_explanations\breast_cancer\mlp\influence_functions_detailed_explanations.json) |
| breast_cancer | mlp | bayesian_rule_list | 114 | 114 | 0.947 | 0.0000 | [JSON](detailed_explanations\breast_cancer\mlp\bayesian_rule_list_detailed_explanations.json) |
| breast_cancer | mlp | corels | 114 | 114 | 0.947 | 0.0000 | [JSON](detailed_explanations\breast_cancer\mlp\corels_detailed_explanations.json) |
| breast_cancer | mlp | feature_ablation | 114 | 114 | 0.947 | 0.0000 | [JSON](detailed_explanations\breast_cancer\mlp\feature_ablation_detailed_explanations.json) |
| breast_cancer | linear_regression | lime | 114 | 114 | 0.956 | 0.0114 | [JSON](detailed_explanations\breast_cancer\linear_regression\lime_detailed_explanations.json) |
| breast_cancer | linear_regression | causal_shap | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\linear_regression\causal_shap_detailed_explanations.json) |
| breast_cancer | linear_regression | shap_interactive | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\linear_regression\shap_interactive_detailed_explanations.json) |
| breast_cancer | linear_regression | prototype | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\linear_regression\prototype_detailed_explanations.json) |
| breast_cancer | linear_regression | counterfactual | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\linear_regression\counterfactual_detailed_explanations.json) |
| breast_cancer | linear_regression | bayesian_rule_list | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\linear_regression\bayesian_rule_list_detailed_explanations.json) |
| breast_cancer | linear_regression | corels | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\linear_regression\corels_detailed_explanations.json) |
| breast_cancer | linear_regression | feature_ablation | 114 | 114 | 0.956 | 0.0000 | [JSON](detailed_explanations\breast_cancer\linear_regression\feature_ablation_detailed_explanations.json) |
| breast_cancer | logistic_regression | lime | 114 | 114 | 0.982 | 0.0041 | [JSON](detailed_explanations\breast_cancer\logistic_regression\lime_detailed_explanations.json) |
| breast_cancer | logistic_regression | causal_shap | 114 | 114 | 0.982 | 0.0000 | [JSON](detailed_explanations\breast_cancer\logistic_regression\causal_shap_detailed_explanations.json) |
| breast_cancer | logistic_regression | shap_interactive | 114 | 114 | 0.982 | 0.0000 | [JSON](detailed_explanations\breast_cancer\logistic_regression\shap_interactive_detailed_explanations.json) |
| breast_cancer | logistic_regression | prototype | 114 | 114 | 0.982 | 0.0000 | [JSON](detailed_explanations\breast_cancer\logistic_regression\prototype_detailed_explanations.json) |
| breast_cancer | logistic_regression | counterfactual | 114 | 114 | 0.982 | 0.0000 | [JSON](detailed_explanations\breast_cancer\logistic_regression\counterfactual_detailed_explanations.json) |
| breast_cancer | logistic_regression | influence_functions | 114 | 114 | 0.982 | 0.0000 | [JSON](detailed_explanations\breast_cancer\logistic_regression\influence_functions_detailed_explanations.json) |
| breast_cancer | logistic_regression | bayesian_rule_list | 114 | 114 | 0.982 | 0.0000 | [JSON](detailed_explanations\breast_cancer\logistic_regression\bayesian_rule_list_detailed_explanations.json) |
| breast_cancer | logistic_regression | corels | 114 | 114 | 0.982 | 0.0000 | [JSON](detailed_explanations\breast_cancer\logistic_regression\corels_detailed_explanations.json) |
| breast_cancer | logistic_regression | feature_ablation | 114 | 114 | 0.982 | 0.0000 | [JSON](detailed_explanations\breast_cancer\logistic_regression\feature_ablation_detailed_explanations.json) |
| heart_disease | decision_tree | shap | 60 | 60 | 0.733 | 0.0000 | [JSON](detailed_explanations\heart_disease\decision_tree\shap_detailed_explanations.json) |
| heart_disease | decision_tree | lime | 60 | 60 | 0.733 | 0.0667 | [JSON](detailed_explanations\heart_disease\decision_tree\lime_detailed_explanations.json) |
| heart_disease | decision_tree | causal_shap | 60 | 60 | 0.733 | 0.0000 | [JSON](detailed_explanations\heart_disease\decision_tree\causal_shap_detailed_explanations.json) |
| heart_disease | decision_tree | shapley_flow | 60 | 60 | 0.733 | 0.0000 | [JSON](detailed_explanations\heart_disease\decision_tree\shapley_flow_detailed_explanations.json) |
| heart_disease | decision_tree | shap_interactive | 60 | 60 | 0.733 | 0.0000 | [JSON](detailed_explanations\heart_disease\decision_tree\shap_interactive_detailed_explanations.json) |
| heart_disease | decision_tree | prototype | 60 | 60 | 0.733 | 0.0000 | [JSON](detailed_explanations\heart_disease\decision_tree\prototype_detailed_explanations.json) |
| heart_disease | decision_tree | counterfactual | 60 | 60 | 0.733 | 0.0000 | [JSON](detailed_explanations\heart_disease\decision_tree\counterfactual_detailed_explanations.json) |
| heart_disease | decision_tree | bayesian_rule_list | 60 | 60 | 0.733 | 0.0000 | [JSON](detailed_explanations\heart_disease\decision_tree\bayesian_rule_list_detailed_explanations.json) |
| heart_disease | decision_tree | corels | 60 | 60 | 0.733 | 0.0000 | [JSON](detailed_explanations\heart_disease\decision_tree\corels_detailed_explanations.json) |
| heart_disease | decision_tree | feature_ablation | 60 | 60 | 0.733 | 0.0000 | [JSON](detailed_explanations\heart_disease\decision_tree\feature_ablation_detailed_explanations.json) |
| heart_disease | random_forest | shap | 60 | 60 | 0.733 | 0.0000 | [JSON](detailed_explanations\heart_disease\random_forest\shap_detailed_explanations.json) |
| heart_disease | random_forest | lime | 60 | 60 | 0.733 | 0.0633 | [JSON](detailed_explanations\heart_disease\random_forest\lime_detailed_explanations.json) |
| heart_disease | random_forest | causal_shap | 60 | 60 | 0.733 | 0.0000 | [JSON](detailed_explanations\heart_disease\random_forest\causal_shap_detailed_explanations.json) |
| heart_disease | random_forest | shapley_flow | 60 | 60 | 0.733 | 0.0000 | [JSON](detailed_explanations\heart_disease\random_forest\shapley_flow_detailed_explanations.json) |
| heart_disease | random_forest | shap_interactive | 60 | 60 | 0.733 | 0.0000 | [JSON](detailed_explanations\heart_disease\random_forest\shap_interactive_detailed_explanations.json) |
| heart_disease | random_forest | prototype | 60 | 60 | 0.733 | 0.0000 | [JSON](detailed_explanations\heart_disease\random_forest\prototype_detailed_explanations.json) |
| heart_disease | random_forest | counterfactual | 60 | 60 | 0.733 | 0.0000 | [JSON](detailed_explanations\heart_disease\random_forest\counterfactual_detailed_explanations.json) |
| heart_disease | random_forest | bayesian_rule_list | 60 | 60 | 0.733 | 0.0000 | [JSON](detailed_explanations\heart_disease\random_forest\bayesian_rule_list_detailed_explanations.json) |
| heart_disease | random_forest | corels | 60 | 60 | 0.733 | 0.0000 | [JSON](detailed_explanations\heart_disease\random_forest\corels_detailed_explanations.json) |
| heart_disease | random_forest | feature_ablation | 60 | 60 | 0.733 | 0.0000 | [JSON](detailed_explanations\heart_disease\random_forest\feature_ablation_detailed_explanations.json) |
| heart_disease | gradient_boosting | shap | 60 | 60 | 0.700 | 0.0000 | [JSON](detailed_explanations\heart_disease\gradient_boosting\shap_detailed_explanations.json) |
| heart_disease | gradient_boosting | lime | 60 | 60 | 0.700 | 0.0833 | [JSON](detailed_explanations\heart_disease\gradient_boosting\lime_detailed_explanations.json) |
| heart_disease | gradient_boosting | causal_shap | 60 | 60 | 0.700 | 0.0000 | [JSON](detailed_explanations\heart_disease\gradient_boosting\causal_shap_detailed_explanations.json) |
| heart_disease | gradient_boosting | shap_interactive | 60 | 60 | 0.700 | 0.0000 | [JSON](detailed_explanations\heart_disease\gradient_boosting\shap_interactive_detailed_explanations.json) |
| heart_disease | gradient_boosting | prototype | 60 | 60 | 0.700 | 0.0000 | [JSON](detailed_explanations\heart_disease\gradient_boosting\prototype_detailed_explanations.json) |
| heart_disease | gradient_boosting | counterfactual | 60 | 60 | 0.700 | 0.0000 | [JSON](detailed_explanations\heart_disease\gradient_boosting\counterfactual_detailed_explanations.json) |
| heart_disease | gradient_boosting | bayesian_rule_list | 60 | 60 | 0.700 | 0.0000 | [JSON](detailed_explanations\heart_disease\gradient_boosting\bayesian_rule_list_detailed_explanations.json) |
| heart_disease | gradient_boosting | corels | 60 | 60 | 0.700 | 0.0000 | [JSON](detailed_explanations\heart_disease\gradient_boosting\corels_detailed_explanations.json) |
| heart_disease | gradient_boosting | feature_ablation | 60 | 60 | 0.700 | 0.0000 | [JSON](detailed_explanations\heart_disease\gradient_boosting\feature_ablation_detailed_explanations.json) |
| heart_disease | mlp | shap | 60 | 60 | 0.800 | 0.0000 | [JSON](detailed_explanations\heart_disease\mlp\shap_detailed_explanations.json) |
| heart_disease | mlp | lime | 60 | 60 | 0.800 | 0.0667 | [JSON](detailed_explanations\heart_disease\mlp\lime_detailed_explanations.json) |
| heart_disease | mlp | integrated_gradients | 60 | 60 | 0.800 | 0.0000 | [JSON](detailed_explanations\heart_disease\mlp\integrated_gradients_detailed_explanations.json) |
| heart_disease | mlp | causal_shap | 60 | 60 | 0.800 | 0.0000 | [JSON](detailed_explanations\heart_disease\mlp\causal_shap_detailed_explanations.json) |
| heart_disease | mlp | shapley_flow | 60 | 60 | 0.800 | 0.0000 | [JSON](detailed_explanations\heart_disease\mlp\shapley_flow_detailed_explanations.json) |
| heart_disease | mlp | shap_interactive | 60 | 60 | 0.800 | 0.0000 | [JSON](detailed_explanations\heart_disease\mlp\shap_interactive_detailed_explanations.json) |
| heart_disease | mlp | prototype | 60 | 60 | 0.800 | 0.0000 | [JSON](detailed_explanations\heart_disease\mlp\prototype_detailed_explanations.json) |
| heart_disease | mlp | counterfactual | 60 | 60 | 0.800 | 0.0000 | [JSON](detailed_explanations\heart_disease\mlp\counterfactual_detailed_explanations.json) |
| heart_disease | mlp | influence_functions | 60 | 60 | 0.800 | 0.0000 | [JSON](detailed_explanations\heart_disease\mlp\influence_functions_detailed_explanations.json) |
| heart_disease | mlp | bayesian_rule_list | 60 | 60 | 0.800 | 0.0000 | [JSON](detailed_explanations\heart_disease\mlp\bayesian_rule_list_detailed_explanations.json) |
| heart_disease | mlp | corels | 60 | 60 | 0.800 | 0.0000 | [JSON](detailed_explanations\heart_disease\mlp\corels_detailed_explanations.json) |
| heart_disease | mlp | feature_ablation | 60 | 60 | 0.800 | 0.0000 | [JSON](detailed_explanations\heart_disease\mlp\feature_ablation_detailed_explanations.json) |
| heart_disease | linear_regression | lime | 60 | 60 | 0.817 | 0.0467 | [JSON](detailed_explanations\heart_disease\linear_regression\lime_detailed_explanations.json) |
| heart_disease | linear_regression | causal_shap | 60 | 60 | 0.817 | 0.0000 | [JSON](detailed_explanations\heart_disease\linear_regression\causal_shap_detailed_explanations.json) |
| heart_disease | linear_regression | shap_interactive | 60 | 60 | 0.817 | 0.0000 | [JSON](detailed_explanations\heart_disease\linear_regression\shap_interactive_detailed_explanations.json) |
| heart_disease | linear_regression | prototype | 60 | 60 | 0.817 | 0.0000 | [JSON](detailed_explanations\heart_disease\linear_regression\prototype_detailed_explanations.json) |
| heart_disease | linear_regression | counterfactual | 60 | 60 | 0.817 | 0.0000 | [JSON](detailed_explanations\heart_disease\linear_regression\counterfactual_detailed_explanations.json) |
| heart_disease | linear_regression | bayesian_rule_list | 60 | 60 | 0.817 | 0.0000 | [JSON](detailed_explanations\heart_disease\linear_regression\bayesian_rule_list_detailed_explanations.json) |
| heart_disease | linear_regression | corels | 60 | 60 | 0.817 | 0.0000 | [JSON](detailed_explanations\heart_disease\linear_regression\corels_detailed_explanations.json) |
| heart_disease | linear_regression | feature_ablation | 60 | 60 | 0.817 | 0.0000 | [JSON](detailed_explanations\heart_disease\linear_regression\feature_ablation_detailed_explanations.json) |
| heart_disease | logistic_regression | lime | 60 | 60 | 0.800 | 0.0433 | [JSON](detailed_explanations\heart_disease\logistic_regression\lime_detailed_explanations.json) |
| heart_disease | logistic_regression | causal_shap | 60 | 60 | 0.800 | 0.0000 | [JSON](detailed_explanations\heart_disease\logistic_regression\causal_shap_detailed_explanations.json) |
| heart_disease | logistic_regression | shap_interactive | 60 | 60 | 0.800 | 0.0000 | [JSON](detailed_explanations\heart_disease\logistic_regression\shap_interactive_detailed_explanations.json) |
| heart_disease | logistic_regression | prototype | 60 | 60 | 0.800 | 0.0000 | [JSON](detailed_explanations\heart_disease\logistic_regression\prototype_detailed_explanations.json) |
| heart_disease | logistic_regression | counterfactual | 60 | 60 | 0.800 | 0.0000 | [JSON](detailed_explanations\heart_disease\logistic_regression\counterfactual_detailed_explanations.json) |
| heart_disease | logistic_regression | influence_functions | 60 | 60 | 0.800 | 0.0000 | [JSON](detailed_explanations\heart_disease\logistic_regression\influence_functions_detailed_explanations.json) |
| heart_disease | logistic_regression | bayesian_rule_list | 60 | 60 | 0.800 | 0.0000 | [JSON](detailed_explanations\heart_disease\logistic_regression\bayesian_rule_list_detailed_explanations.json) |
| heart_disease | logistic_regression | corels | 60 | 60 | 0.800 | 0.0000 | [JSON](detailed_explanations\heart_disease\logistic_regression\corels_detailed_explanations.json) |
| heart_disease | logistic_regression | feature_ablation | 60 | 60 | 0.800 | 0.0000 | [JSON](detailed_explanations\heart_disease\logistic_regression\feature_ablation_detailed_explanations.json) |
| german_credit | decision_tree | shap | 200 | 200 | 0.645 | 0.0000 | [JSON](detailed_explanations\german_credit\decision_tree\shap_detailed_explanations.json) |
| german_credit | decision_tree | lime | 200 | 200 | 0.645 | 0.0121 | [JSON](detailed_explanations\german_credit\decision_tree\lime_detailed_explanations.json) |
| german_credit | decision_tree | causal_shap | 200 | 200 | 0.645 | 0.0000 | [JSON](detailed_explanations\german_credit\decision_tree\causal_shap_detailed_explanations.json) |
| german_credit | decision_tree | shapley_flow | 200 | 200 | 0.645 | 0.0000 | [JSON](detailed_explanations\german_credit\decision_tree\shapley_flow_detailed_explanations.json) |
| german_credit | decision_tree | shap_interactive | 200 | 200 | 0.645 | 0.0000 | [JSON](detailed_explanations\german_credit\decision_tree\shap_interactive_detailed_explanations.json) |
| german_credit | decision_tree | prototype | 200 | 200 | 0.645 | 0.0000 | [JSON](detailed_explanations\german_credit\decision_tree\prototype_detailed_explanations.json) |
| german_credit | decision_tree | counterfactual | 200 | 200 | 0.645 | 0.0000 | [JSON](detailed_explanations\german_credit\decision_tree\counterfactual_detailed_explanations.json) |
| german_credit | decision_tree | bayesian_rule_list | 200 | 200 | 0.645 | 0.0000 | [JSON](detailed_explanations\german_credit\decision_tree\bayesian_rule_list_detailed_explanations.json) |
| german_credit | decision_tree | corels | 200 | 200 | 0.645 | 0.0000 | [JSON](detailed_explanations\german_credit\decision_tree\corels_detailed_explanations.json) |
| german_credit | decision_tree | feature_ablation | 200 | 200 | 0.645 | 0.0000 | [JSON](detailed_explanations\german_credit\decision_tree\feature_ablation_detailed_explanations.json) |
| german_credit | random_forest | shap | 200 | 200 | 0.705 | 0.0000 | [JSON](detailed_explanations\german_credit\random_forest\shap_detailed_explanations.json) |
| german_credit | random_forest | lime | 200 | 200 | 0.705 | 0.0086 | [JSON](detailed_explanations\german_credit\random_forest\lime_detailed_explanations.json) |
| german_credit | random_forest | causal_shap | 200 | 200 | 0.705 | 0.0000 | [JSON](detailed_explanations\german_credit\random_forest\causal_shap_detailed_explanations.json) |
| german_credit | random_forest | shapley_flow | 200 | 200 | 0.705 | 0.0000 | [JSON](detailed_explanations\german_credit\random_forest\shapley_flow_detailed_explanations.json) |
| german_credit | random_forest | shap_interactive | 200 | 200 | 0.705 | 0.0000 | [JSON](detailed_explanations\german_credit\random_forest\shap_interactive_detailed_explanations.json) |
| german_credit | random_forest | prototype | 200 | 200 | 0.705 | 0.0000 | [JSON](detailed_explanations\german_credit\random_forest\prototype_detailed_explanations.json) |
| german_credit | random_forest | counterfactual | 200 | 200 | 0.705 | 0.0000 | [JSON](detailed_explanations\german_credit\random_forest\counterfactual_detailed_explanations.json) |
| german_credit | random_forest | bayesian_rule_list | 200 | 200 | 0.705 | 0.0000 | [JSON](detailed_explanations\german_credit\random_forest\bayesian_rule_list_detailed_explanations.json) |
| german_credit | random_forest | corels | 200 | 200 | 0.705 | 0.0000 | [JSON](detailed_explanations\german_credit\random_forest\corels_detailed_explanations.json) |
| german_credit | random_forest | feature_ablation | 200 | 200 | 0.705 | 0.0000 | [JSON](detailed_explanations\german_credit\random_forest\feature_ablation_detailed_explanations.json) |
| german_credit | gradient_boosting | shap | 200 | 200 | 0.715 | 0.0000 | [JSON](detailed_explanations\german_credit\gradient_boosting\shap_detailed_explanations.json) |
| german_credit | gradient_boosting | lime | 200 | 200 | 0.715 | 0.0214 | [JSON](detailed_explanations\german_credit\gradient_boosting\lime_detailed_explanations.json) |
| german_credit | gradient_boosting | causal_shap | 200 | 200 | 0.715 | 0.0000 | [JSON](detailed_explanations\german_credit\gradient_boosting\causal_shap_detailed_explanations.json) |
| german_credit | gradient_boosting | shap_interactive | 200 | 200 | 0.715 | 0.0000 | [JSON](detailed_explanations\german_credit\gradient_boosting\shap_interactive_detailed_explanations.json) |
| german_credit | gradient_boosting | prototype | 200 | 200 | 0.715 | 0.0000 | [JSON](detailed_explanations\german_credit\gradient_boosting\prototype_detailed_explanations.json) |
| german_credit | gradient_boosting | counterfactual | 200 | 200 | 0.715 | 0.0000 | [JSON](detailed_explanations\german_credit\gradient_boosting\counterfactual_detailed_explanations.json) |
| german_credit | gradient_boosting | bayesian_rule_list | 200 | 200 | 0.715 | 0.0000 | [JSON](detailed_explanations\german_credit\gradient_boosting\bayesian_rule_list_detailed_explanations.json) |
| german_credit | gradient_boosting | corels | 200 | 200 | 0.715 | 0.0000 | [JSON](detailed_explanations\german_credit\gradient_boosting\corels_detailed_explanations.json) |
| german_credit | gradient_boosting | feature_ablation | 200 | 200 | 0.715 | 0.0000 | [JSON](detailed_explanations\german_credit\gradient_boosting\feature_ablation_detailed_explanations.json) |
| german_credit | mlp | shap | 200 | 200 | 0.715 | 0.0000 | [JSON](detailed_explanations\german_credit\mlp\shap_detailed_explanations.json) |
| german_credit | mlp | lime | 200 | 200 | 0.715 | 0.0071 | [JSON](detailed_explanations\german_credit\mlp\lime_detailed_explanations.json) |
| german_credit | mlp | integrated_gradients | 200 | 200 | 0.715 | 0.0000 | [JSON](detailed_explanations\german_credit\mlp\integrated_gradients_detailed_explanations.json) |
| german_credit | mlp | causal_shap | 200 | 200 | 0.715 | 0.0000 | [JSON](detailed_explanations\german_credit\mlp\causal_shap_detailed_explanations.json) |
| german_credit | mlp | shapley_flow | 200 | 200 | 0.715 | 0.0000 | [JSON](detailed_explanations\german_credit\mlp\shapley_flow_detailed_explanations.json) |
| german_credit | mlp | shap_interactive | 200 | 200 | 0.715 | 0.0000 | [JSON](detailed_explanations\german_credit\mlp\shap_interactive_detailed_explanations.json) |
| german_credit | mlp | prototype | 200 | 200 | 0.715 | 0.0000 | [JSON](detailed_explanations\german_credit\mlp\prototype_detailed_explanations.json) |
| german_credit | mlp | counterfactual | 200 | 200 | 0.715 | 0.0000 | [JSON](detailed_explanations\german_credit\mlp\counterfactual_detailed_explanations.json) |
| german_credit | mlp | influence_functions | 200 | 200 | 0.715 | 0.0000 | [JSON](detailed_explanations\german_credit\mlp\influence_functions_detailed_explanations.json) |
| german_credit | mlp | bayesian_rule_list | 200 | 200 | 0.715 | 0.0000 | [JSON](detailed_explanations\german_credit\mlp\bayesian_rule_list_detailed_explanations.json) |
| german_credit | mlp | corels | 200 | 200 | 0.715 | 0.0000 | [JSON](detailed_explanations\german_credit\mlp\corels_detailed_explanations.json) |
| german_credit | mlp | feature_ablation | 200 | 200 | 0.715 | 0.0000 | [JSON](detailed_explanations\german_credit\mlp\feature_ablation_detailed_explanations.json) |
| german_credit | linear_regression | lime | 200 | 200 | 0.725 | 0.0086 | [JSON](detailed_explanations\german_credit\linear_regression\lime_detailed_explanations.json) |
| german_credit | linear_regression | causal_shap | 200 | 200 | 0.725 | 0.0000 | [JSON](detailed_explanations\german_credit\linear_regression\causal_shap_detailed_explanations.json) |
| german_credit | linear_regression | shap_interactive | 200 | 200 | 0.725 | 0.0000 | [JSON](detailed_explanations\german_credit\linear_regression\shap_interactive_detailed_explanations.json) |
| german_credit | linear_regression | prototype | 200 | 200 | 0.725 | 0.0000 | [JSON](detailed_explanations\german_credit\linear_regression\prototype_detailed_explanations.json) |
| german_credit | linear_regression | counterfactual | 200 | 200 | 0.725 | 0.0000 | [JSON](detailed_explanations\german_credit\linear_regression\counterfactual_detailed_explanations.json) |
| german_credit | linear_regression | bayesian_rule_list | 200 | 200 | 0.725 | 0.0000 | [JSON](detailed_explanations\german_credit\linear_regression\bayesian_rule_list_detailed_explanations.json) |
| german_credit | linear_regression | corels | 200 | 200 | 0.725 | 0.0000 | [JSON](detailed_explanations\german_credit\linear_regression\corels_detailed_explanations.json) |
| german_credit | linear_regression | feature_ablation | 200 | 200 | 0.725 | 0.0000 | [JSON](detailed_explanations\german_credit\linear_regression\feature_ablation_detailed_explanations.json) |
| german_credit | logistic_regression | lime | 200 | 200 | 0.735 | 0.0079 | [JSON](detailed_explanations\german_credit\logistic_regression\lime_detailed_explanations.json) |
| german_credit | logistic_regression | causal_shap | 200 | 200 | 0.735 | 0.0000 | [JSON](detailed_explanations\german_credit\logistic_regression\causal_shap_detailed_explanations.json) |
| german_credit | logistic_regression | shap_interactive | 200 | 200 | 0.735 | 0.0000 | [JSON](detailed_explanations\german_credit\logistic_regression\shap_interactive_detailed_explanations.json) |
| german_credit | logistic_regression | prototype | 200 | 200 | 0.735 | 0.0000 | [JSON](detailed_explanations\german_credit\logistic_regression\prototype_detailed_explanations.json) |
| german_credit | logistic_regression | counterfactual | 200 | 200 | 0.735 | 0.0000 | [JSON](detailed_explanations\german_credit\logistic_regression\counterfactual_detailed_explanations.json) |
| german_credit | logistic_regression | influence_functions | 200 | 200 | 0.735 | 0.0000 | [JSON](detailed_explanations\german_credit\logistic_regression\influence_functions_detailed_explanations.json) |
| german_credit | logistic_regression | bayesian_rule_list | 200 | 200 | 0.735 | 0.0000 | [JSON](detailed_explanations\german_credit\logistic_regression\bayesian_rule_list_detailed_explanations.json) |
| german_credit | logistic_regression | corels | 200 | 200 | 0.735 | 0.0000 | [JSON](detailed_explanations\german_credit\logistic_regression\corels_detailed_explanations.json) |
| german_credit | logistic_regression | feature_ablation | 200 | 200 | 0.735 | 0.0000 | [JSON](detailed_explanations\german_credit\logistic_regression\feature_ablation_detailed_explanations.json) |
| iris | decision_tree | shap | 30 | 30 | 0.933 | 0.0000 | [JSON](detailed_explanations\iris\decision_tree\shap_detailed_explanations.json) |
| iris | decision_tree | lime | 30 | 30 | 0.933 | 0.0750 | [JSON](detailed_explanations\iris\decision_tree\lime_detailed_explanations.json) |
| iris | decision_tree | causal_shap | 30 | 30 | 0.933 | 0.0000 | [JSON](detailed_explanations\iris\decision_tree\causal_shap_detailed_explanations.json) |
| iris | decision_tree | shapley_flow | 30 | 30 | 0.933 | 0.0000 | [JSON](detailed_explanations\iris\decision_tree\shapley_flow_detailed_explanations.json) |
| iris | decision_tree | shap_interactive | 30 | 30 | 0.933 | 0.0000 | [JSON](detailed_explanations\iris\decision_tree\shap_interactive_detailed_explanations.json) |
| iris | decision_tree | prototype | 30 | 30 | 0.933 | 0.0000 | [JSON](detailed_explanations\iris\decision_tree\prototype_detailed_explanations.json) |
| iris | decision_tree | counterfactual | 30 | 30 | 0.933 | 0.0000 | [JSON](detailed_explanations\iris\decision_tree\counterfactual_detailed_explanations.json) |
| iris | decision_tree | bayesian_rule_list | 30 | 30 | 0.933 | 0.0000 | [JSON](detailed_explanations\iris\decision_tree\bayesian_rule_list_detailed_explanations.json) |
| iris | decision_tree | corels | 30 | 30 | 0.933 | 0.0000 | [JSON](detailed_explanations\iris\decision_tree\corels_detailed_explanations.json) |
| iris | decision_tree | feature_ablation | 30 | 30 | 0.933 | 0.0000 | [JSON](detailed_explanations\iris\decision_tree\feature_ablation_detailed_explanations.json) |
| iris | random_forest | shap | 30 | 30 | 0.900 | 0.0000 | [JSON](detailed_explanations\iris\random_forest\shap_detailed_explanations.json) |
| iris | random_forest | lime | 30 | 30 | 0.900 | 0.0583 | [JSON](detailed_explanations\iris\random_forest\lime_detailed_explanations.json) |
| iris | random_forest | causal_shap | 30 | 30 | 0.900 | 0.0000 | [JSON](detailed_explanations\iris\random_forest\causal_shap_detailed_explanations.json) |
| iris | random_forest | shapley_flow | 30 | 30 | 0.900 | 0.0000 | [JSON](detailed_explanations\iris\random_forest\shapley_flow_detailed_explanations.json) |
| iris | random_forest | shap_interactive | 30 | 30 | 0.900 | 0.0000 | [JSON](detailed_explanations\iris\random_forest\shap_interactive_detailed_explanations.json) |
| iris | random_forest | prototype | 30 | 30 | 0.900 | 0.0000 | [JSON](detailed_explanations\iris\random_forest\prototype_detailed_explanations.json) |
| iris | random_forest | counterfactual | 30 | 30 | 0.900 | 0.0000 | [JSON](detailed_explanations\iris\random_forest\counterfactual_detailed_explanations.json) |
| iris | random_forest | bayesian_rule_list | 30 | 30 | 0.900 | 0.0000 | [JSON](detailed_explanations\iris\random_forest\bayesian_rule_list_detailed_explanations.json) |
| iris | random_forest | corels | 30 | 30 | 0.900 | 0.0000 | [JSON](detailed_explanations\iris\random_forest\corels_detailed_explanations.json) |
| iris | random_forest | feature_ablation | 30 | 30 | 0.900 | 0.0000 | [JSON](detailed_explanations\iris\random_forest\feature_ablation_detailed_explanations.json) |
| iris | gradient_boosting | shap | 30 | 30 | 0.967 | 0.0000 | [JSON](detailed_explanations\iris\gradient_boosting\shap_detailed_explanations.json) |
| iris | gradient_boosting | lime | 30 | 30 | 0.967 | 0.0833 | [JSON](detailed_explanations\iris\gradient_boosting\lime_detailed_explanations.json) |
| iris | gradient_boosting | causal_shap | 30 | 30 | 0.967 | 0.0000 | [JSON](detailed_explanations\iris\gradient_boosting\causal_shap_detailed_explanations.json) |
| iris | gradient_boosting | shap_interactive | 30 | 30 | 0.967 | 0.0000 | [JSON](detailed_explanations\iris\gradient_boosting\shap_interactive_detailed_explanations.json) |
| iris | gradient_boosting | prototype | 30 | 30 | 0.967 | 0.0000 | [JSON](detailed_explanations\iris\gradient_boosting\prototype_detailed_explanations.json) |
| iris | gradient_boosting | counterfactual | 30 | 30 | 0.967 | 0.0000 | [JSON](detailed_explanations\iris\gradient_boosting\counterfactual_detailed_explanations.json) |
| iris | gradient_boosting | bayesian_rule_list | 30 | 30 | 0.967 | 0.0000 | [JSON](detailed_explanations\iris\gradient_boosting\bayesian_rule_list_detailed_explanations.json) |
| iris | gradient_boosting | corels | 30 | 30 | 0.967 | 0.0000 | [JSON](detailed_explanations\iris\gradient_boosting\corels_detailed_explanations.json) |
| iris | gradient_boosting | feature_ablation | 30 | 30 | 0.967 | 0.0000 | [JSON](detailed_explanations\iris\gradient_boosting\feature_ablation_detailed_explanations.json) |
| iris | mlp | shap | 30 | 30 | 0.967 | 0.0000 | [JSON](detailed_explanations\iris\mlp\shap_detailed_explanations.json) |
| iris | mlp | lime | 30 | 30 | 0.967 | 0.0500 | [JSON](detailed_explanations\iris\mlp\lime_detailed_explanations.json) |
| iris | mlp | integrated_gradients | 30 | 30 | 0.967 | 0.0000 | [JSON](detailed_explanations\iris\mlp\integrated_gradients_detailed_explanations.json) |
| iris | mlp | causal_shap | 30 | 30 | 0.967 | 0.0000 | [JSON](detailed_explanations\iris\mlp\causal_shap_detailed_explanations.json) |
| iris | mlp | shapley_flow | 30 | 30 | 0.967 | 0.0000 | [JSON](detailed_explanations\iris\mlp\shapley_flow_detailed_explanations.json) |
| iris | mlp | shap_interactive | 30 | 30 | 0.967 | 0.0000 | [JSON](detailed_explanations\iris\mlp\shap_interactive_detailed_explanations.json) |
| iris | mlp | prototype | 30 | 30 | 0.967 | 0.0000 | [JSON](detailed_explanations\iris\mlp\prototype_detailed_explanations.json) |
| iris | mlp | counterfactual | 30 | 30 | 0.967 | 0.0000 | [JSON](detailed_explanations\iris\mlp\counterfactual_detailed_explanations.json) |
| iris | mlp | influence_functions | 30 | 30 | 0.967 | 0.0000 | [JSON](detailed_explanations\iris\mlp\influence_functions_detailed_explanations.json) |
| iris | mlp | bayesian_rule_list | 30 | 30 | 0.967 | 0.0000 | [JSON](detailed_explanations\iris\mlp\bayesian_rule_list_detailed_explanations.json) |
| iris | mlp | corels | 30 | 30 | 0.967 | 0.0000 | [JSON](detailed_explanations\iris\mlp\corels_detailed_explanations.json) |
| iris | mlp | feature_ablation | 30 | 30 | 0.967 | 0.0000 | [JSON](detailed_explanations\iris\mlp\feature_ablation_detailed_explanations.json) |
| iris | linear_regression | lime | 30 | 30 | 1.000 | 0.2417 | [JSON](detailed_explanations\iris\linear_regression\lime_detailed_explanations.json) |
| iris | linear_regression | causal_shap | 30 | 30 | 1.000 | 0.0000 | [JSON](detailed_explanations\iris\linear_regression\causal_shap_detailed_explanations.json) |
| iris | linear_regression | shap_interactive | 30 | 30 | 1.000 | 0.0000 | [JSON](detailed_explanations\iris\linear_regression\shap_interactive_detailed_explanations.json) |
| iris | linear_regression | prototype | 30 | 30 | 1.000 | 0.0000 | [JSON](detailed_explanations\iris\linear_regression\prototype_detailed_explanations.json) |
| iris | linear_regression | counterfactual | 30 | 30 | 1.000 | 0.0000 | [JSON](detailed_explanations\iris\linear_regression\counterfactual_detailed_explanations.json) |
| iris | linear_regression | bayesian_rule_list | 30 | 30 | 1.000 | 0.0000 | [JSON](detailed_explanations\iris\linear_regression\bayesian_rule_list_detailed_explanations.json) |
| iris | linear_regression | corels | 30 | 30 | 1.000 | 0.0000 | [JSON](detailed_explanations\iris\linear_regression\corels_detailed_explanations.json) |
| iris | linear_regression | feature_ablation | 30 | 30 | 1.000 | 0.2108 | [JSON](detailed_explanations\iris\linear_regression\feature_ablation_detailed_explanations.json) |
| iris | logistic_regression | lime | 30 | 30 | 0.933 | 0.0583 | [JSON](detailed_explanations\iris\logistic_regression\lime_detailed_explanations.json) |
| iris | logistic_regression | causal_shap | 30 | 30 | 0.933 | 0.0000 | [JSON](detailed_explanations\iris\logistic_regression\causal_shap_detailed_explanations.json) |
| iris | logistic_regression | shap_interactive | 30 | 30 | 0.933 | 0.0000 | [JSON](detailed_explanations\iris\logistic_regression\shap_interactive_detailed_explanations.json) |
| iris | logistic_regression | prototype | 30 | 30 | 0.933 | 0.0000 | [JSON](detailed_explanations\iris\logistic_regression\prototype_detailed_explanations.json) |
| iris | logistic_regression | counterfactual | 30 | 30 | 0.933 | 0.0000 | [JSON](detailed_explanations\iris\logistic_regression\counterfactual_detailed_explanations.json) |
| iris | logistic_regression | influence_functions | 30 | 30 | 0.933 | 0.0000 | [JSON](detailed_explanations\iris\logistic_regression\influence_functions_detailed_explanations.json) |
| iris | logistic_regression | bayesian_rule_list | 30 | 30 | 0.933 | 0.0000 | [JSON](detailed_explanations\iris\logistic_regression\bayesian_rule_list_detailed_explanations.json) |
| iris | logistic_regression | corels | 30 | 30 | 0.933 | 0.0000 | [JSON](detailed_explanations\iris\logistic_regression\corels_detailed_explanations.json) |
| iris | logistic_regression | feature_ablation | 30 | 30 | 0.933 | 0.0000 | [JSON](detailed_explanations\iris\logistic_regression\feature_ablation_detailed_explanations.json) |
| wine_quality | decision_tree | shap | 320 | 320 | 0.641 | 0.0000 | [JSON](detailed_explanations\wine_quality\decision_tree\shap_detailed_explanations.json) |
| wine_quality | decision_tree | lime | 320 | 320 | 0.641 | 0.0375 | [JSON](detailed_explanations\wine_quality\decision_tree\lime_detailed_explanations.json) |
| wine_quality | decision_tree | causal_shap | 320 | 320 | 0.641 | 0.0000 | [JSON](detailed_explanations\wine_quality\decision_tree\causal_shap_detailed_explanations.json) |
| wine_quality | decision_tree | shapley_flow | 320 | 320 | 0.641 | 0.0000 | [JSON](detailed_explanations\wine_quality\decision_tree\shapley_flow_detailed_explanations.json) |
| wine_quality | decision_tree | shap_interactive | 320 | 320 | 0.641 | 0.0000 | [JSON](detailed_explanations\wine_quality\decision_tree\shap_interactive_detailed_explanations.json) |
| wine_quality | decision_tree | prototype | 320 | 320 | 0.641 | 0.0000 | [JSON](detailed_explanations\wine_quality\decision_tree\prototype_detailed_explanations.json) |
| wine_quality | decision_tree | counterfactual | 320 | 320 | 0.641 | 0.0000 | [JSON](detailed_explanations\wine_quality\decision_tree\counterfactual_detailed_explanations.json) |
| wine_quality | decision_tree | bayesian_rule_list | 320 | 320 | 0.641 | 0.0000 | [JSON](detailed_explanations\wine_quality\decision_tree\bayesian_rule_list_detailed_explanations.json) |
| wine_quality | decision_tree | corels | 320 | 320 | 0.641 | 0.0000 | [JSON](detailed_explanations\wine_quality\decision_tree\corels_detailed_explanations.json) |
| wine_quality | decision_tree | feature_ablation | 320 | 320 | 0.641 | 0.0000 | [JSON](detailed_explanations\wine_quality\decision_tree\feature_ablation_detailed_explanations.json) |
| wine_quality | random_forest | shap | 320 | 320 | 0.706 | 0.0000 | [JSON](detailed_explanations\wine_quality\random_forest\shap_detailed_explanations.json) |
| wine_quality | random_forest | lime | 320 | 320 | 0.706 | 0.0273 | [JSON](detailed_explanations\wine_quality\random_forest\lime_detailed_explanations.json) |
| wine_quality | random_forest | causal_shap | 320 | 320 | 0.706 | 0.0000 | [JSON](detailed_explanations\wine_quality\random_forest\causal_shap_detailed_explanations.json) |
| wine_quality | random_forest | shapley_flow | 320 | 320 | 0.706 | 0.0000 | [JSON](detailed_explanations\wine_quality\random_forest\shapley_flow_detailed_explanations.json) |
| wine_quality | random_forest | shap_interactive | 320 | 320 | 0.706 | 0.0000 | [JSON](detailed_explanations\wine_quality\random_forest\shap_interactive_detailed_explanations.json) |
| wine_quality | random_forest | prototype | 320 | 320 | 0.706 | 0.0000 | [JSON](detailed_explanations\wine_quality\random_forest\prototype_detailed_explanations.json) |
| wine_quality | random_forest | counterfactual | 320 | 320 | 0.706 | 0.0000 | [JSON](detailed_explanations\wine_quality\random_forest\counterfactual_detailed_explanations.json) |
| wine_quality | random_forest | bayesian_rule_list | 320 | 320 | 0.706 | 0.0000 | [JSON](detailed_explanations\wine_quality\random_forest\bayesian_rule_list_detailed_explanations.json) |
| wine_quality | random_forest | corels | 320 | 320 | 0.706 | 0.0000 | [JSON](detailed_explanations\wine_quality\random_forest\corels_detailed_explanations.json) |
| wine_quality | random_forest | feature_ablation | 320 | 320 | 0.706 | 0.0000 | [JSON](detailed_explanations\wine_quality\random_forest\feature_ablation_detailed_explanations.json) |
| wine_quality | gradient_boosting | shap | 320 | 320 | 0.700 | 0.0000 | [JSON](detailed_explanations\wine_quality\gradient_boosting\shap_detailed_explanations.json) |
| wine_quality | gradient_boosting | lime | 320 | 320 | 0.700 | 0.0327 | [JSON](detailed_explanations\wine_quality\gradient_boosting\lime_detailed_explanations.json) |
| wine_quality | gradient_boosting | causal_shap | 320 | 320 | 0.700 | 0.0000 | [JSON](detailed_explanations\wine_quality\gradient_boosting\causal_shap_detailed_explanations.json) |
| wine_quality | gradient_boosting | shap_interactive | 320 | 320 | 0.700 | 0.0000 | [JSON](detailed_explanations\wine_quality\gradient_boosting\shap_interactive_detailed_explanations.json) |
| wine_quality | gradient_boosting | prototype | 320 | 320 | 0.700 | 0.0000 | [JSON](detailed_explanations\wine_quality\gradient_boosting\prototype_detailed_explanations.json) |
| wine_quality | gradient_boosting | counterfactual | 320 | 320 | 0.700 | 0.0000 | [JSON](detailed_explanations\wine_quality\gradient_boosting\counterfactual_detailed_explanations.json) |
| wine_quality | gradient_boosting | bayesian_rule_list | 320 | 320 | 0.700 | 0.0000 | [JSON](detailed_explanations\wine_quality\gradient_boosting\bayesian_rule_list_detailed_explanations.json) |
| wine_quality | gradient_boosting | corels | 320 | 320 | 0.700 | 0.0000 | [JSON](detailed_explanations\wine_quality\gradient_boosting\corels_detailed_explanations.json) |
| wine_quality | gradient_boosting | feature_ablation | 320 | 320 | 0.700 | 0.0000 | [JSON](detailed_explanations\wine_quality\gradient_boosting\feature_ablation_detailed_explanations.json) |
| wine_quality | mlp | shap | 320 | 320 | 0.691 | 0.0000 | [JSON](detailed_explanations\wine_quality\mlp\shap_detailed_explanations.json) |
| wine_quality | mlp | lime | 320 | 320 | 0.691 | 0.0318 | [JSON](detailed_explanations\wine_quality\mlp\lime_detailed_explanations.json) |
| wine_quality | mlp | integrated_gradients | 320 | 320 | 0.691 | 0.0000 | [JSON](detailed_explanations\wine_quality\mlp\integrated_gradients_detailed_explanations.json) |
| wine_quality | mlp | causal_shap | 320 | 320 | 0.691 | 0.0000 | [JSON](detailed_explanations\wine_quality\mlp\causal_shap_detailed_explanations.json) |
| wine_quality | mlp | shapley_flow | 320 | 320 | 0.691 | 0.0000 | [JSON](detailed_explanations\wine_quality\mlp\shapley_flow_detailed_explanations.json) |
| wine_quality | mlp | shap_interactive | 320 | 320 | 0.691 | 0.0000 | [JSON](detailed_explanations\wine_quality\mlp\shap_interactive_detailed_explanations.json) |
| wine_quality | mlp | prototype | 320 | 320 | 0.691 | 0.0000 | [JSON](detailed_explanations\wine_quality\mlp\prototype_detailed_explanations.json) |
| wine_quality | mlp | counterfactual | 320 | 320 | 0.691 | 0.0000 | [JSON](detailed_explanations\wine_quality\mlp\counterfactual_detailed_explanations.json) |
| wine_quality | mlp | influence_functions | 320 | 320 | 0.691 | 0.0000 | [JSON](detailed_explanations\wine_quality\mlp\influence_functions_detailed_explanations.json) |
| wine_quality | mlp | bayesian_rule_list | 320 | 320 | 0.691 | 0.0000 | [JSON](detailed_explanations\wine_quality\mlp\bayesian_rule_list_detailed_explanations.json) |
| wine_quality | mlp | corels | 320 | 320 | 0.691 | 0.0000 | [JSON](detailed_explanations\wine_quality\mlp\corels_detailed_explanations.json) |
| wine_quality | mlp | feature_ablation | 320 | 320 | 0.691 | 0.0000 | [JSON](detailed_explanations\wine_quality\mlp\feature_ablation_detailed_explanations.json) |
| wine_quality | linear_regression | lime | 320 | 320 | 0.637 | 0.0909 | [JSON](detailed_explanations\wine_quality\linear_regression\lime_detailed_explanations.json) |
| wine_quality | linear_regression | causal_shap | 320 | 320 | 0.637 | 0.0000 | [JSON](detailed_explanations\wine_quality\linear_regression\causal_shap_detailed_explanations.json) |
| wine_quality | linear_regression | shap_interactive | 320 | 320 | 0.637 | 0.0000 | [JSON](detailed_explanations\wine_quality\linear_regression\shap_interactive_detailed_explanations.json) |
| wine_quality | linear_regression | prototype | 320 | 320 | 0.637 | 0.0000 | [JSON](detailed_explanations\wine_quality\linear_regression\prototype_detailed_explanations.json) |
| wine_quality | linear_regression | counterfactual | 320 | 320 | 0.637 | 0.0000 | [JSON](detailed_explanations\wine_quality\linear_regression\counterfactual_detailed_explanations.json) |
| wine_quality | linear_regression | bayesian_rule_list | 320 | 320 | 0.637 | 0.0000 | [JSON](detailed_explanations\wine_quality\linear_regression\bayesian_rule_list_detailed_explanations.json) |
| wine_quality | linear_regression | corels | 320 | 320 | 0.637 | 0.0000 | [JSON](detailed_explanations\wine_quality\linear_regression\corels_detailed_explanations.json) |
| wine_quality | linear_regression | feature_ablation | 320 | 320 | 0.637 | 0.0705 | [JSON](detailed_explanations\wine_quality\linear_regression\feature_ablation_detailed_explanations.json) |
| wine_quality | logistic_regression | lime | 320 | 320 | 0.653 | 0.0216 | [JSON](detailed_explanations\wine_quality\logistic_regression\lime_detailed_explanations.json) |
| wine_quality | logistic_regression | causal_shap | 320 | 320 | 0.653 | 0.0000 | [JSON](detailed_explanations\wine_quality\logistic_regression\causal_shap_detailed_explanations.json) |
| wine_quality | logistic_regression | shap_interactive | 320 | 320 | 0.653 | 0.0000 | [JSON](detailed_explanations\wine_quality\logistic_regression\shap_interactive_detailed_explanations.json) |
| wine_quality | logistic_regression | prototype | 320 | 320 | 0.653 | 0.0000 | [JSON](detailed_explanations\wine_quality\logistic_regression\prototype_detailed_explanations.json) |
| wine_quality | logistic_regression | counterfactual | 320 | 320 | 0.653 | 0.0000 | [JSON](detailed_explanations\wine_quality\logistic_regression\counterfactual_detailed_explanations.json) |
| wine_quality | logistic_regression | influence_functions | 320 | 320 | 0.653 | 0.0000 | [JSON](detailed_explanations\wine_quality\logistic_regression\influence_functions_detailed_explanations.json) |
| wine_quality | logistic_regression | bayesian_rule_list | 320 | 320 | 0.653 | 0.0000 | [JSON](detailed_explanations\wine_quality\logistic_regression\bayesian_rule_list_detailed_explanations.json) |
| wine_quality | logistic_regression | corels | 320 | 320 | 0.653 | 0.0000 | [JSON](detailed_explanations\wine_quality\logistic_regression\corels_detailed_explanations.json) |
| wine_quality | logistic_regression | feature_ablation | 320 | 320 | 0.653 | 0.0000 | [JSON](detailed_explanations\wine_quality\logistic_regression\feature_ablation_detailed_explanations.json) |
| diabetes | decision_tree | shap | 89 | 89 | 0.494 | 0.0000 | [JSON](detailed_explanations\diabetes\decision_tree\shap_detailed_explanations.json) |
| diabetes | decision_tree | lime | 89 | 89 | 0.494 | 0.0427 | [JSON](detailed_explanations\diabetes\decision_tree\lime_detailed_explanations.json) |
| diabetes | decision_tree | causal_shap | 89 | 89 | 0.494 | 0.0000 | [JSON](detailed_explanations\diabetes\decision_tree\causal_shap_detailed_explanations.json) |
| diabetes | decision_tree | shapley_flow | 89 | 89 | 0.494 | 0.0000 | [JSON](detailed_explanations\diabetes\decision_tree\shapley_flow_detailed_explanations.json) |
| diabetes | decision_tree | shap_interactive | 89 | 89 | 0.494 | 0.0000 | [JSON](detailed_explanations\diabetes\decision_tree\shap_interactive_detailed_explanations.json) |
| diabetes | decision_tree | prototype | 89 | 89 | 0.494 | 0.0000 | [JSON](detailed_explanations\diabetes\decision_tree\prototype_detailed_explanations.json) |
| diabetes | decision_tree | counterfactual | 89 | 89 | 0.494 | 0.0000 | [JSON](detailed_explanations\diabetes\decision_tree\counterfactual_detailed_explanations.json) |
| diabetes | decision_tree | bayesian_rule_list | 89 | 89 | 0.494 | 0.0000 | [JSON](detailed_explanations\diabetes\decision_tree\bayesian_rule_list_detailed_explanations.json) |
| diabetes | decision_tree | corels | 89 | 89 | 0.494 | 0.0000 | [JSON](detailed_explanations\diabetes\decision_tree\corels_detailed_explanations.json) |
| diabetes | decision_tree | feature_ablation | 89 | 89 | 0.494 | 0.0000 | [JSON](detailed_explanations\diabetes\decision_tree\feature_ablation_detailed_explanations.json) |
| diabetes | random_forest | shap | 89 | 89 | 0.584 | 0.0000 | [JSON](detailed_explanations\diabetes\random_forest\shap_detailed_explanations.json) |
| diabetes | random_forest | lime | 89 | 89 | 0.584 | 0.0337 | [JSON](detailed_explanations\diabetes\random_forest\lime_detailed_explanations.json) |
| diabetes | random_forest | causal_shap | 89 | 89 | 0.584 | 0.0000 | [JSON](detailed_explanations\diabetes\random_forest\causal_shap_detailed_explanations.json) |
| diabetes | random_forest | shapley_flow | 89 | 89 | 0.584 | 0.0000 | [JSON](detailed_explanations\diabetes\random_forest\shapley_flow_detailed_explanations.json) |
| diabetes | random_forest | shap_interactive | 89 | 89 | 0.584 | 0.0000 | [JSON](detailed_explanations\diabetes\random_forest\shap_interactive_detailed_explanations.json) |
| diabetes | random_forest | prototype | 89 | 89 | 0.584 | 0.0000 | [JSON](detailed_explanations\diabetes\random_forest\prototype_detailed_explanations.json) |
| diabetes | random_forest | counterfactual | 89 | 89 | 0.584 | 0.0000 | [JSON](detailed_explanations\diabetes\random_forest\counterfactual_detailed_explanations.json) |
| diabetes | random_forest | bayesian_rule_list | 89 | 89 | 0.584 | 0.0000 | [JSON](detailed_explanations\diabetes\random_forest\bayesian_rule_list_detailed_explanations.json) |
| diabetes | random_forest | corels | 89 | 89 | 0.584 | 0.0000 | [JSON](detailed_explanations\diabetes\random_forest\corels_detailed_explanations.json) |
| diabetes | random_forest | feature_ablation | 89 | 89 | 0.584 | 0.0000 | [JSON](detailed_explanations\diabetes\random_forest\feature_ablation_detailed_explanations.json) |
| diabetes | gradient_boosting | shap | 89 | 89 | 0.539 | 0.0000 | [JSON](detailed_explanations\diabetes\gradient_boosting\shap_detailed_explanations.json) |
| diabetes | gradient_boosting | lime | 89 | 89 | 0.539 | 0.0506 | [JSON](detailed_explanations\diabetes\gradient_boosting\lime_detailed_explanations.json) |
| diabetes | gradient_boosting | causal_shap | 89 | 89 | 0.539 | 0.0000 | [JSON](detailed_explanations\diabetes\gradient_boosting\causal_shap_detailed_explanations.json) |
| diabetes | gradient_boosting | shap_interactive | 89 | 89 | 0.539 | 0.0000 | [JSON](detailed_explanations\diabetes\gradient_boosting\shap_interactive_detailed_explanations.json) |
| diabetes | gradient_boosting | prototype | 89 | 89 | 0.539 | 0.0000 | [JSON](detailed_explanations\diabetes\gradient_boosting\prototype_detailed_explanations.json) |
| diabetes | gradient_boosting | counterfactual | 89 | 89 | 0.539 | 0.0000 | [JSON](detailed_explanations\diabetes\gradient_boosting\counterfactual_detailed_explanations.json) |
| diabetes | gradient_boosting | bayesian_rule_list | 89 | 89 | 0.539 | 0.0000 | [JSON](detailed_explanations\diabetes\gradient_boosting\bayesian_rule_list_detailed_explanations.json) |
| diabetes | gradient_boosting | corels | 89 | 89 | 0.539 | 0.0000 | [JSON](detailed_explanations\diabetes\gradient_boosting\corels_detailed_explanations.json) |
| diabetes | gradient_boosting | feature_ablation | 89 | 89 | 0.539 | 0.0000 | [JSON](detailed_explanations\diabetes\gradient_boosting\feature_ablation_detailed_explanations.json) |
| diabetes | mlp | shap | 89 | 89 | 0.449 | 0.0000 | [JSON](detailed_explanations\diabetes\mlp\shap_detailed_explanations.json) |
| diabetes | mlp | lime | 89 | 89 | 0.449 | 0.0438 | [JSON](detailed_explanations\diabetes\mlp\lime_detailed_explanations.json) |
| diabetes | mlp | integrated_gradients | 89 | 89 | 0.449 | 0.0000 | [JSON](detailed_explanations\diabetes\mlp\integrated_gradients_detailed_explanations.json) |
| diabetes | mlp | causal_shap | 89 | 89 | 0.449 | 0.0000 | [JSON](detailed_explanations\diabetes\mlp\causal_shap_detailed_explanations.json) |
| diabetes | mlp | shapley_flow | 89 | 89 | 0.449 | 0.0000 | [JSON](detailed_explanations\diabetes\mlp\shapley_flow_detailed_explanations.json) |
| diabetes | mlp | shap_interactive | 89 | 89 | 0.449 | 0.0000 | [JSON](detailed_explanations\diabetes\mlp\shap_interactive_detailed_explanations.json) |
| diabetes | mlp | prototype | 89 | 89 | 0.449 | 0.0000 | [JSON](detailed_explanations\diabetes\mlp\prototype_detailed_explanations.json) |
| diabetes | mlp | counterfactual | 89 | 89 | 0.449 | 0.0000 | [JSON](detailed_explanations\diabetes\mlp\counterfactual_detailed_explanations.json) |
| diabetes | mlp | influence_functions | 89 | 89 | 0.449 | 0.0000 | [JSON](detailed_explanations\diabetes\mlp\influence_functions_detailed_explanations.json) |
| diabetes | mlp | bayesian_rule_list | 89 | 89 | 0.449 | 0.0000 | [JSON](detailed_explanations\diabetes\mlp\bayesian_rule_list_detailed_explanations.json) |
| diabetes | mlp | corels | 89 | 89 | 0.449 | 0.0000 | [JSON](detailed_explanations\diabetes\mlp\corels_detailed_explanations.json) |
| diabetes | mlp | feature_ablation | 89 | 89 | 0.449 | 0.0000 | [JSON](detailed_explanations\diabetes\mlp\feature_ablation_detailed_explanations.json) |
| diabetes | linear_regression | lime | 89 | 89 | 0.607 | 0.0989 | [JSON](detailed_explanations\diabetes\linear_regression\lime_detailed_explanations.json) |
| diabetes | linear_regression | causal_shap | 89 | 89 | 0.607 | 0.0000 | [JSON](detailed_explanations\diabetes\linear_regression\causal_shap_detailed_explanations.json) |
| diabetes | linear_regression | shap_interactive | 89 | 89 | 0.607 | 0.0000 | [JSON](detailed_explanations\diabetes\linear_regression\shap_interactive_detailed_explanations.json) |
| diabetes | linear_regression | prototype | 89 | 89 | 0.607 | 0.0000 | [JSON](detailed_explanations\diabetes\linear_regression\prototype_detailed_explanations.json) |
| diabetes | linear_regression | counterfactual | 89 | 89 | 0.607 | 0.0000 | [JSON](detailed_explanations\diabetes\linear_regression\counterfactual_detailed_explanations.json) |
| diabetes | linear_regression | bayesian_rule_list | 89 | 89 | 0.607 | 0.0000 | [JSON](detailed_explanations\diabetes\linear_regression\bayesian_rule_list_detailed_explanations.json) |
| diabetes | linear_regression | corels | 89 | 89 | 0.607 | 0.0000 | [JSON](detailed_explanations\diabetes\linear_regression\corels_detailed_explanations.json) |
| diabetes | linear_regression | feature_ablation | 89 | 89 | 0.607 | 0.1184 | [JSON](detailed_explanations\diabetes\linear_regression\feature_ablation_detailed_explanations.json) |
| diabetes | logistic_regression | lime | 89 | 89 | 0.652 | 0.0315 | [JSON](detailed_explanations\diabetes\logistic_regression\lime_detailed_explanations.json) |
| diabetes | logistic_regression | causal_shap | 89 | 89 | 0.652 | 0.0000 | [JSON](detailed_explanations\diabetes\logistic_regression\causal_shap_detailed_explanations.json) |
| diabetes | logistic_regression | shap_interactive | 89 | 89 | 0.652 | 0.0000 | [JSON](detailed_explanations\diabetes\logistic_regression\shap_interactive_detailed_explanations.json) |
| diabetes | logistic_regression | prototype | 89 | 89 | 0.652 | 0.0000 | [JSON](detailed_explanations\diabetes\logistic_regression\prototype_detailed_explanations.json) |
| diabetes | logistic_regression | counterfactual | 89 | 89 | 0.652 | 0.0000 | [JSON](detailed_explanations\diabetes\logistic_regression\counterfactual_detailed_explanations.json) |
| diabetes | logistic_regression | influence_functions | 89 | 89 | 0.652 | 0.0000 | [JSON](detailed_explanations\diabetes\logistic_regression\influence_functions_detailed_explanations.json) |
| diabetes | logistic_regression | bayesian_rule_list | 89 | 89 | 0.652 | 0.0000 | [JSON](detailed_explanations\diabetes\logistic_regression\bayesian_rule_list_detailed_explanations.json) |
| diabetes | logistic_regression | corels | 89 | 89 | 0.652 | 0.0000 | [JSON](detailed_explanations\diabetes\logistic_regression\corels_detailed_explanations.json) |
| diabetes | logistic_regression | feature_ablation | 89 | 89 | 0.652 | 0.0000 | [JSON](detailed_explanations\diabetes\logistic_regression\feature_ablation_detailed_explanations.json) |
| wine_classification | decision_tree | shap | 36 | 36 | 0.944 | 0.0000 | [JSON](detailed_explanations\wine_classification\decision_tree\shap_detailed_explanations.json) |
| wine_classification | decision_tree | lime | 36 | 36 | 0.944 | 0.0000 | [JSON](detailed_explanations\wine_classification\decision_tree\lime_detailed_explanations.json) |
| wine_classification | decision_tree | causal_shap | 36 | 36 | 0.944 | 0.0000 | [JSON](detailed_explanations\wine_classification\decision_tree\causal_shap_detailed_explanations.json) |
| wine_classification | decision_tree | shapley_flow | 36 | 36 | 0.944 | 0.0000 | [JSON](detailed_explanations\wine_classification\decision_tree\shapley_flow_detailed_explanations.json) |
| wine_classification | decision_tree | shap_interactive | 36 | 36 | 0.944 | 0.0000 | [JSON](detailed_explanations\wine_classification\decision_tree\shap_interactive_detailed_explanations.json) |
| wine_classification | decision_tree | prototype | 36 | 36 | 0.944 | 0.0000 | [JSON](detailed_explanations\wine_classification\decision_tree\prototype_detailed_explanations.json) |
| wine_classification | decision_tree | counterfactual | 36 | 36 | 0.944 | 0.0000 | [JSON](detailed_explanations\wine_classification\decision_tree\counterfactual_detailed_explanations.json) |
| wine_classification | decision_tree | bayesian_rule_list | 36 | 36 | 0.944 | 0.0000 | [JSON](detailed_explanations\wine_classification\decision_tree\bayesian_rule_list_detailed_explanations.json) |
| wine_classification | decision_tree | corels | 36 | 36 | 0.944 | 0.0000 | [JSON](detailed_explanations\wine_classification\decision_tree\corels_detailed_explanations.json) |
| wine_classification | decision_tree | feature_ablation | 36 | 36 | 0.944 | 0.0000 | [JSON](detailed_explanations\wine_classification\decision_tree\feature_ablation_detailed_explanations.json) |
| wine_classification | random_forest | shap | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\random_forest\shap_detailed_explanations.json) |
| wine_classification | random_forest | lime | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\random_forest\lime_detailed_explanations.json) |
| wine_classification | random_forest | causal_shap | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\random_forest\causal_shap_detailed_explanations.json) |
| wine_classification | random_forest | shapley_flow | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\random_forest\shapley_flow_detailed_explanations.json) |
| wine_classification | random_forest | shap_interactive | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\random_forest\shap_interactive_detailed_explanations.json) |
| wine_classification | random_forest | prototype | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\random_forest\prototype_detailed_explanations.json) |
| wine_classification | random_forest | counterfactual | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\random_forest\counterfactual_detailed_explanations.json) |
| wine_classification | random_forest | bayesian_rule_list | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\random_forest\bayesian_rule_list_detailed_explanations.json) |
| wine_classification | random_forest | corels | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\random_forest\corels_detailed_explanations.json) |
| wine_classification | random_forest | feature_ablation | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\random_forest\feature_ablation_detailed_explanations.json) |
| wine_classification | gradient_boosting | shap | 36 | 36 | 0.944 | 0.0000 | [JSON](detailed_explanations\wine_classification\gradient_boosting\shap_detailed_explanations.json) |
| wine_classification | gradient_boosting | lime | 36 | 36 | 0.944 | 0.0214 | [JSON](detailed_explanations\wine_classification\gradient_boosting\lime_detailed_explanations.json) |
| wine_classification | gradient_boosting | causal_shap | 36 | 36 | 0.944 | 0.0000 | [JSON](detailed_explanations\wine_classification\gradient_boosting\causal_shap_detailed_explanations.json) |
| wine_classification | gradient_boosting | shap_interactive | 36 | 36 | 0.944 | 0.0000 | [JSON](detailed_explanations\wine_classification\gradient_boosting\shap_interactive_detailed_explanations.json) |
| wine_classification | gradient_boosting | prototype | 36 | 36 | 0.944 | 0.0000 | [JSON](detailed_explanations\wine_classification\gradient_boosting\prototype_detailed_explanations.json) |
| wine_classification | gradient_boosting | counterfactual | 36 | 36 | 0.944 | 0.0000 | [JSON](detailed_explanations\wine_classification\gradient_boosting\counterfactual_detailed_explanations.json) |
| wine_classification | gradient_boosting | bayesian_rule_list | 36 | 36 | 0.944 | 0.0000 | [JSON](detailed_explanations\wine_classification\gradient_boosting\bayesian_rule_list_detailed_explanations.json) |
| wine_classification | gradient_boosting | corels | 36 | 36 | 0.944 | 0.0000 | [JSON](detailed_explanations\wine_classification\gradient_boosting\corels_detailed_explanations.json) |
| wine_classification | gradient_boosting | feature_ablation | 36 | 36 | 0.944 | 0.0000 | [JSON](detailed_explanations\wine_classification\gradient_boosting\feature_ablation_detailed_explanations.json) |
| wine_classification | mlp | shap | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\mlp\shap_detailed_explanations.json) |
| wine_classification | mlp | lime | 36 | 36 | 1.000 | 0.0128 | [JSON](detailed_explanations\wine_classification\mlp\lime_detailed_explanations.json) |
| wine_classification | mlp | integrated_gradients | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\mlp\integrated_gradients_detailed_explanations.json) |
| wine_classification | mlp | causal_shap | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\mlp\causal_shap_detailed_explanations.json) |
| wine_classification | mlp | shapley_flow | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\mlp\shapley_flow_detailed_explanations.json) |
| wine_classification | mlp | shap_interactive | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\mlp\shap_interactive_detailed_explanations.json) |
| wine_classification | mlp | prototype | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\mlp\prototype_detailed_explanations.json) |
| wine_classification | mlp | counterfactual | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\mlp\counterfactual_detailed_explanations.json) |
| wine_classification | mlp | influence_functions | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\mlp\influence_functions_detailed_explanations.json) |
| wine_classification | mlp | bayesian_rule_list | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\mlp\bayesian_rule_list_detailed_explanations.json) |
| wine_classification | mlp | corels | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\mlp\corels_detailed_explanations.json) |
| wine_classification | mlp | feature_ablation | 36 | 36 | 1.000 | 0.0000 | [JSON](detailed_explanations\wine_classification\mlp\feature_ablation_detailed_explanations.json) |
| wine_classification | linear_regression | lime | 36 | 36 | 0.861 | 0.0769 | [JSON](detailed_explanations\wine_classification\linear_regression\lime_detailed_explanations.json) |
| wine_classification | linear_regression | causal_shap | 36 | 36 | 0.861 | 0.0000 | [JSON](detailed_explanations\wine_classification\linear_regression\causal_shap_detailed_explanations.json) |
| wine_classification | linear_regression | shap_interactive | 36 | 36 | 0.861 | 0.0000 | [JSON](detailed_explanations\wine_classification\linear_regression\shap_interactive_detailed_explanations.json) |
| wine_classification | linear_regression | prototype | 36 | 36 | 0.861 | 0.0000 | [JSON](detailed_explanations\wine_classification\linear_regression\prototype_detailed_explanations.json) |
| wine_classification | linear_regression | counterfactual | 36 | 36 | 0.861 | 0.0000 | [JSON](detailed_explanations\wine_classification\linear_regression\counterfactual_detailed_explanations.json) |
| wine_classification | linear_regression | bayesian_rule_list | 36 | 36 | 0.861 | 0.0000 | [JSON](detailed_explanations\wine_classification\linear_regression\bayesian_rule_list_detailed_explanations.json) |
| wine_classification | linear_regression | corels | 36 | 36 | 0.861 | 0.0000 | [JSON](detailed_explanations\wine_classification\linear_regression\corels_detailed_explanations.json) |
| wine_classification | linear_regression | feature_ablation | 36 | 36 | 0.861 | 0.1087 | [JSON](detailed_explanations\wine_classification\linear_regression\feature_ablation_detailed_explanations.json) |
| wine_classification | logistic_regression | lime | 36 | 36 | 0.972 | 0.0171 | [JSON](detailed_explanations\wine_classification\logistic_regression\lime_detailed_explanations.json) |
| wine_classification | logistic_regression | causal_shap | 36 | 36 | 0.972 | 0.0000 | [JSON](detailed_explanations\wine_classification\logistic_regression\causal_shap_detailed_explanations.json) |
| wine_classification | logistic_regression | shap_interactive | 36 | 36 | 0.972 | 0.0000 | [JSON](detailed_explanations\wine_classification\logistic_regression\shap_interactive_detailed_explanations.json) |
| wine_classification | logistic_regression | prototype | 36 | 36 | 0.972 | 0.0000 | [JSON](detailed_explanations\wine_classification\logistic_regression\prototype_detailed_explanations.json) |
| wine_classification | logistic_regression | counterfactual | 36 | 36 | 0.972 | 0.0000 | [JSON](detailed_explanations\wine_classification\logistic_regression\counterfactual_detailed_explanations.json) |
| wine_classification | logistic_regression | influence_functions | 36 | 36 | 0.972 | 0.0000 | [JSON](detailed_explanations\wine_classification\logistic_regression\influence_functions_detailed_explanations.json) |
| wine_classification | logistic_regression | bayesian_rule_list | 36 | 36 | 0.972 | 0.0000 | [JSON](detailed_explanations\wine_classification\logistic_regression\bayesian_rule_list_detailed_explanations.json) |
| wine_classification | logistic_regression | corels | 36 | 36 | 0.972 | 0.0000 | [JSON](detailed_explanations\wine_classification\logistic_regression\corels_detailed_explanations.json) |
| wine_classification | logistic_regression | feature_ablation | 36 | 36 | 0.972 | 0.0000 | [JSON](detailed_explanations\wine_classification\logistic_regression\feature_ablation_detailed_explanations.json) |
| digits | decision_tree | shap | 360 | 360 | 0.808 | 0.0000 | [JSON](detailed_explanations\digits\decision_tree\shap_detailed_explanations.json) |
| digits | decision_tree | lime | 360 | 360 | 0.808 | 0.0063 | [JSON](detailed_explanations\digits\decision_tree\lime_detailed_explanations.json) |
| digits | decision_tree | causal_shap | 360 | 360 | 0.808 | 0.0000 | [JSON](detailed_explanations\digits\decision_tree\causal_shap_detailed_explanations.json) |
| digits | decision_tree | shapley_flow | 360 | 360 | 0.808 | 0.0000 | [JSON](detailed_explanations\digits\decision_tree\shapley_flow_detailed_explanations.json) |
| digits | decision_tree | shap_interactive | 360 | 360 | 0.808 | 0.0000 | [JSON](detailed_explanations\digits\decision_tree\shap_interactive_detailed_explanations.json) |
| digits | decision_tree | prototype | 360 | 360 | 0.808 | 0.0000 | [JSON](detailed_explanations\digits\decision_tree\prototype_detailed_explanations.json) |
| digits | decision_tree | counterfactual | 360 | 360 | 0.808 | 0.0000 | [JSON](detailed_explanations\digits\decision_tree\counterfactual_detailed_explanations.json) |
| digits | decision_tree | bayesian_rule_list | 360 | 360 | 0.808 | 0.0000 | [JSON](detailed_explanations\digits\decision_tree\bayesian_rule_list_detailed_explanations.json) |
| digits | decision_tree | corels | 360 | 360 | 0.808 | 0.0000 | [JSON](detailed_explanations\digits\decision_tree\corels_detailed_explanations.json) |
| digits | decision_tree | feature_ablation | 360 | 360 | 0.808 | 0.0000 | [JSON](detailed_explanations\digits\decision_tree\feature_ablation_detailed_explanations.json) |
| digits | random_forest | shap | 360 | 360 | 0.961 | 0.0000 | [JSON](detailed_explanations\digits\random_forest\shap_detailed_explanations.json) |
| digits | random_forest | lime | 360 | 360 | 0.961 | 0.0034 | [JSON](detailed_explanations\digits\random_forest\lime_detailed_explanations.json) |
| digits | random_forest | causal_shap | 360 | 360 | 0.961 | 0.0000 | [JSON](detailed_explanations\digits\random_forest\causal_shap_detailed_explanations.json) |
| digits | random_forest | shapley_flow | 360 | 360 | 0.961 | 0.0000 | [JSON](detailed_explanations\digits\random_forest\shapley_flow_detailed_explanations.json) |
| digits | random_forest | shap_interactive | 360 | 360 | 0.961 | 0.0000 | [JSON](detailed_explanations\digits\random_forest\shap_interactive_detailed_explanations.json) |
| digits | random_forest | prototype | 360 | 360 | 0.961 | 0.0000 | [JSON](detailed_explanations\digits\random_forest\prototype_detailed_explanations.json) |
| digits | random_forest | counterfactual | 360 | 360 | 0.961 | 0.0000 | [JSON](detailed_explanations\digits\random_forest\counterfactual_detailed_explanations.json) |
| digits | random_forest | bayesian_rule_list | 360 | 360 | 0.961 | 0.0000 | [JSON](detailed_explanations\digits\random_forest\bayesian_rule_list_detailed_explanations.json) |
| digits | random_forest | corels | 360 | 360 | 0.961 | 0.0000 | [JSON](detailed_explanations\digits\random_forest\corels_detailed_explanations.json) |
| digits | random_forest | feature_ablation | 360 | 360 | 0.961 | 0.0000 | [JSON](detailed_explanations\digits\random_forest\feature_ablation_detailed_explanations.json) |
| digits | gradient_boosting | shap | 360 | 360 | 0.953 | 0.0000 | [JSON](detailed_explanations\digits\gradient_boosting\shap_detailed_explanations.json) |
| digits | gradient_boosting | lime | 360 | 360 | 0.953 | 0.0036 | [JSON](detailed_explanations\digits\gradient_boosting\lime_detailed_explanations.json) |
| digits | gradient_boosting | causal_shap | 360 | 360 | 0.953 | 0.0000 | [JSON](detailed_explanations\digits\gradient_boosting\causal_shap_detailed_explanations.json) |
| digits | gradient_boosting | shap_interactive | 360 | 360 | 0.953 | 0.0000 | [JSON](detailed_explanations\digits\gradient_boosting\shap_interactive_detailed_explanations.json) |
| digits | gradient_boosting | prototype | 360 | 360 | 0.953 | 0.0000 | [JSON](detailed_explanations\digits\gradient_boosting\prototype_detailed_explanations.json) |
| digits | gradient_boosting | counterfactual | 360 | 360 | 0.953 | 0.0000 | [JSON](detailed_explanations\digits\gradient_boosting\counterfactual_detailed_explanations.json) |
| digits | gradient_boosting | bayesian_rule_list | 360 | 360 | 0.953 | 0.0000 | [JSON](detailed_explanations\digits\gradient_boosting\bayesian_rule_list_detailed_explanations.json) |
| digits | gradient_boosting | corels | 360 | 360 | 0.953 | 0.0000 | [JSON](detailed_explanations\digits\gradient_boosting\corels_detailed_explanations.json) |
| digits | gradient_boosting | feature_ablation | 360 | 360 | 0.953 | 0.0000 | [JSON](detailed_explanations\digits\gradient_boosting\feature_ablation_detailed_explanations.json) |
| digits | mlp | shap | 360 | 360 | 0.978 | 0.0000 | [JSON](detailed_explanations\digits\mlp\shap_detailed_explanations.json) |
| digits | mlp | lime | 360 | 360 | 0.978 | 0.0021 | [JSON](detailed_explanations\digits\mlp\lime_detailed_explanations.json) |
| digits | mlp | integrated_gradients | 360 | 360 | 0.978 | 0.0000 | [JSON](detailed_explanations\digits\mlp\integrated_gradients_detailed_explanations.json) |
| digits | mlp | causal_shap | 360 | 360 | 0.978 | 0.0000 | [JSON](detailed_explanations\digits\mlp\causal_shap_detailed_explanations.json) |
| digits | mlp | shapley_flow | 360 | 360 | 0.978 | 0.0000 | [JSON](detailed_explanations\digits\mlp\shapley_flow_detailed_explanations.json) |
| digits | mlp | shap_interactive | 360 | 360 | 0.978 | 0.0000 | [JSON](detailed_explanations\digits\mlp\shap_interactive_detailed_explanations.json) |
| digits | mlp | prototype | 360 | 360 | 0.978 | 0.0000 | [JSON](detailed_explanations\digits\mlp\prototype_detailed_explanations.json) |
| digits | mlp | counterfactual | 360 | 360 | 0.978 | 0.0000 | [JSON](detailed_explanations\digits\mlp\counterfactual_detailed_explanations.json) |
| digits | mlp | influence_functions | 360 | 360 | 0.978 | 0.0000 | [JSON](detailed_explanations\digits\mlp\influence_functions_detailed_explanations.json) |
| digits | mlp | bayesian_rule_list | 360 | 360 | 0.978 | 0.0000 | [JSON](detailed_explanations\digits\mlp\bayesian_rule_list_detailed_explanations.json) |
| digits | mlp | corels | 360 | 360 | 0.978 | 0.0000 | [JSON](detailed_explanations\digits\mlp\corels_detailed_explanations.json) |
| digits | mlp | feature_ablation | 360 | 360 | 0.978 | 0.0000 | [JSON](detailed_explanations\digits\mlp\feature_ablation_detailed_explanations.json) |
| digits | linear_regression | lime | 360 | 360 | 0.242 | 0.0156 | [JSON](detailed_explanations\digits\linear_regression\lime_detailed_explanations.json) |
| digits | linear_regression | causal_shap | 360 | 360 | 0.242 | 0.0000 | [JSON](detailed_explanations\digits\linear_regression\causal_shap_detailed_explanations.json) |
| digits | linear_regression | shap_interactive | 360 | 360 | 0.242 | 0.0000 | [JSON](detailed_explanations\digits\linear_regression\shap_interactive_detailed_explanations.json) |
| digits | linear_regression | prototype | 360 | 360 | 0.242 | 0.0000 | [JSON](detailed_explanations\digits\linear_regression\prototype_detailed_explanations.json) |
| digits | linear_regression | counterfactual | 360 | 360 | 0.242 | 0.0000 | [JSON](detailed_explanations\digits\linear_regression\counterfactual_detailed_explanations.json) |
| digits | linear_regression | bayesian_rule_list | 360 | 360 | 0.242 | 0.0000 | [JSON](detailed_explanations\digits\linear_regression\bayesian_rule_list_detailed_explanations.json) |
| digits | linear_regression | corels | 360 | 360 | 0.242 | 0.0000 | [JSON](detailed_explanations\digits\linear_regression\corels_detailed_explanations.json) |
| digits | linear_regression | feature_ablation | 360 | 360 | 0.242 | 0.1842 | [JSON](detailed_explanations\digits\linear_regression\feature_ablation_detailed_explanations.json) |
| digits | logistic_regression | lime | 360 | 360 | 0.972 | 0.0030 | [JSON](detailed_explanations\digits\logistic_regression\lime_detailed_explanations.json) |
| digits | logistic_regression | causal_shap | 360 | 360 | 0.972 | 0.0000 | [JSON](detailed_explanations\digits\logistic_regression\causal_shap_detailed_explanations.json) |
| digits | logistic_regression | shap_interactive | 360 | 360 | 0.972 | 0.0000 | [JSON](detailed_explanations\digits\logistic_regression\shap_interactive_detailed_explanations.json) |
| digits | logistic_regression | prototype | 360 | 360 | 0.972 | 0.0000 | [JSON](detailed_explanations\digits\logistic_regression\prototype_detailed_explanations.json) |
| digits | logistic_regression | counterfactual | 360 | 360 | 0.972 | 0.0000 | [JSON](detailed_explanations\digits\logistic_regression\counterfactual_detailed_explanations.json) |
| digits | logistic_regression | influence_functions | 360 | 360 | 0.972 | 0.0000 | [JSON](detailed_explanations\digits\logistic_regression\influence_functions_detailed_explanations.json) |
| digits | logistic_regression | bayesian_rule_list | 360 | 360 | 0.972 | 0.0000 | [JSON](detailed_explanations\digits\logistic_regression\bayesian_rule_list_detailed_explanations.json) |
| digits | logistic_regression | corels | 360 | 360 | 0.972 | 0.0000 | [JSON](detailed_explanations\digits\logistic_regression\corels_detailed_explanations.json) |
| digits | logistic_regression | feature_ablation | 360 | 360 | 0.972 | 0.0000 | [JSON](detailed_explanations\digits\logistic_regression\feature_ablation_detailed_explanations.json) |
| mnist | cnn | prototype | 200 | 200 | 0.975 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\prototype_detailed_explanations.json) |
| mnist | cnn | counterfactual | 200 | 200 | 0.975 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\counterfactual_detailed_explanations.json) |
| mnist | cnn | tcav | 200 | 200 | 0.975 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\tcav_detailed_explanations.json) |
| mnist | cnn | concept_bottleneck | 200 | 200 | 0.975 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\concept_bottleneck_detailed_explanations.json) |
| mnist | cnn | occlusion | 200 | 200 | 0.975 | 0.0000 | [JSON](detailed_explanations\mnist\cnn\occlusion_detailed_explanations.json) |
| mnist | vit | tcav | 200 | 200 | 0.710 | 0.0000 | [JSON](detailed_explanations\mnist\vit\tcav_detailed_explanations.json) |
| mnist | vit | concept_bottleneck | 200 | 200 | 0.710 | 0.0000 | [JSON](detailed_explanations\mnist\vit\concept_bottleneck_detailed_explanations.json) |
| mnist | vit | occlusion | 200 | 200 | 0.710 | 0.0000 | [JSON](detailed_explanations\mnist\vit\occlusion_detailed_explanations.json) |
| mnist | resnet | prototype | 200 | 200 | 0.930 | 0.0000 | [JSON](detailed_explanations\mnist\resnet\prototype_detailed_explanations.json) |
| mnist | resnet | counterfactual | 200 | 200 | 0.930 | 0.0000 | [JSON](detailed_explanations\mnist\resnet\counterfactual_detailed_explanations.json) |
| cifar10 | cnn | prototype | 400 | 400 | 0.512 | 0.0000 | [JSON](detailed_explanations\cifar10\cnn\prototype_detailed_explanations.json) |
| cifar10 | cnn | counterfactual | 400 | 400 | 0.512 | 0.0000 | [JSON](detailed_explanations\cifar10\cnn\counterfactual_detailed_explanations.json) |
| cifar10 | cnn | tcav | 400 | 400 | 0.512 | 0.0000 | [JSON](detailed_explanations\cifar10\cnn\tcav_detailed_explanations.json) |
| cifar10 | cnn | concept_bottleneck | 400 | 400 | 0.512 | 0.0000 | [JSON](detailed_explanations\cifar10\cnn\concept_bottleneck_detailed_explanations.json) |
| cifar10 | cnn | occlusion | 400 | 400 | 0.512 | 0.0000 | [JSON](detailed_explanations\cifar10\cnn\occlusion_detailed_explanations.json) |
| cifar10 | vit | prototype | 400 | 400 | 0.253 | 0.0000 | [JSON](detailed_explanations\cifar10\vit\prototype_detailed_explanations.json) |
| cifar10 | vit | counterfactual | 400 | 400 | 0.253 | 0.0000 | [JSON](detailed_explanations\cifar10\vit\counterfactual_detailed_explanations.json) |
| cifar10 | vit | tcav | 400 | 400 | 0.253 | 0.0000 | [JSON](detailed_explanations\cifar10\vit\tcav_detailed_explanations.json) |
| cifar10 | vit | concept_bottleneck | 400 | 400 | 0.253 | 0.0000 | [JSON](detailed_explanations\cifar10\vit\concept_bottleneck_detailed_explanations.json) |
| cifar10 | vit | occlusion | 400 | 400 | 0.253 | 0.0000 | [JSON](detailed_explanations\cifar10\vit\occlusion_detailed_explanations.json) |
| cifar10 | resnet | prototype | 400 | 400 | 0.395 | 0.0000 | [JSON](detailed_explanations\cifar10\resnet\prototype_detailed_explanations.json) |
| cifar10 | resnet | counterfactual | 400 | 400 | 0.395 | 0.0000 | [JSON](detailed_explanations\cifar10\resnet\counterfactual_detailed_explanations.json) |
| fashion_mnist | cnn | prototype | 400 | 400 | 0.845 | 0.0000 | [JSON](detailed_explanations\fashion_mnist\cnn\prototype_detailed_explanations.json) |
| fashion_mnist | cnn | counterfactual | 400 | 400 | 0.845 | 0.0000 | [JSON](detailed_explanations\fashion_mnist\cnn\counterfactual_detailed_explanations.json) |
| fashion_mnist | cnn | tcav | 400 | 400 | 0.845 | 0.0000 | [JSON](detailed_explanations\fashion_mnist\cnn\tcav_detailed_explanations.json) |
| fashion_mnist | cnn | concept_bottleneck | 400 | 400 | 0.845 | 0.0000 | [JSON](detailed_explanations\fashion_mnist\cnn\concept_bottleneck_detailed_explanations.json) |
| fashion_mnist | cnn | occlusion | 400 | 400 | 0.845 | 0.0000 | [JSON](detailed_explanations\fashion_mnist\cnn\occlusion_detailed_explanations.json) |
| fashion_mnist | vit | tcav | 400 | 400 | 0.710 | 0.0000 | [JSON](detailed_explanations\fashion_mnist\vit\tcav_detailed_explanations.json) |
| fashion_mnist | vit | concept_bottleneck | 400 | 400 | 0.710 | 0.0000 | [JSON](detailed_explanations\fashion_mnist\vit\concept_bottleneck_detailed_explanations.json) |
| fashion_mnist | vit | occlusion | 400 | 400 | 0.710 | 0.0000 | [JSON](detailed_explanations\fashion_mnist\vit\occlusion_detailed_explanations.json) |
| fashion_mnist | resnet | prototype | 400 | 400 | 0.757 | 0.0000 | [JSON](detailed_explanations\fashion_mnist\resnet\prototype_detailed_explanations.json) |
| fashion_mnist | resnet | counterfactual | 400 | 400 | 0.757 | 0.0000 | [JSON](detailed_explanations\fashion_mnist\resnet\counterfactual_detailed_explanations.json) |
| imdb | bert | lime | 200 | 200 | 0.810 | 0.0200 | [JSON](detailed_explanations\imdb\bert\lime_detailed_explanations.json) |
| imdb | bert | text_occlusion | 200 | 200 | 0.810 | 0.0000 | [JSON](detailed_explanations\imdb\bert\text_occlusion_detailed_explanations.json) |
| imdb | bert | attention_visualization | 200 | 200 | 0.810 | 0.0104 | [JSON](detailed_explanations\imdb\bert\attention_visualization_detailed_explanations.json) |
| imdb | lstm | lime | 200 | 200 | 0.815 | 0.0200 | [JSON](detailed_explanations\imdb\lstm\lime_detailed_explanations.json) |
| imdb | lstm | text_occlusion | 200 | 200 | 0.815 | 0.0000 | [JSON](detailed_explanations\imdb\lstm\text_occlusion_detailed_explanations.json) |
| imdb | lstm | attention_visualization | 200 | 200 | 0.815 | 0.0104 | [JSON](detailed_explanations\imdb\lstm\attention_visualization_detailed_explanations.json) |
| imdb | roberta | lime | 200 | 200 | 0.870 | 0.0200 | [JSON](detailed_explanations\imdb\roberta\lime_detailed_explanations.json) |
| imdb | roberta | text_occlusion | 200 | 200 | 0.870 | 0.0000 | [JSON](detailed_explanations\imdb\roberta\text_occlusion_detailed_explanations.json) |
| imdb | roberta | attention_visualization | 200 | 200 | 0.870 | 0.0104 | [JSON](detailed_explanations\imdb\roberta\attention_visualization_detailed_explanations.json) |
| imdb | naive_bayes_text | lime | 200 | 200 | 0.805 | 0.0200 | [JSON](detailed_explanations\imdb\naive_bayes_text\lime_detailed_explanations.json) |
| imdb | naive_bayes_text | text_occlusion | 200 | 200 | 0.805 | 0.0000 | [JSON](detailed_explanations\imdb\naive_bayes_text\text_occlusion_detailed_explanations.json) |
| imdb | naive_bayes_text | attention_visualization | 200 | 200 | 0.805 | 0.0104 | [JSON](detailed_explanations\imdb\naive_bayes_text\attention_visualization_detailed_explanations.json) |
| imdb | svm_text | lime | 200 | 200 | 0.805 | 0.0200 | [JSON](detailed_explanations\imdb\svm_text\lime_detailed_explanations.json) |
| imdb | svm_text | text_occlusion | 200 | 200 | 0.805 | 0.0000 | [JSON](detailed_explanations\imdb\svm_text\text_occlusion_detailed_explanations.json) |
| imdb | svm_text | attention_visualization | 200 | 200 | 0.805 | 0.0104 | [JSON](detailed_explanations\imdb\svm_text\attention_visualization_detailed_explanations.json) |
| imdb | xgboost_text | lime | 200 | 200 | 0.790 | 0.0200 | [JSON](detailed_explanations\imdb\xgboost_text\lime_detailed_explanations.json) |
| imdb | xgboost_text | text_occlusion | 200 | 200 | 0.790 | 0.0000 | [JSON](detailed_explanations\imdb\xgboost_text\text_occlusion_detailed_explanations.json) |
| imdb | xgboost_text | attention_visualization | 200 | 200 | 0.790 | 0.0104 | [JSON](detailed_explanations\imdb\xgboost_text\attention_visualization_detailed_explanations.json) |
| 20newsgroups | bert | lime | 200 | 200 | 0.715 | 0.0200 | [JSON](detailed_explanations\20newsgroups\bert\lime_detailed_explanations.json) |
| 20newsgroups | bert | text_occlusion | 200 | 200 | 0.715 | 0.5000 | [JSON](detailed_explanations\20newsgroups\bert\text_occlusion_detailed_explanations.json) |
| 20newsgroups | bert | attention_visualization | 200 | 200 | 0.715 | 0.0411 | [JSON](detailed_explanations\20newsgroups\bert\attention_visualization_detailed_explanations.json) |
| 20newsgroups | lstm | lime | 200 | 200 | 0.710 | 0.0200 | [JSON](detailed_explanations\20newsgroups\lstm\lime_detailed_explanations.json) |
| 20newsgroups | lstm | text_occlusion | 200 | 200 | 0.710 | 1.5000 | [JSON](detailed_explanations\20newsgroups\lstm\text_occlusion_detailed_explanations.json) |
| 20newsgroups | lstm | attention_visualization | 200 | 200 | 0.710 | 0.0445 | [JSON](detailed_explanations\20newsgroups\lstm\attention_visualization_detailed_explanations.json) |
| 20newsgroups | roberta | lime | 200 | 200 | 0.840 | 0.0200 | [JSON](detailed_explanations\20newsgroups\roberta\lime_detailed_explanations.json) |
| 20newsgroups | roberta | text_occlusion | 200 | 200 | 0.840 | 0.5000 | [JSON](detailed_explanations\20newsgroups\roberta\text_occlusion_detailed_explanations.json) |
| 20newsgroups | roberta | attention_visualization | 200 | 200 | 0.840 | 0.0379 | [JSON](detailed_explanations\20newsgroups\roberta\attention_visualization_detailed_explanations.json) |
| 20newsgroups | naive_bayes_text | lime | 200 | 200 | 0.735 | 0.0200 | [JSON](detailed_explanations\20newsgroups\naive_bayes_text\lime_detailed_explanations.json) |
| 20newsgroups | naive_bayes_text | text_occlusion | 200 | 200 | 0.735 | 1.5000 | [JSON](detailed_explanations\20newsgroups\naive_bayes_text\text_occlusion_detailed_explanations.json) |
| 20newsgroups | naive_bayes_text | attention_visualization | 200 | 200 | 0.735 | 0.0480 | [JSON](detailed_explanations\20newsgroups\naive_bayes_text\attention_visualization_detailed_explanations.json) |
| 20newsgroups | svm_text | lime | 200 | 200 | 0.795 | 0.0200 | [JSON](detailed_explanations\20newsgroups\svm_text\lime_detailed_explanations.json) |
| 20newsgroups | svm_text | text_occlusion | 200 | 200 | 0.795 | 1.5000 | [JSON](detailed_explanations\20newsgroups\svm_text\text_occlusion_detailed_explanations.json) |
| 20newsgroups | svm_text | attention_visualization | 200 | 200 | 0.795 | 0.0399 | [JSON](detailed_explanations\20newsgroups\svm_text\attention_visualization_detailed_explanations.json) |
| 20newsgroups | xgboost_text | lime | 200 | 200 | 0.705 | 0.0200 | [JSON](detailed_explanations\20newsgroups\xgboost_text\lime_detailed_explanations.json) |
| 20newsgroups | xgboost_text | text_occlusion | 200 | 200 | 0.705 | 1.5000 | [JSON](detailed_explanations\20newsgroups\xgboost_text\text_occlusion_detailed_explanations.json) |
| 20newsgroups | xgboost_text | attention_visualization | 200 | 200 | 0.705 | 0.0383 | [JSON](detailed_explanations\20newsgroups\xgboost_text\attention_visualization_detailed_explanations.json) |
| ag_news | bert | lime | 200 | 200 | 0.790 | 0.0200 | [JSON](detailed_explanations\ag_news\bert\lime_detailed_explanations.json) |
| ag_news | bert | text_occlusion | 200 | 200 | 0.790 | 0.0000 | [JSON](detailed_explanations\ag_news\bert\text_occlusion_detailed_explanations.json) |
| ag_news | bert | attention_visualization | 200 | 200 | 0.790 | 0.0656 | [JSON](detailed_explanations\ag_news\bert\attention_visualization_detailed_explanations.json) |
| ag_news | lstm | lime | 200 | 200 | 0.780 | 0.0200 | [JSON](detailed_explanations\ag_news\lstm\lime_detailed_explanations.json) |
| ag_news | lstm | text_occlusion | 200 | 200 | 0.780 | 0.0000 | [JSON](detailed_explanations\ag_news\lstm\text_occlusion_detailed_explanations.json) |
| ag_news | lstm | attention_visualization | 200 | 200 | 0.780 | 0.0617 | [JSON](detailed_explanations\ag_news\lstm\attention_visualization_detailed_explanations.json) |
| ag_news | roberta | lime | 200 | 200 | 0.900 | 0.0200 | [JSON](detailed_explanations\ag_news\roberta\lime_detailed_explanations.json) |
| ag_news | roberta | text_occlusion | 200 | 200 | 0.900 | 0.0000 | [JSON](detailed_explanations\ag_news\roberta\text_occlusion_detailed_explanations.json) |
| ag_news | roberta | attention_visualization | 200 | 200 | 0.900 | 0.0667 | [JSON](detailed_explanations\ag_news\roberta\attention_visualization_detailed_explanations.json) |
| ag_news | naive_bayes_text | lime | 200 | 200 | 0.815 | 0.0200 | [JSON](detailed_explanations\ag_news\naive_bayes_text\lime_detailed_explanations.json) |
| ag_news | naive_bayes_text | text_occlusion | 200 | 200 | 0.815 | 0.0000 | [JSON](detailed_explanations\ag_news\naive_bayes_text\text_occlusion_detailed_explanations.json) |
| ag_news | naive_bayes_text | attention_visualization | 200 | 200 | 0.815 | 0.0625 | [JSON](detailed_explanations\ag_news\naive_bayes_text\attention_visualization_detailed_explanations.json) |
| ag_news | svm_text | lime | 200 | 200 | 0.790 | 0.0200 | [JSON](detailed_explanations\ag_news\svm_text\lime_detailed_explanations.json) |
| ag_news | svm_text | text_occlusion | 200 | 200 | 0.790 | 0.0000 | [JSON](detailed_explanations\ag_news\svm_text\text_occlusion_detailed_explanations.json) |
| ag_news | svm_text | attention_visualization | 200 | 200 | 0.790 | 0.0641 | [JSON](detailed_explanations\ag_news\svm_text\attention_visualization_detailed_explanations.json) |
| ag_news | xgboost_text | lime | 200 | 200 | 0.710 | 0.0200 | [JSON](detailed_explanations\ag_news\xgboost_text\lime_detailed_explanations.json) |
| ag_news | xgboost_text | text_occlusion | 200 | 200 | 0.710 | 0.0000 | [JSON](detailed_explanations\ag_news\xgboost_text\text_occlusion_detailed_explanations.json) |
| ag_news | xgboost_text | attention_visualization | 200 | 200 | 0.710 | 0.0680 | [JSON](detailed_explanations\ag_news\xgboost_text\attention_visualization_detailed_explanations.json) |

## Model Performance Analysis by Dataset

### 20newsgroups

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| bert | 0.9380 | 0.7150 | N/A | N/A |
| lstm | 0.8950 | 0.7100 | N/A | N/A |
| roberta | 0.9790 | 0.8400 | N/A | N/A |
| naive_bayes_text | 0.9370 | 0.7350 | N/A | N/A |
| svm_text | 0.9800 | 0.7950 | N/A | N/A |
| xgboost_text | 0.9480 | 0.7050 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| bert | lime | 0.1026 | 0.6400 | 0.0000 |
| bert | text_occlusion | 0.0376 | 0.0000 | 0.0000 |
| bert | attention_visualization | 0.0988 | 0.0000 | 0.0000 |
| lstm | lime | 0.0949 | 0.6800 | 0.0000 |
| lstm | text_occlusion | 0.0409 | 0.0000 | 0.0000 |
| lstm | attention_visualization | 0.1040 | 0.0000 | 0.0000 |
| roberta | lime | 52.9093 | 0.7800 | 0.0000 |
| roberta | text_occlusion | 10.3211 | 0.0000 | 0.0000 |
| roberta | attention_visualization | 33.8771 | 0.0000 | 0.0000 |
| naive_bayes_text | lime | 0.1124 | 0.6800 | 0.0000 |
| naive_bayes_text | text_occlusion | 0.0508 | 0.0000 | 0.0000 |
| naive_bayes_text | attention_visualization | 0.1222 | 0.0000 | 0.0000 |
| svm_text | lime | 0.1893 | 0.8000 | 0.0000 |
| svm_text | text_occlusion | 0.0810 | 0.0000 | 0.0000 |
| svm_text | attention_visualization | 0.2035 | 0.0000 | 0.0000 |
| xgboost_text | lime | 0.2105 | 0.7000 | 0.0000 |
| xgboost_text | text_occlusion | 0.0772 | 0.0000 | 0.0000 |
| xgboost_text | attention_visualization | 0.1991 | 0.0000 | 0.0000 |

### adult_income

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| decision_tree | 0.8405 | 0.8326 | N/A | N/A |
| random_forest | 0.8425 | 0.8333 | N/A | N/A |
| gradient_boosting | 0.8387 | 0.8356 | N/A | N/A |
| mlp | 0.8257 | 0.8236 | N/A | N/A |
| linear_regression | 0.7913 | 0.7915 | N/A | N/A |
| logistic_regression | 0.8089 | 0.8087 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| decision_tree | shap | 0.0011 | 0.1900 | 0.0200 |
| decision_tree | lime | 0.0230 | 0.1000 | 0.0300 |
| decision_tree | causal_shap | 0.0179 | 0.2400 | 0.0200 |
| decision_tree | shapley_flow | 0.0088 | 0.1000 | 0.0000 |
| decision_tree | shap_interactive | 0.0039 | 0.4000 | 0.0000 |
| decision_tree | prototype | 0.0010 | 0.6900 | 0.8228 |
| decision_tree | counterfactual | 0.0006 | 0.6700 | 0.1743 |
| decision_tree | bayesian_rule_list | 0.0007 | 0.0000 | 0.0000 |
| decision_tree | corels | 0.0004 | 0.0000 | 0.0000 |
| decision_tree | feature_ablation | 0.0007 | 0.0000 | 0.0000 |
| random_forest | shap | 0.0309 | 0.1900 | 0.0200 |
| random_forest | lime | 0.0305 | 0.1000 | 0.0200 |
| random_forest | causal_shap | 0.6718 | 0.2400 | 0.0200 |
| random_forest | shapley_flow | 0.3408 | 0.1333 | 0.0000 |
| random_forest | shap_interactive | 0.1759 | 0.6000 | 0.0000 |
| random_forest | prototype | 0.0045 | 0.7150 | 0.8098 |
| random_forest | counterfactual | 0.0036 | 0.6850 | 0.1959 |
| random_forest | bayesian_rule_list | 0.0036 | 0.0000 | 0.0000 |
| random_forest | corels | 0.0030 | 0.0000 | 0.0000 |
| random_forest | feature_ablation | 0.0171 | 0.0000 | 0.0000 |
| gradient_boosting | shap | 0.0019 | 0.2100 | 0.0300 |
| gradient_boosting | lime | 0.0090 | 0.1400 | 0.0300 |
| gradient_boosting | causal_shap | 0.0401 | 0.2600 | 0.0200 |
| gradient_boosting | shap_interactive | 0.0069 | 0.4000 | 0.0000 |
| gradient_boosting | prototype | 0.0008 | 0.6900 | 0.8163 |
| gradient_boosting | counterfactual | 0.0006 | 0.7250 | 0.2130 |
| gradient_boosting | bayesian_rule_list | 0.0007 | 0.0000 | 0.0000 |
| gradient_boosting | corels | 0.0006 | 0.0000 | 0.0000 |
| gradient_boosting | feature_ablation | 0.0009 | 0.0000 | 0.0000 |
| mlp | shap | 0.0023 | 0.2200 | 0.0250 |
| mlp | lime | 0.0188 | 0.0800 | 0.0317 |
| mlp | integrated_gradients | 0.0432 | 0.0000 | 0.0000 |
| mlp | causal_shap | 0.0178 | 0.2400 | 0.0090 |
| mlp | shapley_flow | 0.0075 | 0.1000 | 0.0000 |
| mlp | shap_interactive | 0.0041 | 0.4000 | 0.0000 |
| mlp | prototype | 0.0008 | 0.7000 | 0.7951 |
| mlp | counterfactual | 0.0005 | 0.6950 | 0.1871 |
| mlp | influence_functions | 0.0183 | 0.0000 | 0.0000 |
| mlp | bayesian_rule_list | 0.0007 | 0.0000 | 0.0000 |
| mlp | corels | 0.0004 | 0.0000 | 0.0000 |
| mlp | feature_ablation | 0.0005 | 0.0000 | 0.0000 |
| linear_regression | lime | 0.0096 | 0.0600 | 0.0000 |
| linear_regression | causal_shap | 0.0206 | 0.1000 | 0.0100 |
| linear_regression | shap_interactive | 0.0042 | 0.0000 | 0.0000 |
| linear_regression | prototype | 0.0008 | 0.5850 | 0.5725 |
| linear_regression | counterfactual | 0.0005 | 0.6000 | 0.4333 |
| linear_regression | bayesian_rule_list | 0.0005 | 0.0000 | 0.0000 |
| linear_regression | corels | 0.0003 | 0.0000 | 0.0000 |
| linear_regression | feature_ablation | 0.0005 | 0.0000 | 0.0000 |
| logistic_regression | lime | 0.0087 | 0.0400 | 0.0000 |
| logistic_regression | causal_shap | 0.0169 | 0.1400 | 0.0400 |
| logistic_regression | shap_interactive | 0.0038 | 0.2000 | 0.0000 |
| logistic_regression | prototype | 0.0007 | 0.6550 | 0.7932 |
| logistic_regression | counterfactual | 0.0005 | 0.6850 | 0.1945 |
| logistic_regression | influence_functions | 0.0141 | 0.0000 | 0.0000 |
| logistic_regression | bayesian_rule_list | 0.0005 | 0.0000 | 0.0000 |
| logistic_regression | corels | 0.0003 | 0.0000 | 0.0000 |
| logistic_regression | feature_ablation | 0.0003 | 0.0000 | 0.0000 |

### ag_news

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| bert | 0.9640 | 0.7900 | N/A | N/A |
| lstm | 0.9350 | 0.7800 | N/A | N/A |
| roberta | 0.9770 | 0.9000 | N/A | N/A |
| naive_bayes_text | 0.9710 | 0.8150 | N/A | N/A |
| svm_text | 0.9930 | 0.7900 | N/A | N/A |
| xgboost_text | 0.9750 | 0.7100 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| bert | lime | 0.0879 | 0.8400 | 0.0000 |
| bert | text_occlusion | 0.0215 | 0.0000 | 0.0000 |
| bert | attention_visualization | 0.0653 | 0.0000 | 0.0000 |
| lstm | lime | 0.0924 | 0.8200 | 0.0000 |
| lstm | text_occlusion | 0.0189 | 0.0000 | 0.0000 |
| lstm | attention_visualization | 0.0758 | 0.0000 | 0.0000 |
| roberta | lime | 15.3733 | 0.8800 | 0.0000 |
| roberta | text_occlusion | 4.1286 | 0.0000 | 0.0000 |
| roberta | attention_visualization | 13.8400 | 0.0000 | 0.0000 |
| naive_bayes_text | lime | 0.1088 | 0.8600 | 0.0000 |
| naive_bayes_text | text_occlusion | 0.0185 | 0.0000 | 0.0000 |
| naive_bayes_text | attention_visualization | 0.0738 | 0.0000 | 0.0000 |
| svm_text | lime | 0.1527 | 0.8600 | 0.0000 |
| svm_text | text_occlusion | 0.0361 | 0.0000 | 0.0000 |
| svm_text | attention_visualization | 0.1250 | 0.0000 | 0.0000 |
| xgboost_text | lime | 0.2081 | 0.7000 | 0.0000 |
| xgboost_text | text_occlusion | 0.0411 | 0.0000 | 0.0000 |
| xgboost_text | attention_visualization | 0.1494 | 0.0000 | 0.0000 |

### breast_cancer

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| decision_tree | 1.0000 | 0.9123 | N/A | N/A |
| random_forest | 1.0000 | 0.9561 | N/A | N/A |
| gradient_boosting | 1.0000 | 0.9561 | N/A | N/A |
| mlp | 1.0000 | 0.9474 | N/A | N/A |
| linear_regression | 0.9692 | 0.9561 | N/A | N/A |
| logistic_regression | 0.9890 | 0.9825 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| decision_tree | shap | 0.0022 | 0.1900 | 0.0000 |
| decision_tree | lime | 0.0082 | 0.0800 | 0.0000 |
| decision_tree | causal_shap | 0.0911 | 0.4000 | 0.0067 |
| decision_tree | shapley_flow | 0.0389 | 0.0000 | 0.0000 |
| decision_tree | shap_interactive | 0.0047 | 0.6000 | 0.0000 |
| decision_tree | prototype | 0.0001 | 0.9123 | 0.9518 |
| decision_tree | counterfactual | 0.0001 | 0.9123 | 0.0798 |
| decision_tree | bayesian_rule_list | 0.0018 | 0.0000 | 0.0000 |
| decision_tree | corels | 0.0010 | 0.0000 | 0.0000 |
| decision_tree | feature_ablation | 0.0019 | 0.0000 | 0.0000 |
| random_forest | shap | 0.0946 | 0.0200 | 0.0000 |
| random_forest | lime | 0.0177 | 0.0000 | 0.0000 |
| random_forest | causal_shap | 4.0582 | 0.0400 | 0.0000 |
| random_forest | shapley_flow | 1.9812 | 0.0000 | 0.0000 |
| random_forest | shap_interactive | 0.2541 | 0.0000 | 0.0000 |
| random_forest | prototype | 0.0033 | 0.9561 | 0.9240 |
| random_forest | counterfactual | 0.0035 | 0.9561 | 0.1490 |
| random_forest | bayesian_rule_list | 0.0058 | 0.0000 | 0.0000 |
| random_forest | corels | 0.0052 | 0.0000 | 0.0000 |
| random_forest | feature_ablation | 0.1065 | 0.0000 | 0.0000 |
| gradient_boosting | shap | 0.0063 | 0.0800 | 0.0000 |
| gradient_boosting | lime | 0.0094 | 0.0000 | 0.0000 |
| gradient_boosting | causal_shap | 0.2261 | 0.0800 | 0.0000 |
| gradient_boosting | shap_interactive | 0.0168 | 0.0000 | 0.0000 |
| gradient_boosting | prototype | 0.0002 | 0.9561 | 0.9511 |
| gradient_boosting | counterfactual | 0.0003 | 0.9561 | 0.0961 |
| gradient_boosting | bayesian_rule_list | 0.0022 | 0.0000 | 0.0000 |
| gradient_boosting | corels | 0.0016 | 0.0000 | 0.0000 |
| gradient_boosting | feature_ablation | 0.0053 | 0.0000 | 0.0000 |
| mlp | shap | 0.0034 | 0.0600 | 0.0000 |
| mlp | lime | 0.0095 | 0.0400 | 0.0000 |
| mlp | integrated_gradients | 0.2721 | 0.0000 | 0.0000 |
| mlp | causal_shap | 0.1250 | 0.1000 | 0.0057 |
| mlp | shapley_flow | 0.0519 | 0.0333 | 0.0000 |
| mlp | shap_interactive | 0.0063 | 0.2000 | 0.0000 |
| mlp | prototype | 0.0002 | 0.9474 | 0.9459 |
| mlp | counterfactual | 0.0002 | 0.9474 | 0.0956 |
| mlp | influence_functions | 0.0198 | 0.0000 | 0.0000 |
| mlp | bayesian_rule_list | 0.0021 | 0.0000 | 0.0000 |
| mlp | corels | 0.0012 | 0.0000 | 0.0000 |
| mlp | feature_ablation | 0.0030 | 0.0000 | 0.0000 |
| linear_regression | lime | 0.0123 | 0.0000 | 0.0017 |
| linear_regression | causal_shap | 0.0988 | 0.2400 | 0.0013 |
| linear_regression | shap_interactive | 0.0051 | 0.4000 | 0.0000 |
| linear_regression | prototype | 0.0002 | 0.9561 | 0.6966 |
| linear_regression | counterfactual | 0.0002 | 0.9561 | 0.4314 |
| linear_regression | bayesian_rule_list | 0.0021 | 0.0000 | 0.0000 |
| linear_regression | corels | 0.0018 | 0.0000 | 0.0000 |
| linear_regression | feature_ablation | 0.0019 | 0.0000 | 0.0000 |
| logistic_regression | lime | 0.0105 | 0.0200 | 0.0000 |
| logistic_regression | causal_shap | 0.0972 | 0.0400 | 0.0000 |
| logistic_regression | shap_interactive | 0.0062 | 0.0000 | 0.0000 |
| logistic_regression | prototype | 0.0001 | 0.9825 | 0.9331 |
| logistic_regression | counterfactual | 0.0001 | 0.9825 | 0.1252 |
| logistic_regression | influence_functions | 0.0233 | 0.0000 | 0.0000 |
| logistic_regression | bayesian_rule_list | 0.0019 | 0.0000 | 0.0000 |
| logistic_regression | corels | 0.0011 | 0.0000 | 0.0000 |
| logistic_regression | feature_ablation | 0.0020 | 0.0000 | 0.0000 |

### cifar10

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| cnn | 0.8715 | 0.5125 | N/A | N/A |
| vit | 0.3250 | 0.2525 | N/A | N/A |
| resnet | 0.9010 | 0.3950 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| cnn | prototype | 0.0038 | 0.4750 | 0.7854707 |
| cnn | counterfactual | 0.0467 | 0.4900 | 0.7617468 |
| cnn | tcav | 0.0000 | 0.0000 | 0.0000 |
| cnn | concept_bottleneck | 0.0000 | 0.0000 | 0.0000 |
| cnn | occlusion | 0.0914 | 0.0000 | 0.0000 |
| vit | prototype | 0.0049 | 0.1450 | 0.7489129 |
| vit | counterfactual | 0.0484 | 0.1300 | 0.8460481 |
| vit | tcav | 0.0000 | 0.0000 | 0.0000 |
| vit | concept_bottleneck | 0.0000 | 0.0000 | 0.0000 |
| vit | occlusion | 0.2949 | 0.0000 | 0.0000 |
| resnet | prototype | 0.0077 | 0.3950 | 0.74938685 |
| resnet | counterfactual | 0.0518 | 0.3950 | 0.66736954 |

### compas

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| decision_tree | 0.7375 | 0.6736 | N/A | N/A |
| random_forest | 0.7538 | 0.6826 | N/A | N/A |
| gradient_boosting | 0.7054 | 0.6951 | N/A | N/A |
| mlp | 0.6881 | 0.6854 | N/A | N/A |
| linear_regression | 0.6749 | 0.6868 | N/A | N/A |
| logistic_regression | 0.6767 | 0.6854 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| decision_tree | shap | 0.0006 | 0.6500 | 0.0300 |
| decision_tree | lime | 0.0091 | 0.3200 | 0.0800 |
| decision_tree | causal_shap | 0.0093 | 0.4800 | 0.0000 |
| decision_tree | shapley_flow | 0.0043 | 0.3333 | 0.0000 |
| decision_tree | shap_interactive | 0.0015 | 0.4000 | 0.0000 |
| decision_tree | prototype | 0.0002 | 0.6550 | 0.7376 |
| decision_tree | counterfactual | 0.0002 | 0.6250 | 0.2716 |
| decision_tree | bayesian_rule_list | 0.0004 | 0.0000 | 0.0000 |
| decision_tree | corels | 0.0002 | 0.0000 | 0.0000 |
| decision_tree | feature_ablation | 0.0003 | 0.0000 | 0.0000 |
| random_forest | shap | 0.0174 | 0.6300 | 0.0383 |
| random_forest | lime | 0.0180 | 0.3600 | 0.0300 |
| random_forest | causal_shap | 0.3482 | 0.4800 | 0.0300 |
| random_forest | shapley_flow | 0.1854 | 0.4333 | 0.0000 |
| random_forest | shap_interactive | 0.0540 | 0.4000 | 0.0000 |
| random_forest | prototype | 0.0035 | 0.6150 | 0.6974 |
| random_forest | counterfactual | 0.0055 | 0.6950 | 0.2975 |
| random_forest | bayesian_rule_list | 0.0051 | 0.0000 | 0.0000 |
| random_forest | corels | 0.0039 | 0.0000 | 0.0000 |
| random_forest | feature_ablation | 0.0200 | 0.0000 | 0.0000 |
| gradient_boosting | shap | 0.0013 | 0.6100 | 0.0250 |
| gradient_boosting | lime | 0.0125 | 0.4000 | 0.1400 |
| gradient_boosting | causal_shap | 0.0284 | 0.4600 | 0.0300 |
| gradient_boosting | shap_interactive | 0.0063 | 0.2000 | 0.0000 |
| gradient_boosting | prototype | 0.0005 | 0.6950 | 0.6932 |
| gradient_boosting | counterfactual | 0.0005 | 0.6450 | 0.3075 |
| gradient_boosting | bayesian_rule_list | 0.0011 | 0.0000 | 0.0000 |
| gradient_boosting | corels | 0.0005 | 0.0000 | 0.0000 |
| gradient_boosting | feature_ablation | 0.0007 | 0.0000 | 0.0000 |
| mlp | shap | 0.0024 | 0.5800 | 0.0100 |
| mlp | lime | 0.0091 | 0.0400 | 0.0000 |
| mlp | integrated_gradients | 0.0250 | 0.0000 | 0.0000 |
| mlp | causal_shap | 0.0109 | 0.3400 | 0.0000 |
| mlp | shapley_flow | 0.0066 | 0.2333 | 0.0000 |
| mlp | shap_interactive | 0.0017 | 0.0000 | 0.0000 |
| mlp | prototype | 0.0002 | 0.6700 | 0.6845 |
| mlp | counterfactual | 0.0004 | 0.6750 | 0.3109 |
| mlp | influence_functions | 0.0174 | 0.0000 | 0.0000 |
| mlp | bayesian_rule_list | 0.0004 | 0.0000 | 0.0000 |
| mlp | corels | 0.0002 | 0.0000 | 0.0000 |
| mlp | feature_ablation | 0.0003 | 0.0000 | 0.0000 |
| linear_regression | lime | 0.0092 | 0.1400 | 0.0100 |
| linear_regression | causal_shap | 0.0087 | 0.2800 | 0.0100 |
| linear_regression | shap_interactive | 0.0012 | 0.0000 | 0.0000 |
| linear_regression | prototype | 0.0002 | 0.6500 | 0.6079 |
| linear_regression | counterfactual | 0.0002 | 0.7100 | 0.3879 |
| linear_regression | bayesian_rule_list | 0.0004 | 0.0000 | 0.0000 |
| linear_regression | corels | 0.0002 | 0.0000 | 0.0000 |
| linear_regression | feature_ablation | 0.0005 | 0.0000 | 0.0000 |
| logistic_regression | lime | 0.0078 | 0.1600 | 0.0000 |
| logistic_regression | causal_shap | 0.0079 | 0.3000 | 0.0000 |
| logistic_regression | shap_interactive | 0.0035 | 0.0000 | 0.0000 |
| logistic_regression | prototype | 0.0002 | 0.6900 | 0.6496 |
| logistic_regression | counterfactual | 0.0002 | 0.6500 | 0.3619 |
| logistic_regression | influence_functions | 0.0145 | 0.0000 | 0.0000 |
| logistic_regression | bayesian_rule_list | 0.0004 | 0.0000 | 0.0000 |
| logistic_regression | corels | 0.0002 | 0.0000 | 0.0000 |
| logistic_regression | feature_ablation | 0.0002 | 0.0000 | 0.0000 |

### diabetes

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| decision_tree | 0.9858 | 0.4944 | N/A | N/A |
| random_forest | 0.9972 | 0.5843 | N/A | N/A |
| gradient_boosting | 0.9830 | 0.5393 | N/A | N/A |
| mlp | 0.9575 | 0.4494 | N/A | N/A |
| linear_regression | 0.0000 | 0.0000 | N/A | N/A |
| logistic_regression | 0.6459 | 0.6517 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| decision_tree | shap | 0.0010 | 0.7584 | 0.0375 |
| decision_tree | lime | 0.0090 | 0.2200 | 0.0467 |
| decision_tree | causal_shap | 0.0398 | 0.3900 | 0.0250 |
| decision_tree | shapley_flow | 0.0141 | 0.1333 | 0.0000 |
| decision_tree | shap_interactive | 0.0039 | 0.6000 | 0.0000 |
| decision_tree | prototype | 0.0001 | 0.4944 | 0.9553 |
| decision_tree | counterfactual | 0.0001 | 0.4944 | 0.0500 |
| decision_tree | bayesian_rule_list | 0.0009 | 0.0000 | 0.0000 |
| decision_tree | corels | 0.0006 | 0.0000 | 0.0000 |
| decision_tree | feature_ablation | 0.0008 | 0.0000 | 0.0000 |
| random_forest | shap | 0.0425 | 0.4270 | 0.0135 |
| random_forest | lime | 0.0250 | 0.0700 | 0.0000 |
| random_forest | causal_shap | 1.4198 | 0.1200 | 0.0022 |
| random_forest | shapley_flow | 0.6845 | 0.0667 | 0.0000 |
| random_forest | shap_interactive | 0.1771 | 0.1000 | 0.0000 |
| random_forest | prototype | 0.0032 | 0.5843 | 0.6618 |
| random_forest | counterfactual | 0.0033 | 0.5843 | 0.4042 |
| random_forest | bayesian_rule_list | 0.0037 | 0.0000 | 0.0000 |
| random_forest | corels | 0.0035 | 0.0000 | 0.0000 |
| random_forest | feature_ablation | 0.0392 | 0.0000 | 0.0000 |
| gradient_boosting | shap | 0.0065 | 0.4831 | 0.0328 |
| gradient_boosting | lime | 0.0111 | 0.1100 | 0.0210 |
| gradient_boosting | causal_shap | 0.2039 | 0.3700 | 0.0133 |
| gradient_boosting | shap_interactive | 0.0270 | 0.2000 | 0.0000 |
| gradient_boosting | prototype | 0.0006 | 0.5393 | 0.7733 |
| gradient_boosting | counterfactual | 0.0007 | 0.5393 | 0.2912 |
| gradient_boosting | bayesian_rule_list | 0.0013 | 0.0000 | 0.0000 |
| gradient_boosting | corels | 0.0009 | 0.0000 | 0.0000 |
| gradient_boosting | feature_ablation | 0.0052 | 0.0000 | 0.0000 |
| mlp | shap | 0.0013 | 0.6854 | 0.0094 |
| mlp | lime | 0.0091 | 0.1400 | 0.0022 |
| mlp | integrated_gradients | 0.0830 | 0.0000 | 0.0000 |
| mlp | causal_shap | 0.0379 | 0.3900 | 0.0069 |
| mlp | shapley_flow | 0.0182 | 0.1000 | 0.0000 |
| mlp | shap_interactive | 0.0052 | 0.2000 | 0.0000 |
| mlp | prototype | 0.0001 | 0.4494 | 0.8152 |
| mlp | counterfactual | 0.0002 | 0.4494 | 0.2412 |
| mlp | influence_functions | 0.0197 | 0.0000 | 0.0000 |
| mlp | bayesian_rule_list | 0.0009 | 0.0000 | 0.0000 |
| mlp | corels | 0.0005 | 0.0000 | 0.0000 |
| mlp | feature_ablation | 0.0011 | 0.0000 | 0.0000 |
| linear_regression | lime | 0.0132 | 0.2881 | 0.7549 |
| linear_regression | causal_shap | 0.0270 | 0.5771 | 0.4460 |
| linear_regression | shap_interactive | 0.0030 | 0.6934 | 0.3600 |
| linear_regression | prototype | 0.0002 | 0.5506 | 0.0000 |
| linear_regression | counterfactual | 0.0001 | 0.5506 | 0.4054 |
| linear_regression | bayesian_rule_list | 0.0008 | 0.0000 | 0.0000 |
| linear_regression | corels | 0.0004 | 0.0000 | 0.0000 |
| linear_regression | feature_ablation | 0.0006 | 0.0000 | 0.0000 |
| logistic_regression | lime | 0.0097 | 0.0600 | 0.0000 |
| logistic_regression | causal_shap | 0.0287 | 0.2600 | 0.0000 |
| logistic_regression | shap_interactive | 0.0033 | 0.1000 | 0.0000 |
| logistic_regression | prototype | 0.0001 | 0.6517 | 0.6880 |
| logistic_regression | counterfactual | 0.0001 | 0.6517 | 0.3780 |
| logistic_regression | influence_functions | 0.0144 | 0.0000 | 0.0000 |
| logistic_regression | bayesian_rule_list | 0.0007 | 0.0000 | 0.0000 |
| logistic_regression | corels | 0.0004 | 0.0000 | 0.0000 |
| logistic_regression | feature_ablation | 0.0008 | 0.0000 | 0.0000 |

### digits

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| decision_tree | 0.9875 | 0.8083 | N/A | N/A |
| random_forest | 1.0000 | 0.9611 | N/A | N/A |
| gradient_boosting | 1.0000 | 0.9528 | N/A | N/A |
| mlp | 1.0000 | 0.9778 | N/A | N/A |
| linear_regression | 0.0000 | 0.0000 | N/A | N/A |
| logistic_regression | 0.9993 | 0.9722 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| decision_tree | shap | 0.0066 | 0.6845 | 0.1642 |
| decision_tree | lime | 0.0098 | 0.1770 | 0.0200 |
| decision_tree | causal_shap | 0.2125 | 0.5526 | 0.0569 |
| decision_tree | shapley_flow | 0.0831 | 0.1575 | 0.0000 |
| decision_tree | shap_interactive | 0.0073 | 0.5886 | 0.2000 |
| decision_tree | prototype | 0.0003 | 0.8350 | 0.9091 |
| decision_tree | counterfactual | 0.0004 | 0.8400 | 0.1320 |
| decision_tree | bayesian_rule_list | 0.0039 | 0.0000 | 0.0000 |
| decision_tree | corels | 0.0062 | 0.0000 | 0.0000 |
| decision_tree | feature_ablation | 0.0039 | 0.0000 | 0.0000 |
| random_forest | shap | 0.1970 | 0.0693 | 0.0167 |
| random_forest | lime | 0.0190 | 0.0533 | 0.0000 |
| random_forest | causal_shap | 8.1042 | 0.2587 | 0.0000 |
| random_forest | shapley_flow | 4.1689 | 0.0222 | 0.0000 |
| random_forest | shap_interactive | 0.4203 | 0.0000 | 0.0000 |
| random_forest | prototype | 0.0031 | 0.9650 | 0.8277 |
| random_forest | counterfactual | 0.0039 | 0.9650 | 0.3689 |
| random_forest | bayesian_rule_list | 0.0074 | 0.0000 | 0.0000 |
| random_forest | corels | 0.0102 | 0.0000 | 0.0000 |
| random_forest | feature_ablation | 0.2030 | 0.0000 | 0.0000 |
| gradient_boosting | shap | 0.0448 | 0.2340 | 0.0210 |
| gradient_boosting | lime | 0.0140 | 0.0400 | 0.0000 |
| gradient_boosting | causal_shap | 1.7299 | 0.4628 | 0.0010 |
| gradient_boosting | shap_interactive | 0.0680 | 0.1600 | 0.0000 |
| gradient_boosting | prototype | 0.0009 | 0.9450 | 0.9111 |
| gradient_boosting | counterfactual | 0.0011 | 0.9500 | 0.1655 |
| gradient_boosting | bayesian_rule_list | 0.0049 | 0.0000 | 0.0000 |
| gradient_boosting | corels | 0.0081 | 0.0000 | 0.0000 |
| gradient_boosting | feature_ablation | 0.0505 | 0.0000 | 0.0000 |
| mlp | shap | 0.0070 | 0.0373 | 0.0000 |
| mlp | lime | 0.0105 | 0.0050 | 0.0000 |
| mlp | integrated_gradients | 0.5421 | 0.0000 | 0.0000 |
| mlp | causal_shap | 0.2778 | 0.0494 | 0.0000 |
| mlp | shapley_flow | 0.1235 | 0.0000 | 0.0000 |
| mlp | shap_interactive | 0.0102 | 0.0000 | 0.0000 |
| mlp | prototype | 0.0002 | 0.9850 | 0.9231 |
| mlp | counterfactual | 0.0004 | 0.9800 | 0.1478 |
| mlp | influence_functions | 0.0205 | 0.0000 | 0.0000 |
| mlp | bayesian_rule_list | 0.0037 | 0.0000 | 0.0000 |
| mlp | corels | 0.0063 | 0.0000 | 0.0000 |
| mlp | feature_ablation | 0.0062 | 0.0000 | 0.0000 |
| linear_regression | lime | 0.0211 | 0.2141 | 0.4145 |
| linear_regression | causal_shap | 0.2384 | 0.3413 | 0.3577 |
| linear_regression | shap_interactive | 0.0071 | 0.2149 | 0.3443 |
| linear_regression | prototype | 0.0003 | 0.1850 | 0.0000 |
| linear_regression | counterfactual | 0.0004 | 0.2150 | 0.0265 |
| linear_regression | bayesian_rule_list | 0.0050 | 0.0000 | 0.0000 |
| linear_regression | corels | 0.0082 | 0.0000 | 0.0000 |
| linear_regression | feature_ablation | 0.0046 | 0.0000 | 0.0000 |
| logistic_regression | lime | 0.0145 | 0.0000 | 0.0000 |
| logistic_regression | causal_shap | 0.2161 | 0.1571 | 0.0005 |
| logistic_regression | shap_interactive | 0.0073 | 0.1886 | 0.0000 |
| logistic_regression | prototype | 0.0002 | 0.9650 | 0.9109 |
| logistic_regression | counterfactual | 0.0004 | 0.9700 | 0.1742 |
| logistic_regression | influence_functions | 0.0165 | 0.0000 | 0.0000 |
| logistic_regression | bayesian_rule_list | 0.0045 | 0.0000 | 0.0000 |
| logistic_regression | corels | 0.0076 | 0.0000 | 0.0000 |
| logistic_regression | feature_ablation | 0.0039 | 0.0000 | 0.0000 |

### fashion_mnist

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| cnn | 0.9440 | 0.8450 | N/A | N/A |
| vit | 0.7290 | 0.7100 | N/A | N/A |
| resnet | 0.9055 | 0.7575 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| cnn | prototype | 0.0014 | 0.8700 | 0.8511568 |
| cnn | counterfactual | 0.0058 | 0.8750 | 0.3133816 |
| cnn | tcav | 0.0000 | 0.0000 | 0.0000 |
| cnn | concept_bottleneck | 0.0000 | 0.0000 | 0.0000 |
| cnn | occlusion | 0.0190 | 0.0000 | 0.0000 |
| vit | tcav | 0.0000 | 0.0000 | 0.0000 |
| vit | concept_bottleneck | 0.0000 | 0.0000 | 0.0000 |
| vit | occlusion | 0.0857 | 0.0000 | 0.0000 |
| resnet | prototype | 0.0058 | 0.7750 | 0.8298211 |
| resnet | counterfactual | 0.0112 | 0.7700 | 0.3005286 |

### german_credit

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| decision_tree | 0.8950 | 0.6450 | N/A | N/A |
| random_forest | 0.9287 | 0.7050 | N/A | N/A |
| gradient_boosting | 0.8387 | 0.7150 | N/A | N/A |
| mlp | 0.8425 | 0.7150 | N/A | N/A |
| linear_regression | 0.7037 | 0.7250 | N/A | N/A |
| logistic_regression | 0.7013 | 0.7350 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| decision_tree | shap | 0.0009 | 0.5300 | 0.0450 |
| decision_tree | lime | 0.0099 | 0.2000 | 0.0200 |
| decision_tree | causal_shap | 0.0224 | 0.4000 | 0.0267 |
| decision_tree | shapley_flow | 0.0105 | 0.1667 | 0.0000 |
| decision_tree | shap_interactive | 0.0034 | 0.4000 | 0.0000 |
| decision_tree | prototype | 0.0001 | 0.6450 | 0.9130 |
| decision_tree | counterfactual | 0.0001 | 0.6450 | 0.1025 |
| decision_tree | bayesian_rule_list | 0.0006 | 0.0000 | 0.0000 |
| decision_tree | corels | 0.0003 | 0.0000 | 0.0000 |
| decision_tree | feature_ablation | 0.0005 | 0.0000 | 0.0000 |
| random_forest | shap | 0.0312 | 0.2500 | 0.0103 |
| random_forest | lime | 0.0213 | 0.1400 | 0.0000 |
| random_forest | causal_shap | 0.9309 | 0.1800 | 0.0000 |
| random_forest | shapley_flow | 0.4802 | 0.1000 | 0.0000 |
| random_forest | shap_interactive | 0.1743 | 0.0000 | 0.0000 |
| random_forest | prototype | 0.0036 | 0.7050 | 0.7289 |
| random_forest | counterfactual | 0.0034 | 0.7050 | 0.3051 |
| random_forest | bayesian_rule_list | 0.0043 | 0.0000 | 0.0000 |
| random_forest | corels | 0.0045 | 0.0000 | 0.0000 |
| random_forest | feature_ablation | 0.0265 | 0.0000 | 0.0000 |
| gradient_boosting | shap | 0.0021 | 0.2600 | 0.0508 |
| gradient_boosting | lime | 0.0101 | 0.1000 | 0.0207 |
| gradient_boosting | causal_shap | 0.0526 | 0.2000 | 0.0250 |
| gradient_boosting | shap_interactive | 0.0098 | 0.0000 | 0.0000 |
| gradient_boosting | prototype | 0.0004 | 0.7150 | 0.7451 |
| gradient_boosting | counterfactual | 0.0006 | 0.7150 | 0.2889 |
| gradient_boosting | bayesian_rule_list | 0.0009 | 0.0000 | 0.0000 |
| gradient_boosting | corels | 0.0006 | 0.0000 | 0.0000 |
| gradient_boosting | feature_ablation | 0.0019 | 0.0000 | 0.0000 |
| mlp | shap | 0.0009 | 0.5100 | 0.0348 |
| mlp | lime | 0.0098 | 0.2600 | 0.0000 |
| mlp | integrated_gradients | 0.0593 | 0.0000 | 0.0000 |
| mlp | causal_shap | 0.0294 | 0.3600 | 0.0117 |
| mlp | shapley_flow | 0.0130 | 0.2000 | 0.0000 |
| mlp | shap_interactive | 0.0044 | 0.0000 | 0.0000 |
| mlp | prototype | 0.0002 | 0.7150 | 0.8110 |
| mlp | counterfactual | 0.0002 | 0.7150 | 0.2207 |
| mlp | influence_functions | 0.0220 | 0.0000 | 0.0000 |
| mlp | bayesian_rule_list | 0.0006 | 0.0000 | 0.0000 |
| mlp | corels | 0.0003 | 0.0000 | 0.0000 |
| mlp | feature_ablation | 0.0006 | 0.0000 | 0.0000 |
| linear_regression | lime | 0.0095 | 0.0600 | 0.0167 |
| linear_regression | causal_shap | 0.0260 | 0.0800 | 0.0050 |
| linear_regression | shap_interactive | 0.0054 | 0.0000 | 0.0000 |
| linear_regression | prototype | 0.0001 | 0.7250 | 0.5913 |
| linear_regression | counterfactual | 0.0002 | 0.7250 | 0.4427 |
| linear_regression | bayesian_rule_list | 0.0010 | 0.0000 | 0.0000 |
| linear_regression | corels | 0.0003 | 0.0000 | 0.0000 |
| linear_regression | feature_ablation | 0.0007 | 0.0000 | 0.0000 |
| logistic_regression | lime | 0.0100 | 0.0800 | 0.0040 |
| logistic_regression | causal_shap | 0.0220 | 0.0600 | 0.0050 |
| logistic_regression | shap_interactive | 0.0038 | 0.0000 | 0.0000 |
| logistic_regression | prototype | 0.0001 | 0.7350 | 0.7158 |
| logistic_regression | counterfactual | 0.0001 | 0.7350 | 0.3183 |
| logistic_regression | influence_functions | 0.0179 | 0.0000 | 0.0000 |
| logistic_regression | bayesian_rule_list | 0.0006 | 0.0000 | 0.0000 |
| logistic_regression | corels | 0.0003 | 0.0000 | 0.0000 |
| logistic_regression | feature_ablation | 0.0005 | 0.0000 | 0.0000 |

### heart_disease

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| decision_tree | 0.9916 | 0.7333 | N/A | N/A |
| random_forest | 1.0000 | 0.7333 | N/A | N/A |
| gradient_boosting | 0.9451 | 0.7000 | N/A | N/A |
| mlp | 0.8186 | 0.8000 | N/A | N/A |
| linear_regression | 0.7089 | 0.8167 | N/A | N/A |
| logistic_regression | 0.7131 | 0.8000 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| decision_tree | shap | 0.0006 | 0.6667 | 0.0083 |
| decision_tree | lime | 0.0095 | 0.2000 | 0.0200 |
| decision_tree | causal_shap | 0.0158 | 0.4400 | 0.0067 |
| decision_tree | shapley_flow | 0.0073 | 0.2000 | 0.0333 |
| decision_tree | shap_interactive | 0.0047 | 0.8000 | 0.0000 |
| decision_tree | prototype | 0.0001 | 0.7333 | 0.9831 |
| decision_tree | counterfactual | 0.0003 | 0.7333 | 0.0205 |
| decision_tree | bayesian_rule_list | 0.0005 | 0.0000 | 0.0000 |
| decision_tree | corels | 0.0002 | 0.0000 | 0.0000 |
| decision_tree | feature_ablation | 0.0004 | 0.0000 | 0.0000 |
| random_forest | shap | 0.0272 | 0.5167 | 0.0056 |
| random_forest | lime | 0.0228 | 0.1800 | 0.0000 |
| random_forest | causal_shap | 0.6725 | 0.2800 | 0.0040 |
| random_forest | shapley_flow | 0.3348 | 0.1667 | 0.0000 |
| random_forest | shap_interactive | 0.1562 | 0.0000 | 0.0000 |
| random_forest | prototype | 0.0039 | 0.7333 | 0.7346 |
| random_forest | counterfactual | 0.0036 | 0.7333 | 0.3022 |
| random_forest | bayesian_rule_list | 0.0038 | 0.0000 | 0.0000 |
| random_forest | corels | 0.0035 | 0.0000 | 0.0000 |
| random_forest | feature_ablation | 0.0191 | 0.0000 | 0.0000 |
| gradient_boosting | shap | 0.0019 | 0.5500 | 0.0333 |
| gradient_boosting | lime | 0.0100 | 0.1000 | 0.0000 |
| gradient_boosting | causal_shap | 0.0359 | 0.3200 | 0.0200 |
| gradient_boosting | shap_interactive | 0.0103 | 0.4000 | 0.0000 |
| gradient_boosting | prototype | 0.0003 | 0.7000 | 0.8027 |
| gradient_boosting | counterfactual | 0.0003 | 0.7000 | 0.2336 |
| gradient_boosting | bayesian_rule_list | 0.0009 | 0.0000 | 0.0000 |
| gradient_boosting | corels | 0.0004 | 0.0000 | 0.0000 |
| gradient_boosting | feature_ablation | 0.0017 | 0.0000 | 0.0000 |
| mlp | shap | 0.0008 | 0.3833 | 0.0167 |
| mlp | lime | 0.0101 | 0.0600 | 0.0400 |
| mlp | integrated_gradients | 0.0427 | 0.0000 | 0.0000 |
| mlp | causal_shap | 0.0202 | 0.2600 | 0.0050 |
| mlp | shapley_flow | 0.0087 | 0.1000 | 0.0000 |
| mlp | shap_interactive | 0.0042 | 0.0000 | 0.0000 |
| mlp | prototype | 0.0001 | 0.8000 | 0.7834 |
| mlp | counterfactual | 0.0001 | 0.8000 | 0.2512 |
| mlp | influence_functions | 0.0197 | 0.0000 | 0.0000 |
| mlp | bayesian_rule_list | 0.0005 | 0.0000 | 0.0000 |
| mlp | corels | 0.0003 | 0.0000 | 0.0000 |
| mlp | feature_ablation | 0.0005 | 0.0000 | 0.0000 |
| linear_regression | lime | 0.0133 | 0.0000 | 0.0000 |
| linear_regression | causal_shap | 0.0153 | 0.2600 | 0.0000 |
| linear_regression | shap_interactive | 0.0042 | 0.0000 | 0.0000 |
| linear_regression | prototype | 0.0001 | 0.8167 | 0.6256 |
| linear_regression | counterfactual | 0.0001 | 0.8167 | 0.4117 |
| linear_regression | bayesian_rule_list | 0.0005 | 0.0000 | 0.0000 |
| linear_regression | corels | 0.0004 | 0.0000 | 0.0000 |
| linear_regression | feature_ablation | 0.0003 | 0.0000 | 0.0000 |
| logistic_regression | lime | 0.0107 | 0.0200 | 0.0100 |
| logistic_regression | causal_shap | 0.0157 | 0.2400 | 0.0200 |
| logistic_regression | shap_interactive | 0.0030 | 0.2000 | 0.2000 |
| logistic_regression | prototype | 0.0001 | 0.8000 | 0.7513 |
| logistic_regression | counterfactual | 0.0002 | 0.8000 | 0.2860 |
| logistic_regression | influence_functions | 0.0160 | 0.0000 | 0.0000 |
| logistic_regression | bayesian_rule_list | 0.0005 | 0.0000 | 0.0000 |
| logistic_regression | corels | 0.0002 | 0.0000 | 0.0000 |
| logistic_regression | feature_ablation | 0.0004 | 0.0000 | 0.0000 |

### imdb

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| bert | 0.9180 | 0.8100 | N/A | N/A |
| lstm | 0.8870 | 0.8150 | N/A | N/A |
| roberta | 0.9240 | 0.8700 | N/A | N/A |
| naive_bayes_text | 0.9850 | 0.8050 | N/A | N/A |
| svm_text | 0.9970 | 0.8050 | N/A | N/A |
| xgboost_text | 0.9890 | 0.7900 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| bert | lime | 0.0570 | 0.8400 | 0.0000 |
| bert | text_occlusion | 0.0389 | 0.0000 | 0.0000 |
| bert | attention_visualization | 0.0803 | 0.0000 | 0.0000 |
| lstm | lime | 0.0615 | 0.8000 | 0.0000 |
| lstm | text_occlusion | 0.0350 | 0.0000 | 0.0000 |
| lstm | attention_visualization | 0.0864 | 0.0000 | 0.0000 |
| roberta | lime | 17.0277 | 0.8800 | 0.0000 |
| roberta | text_occlusion | 15.0937 | 0.0000 | 0.0000 |
| roberta | attention_visualization | 48.1745 | 0.0000 | 0.0000 |
| naive_bayes_text | lime | 0.1148 | 0.8200 | 0.0000 |
| naive_bayes_text | text_occlusion | 0.0598 | 0.0000 | 0.0000 |
| naive_bayes_text | attention_visualization | 0.1508 | 0.0000 | 0.0000 |
| svm_text | lime | 0.2135 | 0.7600 | 0.0000 |
| svm_text | text_occlusion | 0.1387 | 0.0000 | 0.0000 |
| svm_text | attention_visualization | 0.3299 | 0.0000 | 0.0000 |
| xgboost_text | lime | 0.1981 | 0.7400 | 0.0000 |
| xgboost_text | text_occlusion | 0.1066 | 0.0000 | 0.0000 |
| xgboost_text | attention_visualization | 0.2499 | 0.0000 | 0.0000 |

### iris

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| decision_tree | 1.0000 | 0.9333 | N/A | N/A |
| random_forest | 1.0000 | 0.9000 | N/A | N/A |
| gradient_boosting | 1.0000 | 0.9667 | N/A | N/A |
| mlp | 0.9833 | 0.9667 | N/A | N/A |
| linear_regression | 0.0000 | 0.0000 | N/A | N/A |
| logistic_regression | 0.9583 | 0.9333 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| decision_tree | shap | 0.0007 | 0.4000 | 0.0000 |
| decision_tree | lime | 0.0105 | 0.0167 | 0.0000 |
| decision_tree | causal_shap | 0.0152 | 0.4000 | 0.0000 |
| decision_tree | shapley_flow | 0.0056 | 0.0167 | 0.0000 |
| decision_tree | shap_interactive | 0.0018 | 0.4000 | 0.0000 |
| decision_tree | prototype | 0.0001 | 0.9333 | 0.9937 |
| decision_tree | counterfactual | 0.0001 | 0.9333 | 0.0272 |
| decision_tree | bayesian_rule_list | 0.0005 | 0.0000 | 0.0000 |
| decision_tree | corels | 0.0002 | 0.0000 | 0.0000 |
| decision_tree | feature_ablation | 0.0003 | 0.0000 | 0.0000 |
| random_forest | shap | 0.0242 | 0.2333 | 0.0167 |
| random_forest | lime | 0.0191 | 0.0500 | 0.0167 |
| random_forest | causal_shap | 0.5398 | 0.2000 | 0.0000 |
| random_forest | shapley_flow | 0.2766 | 0.0333 | 0.0333 |
| random_forest | shap_interactive | 0.1517 | 0.0000 | 0.0000 |
| random_forest | prototype | 0.0044 | 0.9000 | 0.9382 |
| random_forest | counterfactual | 0.0060 | 0.9000 | 0.0886 |
| random_forest | bayesian_rule_list | 0.0051 | 0.0000 | 0.0000 |
| random_forest | corels | 0.0038 | 0.0000 | 0.0000 |
| random_forest | feature_ablation | 0.0150 | 0.0000 | 0.0000 |
| gradient_boosting | shap | 0.0036 | 0.3167 | 0.0000 |
| gradient_boosting | lime | 0.0117 | 0.0167 | 0.0000 |
| gradient_boosting | causal_shap | 0.0874 | 0.3167 | 0.0000 |
| gradient_boosting | shap_interactive | 0.0206 | 0.0000 | 0.0000 |
| gradient_boosting | prototype | 0.0008 | 0.9667 | 0.9939 |
| gradient_boosting | counterfactual | 0.0010 | 0.9667 | 0.0276 |
| gradient_boosting | bayesian_rule_list | 0.0016 | 0.0000 | 0.0000 |
| gradient_boosting | corels | 0.0010 | 0.0000 | 0.0000 |
| gradient_boosting | feature_ablation | 0.0026 | 0.0000 | 0.0000 |
| mlp | shap | 0.0009 | 0.2167 | 0.0167 |
| mlp | lime | 0.0113 | 0.0667 | 0.0083 |
| mlp | integrated_gradients | 0.0391 | 0.0000 | 0.0000 |
| mlp | causal_shap | 0.0150 | 0.1833 | 0.0083 |
| mlp | shapley_flow | 0.0067 | 0.0000 | 0.0000 |
| mlp | shap_interactive | 0.0030 | 0.0000 | 0.0000 |
| mlp | prototype | 0.0001 | 0.9667 | 0.9526 |
| mlp | counterfactual | 0.0001 | 0.9667 | 0.0760 |
| mlp | influence_functions | 0.0110 | 0.0000 | 0.0000 |
| mlp | bayesian_rule_list | 0.0005 | 0.0000 | 0.0000 |
| mlp | corels | 0.0004 | 0.0000 | 0.0000 |
| mlp | feature_ablation | 0.0005 | 0.0000 | 0.0000 |
| linear_regression | lime | 0.0104 | 0.2115 | 0.3833 |
| linear_regression | causal_shap | 0.0100 | 0.4779 | 0.5333 |
| linear_regression | shap_interactive | 0.0022 | 0.5038 | 0.2000 |
| linear_regression | prototype | 0.0003 | 0.6667 | 0.0000 |
| linear_regression | counterfactual | 0.0001 | 0.6667 | 0.3115 |
| linear_regression | bayesian_rule_list | 0.0004 | 0.0000 | 0.0000 |
| linear_regression | corels | 0.0003 | 0.0000 | 0.0000 |
| linear_regression | feature_ablation | 0.0004 | 0.0000 | 0.0000 |
| logistic_regression | lime | 0.0125 | 0.0500 | 0.0222 |
| logistic_regression | causal_shap | 0.0109 | 0.1667 | 0.0000 |
| logistic_regression | shap_interactive | 0.0031 | 0.0000 | 0.0000 |
| logistic_regression | prototype | 0.0002 | 0.9333 | 0.8678 |
| logistic_regression | counterfactual | 0.0002 | 0.9333 | 0.1653 |
| logistic_regression | influence_functions | 0.0093 | 0.0000 | 0.0000 |
| logistic_regression | bayesian_rule_list | 0.0005 | 0.0000 | 0.0000 |
| logistic_regression | corels | 0.0003 | 0.0000 | 0.0000 |
| logistic_regression | feature_ablation | 0.0003 | 0.0000 | 0.0000 |

### mnist

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| cnn | 0.9970 | 0.9750 | N/A | N/A |
| vit | 0.7790 | 0.7100 | N/A | N/A |
| resnet | 0.9790 | 0.9300 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| cnn | prototype | 0.0015 | 0.9750 | 0.65870225 |
| cnn | counterfactual | 0.0039 | 0.9750 | 0.463766 |
| cnn | tcav | 0.0000 | 0.0000 | 0.0000 |
| cnn | concept_bottleneck | 0.0000 | 0.0000 | 0.0000 |
| cnn | occlusion | 0.0262 | 0.0000 | 0.0000 |
| vit | tcav | 0.0000 | 0.0000 | 0.0000 |
| vit | concept_bottleneck | 0.0000 | 0.0000 | 0.0000 |
| vit | occlusion | 0.0940 | 0.0000 | 0.0000 |
| resnet | prototype | 0.0072 | 0.9300 | 0.6776398 |
| resnet | counterfactual | 0.0076 | 0.9300 | 0.4899005 |

### wine_classification

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| decision_tree | 1.0000 | 0.9444 | N/A | N/A |
| random_forest | 1.0000 | 1.0000 | N/A | N/A |
| gradient_boosting | 1.0000 | 0.9444 | N/A | N/A |
| mlp | 1.0000 | 1.0000 | N/A | N/A |
| linear_regression | 0.0000 | 0.0000 | N/A | N/A |
| logistic_regression | 1.0000 | 0.9722 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| decision_tree | shap | 0.0014 | 0.3889 | 0.0278 |
| decision_tree | lime | 0.0113 | 0.0000 | 0.0000 |
| decision_tree | causal_shap | 0.0420 | 0.3333 | 0.0000 |
| decision_tree | shapley_flow | 0.0165 | 0.0000 | 0.0000 |
| decision_tree | shap_interactive | 0.0046 | 0.2000 | 0.0000 |
| decision_tree | prototype | 0.0001 | 0.9444 | 0.9598 |
| decision_tree | counterfactual | 0.0001 | 0.9444 | 0.0658 |
| decision_tree | bayesian_rule_list | 0.0009 | 0.0000 | 0.0000 |
| decision_tree | corels | 0.0005 | 0.0000 | 0.0000 |
| decision_tree | feature_ablation | 0.0010 | 0.0000 | 0.0000 |
| random_forest | shap | 0.0466 | 0.0972 | 0.0000 |
| random_forest | lime | 0.0191 | 0.0278 | 0.0000 |
| random_forest | causal_shap | 1.5310 | 0.0833 | 0.0000 |
| random_forest | shapley_flow | 0.7512 | 0.0333 | 0.0000 |
| random_forest | shap_interactive | 0.1630 | 0.3000 | 0.0000 |
| random_forest | prototype | 0.0052 | 1.0000 | 0.9266 |
| random_forest | counterfactual | 0.0037 | 1.0000 | 0.1585 |
| random_forest | bayesian_rule_list | 0.0040 | 0.0000 | 0.0000 |
| random_forest | corels | 0.0037 | 0.0000 | 0.0000 |
| random_forest | feature_ablation | 0.0446 | 0.0000 | 0.0000 |
| gradient_boosting | shap | 0.0071 | 0.1528 | 0.0000 |
| gradient_boosting | lime | 0.0105 | 0.0000 | 0.0000 |
| gradient_boosting | causal_shap | 0.2394 | 0.0694 | 0.0000 |
| gradient_boosting | shap_interactive | 0.0257 | 0.1000 | 0.0000 |
| gradient_boosting | prototype | 0.0006 | 0.9444 | 0.9610 |
| gradient_boosting | counterfactual | 0.0009 | 0.9444 | 0.0670 |
| gradient_boosting | bayesian_rule_list | 0.0019 | 0.0000 | 0.0000 |
| gradient_boosting | corels | 0.0013 | 0.0000 | 0.0000 |
| gradient_boosting | feature_ablation | 0.0079 | 0.0000 | 0.0000 |
| mlp | shap | 0.0017 | 0.1111 | 0.0000 |
| mlp | lime | 0.0106 | 0.0278 | 0.0000 |
| mlp | integrated_gradients | 0.1142 | 0.0000 | 0.0000 |
| mlp | causal_shap | 0.0497 | 0.0833 | 0.0000 |
| mlp | shapley_flow | 0.0213 | 0.0333 | 0.0000 |
| mlp | shap_interactive | 0.0050 | 0.0000 | 0.0000 |
| mlp | prototype | 0.0001 | 1.0000 | 0.9422 |
| mlp | counterfactual | 0.0001 | 1.0000 | 0.1025 |
| mlp | influence_functions | 0.0166 | 0.0000 | 0.0000 |
| mlp | bayesian_rule_list | 0.0009 | 0.0000 | 0.0000 |
| mlp | corels | 0.0007 | 0.0000 | 0.0000 |
| mlp | feature_ablation | 0.0025 | 0.0000 | 0.0000 |
| linear_regression | lime | 0.0121 | 0.4623 | 0.3360 |
| linear_regression | causal_shap | 0.0381 | 0.5794 | 0.4808 |
| linear_regression | shap_interactive | 0.0035 | 0.7036 | 0.4923 |
| linear_regression | prototype | 0.0002 | 0.5833 | 0.0000 |
| linear_regression | counterfactual | 0.0002 | 0.5833 | 0.3405 |
| linear_regression | bayesian_rule_list | 0.0009 | 0.0000 | 0.0000 |
| linear_regression | corels | 0.0005 | 0.0000 | 0.0000 |
| linear_regression | feature_ablation | 0.0008 | 0.0000 | 0.0000 |
| logistic_regression | lime | 0.0086 | 0.0556 | 0.0000 |
| logistic_regression | causal_shap | 0.0382 | 0.0972 | 0.0000 |
| logistic_regression | shap_interactive | 0.0030 | 0.0000 | 0.0000 |
| logistic_regression | prototype | 0.0002 | 0.9722 | 0.9369 |
| logistic_regression | counterfactual | 0.0003 | 0.9722 | 0.1235 |
| logistic_regression | influence_functions | 0.0096 | 0.0000 | 0.0000 |
| logistic_regression | bayesian_rule_list | 0.0012 | 0.0000 | 0.0000 |
| logistic_regression | corels | 0.0009 | 0.0000 | 0.0000 |
| logistic_regression | feature_ablation | 0.0008 | 0.0000 | 0.0000 |

### wine_quality

#### Model Performance Summary

| Model | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|----------|
| decision_tree | 0.8874 | 0.6406 | N/A | N/A |
| random_forest | 0.9679 | 0.7063 | N/A | N/A |
| gradient_boosting | 0.8694 | 0.7000 | N/A | N/A |
| mlp | 0.9124 | 0.6906 | N/A | N/A |
| linear_regression | 0.0000 | 0.0000 | N/A | N/A |
| logistic_regression | 0.6302 | 0.6531 | N/A | N/A |

#### XAI Evaluation Results

| Model | Explanation Method | Time Complexity | Faithfulness | Monotonicity |
|-------|-------------------|--------|--------|--------|
| decision_tree | shap | 0.0010 | 0.7200 | 0.0237 |
| decision_tree | lime | 0.0091 | 0.1300 | 0.0200 |
| decision_tree | causal_shap | 0.0337 | 0.1600 | 0.0050 |
| decision_tree | shapley_flow | 0.0159 | 0.0000 | 0.0000 |
| decision_tree | shap_interactive | 0.0069 | 0.2000 | 0.0000 |
| decision_tree | prototype | 0.0001 | 0.6500 | 0.8927 |
| decision_tree | counterfactual | 0.0002 | 0.5900 | 0.1392 |
| decision_tree | bayesian_rule_list | 0.0010 | 0.0000 | 0.0000 |
| decision_tree | corels | 0.0006 | 0.0000 | 0.0000 |
| decision_tree | feature_ablation | 0.0008 | 0.0000 | 0.0000 |
| random_forest | shap | 0.0431 | 0.3550 | 0.0175 |
| random_forest | lime | 0.0233 | 0.0400 | 0.0025 |
| random_forest | causal_shap | 1.2929 | 0.2000 | 0.0000 |
| random_forest | shapley_flow | 0.6594 | 0.0000 | 0.0000 |
| random_forest | shap_interactive | 0.1732 | 0.2000 | 0.0000 |
| random_forest | prototype | 0.0032 | 0.6600 | 0.6658 |
| random_forest | counterfactual | 0.0034 | 0.7100 | 0.3748 |
| random_forest | bayesian_rule_list | 0.0039 | 0.0000 | 0.0000 |
| random_forest | corels | 0.0038 | 0.0000 | 0.0000 |
| random_forest | feature_ablation | 0.0369 | 0.0000 | 0.0000 |
| gradient_boosting | shap | 0.0073 | 0.4050 | 0.0175 |
| gradient_boosting | lime | 0.0110 | 0.0500 | 0.0029 |
| gradient_boosting | causal_shap | 0.2263 | 0.1500 | 0.0050 |
| gradient_boosting | shap_interactive | 0.0256 | 0.0000 | 0.0000 |
| gradient_boosting | prototype | 0.0006 | 0.7050 | 0.7148 |
| gradient_boosting | counterfactual | 0.0007 | 0.6950 | 0.3426 |
| gradient_boosting | bayesian_rule_list | 0.0016 | 0.0000 | 0.0000 |
| gradient_boosting | corels | 0.0010 | 0.0000 | 0.0000 |
| gradient_boosting | feature_ablation | 0.0053 | 0.0000 | 0.0000 |
| mlp | shap | 0.0013 | 0.6600 | 0.0053 |
| mlp | lime | 0.0098 | 0.0400 | 0.0000 |
| mlp | integrated_gradients | 0.0955 | 0.0000 | 0.0000 |
| mlp | causal_shap | 0.0467 | 0.2600 | 0.0000 |
| mlp | shapley_flow | 0.0214 | 0.0833 | 0.0000 |
| mlp | shap_interactive | 0.0066 | 0.0000 | 0.0000 |
| mlp | prototype | 0.0002 | 0.6700 | 0.8188 |
| mlp | counterfactual | 0.0003 | 0.6800 | 0.2288 |
| mlp | influence_functions | 0.0206 | 0.0000 | 0.0000 |
| mlp | bayesian_rule_list | 0.0011 | 0.0000 | 0.0000 |
| mlp | corels | 0.0006 | 0.0000 | 0.0000 |
| mlp | feature_ablation | 0.0012 | 0.0000 | 0.0000 |
| linear_regression | lime | 0.0110 | 0.4046 | 0.3646 |
| linear_regression | causal_shap | 0.0422 | 0.5872 | 0.4127 |
| linear_regression | shap_interactive | 0.0035 | 0.5430 | 0.3636 |
| linear_regression | prototype | 0.0003 | 0.4850 | 0.0000 |
| linear_regression | counterfactual | 0.0003 | 0.5250 | 0.3794 |
| linear_regression | bayesian_rule_list | 0.0015 | 0.0000 | 0.0000 |
| linear_regression | corels | 0.0005 | 0.0000 | 0.0000 |
| linear_regression | feature_ablation | 0.0008 | 0.0000 | 0.0000 |
| logistic_regression | lime | 0.0166 | 0.0300 | 0.0000 |
| logistic_regression | causal_shap | 0.0363 | 0.2700 | 0.0100 |
| logistic_regression | shap_interactive | 0.0035 | 0.2000 | 0.0000 |
| logistic_regression | prototype | 0.0002 | 0.5900 | 0.6465 |
| logistic_regression | counterfactual | 0.0003 | 0.6250 | 0.4019 |
| logistic_regression | influence_functions | 0.0240 | 0.0000 | 0.0000 |
| logistic_regression | bayesian_rule_list | 0.0009 | 0.0000 | 0.0000 |
| logistic_regression | corels | 0.0006 | 0.0000 | 0.0000 |
| logistic_regression | feature_ablation | 0.0008 | 0.0000 | 0.0000 |

## Best Performing Models by Dataset

Ranking models by test accuracy on each dataset.

### 20newsgroups - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | roberta | 0.8400 |
| 2 | svm_text | 0.7950 |
| 3 | naive_bayes_text | 0.7350 |
| 4 | bert | 0.7150 |
| 5 | lstm | 0.7100 |
| 6 | xgboost_text | 0.7050 |

### adult_income - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | gradient_boosting | 0.8356 |
| 2 | random_forest | 0.8333 |
| 3 | decision_tree | 0.8326 |
| 4 | mlp | 0.8236 |
| 5 | logistic_regression | 0.8087 |
| 6 | linear_regression | 0.7915 |

### ag_news - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | roberta | 0.9000 |
| 2 | naive_bayes_text | 0.8150 |
| 3 | bert | 0.7900 |
| 4 | svm_text | 0.7900 |
| 5 | lstm | 0.7800 |
| 6 | xgboost_text | 0.7100 |

### breast_cancer - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | logistic_regression | 0.9825 |
| 2 | random_forest | 0.9561 |
| 3 | gradient_boosting | 0.9561 |
| 4 | linear_regression | 0.9561 |
| 5 | mlp | 0.9474 |
| 6 | decision_tree | 0.9123 |

### cifar10 - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | cnn | 0.5125 |
| 2 | resnet | 0.3950 |
| 3 | vit | 0.2525 |

### compas - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | gradient_boosting | 0.6951 |
| 2 | linear_regression | 0.6868 |
| 3 | mlp | 0.6854 |
| 4 | logistic_regression | 0.6854 |
| 5 | random_forest | 0.6826 |
| 6 | decision_tree | 0.6736 |

### diabetes - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | logistic_regression | 0.6517 |
| 2 | random_forest | 0.5843 |
| 3 | gradient_boosting | 0.5393 |
| 4 | decision_tree | 0.4944 |
| 5 | mlp | 0.4494 |
| 6 | linear_regression | 0.0000 |

### digits - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | mlp | 0.9778 |
| 2 | logistic_regression | 0.9722 |
| 3 | random_forest | 0.9611 |
| 4 | gradient_boosting | 0.9528 |
| 5 | decision_tree | 0.8083 |
| 6 | linear_regression | 0.0000 |

### fashion_mnist - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | cnn | 0.8450 |
| 2 | resnet | 0.7575 |
| 3 | vit | 0.7100 |

### german_credit - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | logistic_regression | 0.7350 |
| 2 | linear_regression | 0.7250 |
| 3 | gradient_boosting | 0.7150 |
| 4 | mlp | 0.7150 |
| 5 | random_forest | 0.7050 |
| 6 | decision_tree | 0.6450 |

### heart_disease - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | linear_regression | 0.8167 |
| 2 | mlp | 0.8000 |
| 3 | logistic_regression | 0.8000 |
| 4 | decision_tree | 0.7333 |
| 5 | random_forest | 0.7333 |
| 6 | gradient_boosting | 0.7000 |

### imdb - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | roberta | 0.8700 |
| 2 | lstm | 0.8150 |
| 3 | bert | 0.8100 |
| 4 | naive_bayes_text | 0.8050 |
| 5 | svm_text | 0.8050 |
| 6 | xgboost_text | 0.7900 |

### iris - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | gradient_boosting | 0.9667 |
| 2 | mlp | 0.9667 |
| 3 | decision_tree | 0.9333 |
| 4 | logistic_regression | 0.9333 |
| 5 | random_forest | 0.9000 |
| 6 | linear_regression | 0.0000 |

### mnist - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | cnn | 0.9750 |
| 2 | resnet | 0.9300 |
| 3 | vit | 0.7100 |

### wine_classification - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | random_forest | 1.0000 |
| 2 | mlp | 1.0000 |
| 3 | logistic_regression | 0.9722 |
| 4 | decision_tree | 0.9444 |
| 5 | gradient_boosting | 0.9444 |
| 6 | linear_regression | 0.0000 |

### wine_quality - Model Rankings

| Rank | Model | Test Accuracy |
|------|-------|---------------|
| 1 | random_forest | 0.7063 |
| 2 | gradient_boosting | 0.7000 |
| 3 | mlp | 0.6906 |
| 4 | logistic_regression | 0.6531 |
| 5 | decision_tree | 0.6406 |
| 6 | linear_regression | 0.0000 |

## Top Performing XAI Combinations

### Best Time Complexity

| Rank | Dataset | Model | Explanation | Score |
|------|---------|-------|-------------|-------|
| 1 | 20newsgroups | roberta | lime | 52.9093 |
| 2 | imdb | roberta | attention_visualization | 48.1745 |
| 3 | 20newsgroups | roberta | attention_visualization | 33.8771 |
| 4 | imdb | roberta | lime | 17.0277 |
| 5 | ag_news | roberta | lime | 15.3733 |
| 6 | imdb | roberta | text_occlusion | 15.0937 |
| 7 | ag_news | roberta | attention_visualization | 13.8400 |
| 8 | 20newsgroups | roberta | text_occlusion | 10.3211 |
| 9 | digits | random_forest | causal_shap | 8.1042 |
| 10 | digits | random_forest | shapley_flow | 4.1689 |

### Best Faithfulness

| Rank | Dataset | Model | Explanation | Score |
|------|---------|-------|-------------|-------|
| 1 | wine_classification | random_forest | prototype | 1.0000 |
| 2 | wine_classification | random_forest | counterfactual | 1.0000 |
| 3 | wine_classification | mlp | prototype | 1.0000 |
| 4 | wine_classification | mlp | counterfactual | 1.0000 |
| 5 | digits | mlp | prototype | 0.9850 |
| 6 | breast_cancer | logistic_regression | prototype | 0.9825 |
| 7 | breast_cancer | logistic_regression | counterfactual | 0.9825 |
| 8 | digits | mlp | counterfactual | 0.9800 |
| 9 | mnist | cnn | prototype | 0.9750 |
| 10 | mnist | cnn | counterfactual | 0.9750 |

### Best Monotonicity

| Rank | Dataset | Model | Explanation | Score |
|------|---------|-------|-------------|-------|
| 1 | iris | gradient_boosting | prototype | 0.9939 |
| 2 | iris | decision_tree | prototype | 0.9937 |
| 3 | heart_disease | decision_tree | prototype | 0.9831 |
| 4 | wine_classification | gradient_boosting | prototype | 0.9610 |
| 5 | wine_classification | decision_tree | prototype | 0.9598 |
| 6 | diabetes | decision_tree | prototype | 0.9553 |
| 7 | iris | mlp | prototype | 0.9526 |
| 8 | breast_cancer | decision_tree | prototype | 0.9518 |
| 9 | breast_cancer | gradient_boosting | prototype | 0.9511 |
| 10 | breast_cancer | mlp | prototype | 0.9459 |

### Best Completeness

| Rank | Dataset | Model | Explanation | Score |
|------|---------|-------|-------------|-------|
| 1 | digits | linear_regression | counterfactual | 1.1000 |
| 2 | adult_income | decision_tree | prototype | 1.0000 |
| 3 | adult_income | decision_tree | counterfactual | 1.0000 |
| 4 | adult_income | random_forest | prototype | 1.0000 |
| 5 | adult_income | random_forest | counterfactual | 1.0000 |
| 6 | adult_income | gradient_boosting | prototype | 1.0000 |
| 7 | adult_income | gradient_boosting | counterfactual | 1.0000 |
| 8 | adult_income | mlp | prototype | 1.0000 |
| 9 | adult_income | mlp | counterfactual | 1.0000 |
| 10 | adult_income | linear_regression | prototype | 1.0000 |

### Best Stability

| Rank | Dataset | Model | Explanation | Score |
|------|---------|-------|-------------|-------|
| 1 | adult_income | decision_tree | shapley_flow | 1.0000 |
| 2 | adult_income | decision_tree | prototype | 1.0000 |
| 3 | adult_income | decision_tree | bayesian_rule_list | 1.0000 |
| 4 | adult_income | random_forest | shapley_flow | 1.0000 |
| 5 | adult_income | random_forest | bayesian_rule_list | 1.0000 |
| 6 | adult_income | gradient_boosting | bayesian_rule_list | 1.0000 |
| 7 | adult_income | mlp | integrated_gradients | 1.0000 |
| 8 | adult_income | mlp | shapley_flow | 1.0000 |
| 9 | adult_income | mlp | bayesian_rule_list | 1.0000 |
| 10 | adult_income | linear_regression | bayesian_rule_list | 1.0000 |

