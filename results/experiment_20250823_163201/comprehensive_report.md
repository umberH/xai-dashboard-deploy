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

| Dataset             | Model               | Explanation Method      | Detailed Report   |   Time Complexity |   Faithfulness |   Monotonicity |   Completeness |   Stability |   Consistency |   Sparsity |   Simplicity |   Advanced Identity |   Advanced Separability |   Advanced Non Sensitivity |   Advanced Compactness |   Advanced Correctness |   Advanced Entropy |   Advanced Gini Coefficient |   Advanced Kl Divergence |
|:--------------------|:--------------------|:------------------------|:------------------|------------------:|---------------:|---------------:|---------------:|------------:|--------------:|-----------:|-------------:|--------------------:|------------------------:|---------------------------:|-----------------------:|-----------------------:|-------------------:|----------------------------:|-------------------------:|
| adult_income        | decision_tree       | shap                    |                   |       0.00112851  |      0.19      |    0.02        |    0.01        |   0         |    0.465119   | 0.03       |  0.952       |            0.943182 |             0.170619    |                1           |            0.1775      |               0.624    |        0.0215338   |                 0.142       |              0.168466    |
| adult_income        | decision_tree       | lime                    |                   |       0.022963    |      0.1       |    0.03        |    0           |   0         |    0.50595    | 0.024      |  0.949663    |            0.869565 |             0.235224    |                1           |            0.237498    |               0.60146  |        0.00857852  |                 0.189663    |              0.231421    |
| adult_income        | decision_tree       | causal_shap             |                   |       0.0178612   |      0.24      |    0.02        |    0.02        |   0         |    0.505029   | 0.048      |  0.949454    |            0.987654 |             0.19188     |                1           |            0.19871     |               0.58178  |        0.0371585   |                 0.160654    |              0.182841    |
| adult_income        | decision_tree       | shapley_flow            |                   |       0.0087805   |      0.1       |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.56     |        0           |                 0           |              0           |
| adult_income        | decision_tree       | shap_interactive        |                   |       0.00393195  |      0.4       |    0           |    0           |   0         |    0          | 0          |  0.96        |            1        |             0.2         |                1           |            0.2         |               0.34     |       -1.24267e-11 |                 0.16        |              0.2         |
| adult_income        | decision_tree       | prototype               |                   |       0.0010325   |      0.69      |    0.822838    |    1           |   1         |    1          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| adult_income        | decision_tree       | counterfactual          |                   |       0.000597302 |      0.67      |    0.174295    |    1           |   0.843172  |    0.671827   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| adult_income        | decision_tree       | bayesian_rule_list      |                   |       0.000724714 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.567    |        0           |                 0           |              0           |
| adult_income        | decision_tree       | corels                  |                   |       0.000370939 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0.567    |        1           |                 2.22045e-16 |              0           |
| adult_income        | decision_tree       | feature_ablation        |                   |       0.000665693 |      0         |    0           |    0           |   0         |    0.463231   | 0.024      |  0.944       |            1        |             0.224495    |                1           |            0.23        |               0.604    |        0.0172271   |                 0.184       |              0.222773    |
| adult_income        | random_forest       | shap                    |                   |       0.0308834   |      0.19      |    0.02        |    0           |   0         |    0.469635   | 0.014      |  0.944       |            0.94382  |             0.164747    |                1           |            0.1675      |               0.617    |        0.0290917   |                 0.134       |              0.160908    |
| adult_income        | random_forest       | lime                    |                   |       0.0305426   |      0.1       |    0.02        |    0           |   0         |    0.406641   | 0.012      |  0.962696    |            0.888889 |             0.176983    |                1           |            0.178564    |               0.584327 |        0.0057321   |                 0.142696    |              0.174268    |
| adult_income        | random_forest       | causal_shap             |                   |       0.671774    |      0.24      |    0.02        |    0           |   0         |    0.521759   | 0.032      |  0.943771    |            1        |             0.171107    |                1           |            0.178295    |               0.578977 |        0.0338611   |                 0.143771    |              0.166139    |
| adult_income        | random_forest       | shapley_flow            |                   |       0.34079     |      0.133333  |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.56     |        0           |                 0           |              0           |
| adult_income        | random_forest       | shap_interactive        |                   |       0.175905    |      0.6       |    0           |    0           |   0         |    0          | 0          |  0.96        |            1        |             0.2         |                1           |            0.2         |               0.34     |       -1.24267e-11 |                 0.16        |              0.2         |
| adult_income        | random_forest       | prototype               |                   |       0.00447102  |      0.715     |    0.80976     |    1           |   0.999988  |    0.912645   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| adult_income        | random_forest       | counterfactual          |                   |       0.00358183  |      0.685     |    0.195916    |    1           |   0.803514  |    0.485688   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| adult_income        | random_forest       | bayesian_rule_list      |                   |       0.0035549   |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.56     |        0           |                 0           |              0           |
| adult_income        | random_forest       | corels                  |                   |       0.00297282  |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0.56     |        1           |                 2.22045e-16 |              0           |
| adult_income        | random_forest       | feature_ablation        |                   |       0.0170963   |      0         |    0           |    0           |   0         |    0.45093    | 0.012      |  0.932       |            1        |             0.213165    |                0.999999    |            0.215       |               0.604    |        0.0308792   |                 0.172       |              0.209121    |
| adult_income        | gradient_boosting   | shap                    |                   |       0.00191215  |      0.21      |    0.03        |    0           |   0         |    0.489584   | 0.022      |  0.94        |            0.943182 |             0.182454    |                0.999989    |            0.1875      |               0.644    |        0.031611    |                 0.15        |              0.178389    |
| adult_income        | gradient_boosting   | lime                    |                   |       0.00900257  |      0.14      |    0.03        |    0           |   0         |    0.526593   | 0.036      |  0.958349    |            0.930233 |             0.170006    |                1           |            0.173898    |               0.608999 |        0.0169884   |                 0.138349    |              0.163012    |
| adult_income        | gradient_boosting   | causal_shap             |                   |       0.0400744   |      0.26      |    0.02        |    0           |   0         |    0.584814   | 0.032      |  0.956133    |            1        |             0.182119    |                0.999995    |            0.187823    |               0.612654 |        0.0283397   |                 0.149848    |              0.17166     |
| adult_income        | gradient_boosting   | shap_interactive        |                   |       0.00692     |      0.4       |    0           |    0           |   0         |    0          | 0          |  0.96        |            1        |             0.2         |                1           |            0.2         |               0.34     |       -1.24267e-11 |                 0.16        |              0.2         |
| adult_income        | gradient_boosting   | prototype               |                   |       0.00082162  |      0.69      |    0.816342    |    1           |   0         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| adult_income        | gradient_boosting   | counterfactual          |                   |       0.000641645 |      0.725     |    0.212966    |    1           |   0.765892  |    0.803611   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| adult_income        | gradient_boosting   | bayesian_rule_list      |                   |       0.000738451 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.581    |        0           |                 0           |              0           |
| adult_income        | gradient_boosting   | corels                  |                   |       0.000599761 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0.581    |        1           |                 2.22045e-16 |              0           |
| adult_income        | gradient_boosting   | feature_ablation        |                   |       0.000912256 |      0         |    0           |    0           |   0         |    0.495429   | 0.02       |  0.936       |            1        |             0.240412    |                0.999999    |            0.245       |               0.638    |        0.0222657   |                 0.196       |              0.237734    |
| adult_income        | mlp                 | shap                    |                   |       0.00233673  |      0.22      |    0.025       |    0           |   0         |    0.439579   | 0.026      |  0.942       |            0.903226 |             0.196995    |                1           |            0.2025      |               0.64     |        0.0258406   |                 0.162       |              0.194159    |
| adult_income        | mlp                 | lime                    |                   |       0.0188409   |      0.08      |    0.0316667   |    0           |   0         |    0.610452   | 0.072      |  0.954857    |            0.87234  |             0.102779    |                1           |            0.116439    |               0.569696 |        0.0521747   |                 0.0948573   |              0.0878253   |
| adult_income        | mlp                 | integrated_gradients    |                   |       0.0431746   |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.583333 |        0           |                 0           |              0           |
| adult_income        | mlp                 | causal_shap             |                   |       0.0177758   |      0.24      |    0.009       |    0           |   0         |    0.625643   | 0.036      |  0.966149    |            1        |             0.159127    |                1           |            0.16248     |               0.595332 |        0.0349001   |                 0.129767    |              0.1451      |
| adult_income        | mlp                 | shapley_flow            |                   |       0.007507    |      0.1       |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.583333 |        0           |                 0           |              0           |
| adult_income        | mlp                 | shap_interactive        |                   |       0.00410805  |      0.4       |    0           |    0           |   0         |    0          | 0          |  0.96        |            1        |             0.2         |                1           |            0.2         |               0.48     |       -1.24267e-11 |                 0.16        |              0.2         |
| adult_income        | mlp                 | prototype               |                   |       0.000751915 |      0.7       |    0.795118    |    1           |   0         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| adult_income        | mlp                 | counterfactual          |                   |       0.000457683 |      0.695     |    0.18711     |    1           |   0.942389  |    0.503033   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| adult_income        | mlp                 | influence_functions     |                   |       0.0183074   |      0         |    0           |    0           |   0.261524  |    0.438421   | 0.6        |  0.435751    |            1        |             0.425443    |                0.999999    |            0.510201    |               0.745377 |        0.776781    |                 0.435751    |              0.223219    |
| adult_income        | mlp                 | bayesian_rule_list      |                   |       0.000663841 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.574    |        0           |                 0           |              0           |
| adult_income        | mlp                 | corels                  |                   |       0.000361261 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0.574    |        1           |                 2.22045e-16 |              0           |
| adult_income        | mlp                 | feature_ablation        |                   |       0.000509605 |      0         |    0           |    0           |   0         |    0.437714   | 0.024      |  0.932       |            1        |             0.284495    |                1           |            0.29        |               0.636    |        0.0172271   |                 0.232       |              0.282773    |
| adult_income        | linear_regression   | lime                    |                   |       0.00958813  |      0.06      |    0           |    0           |   0         |    0.479851   | 0.096      |  0.942429    |            0.849057 |             0.102639    |                1           |            0.123349    |               0.510049 |        0.0745686   |                 0.102429    |              0.0854314   |
| adult_income        | linear_regression   | causal_shap             |                   |       0.0205704   |      0.1       |    0.01        |    0           |   0         |    0.538081   | 0.06       |  0.969567    |            1        |             0.0611028   |                1           |            0.0690038   |               0.505225 |        0.0499062   |                 0.0575667   |              0.0500938   |
| adult_income        | linear_regression   | shap_interactive        |                   |       0.00424924  |      0         |    0           |    0           |   0         |    0          | 0          |  0.96        |            0.8      |             0.2         |                1           |            0.2         |               0.48     |       -1.24267e-11 |                 0.16        |              0.2         |
| adult_income        | linear_regression   | prototype               |                   |       0.000817969 |      0.585     |    0.572482    |    1           |   0         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| adult_income        | linear_regression   | counterfactual          |                   |       0.000450317 |      0.6       |    0.433338    |    1           |   0.750384  |    0.531214   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| adult_income        | linear_regression   | bayesian_rule_list      |                   |       0.000539246 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.532    |        0           |                 0           |              0           |
| adult_income        | linear_regression   | corels                  |                   |       0.000333555 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0.532    |        1           |                 2.22045e-16 |              0           |
| adult_income        | linear_regression   | feature_ablation        |                   |       0.000488114 |      0         |    0           |    0           |   0         |    0.366667   | 0.056      |  0.956       |            1        |             0.0571548   |                1           |            0.07        |               0.52     |        0.0481062   |                 0.056       |              0.0518938   |
| adult_income        | logistic_regression | lime                    |                   |       0.00866231  |      0.04      |    0           |    0           |   0         |    0.52749    | 0.048      |  0.959863    |            0.851064 |             0.113255    |                0.5         |            0.123315    |               0.532823 |        0.0335016   |                 0.0998625   |              0.106498    |
| adult_income        | logistic_regression | causal_shap             |                   |       0.016878    |      0.14      |    0.04        |    0           |   0         |    0.551835   | 0.092      |  0.950881    |            0.990099 |             0.157521    |                0.999999    |            0.16235     |               0.545631 |        0.0953057   |                 0.134609    |              0.124694    |
| adult_income        | logistic_regression | shap_interactive        |                   |       0.00384393  |      0.2       |    0           |    0           |   0         |    0          | 0          |  0.96        |            1        |             0.2         |                1           |            0.2         |               0.34     |       -1.24267e-11 |                 0.16        |              0.2         |
| adult_income        | logistic_regression | prototype               |                   |       0.000736904 |      0.655     |    0.793164    |    1           |   0         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| adult_income        | logistic_regression | counterfactual          |                   |       0.000516241 |      0.685     |    0.194542    |    1           |   0.91168   |    0.859329   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| adult_income        | logistic_regression | influence_functions     |                   |       0.0140696   |      0         |    0           |    0           |   0.261524  |    0.438421   | 0.6        |  0.435751    |            1        |             0.425443    |                1           |            0.510201    |               0.640377 |        0.776781    |                 0.435751    |              0.223219    |
| adult_income        | logistic_regression | bayesian_rule_list      |                   |       0.000510683 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.56     |        0           |                 0           |              0           |
| adult_income        | logistic_regression | corels                  |                   |       0.000349255 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0.56     |        1           |                 2.22045e-16 |              0           |
| adult_income        | logistic_regression | feature_ablation        |                   |       0.000335207 |      0         |    0           |    0           |   0         |    0.518999   | 0.036      |  0.956       |            1        |             0.136742    |                1           |            0.145       |               0.552    |        0.0258406   |                 0.116       |              0.134159    |
| compas              | decision_tree       | shap                    |                   |       0.000647957 |      0.65      |    0.03        |    0           |   0         |    0.686124   | 0.35       |  0.7         |            0.629213 |             0.371231    |                0.999943    |            0.525       |               0.609    |        0.152495    |                 0.35        |              0.497505    |
| compas              | decision_tree       | lime                    |                   |       0.00910418  |      0.32      |    0.08        |    0           |   0         |    0.730212   | 0.613333   |  0.684714    |            0.520833 |             0.637566    |                1           |            0.90526     |               0.588193 |        0.0340977   |                 0.604714    |              0.885902    |
| compas              | decision_tree       | causal_shap             |                   |       0.00933827  |      0.48      |    0           |    4.44089e-18 |   0         |    0.636727   | 0.306667   |  0.763264    |            1        |             0.233133    |                0.999981    |            0.321456    |               0.402963 |        0.216285    |                 0.223699    |              0.263715    |
| compas              | decision_tree       | shapley_flow            |                   |       0.00433082  |      0.333333  |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.373333 |        0           |                 0           |              0           |
| compas              | decision_tree       | shap_interactive        |                   |       0.00151949  |      0.4       |    0           |    0           |   0         |    0          | 0.133333   |  0.933333    |            1        |             0.141421    |                1           |            0.2         |               0.48     |       -1.82048e-11 |                 0.133333    |              0.2         |
| compas              | decision_tree       | prototype               |                   |       0.000203884 |      0.655     |    0.737592    |    1           |   0         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| compas              | decision_tree       | counterfactual          |                   |       0.000204183 |      0.625     |    0.27163     |    1           |   0.977457  |    0.483548   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| compas              | decision_tree       | bayesian_rule_list      |                   |       0.000356064 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.42     |        0           |                 0           |              0           |
| compas              | decision_tree       | corels                  |                   |       0.000209913 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0.42     |        1           |                 0           |              0           |
| compas              | decision_tree       | feature_ablation        |                   |       0.000267768 |      0         |    0           |    0           |   0         |    0.674688   | 0.366667   |  0.666667    |            1        |             0.388909    |                0.999986    |            0.55        |               0.526    |        0.184042    |                 0.366667    |              0.515958    |
| compas              | random_forest       | shap                    |                   |       0.017429    |      0.63      |    0.0383333   |    0           |   0         |    0.716393   | 0.323333   |  0.693333    |            0.654762 |             0.342947    |                0.999957    |            0.485       |               0.624    |        0.177732    |                 0.323333    |              0.452268    |
| compas              | random_forest       | lime                    |                   |       0.0179551   |      0.36      |    0.03        |    0           |   0         |    0.776242   | 0.473333   |  0.697164    |            0.605263 |             0.430531    |                1           |            0.615185    |               0.541543 |        0.166385    |                 0.417164    |              0.553615    |
| compas              | random_forest       | causal_shap             |                   |       0.348181    |      0.48      |    0.03        |    0           |   0         |    0.648555   | 0.32       |  0.755814    |            1        |             0.228269    |                0.999994    |            0.307355    |               0.455589 |        0.265855    |                 0.216756    |              0.234145    |
| compas              | random_forest       | shapley_flow            |                   |       0.185389    |      0.433333  |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.373333 |        0           |                 0           |              0           |
| compas              | random_forest       | shap_interactive        |                   |       0.0539635   |      0.4       |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.56     |        0           |                 0           |              0           |
| compas              | random_forest       | prototype               |                   |       0.00353607  |      0.615     |    0.697396    |    1           |   0.970614  |    0.358739   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| compas              | random_forest       | counterfactual          |                   |       0.00554905  |      0.695     |    0.297492    |    1           |   0.927032  |    0.569789   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| compas              | random_forest       | bayesian_rule_list      |                   |       0.00507622  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.441    |        0           |                 0           |              0           |
| compas              | random_forest       | corels                  |                   |       0.00388963  |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0.441    |        1           |                 0           |              0           |
| compas              | random_forest       | feature_ablation        |                   |       0.019964    |      0         |    0           |    0           |   0         |    0.711828   | 0.293333   |  0.633333    |            1        |             0.311127    |                0.999895    |            0.44        |               0.564    |        0.267135    |                 0.293333    |              0.392865    |
| compas              | gradient_boosting   | shap                    |                   |       0.00131239  |      0.61      |    0.025       |    0           |   0         |    0.709605   | 0.323333   |  0.713333    |            0.670455 |             0.342947    |                0.999888    |            0.485       |               0.649    |        0.155114    |                 0.323333    |              0.454886    |
| compas              | gradient_boosting   | lime                    |                   |       0.0125057   |      0.4       |    0.14        |    0           |   0.398965  |    0.912444   | 0.56       |  0.70961     |            0.568182 |             0.579534    |                1           |            0.823936    |               0.646938 |        0.0426865   |                 0.54961     |              0.797314    |
| compas              | gradient_boosting   | causal_shap             |                   |       0.0284174   |      0.46      |    0.03        |    0           |   0         |    0.632639   | 0.326667   |  0.673371    |            1        |             0.169995    |                0.998962    |            0.230199    |               0.451805 |        0.327131    |                 0.173371    |              0.172869    |
| compas              | gradient_boosting   | shap_interactive        |                   |       0.00630717  |      0.2       |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.56     |        0           |                 0           |              0           |
| compas              | gradient_boosting   | prototype               |                   |       0.000464025 |      0.695     |    0.69324     |    1           |   0         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| compas              | gradient_boosting   | counterfactual          |                   |       0.000505896 |      0.645     |    0.30753     |    1           |   0.989578  |    0.917819   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| compas              | gradient_boosting   | bayesian_rule_list      |                   |       0.00107957  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.469    |        0           |                 0           |              0           |
| compas              | gradient_boosting   | corels                  |                   |       0.000486562 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0.469    |        1           |                 0           |              0           |
| compas              | gradient_boosting   | feature_ablation        |                   |       0.00065587  |      0         |    0           |    0           |   0         |    0.681452   | 0.333333   |  0.693333    |            1        |             0.353553    |                1           |            0.5         |               0.598    |        0.17666     |                 0.333333    |              0.46334     |
| compas              | mlp                 | shap                    |                   |       0.00237506  |      0.58      |    0.01        |    0           |   0         |    0.743194   | 0.38       |  0.8         |            0.655556 |             0.403051    |                1           |            0.57        |               0.643    |        0.0126186   |                 0.38        |              0.567381    |
| compas              | mlp                 | lime                    |                   |       0.00906323  |      0.04      |    0           |    0           |   0         |    0.796976   | 0.333333   |  0.810077    |            0.642857 |             0.320912    |                1           |            0.458988    |               0.533033 |        0.0738206   |                 0.310077    |              0.426179    |
| compas              | mlp                 | integrated_gradients    |                   |       0.0249797   |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.42     |        0           |                 0           |              0           |
| compas              | mlp                 | causal_shap             |                   |       0.0109186   |      0.34      |    0           |    0           |   0         |    0.581651   | 0.293333   |  0.80301     |            1        |             0.256681    |                1           |            0.345589    |               0.505247 |        0.146169    |                 0.236535    |              0.313831    |
| compas              | mlp                 | shapley_flow            |                   |       0.00664547  |      0.233333  |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.42     |        0           |                 0           |              0           |
| compas              | mlp                 | shap_interactive        |                   |       0.00166326  |      0         |    0           |    0           |   0.0202041 |    0.666667   | 0.266667   |  0.666667    |            0.75     |             0.282843    |                0.999999    |            0.4         |               0.6      |        0.252372    |                 0.266667    |              0.347628    |
| compas              | mlp                 | prototype               |                   |       0.000204664 |      0.67      |    0.684513    |    1           |   0         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| compas              | mlp                 | counterfactual          |                   |       0.000368925 |      0.675     |    0.310902    |    1           |   0.955895  |    0.61676    | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| compas              | mlp                 | influence_functions     |                   |       0.0173557   |      0         |    0           |    0           |   0.38339   |    0.718421   | 0.666667   |  0.432507    |            1        |             0.419383    |                1           |            0.607785    |               0.635607 |        0.641524    |                 0.432507    |              0.358476    |
| compas              | mlp                 | bayesian_rule_list      |                   |       0.000374177 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.469    |        0           |                 0           |              0           |
| compas              | mlp                 | corels                  |                   |       0.000228446 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0.469    |        1           |                 0           |              0           |
| compas              | mlp                 | feature_ablation        |                   |       0.000305676 |      0         |    0           |    0           |   0         |    0.716749   | 0.38       |  0.8         |            1        |             0.403051    |                1           |            0.57        |               0.58     |        0.0126186   |                 0.38        |              0.567381    |
| compas              | linear_regression   | lime                    |                   |       0.00924299  |      0.14      |    0.01        |    0           |   0         |    0.64641    | 0.08       |  0.942296    |            0.96875  |             0.0650264   |                1           |            0.0908107   |               0.458496 |        0.0367762   |                 0.0622963   |              0.0832238   |
| compas              | linear_regression   | causal_shap             |                   |       0.00870787  |      0.28      |    0.01        |    0           |   0         |    0.601387   | 0.24       |  0.823794    |            1        |             0.212875    |                0.999999    |            0.301392    |               0.512321 |        0.100296    |                 0.203794    |              0.279704    |
| compas              | linear_regression   | shap_interactive        |                   |       0.00121598  |      0         |    0           |    0           |   0.0202041 |    0.666667   | 0.266667   |  0.666667    |            0.75     |             0.282843    |                1           |            0.4         |               0.6      |        0.252372    |                 0.266667    |              0.347628    |
| compas              | linear_regression   | prototype               |                   |       0.000227772 |      0.65      |    0.607879    |    1           |   0         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| compas              | linear_regression   | counterfactual          |                   |       0.000206215 |      0.71      |    0.387895    |    1           |   0.966365  |    0.220863   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| compas              | linear_regression   | bayesian_rule_list      |                   |       0.000379934 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.483    |        0           |                 0           |              0           |
| compas              | linear_regression   | corels                  |                   |       0.000210156 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0.483    |        1           |                 0           |              0           |
| compas              | linear_regression   | feature_ablation        |                   |       0.000541501 |      0         |    0           |    0           |   0         |    0.761667   | 0.326667   |  0.826667    |            1        |             0.346482    |                1           |            0.49        |               0.584    |        0.0126186   |                 0.326667    |              0.487381    |
| compas              | logistic_regression | lime                    |                   |       0.00782068  |      0.16      |    0           |    0           |   0         |    0.455342   | 0.04       |  0.972135    |            0.96875  |             0.0330274   |                0.5         |            0.0474952   |               0.44568  |        0.019091    |                 0.0321351   |              0.040909    |
| compas              | logistic_regression | causal_shap             |                   |       0.00791212  |      0.3       |    0           |    0           |   0         |    0.598099   | 0.24       |  0.829187    |            1        |             0.219596    |                1           |            0.310738    |               0.516668 |        0.0879886   |                 0.209187    |              0.292011    |
| compas              | logistic_regression | shap_interactive        |                   |       0.00346007  |      0         |    0           |    0           |   0.0202041 |    0.666667   | 0.266667   |  0.666667    |            0.75     |             0.282843    |                0.999999    |            0.4         |               0.6      |        0.252372    |                 0.266667    |              0.347628    |
| compas              | logistic_regression | prototype               |                   |       0.000208685 |      0.69      |    0.649615    |    1           |   0.927367  |    0.999285   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| compas              | logistic_regression | counterfactual          |                   |       0.000199471 |      0.65      |    0.361943    |    1           |   0.992163  |    0.311146   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| compas              | logistic_regression | influence_functions     |                   |       0.0145357   |      0         |    0           |    0           |   0.38339   |    0.718421   | 0.666667   |  0.432507    |            1        |             0.419383    |                0.999999    |            0.607785    |               0.670607 |        0.641524    |                 0.432507    |              0.358476    |
| compas              | logistic_regression | bayesian_rule_list      |                   |       0.000352829 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.469    |        0           |                 0           |              0           |
| compas              | logistic_regression | corels                  |                   |       0.000203207 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0.469    |        1           |                 0           |              0           |
| compas              | logistic_regression | feature_ablation        |                   |       0.000236521 |      0         |    0           |    0           |   0         |    0.783476   | 0.36       |  0.82        |            1        |             0.381838    |                1           |            0.54        |               0.596    |       -4.91529e-11 |                 0.36        |              0.54        |
| breast_cancer       | decision_tree       | shap                    |                   |       0.00219252  |      0.19      |    0           |    0           |   0         |    0.204814   | 0          |  0.991333    |            0.861111 |             0.19        |                1           |            0.187586    |               0.687    |        0.0142657   |                 0.181333    |              0.175734    |
| breast_cancer       | decision_tree       | lime                    |                   |       0.0081867   |      0.08      |    0           |    0           |   0         |    0.282253   | 0.0146667  |  0.990987    |            0.818182 |             0.2         |                0.5         |            0.197496    |               0.676901 |        0.020977    |                 0.190987    |              0.179023    |
| breast_cancer       | decision_tree       | causal_shap             |                   |       0.0910866   |      0.4       |    0.00666667  |    0           |   1         |    0.520001   | 0          |  1           |            1        |             0.46        |                1           |            0.452729    |               0.734478 |        0.0616651   |                 0.437985    |              0.398335    |
| breast_cancer       | decision_tree       | shapley_flow            |                   |       0.0389063   |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.676667 |        0           |                 0           |              0           |
| breast_cancer       | decision_tree       | shap_interactive        |                   |       0.0046947   |      0.6       |    0           |    0           |   1         |    0.543804   | 0          |  1           |            0.666667 |             0.8         |                1           |            0.772414    |               0.94     |        0.129203    |                 0.746667    |              0.670797    |
| breast_cancer       | decision_tree       | prototype               |                   |       0.000114384 |      0.912281  |    0.951792    |    1           |   0.860339  |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| breast_cancer       | decision_tree       | counterfactual          |                   |       0.000131072 |      0.912281  |    0.0797843   |    1           |   0.135535  |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| breast_cancer       | decision_tree       | bayesian_rule_list      |                   |       0.00176833  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.63     |        0           |                 0           |              0           |
| breast_cancer       | decision_tree       | corels                  |                   |       0.00101405  |      0         |    0           |    0           |   0         |    0.151065   | 0          |  0.935823    |            1        |             1           |                1           |            0.966274    |               0.774655 |        0.202057    |                 0.935823    |              0.797943    |
| breast_cancer       | decision_tree       | feature_ablation        |                   |       0.0018799   |      0         |    0           |    0           |   0         |    0.175661   | 0          |  0.99        |            1        |             0.22        |                1           |            0.217241    |               0.696    |        0.0163036   |                 0.21        |              0.203696    |
| breast_cancer       | random_forest       | shap                    |                   |       0.0946088   |      0.02      |    0           |    0           |   0         |    0.196116   | 0          |  0.997667    |            0.905405 |             0.02        |                0.5         |            0.0182759   |               0.671    |        0.00730598  |                 0.0176667   |              0.012694    |
| breast_cancer       | random_forest       | lime                    |                   |       0.0176719   |      0         |    0           |    0           |   0         |    0.161335   | 0.0733333  |  0.976573    |            0.815789 |             0.13273     |                0.5         |            0.120643    |               0.670449 |        0.0672942   |                 0.116573    |              0.0727058   |
| breast_cancer       | random_forest       | causal_shap             |                   |       4.05819     |      0.04      |    0           |    0           |   1         |    0.356059   | 0.130667   |  1           |            0.996785 |             0.392976    |                0.999998    |            0.340695    |               0.697496 |        0.207435    |                 0.331293    |              0.192565    |
| breast_cancer       | random_forest       | shapley_flow            |                   |       1.98121     |      0         |    0           |    0           |   0         |    0          | 0          |  0.998889    |            1        |             0.0333333   |                0.5         |            0.0333333   |               0.663333 |       -9.80047e-13 |                 0.0322222   |              0.0333333   |
| breast_cancer       | random_forest       | shap_interactive        |                   |       0.254072    |      0         |    0           |    0           |   1         |    1          | 0          |  1           |            1        |             0.6         |                1           |            0.6         |               0.74     |       -1.76408e-11 |                 0.58        |              0.6         |
| breast_cancer       | random_forest       | prototype               |                   |       0.00329801  |      0.95614   |    0.923974    |    1           |   0.594429  |    0.582042   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| breast_cancer       | random_forest       | counterfactual          |                   |       0.00351322  |      0.95614   |    0.149001    |    1           |   0.739921  |    0.929266   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| breast_cancer       | random_forest       | bayesian_rule_list      |                   |       0.00580185  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.665    |        0           |                 0           |              0           |
| breast_cancer       | random_forest       | corels                  |                   |       0.00517552  |      0         |    0           |    0           |   0         |    0.151065   | 0          |  0.935823    |            1        |             1           |                1           |            0.966274    |               0.809655 |        0.202057    |                 0.935823    |              0.797943    |
| breast_cancer       | random_forest       | feature_ablation        |                   |       0.106547    |      0         |    0           |    0           |   0         |    0.196116   | 0          |  0.995333    |            1        |             0.04        |                0.5         |            0.0365517   |               0.67     |        0.014612    |                 0.0353333   |              0.025388    |
| breast_cancer       | gradient_boosting   | shap                    |                   |       0.00630918  |      0.08      |    0           |    0           |   0         |    0.190397   | 0          |  0.996       |            0.96875  |             0.09        |                1           |            0.0889655   |               0.692    |        0.00611385  |                 0.086       |              0.0838861   |
| breast_cancer       | gradient_boosting   | lime                    |                   |       0.00935741  |      0         |    0           |    0           |   0         |    0.116412   | 0.0146667  |  0.994671    |            1        |             0.04        |                0.5         |            0.0372097   |               0.675709 |        0.0179858   |                 0.0346708   |              0.0220142   |
| breast_cancer       | gradient_boosting   | causal_shap             |                   |       0.22613     |      0.08      |    0           |    0           |   0         |    0.378499   | 0.0726667  |  0.991218    |            1        |             0.64        |                0.999999    |            0.573311    |               0.807278 |        0.276708    |                 0.558728    |              0.363292    |
| breast_cancer       | gradient_boosting   | shap_interactive        |                   |       0.0167996   |      0         |    0           |    0           |   0         |    0.291687   | 0.126667   |  0.86        |            0.285714 |             0.931426    |                1           |            0.889655    |               0.86     |        0.317161    |                 0.86        |              0.682839    |
| breast_cancer       | gradient_boosting   | prototype               |                   |       0.00023589  |      0.95614   |    0.95109     |    1           |   0.915196  |    0.0686003  | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| breast_cancer       | gradient_boosting   | counterfactual          |                   |       0.000278153 |      0.95614   |    0.0961155   |    1           |   0.604589  |    0.84873    | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| breast_cancer       | gradient_boosting   | bayesian_rule_list      |                   |       0.00223126  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.665    |        0           |                 0           |              0           |
| breast_cancer       | gradient_boosting   | corels                  |                   |       0.00156011  |      0         |    0           |    0           |   0         |    0.151065   | 0          |  0.935823    |            1        |             1           |                1           |            0.966274    |               0.809655 |        0.202057    |                 0.935823    |              0.797943    |
| breast_cancer       | gradient_boosting   | feature_ablation        |                   |       0.00530326  |      0         |    0           |    0           |   0         |    0.163174   | 0          |  0.994       |            1        |             0.12        |                1           |            0.117931    |               0.708    |        0.0122277   |                 0.114       |              0.107772    |
| breast_cancer       | mlp                 | shap                    |                   |       0.00338436  |      0.06      |    0           |    0           |   0         |    0.263996   | 0.0126667  |  0.990667    |            0.953846 |             0.0633553   |                0.5         |            0.0627586   |               0.679    |        0.0160394   |                 0.0606667   |              0.0539606   |
| breast_cancer       | mlp                 | lime                    |                   |       0.00947318  |      0.04      |    0           |    0           |   0         |    0.238983   | 0.0146667  |  0.992257    |            0.875    |             0.08        |                0.5         |            0.0745256   |               0.653551 |        0.028322    |                 0.072257    |              0.051678    |
| breast_cancer       | mlp                 | integrated_gradients    |                   |       0.272118    |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.653333 |        0           |                 0           |              0           |
| breast_cancer       | mlp                 | causal_shap             |                   |       0.124999    |      0.1       |    0.00571429  |    0           |   1         |    0.228945   | 0.166      |  1           |            0.972222 |             0.435915    |                0.999999    |            0.381773    |               0.744732 |        0.218036    |                 0.36839     |              0.241964    |
| breast_cancer       | mlp                 | shapley_flow            |                   |       0.0519368   |      0.0333333 |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.653333 |        0           |                 0           |              0           |
| breast_cancer       | mlp                 | shap_interactive        |                   |       0.00627279  |      0.2       |    0           |    0           |   1         |    0.241683   | 0.193333   |  1           |            0.166667 |             0.775617    |                1           |            0.703448    |               0.86     |        0.625489    |                 0.68        |              0.374511    |
| breast_cancer       | mlp                 | prototype               |                   |       0.000158065 |      0.947368  |    0.945946    |    1           |   0.960662  |    0.378421   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| breast_cancer       | mlp                 | counterfactual          |                   |       0.000204139 |      0.947368  |    0.0955593   |    1           |   0.558347  |    0.981209   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| breast_cancer       | mlp                 | influence_functions     |                   |       0.0198234   |      0         |    0           |    0           |   0.359116  |    0.253196   | 0.733333   |  0.352584    |            1        |             0.321031    |                0.999999    |            0.300094    |               0.93     |        0.933337    |                 0.352584    |              0.0666627   |
| breast_cancer       | mlp                 | bayesian_rule_list      |                   |       0.00210275  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.658    |        0           |                 0           |              0           |
| breast_cancer       | mlp                 | corels                  |                   |       0.00118577  |      0         |    0           |    0           |   0         |    0.151065   | 0          |  0.935823    |            1        |             1           |                1           |            0.966274    |               0.802655 |        0.202057    |                 0.935823    |              0.797943    |
| breast_cancer       | mlp                 | feature_ablation        |                   |       0.00302013  |      0         |    0           |    0           |   0         |    0.267337   | 0.0253333  |  0.982667    |            1        |             0.0867107   |                0.5         |            0.0855172   |               0.674    |        0.0320788   |                 0.0826667   |              0.0679212   |
| breast_cancer       | linear_regression   | lime                    |                   |       0.0122959   |      0         |    0.00166667  |    0           |   0         |    0.239187   | 0.132      |  0.959597    |            0.717391 |             0.299727    |                0.998045    |            0.272906    |               0.688513 |        0.128027    |                 0.259597    |              0.171973    |
| breast_cancer       | linear_regression   | causal_shap             |                   |       0.098817    |      0.24      |    0.00125     |    6.66134e-18 |   1         |    0.448309   | 0.253333   |  1           |            0.87766  |             0.36922     |                0.999999    |            0.308883    |               0.75034  |        0.233836    |                 0.294997    |              0.146164    |
| breast_cancer       | linear_regression   | shap_interactive        |                   |       0.00514154  |      0.4       |    0           |    0           |   1         |    0.415671   | 0          |  1           |            0.285714 |             0.8         |                1           |            0.737931    |               0.94     |        0.264602    |                 0.713333    |              0.535398    |
| breast_cancer       | linear_regression   | prototype               |                   |       0.00015534  |      0.95614   |    0.696639    |    1           |   0.873638  |    0.47183    | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| breast_cancer       | linear_regression   | counterfactual          |                   |       0.000155773 |      0.95614   |    0.431353    |    1           |   0.171567  |    0.34182    | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| breast_cancer       | linear_regression   | bayesian_rule_list      |                   |       0.00210868  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.665    |        0           |                 0           |              0           |
| breast_cancer       | linear_regression   | corels                  |                   |       0.0018031   |      0         |    0           |    0           |   0         |    0.151065   | 0          |  0.935823    |            1        |             1           |                1           |            0.966274    |               0.809655 |        0.202057    |                 0.935823    |              0.797943    |
| breast_cancer       | linear_regression   | feature_ablation        |                   |       0.00191688  |      0         |    0           |    0           |   0         |    0.661155   | 0.0126667  |  0.939333    |            1        |             0.811269    |                1           |            0.785517    |               0.904    |        0.152588    |                 0.759333    |              0.667412    |
| breast_cancer       | logistic_regression | lime                    |                   |       0.0104887   |      0.02      |    0           |    0           |   0         |    0.280589   | 0.0146667  |  0.994787    |            0.911765 |             0.06        |                0.5         |            0.0565755   |               0.693785 |        0.0194039   |                 0.0547871   |              0.0405961   |
| breast_cancer       | logistic_regression | causal_shap             |                   |       0.0971852   |      0.04      |    0           |    0           |   1         |    0.220865   | 0.111333   |  1           |            0.939394 |             0.420301    |                1           |            0.37064     |               0.769439 |        0.210046    |                 0.357988    |              0.229954    |
| breast_cancer       | logistic_regression | shap_interactive        |                   |       0.00615349  |      0         |    0           |    0           |   1         |    0.243782   | 0.32       |  1           |            0.333333 |             0.724967    |                1           |            0.717241    |               1        |        0.544798    |                 0.693333    |              0.455202    |
| breast_cancer       | logistic_regression | prototype               |                   |       0.000127682 |      0.982456  |    0.933096    |    1           |   0.7366    |    0.417443   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| breast_cancer       | logistic_regression | counterfactual          |                   |       0.000127274 |      0.982456  |    0.125231    |    1           |   0.906462  |    0.231799   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| breast_cancer       | logistic_regression | influence_functions     |                   |       0.0233094   |      0         |    0           |    0           |   0.359116  |    0.253196   | 0.733333   |  0.352584    |            1        |             0.321031    |                0.999999    |            0.300094    |               0.965    |        0.933337    |                 0.352584    |              0.0666627   |
| breast_cancer       | logistic_regression | bayesian_rule_list      |                   |       0.00192804  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.686    |        0           |                 0           |              0           |
| breast_cancer       | logistic_regression | corels                  |                   |       0.00107661  |      0         |    0           |    0           |   0         |    0.151065   | 0          |  0.935823    |            1        |             1           |                1           |            0.966274    |               0.830655 |        0.202057    |                 0.935823    |              0.797943    |
| breast_cancer       | logistic_regression | feature_ablation        |                   |       0.00197871  |      0         |    0           |    0           |   0         |    0.178422   | 0          |  0.991333    |            1        |             0.0781265   |                0.999999    |            0.0737931   |               0.71     |        0.0236702   |                 0.0713333   |              0.0563298   |
| heart_disease       | decision_tree       | shap                    |                   |       0.000638433 |      0.666667  |    0.00833333  |    0           |   0         |    0.471527   | 0.0866667  |  0.82        |            0.508475 |             0.589218    |                1           |            0.608333    |               0.713333 |        0.087355    |                 0.486667    |              0.579312    |
| heart_disease       | decision_tree       | lime                    |                   |       0.0095073   |      0.2       |    0.02        |    0           |   0         |    0.545724   | 0.012      |  0.957873    |            0.794118 |             0.194312    |                1           |            0.196799    |               0.589073 |        0.00719578  |                 0.157873    |              0.192804    |
| heart_disease       | decision_tree       | causal_shap             |                   |       0.0157738   |      0.44      |    0.00666667  |    0           |   1         |    0.557795   | 0.156      |  1           |            1        |             0.362353    |                0.999962    |            0.373513    |               0.640816 |        0.146088    |                 0.306199    |              0.313912    |
| heart_disease       | decision_tree       | shapley_flow            |                   |       0.00725129  |      0.2       |    0.0333333   |    0           |   0         |    0          | 0          |  0.993333    |            1        |             0.0333333   |                0.5         |            0.0333333   |               0.57     |       -2.07112e-12 |                 0.0266667   |              0.0333333   |
| heart_disease       | decision_tree       | shap_interactive        |                   |       0.00473285  |      0.8       |    0           |    0           |   1         |    0.806186   | 0.12       |  1           |            1        |             0.722474    |                1           |            0.75        |               0.94     |        0.0861353   |                 0.6         |              0.713865    |
| heart_disease       | decision_tree       | prototype               |                   |       0.0001333   |      0.733333  |    0.983146    |    1           |   0.930747  |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| heart_disease       | decision_tree       | counterfactual          |                   |       0.00025423  |      0.733333  |    0.0204878   |    1           |   0.929938  |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| heart_disease       | decision_tree       | bayesian_rule_list      |                   |       0.000483616 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.513333 |        0           |                 0           |              0           |
| heart_disease       | decision_tree       | corels                  |                   |       0.000227372 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0.513333 |        1           |                 2.22045e-16 |              0           |
| heart_disease       | decision_tree       | feature_ablation        |                   |       0.000374026 |      0         |    0           |    0           |   0         |    0.462711   | 0.092      |  0.82        |            1        |             0.554815    |                0.99999     |            0.575       |               0.724    |        0.0962125   |                 0.46        |              0.543788    |
| heart_disease       | random_forest       | shap                    |                   |       0.0272484   |      0.516667  |    0.00555556  |    0           |   0         |    0.49582    | 0.0666667  |  0.87        |            0.545455 |             0.468041    |                1           |            0.483333    |               0.668333 |        0.0544444   |                 0.386667    |              0.462222    |
| heart_disease       | random_forest       | lime                    |                   |       0.0227753   |      0.18      |    0           |    0           |   0         |    0.450644   | 0.168      |  0.897626    |            0.787879 |             0.212586    |                1           |            0.241836    |               0.565919 |        0.117728    |                 0.197626    |              0.182272    |
| heart_disease       | random_forest       | causal_shap             |                   |       0.672519    |      0.28      |    0.004       |    0           |   1         |    0.435667   | 0.296      |  1           |            0.893471 |             0.267283    |                0.999994    |            0.239473    |               0.610979 |        0.394587    |                 0.212136    |              0.125413    |
| heart_disease       | random_forest       | shapley_flow            |                   |       0.334823    |      0.166667  |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.56     |        0           |                 0           |              0           |
| heart_disease       | random_forest       | shap_interactive        |                   |       0.156237    |      0         |    0           |    0           |   1         |    0.605499   | 0.2        |  1           |            0.25     |             0.213299    |                0.999987    |            0.25        |               0.74     |        0.845313    |                 0.2         |              0.154687    |
| heart_disease       | random_forest       | prototype               |                   |       0.00393958  |      0.733333  |    0.734603    |    1           |   0.88861   |    0.547325   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| heart_disease       | random_forest       | counterfactual          |                   |       0.00357092  |      0.733333  |    0.302171    |    1           |   0.781785  |    0.701236   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| heart_disease       | random_forest       | bayesian_rule_list      |                   |       0.00381933  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.513333 |        0           |                 0           |              0           |
| heart_disease       | random_forest       | corels                  |                   |       0.0035134   |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0.513333 |        1           |                 2.22045e-16 |              0           |
| heart_disease       | random_forest       | feature_ablation        |                   |       0.0191042   |      0         |    0           |    0           |   0         |    0.485887   | 0.056      |  0.868       |            1        |             0.497155    |                1           |            0.51        |               0.68     |        0.0481062   |                 0.408       |              0.491894    |
| heart_disease       | gradient_boosting   | shap                    |                   |       0.00190256  |      0.55      |    0.0333333   |    0           |   0         |    0.462958   | 0.06       |  0.87        |            0.6      |             0.511237    |                1           |            0.525       |               0.655    |        0.0430677   |                 0.42        |              0.506932    |
| heart_disease       | gradient_boosting   | lime                    |                   |       0.00996855  |      0.1       |    0           |    0           |   0         |    0.487513   | 0.168      |  0.889086    |            0.83871  |             0.276814    |                1           |            0.307825    |               0.556944 |        0.114534    |                 0.249086    |              0.245466    |
| heart_disease       | gradient_boosting   | causal_shap             |                   |       0.0358846   |      0.32      |    0.02        |    0           |   1         |    0.498608   | 0.22       |  1           |            1        |             0.310348    |                0.999999    |            0.324827    |               0.574793 |        0.249075    |                 0.270307    |              0.230925    |
| heart_disease       | gradient_boosting   | shap_interactive        |                   |       0.0102649   |      0.4       |    0           |    0           |   1         |    0.612372   | 0.12       |  1           |            1        |             0.322474    |                1           |            0.35        |               0.68     |        0.0861353   |                 0.28        |              0.313865    |
| heart_disease       | gradient_boosting   | prototype               |                   |       0.000256391 |      0.7       |    0.80273     |    1           |   0.921137  |    0.182381   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| heart_disease       | gradient_boosting   | counterfactual          |                   |       0.000315722 |      0.7       |    0.233586    |    1           |   0.919427  |    0.420574   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| heart_disease       | gradient_boosting   | bayesian_rule_list      |                   |       0.000923057 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.49     |        0           |                 0           |              0           |
| heart_disease       | gradient_boosting   | corels                  |                   |       0.000434478 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0.49     |        1           |                 2.22045e-16 |              0           |
| heart_disease       | gradient_boosting   | feature_ablation        |                   |       0.00169423  |      0         |    0           |    0           |   0         |    0.454031   | 0.06       |  0.876       |            1        |             0.481237    |                1           |            0.495       |               0.646    |        0.0430677   |                 0.396       |              0.476932    |
| heart_disease       | mlp                 | shap                    |                   |       0.000844347 |      0.383333  |    0.0166667   |    0           |   0         |    0.487481   | 0.08       |  0.896667    |            0.730769 |             0.33165     |                0.999999    |            0.35        |               0.675    |        0.0574235   |                 0.28        |              0.32591     |
| heart_disease       | mlp                 | lime                    |                   |       0.0100713   |      0.06      |    0.04        |    0           |   0         |    0.408501   | 0.18       |  0.874232    |            0.738095 |             0.228488    |                0.999996    |            0.261596    |               0.609839 |        0.14639     |                 0.214232    |              0.19361     |
| heart_disease       | mlp                 | integrated_gradients    |                   |       0.0427217   |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.63     |        0           |                 0           |              0           |
| heart_disease       | mlp                 | causal_shap             |                   |       0.0201604   |      0.26      |    0.005       |    0           |   0         |    0.443829   | 0.212      |  0.92376     |            0.990415 |             0.266766    |                1           |            0.275456    |               0.638916 |        0.222787    |                 0.228116    |              0.177213    |
| heart_disease       | mlp                 | shapley_flow            |                   |       0.00865595  |      0.1       |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.63     |        0           |                 0           |              0           |
| heart_disease       | mlp                 | shap_interactive        |                   |       0.0042151   |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.7      |        0           |                 0           |              0           |
| heart_disease       | mlp                 | prototype               |                   |       0.000130606 |      0.8       |    0.783445    |    1           |   0.853825  |    0.666336   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| heart_disease       | mlp                 | counterfactual          |                   |       0.000127065 |      0.8       |    0.251229    |    1           |   0.901556  |    0.257826   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| heart_disease       | mlp                 | influence_functions     |                   |       0.0197189   |      0         |    0           |    0           |   0.441602  |    0.427895   | 0.6        |  0.304923    |            1        |             0.281592    |                0.999999    |            0.30181     |               0.800992 |        0.88192     |                 0.304923    |              0.11808     |
| heart_disease       | mlp                 | bayesian_rule_list      |                   |       0.000485476 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.56     |        0           |                 0           |              0           |
| heart_disease       | mlp                 | corels                  |                   |       0.000290767 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0.56     |        1           |                 2.22045e-16 |              0           |
| heart_disease       | mlp                 | feature_ablation        |                   |       0.000479946 |      0         |    0           |    0           |   0         |    0.459181   | 0.084      |  0.892       |            1        |             0.345732    |                1           |            0.365       |               0.68     |        0.0602947   |                 0.292       |              0.339705    |
| heart_disease       | linear_regression   | lime                    |                   |       0.0133485   |      0         |    0           |    0           |   0         |    0.542128   | 0.108      |  0.929543    |            0.848485 |             0.189072    |                0.999982    |            0.209476    |               0.620417 |        0.0710648   |                 0.169543    |              0.168935    |
| heart_disease       | linear_regression   | causal_shap             |                   |       0.0152587   |      0.26      |    0           |    0           |   0         |    0.529488   | 0.148      |  0.919731    |            0.996441 |             0.386285    |                0.999988    |            0.390169    |               0.689384 |        0.129868    |                 0.314674    |              0.330132    |
| heart_disease       | linear_regression   | shap_interactive        |                   |       0.0041873   |      0         |    0           |    0           |   0         |    0          | 0          |  0.96        |            0.833333 |             0.2         |                1           |            0.2         |               0.76     |       -1.24267e-11 |                 0.16        |              0.2         |
| heart_disease       | linear_regression   | prototype               |                   |       0.00011096  |      0.816667  |    0.625645    |    1           |   0.877491  |    0.164073   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| heart_disease       | linear_regression   | counterfactual          |                   |       0.000127884 |      0.816667  |    0.411697    |    1           |   0.807352  |    0.553753   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| heart_disease       | linear_regression   | bayesian_rule_list      |                   |       0.000474882 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.571667 |        0           |                 0           |              0           |
| heart_disease       | linear_regression   | corels                  |                   |       0.000411503 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0.571667 |        1           |                 2.22045e-16 |              0           |
| heart_disease       | linear_regression   | feature_ablation        |                   |       0.000341601 |      0         |    0           |    0           |   0         |    0.593668   | 0.024      |  0.916       |            1        |             0.364495    |                1           |            0.37        |               0.688    |        0.0172271   |                 0.296       |              0.362773    |
| heart_disease       | logistic_regression | lime                    |                   |       0.0107348   |      0.02      |    0.01        |    0           |   0         |    0.640783   | 0.084      |  0.936432    |            0.870968 |             0.15146     |                1           |            0.167539    |               0.596768 |        0.0643473   |                 0.136432    |              0.135653    |
| heart_disease       | logistic_regression | causal_shap             |                   |       0.0156687   |      0.24      |    0.02        |    2.22045e-18 |   0         |    0.530908   | 0.212      |  0.900411    |            0.927835 |             0.391567    |                1           |            0.396974    |               0.676396 |        0.181188    |                 0.324503    |              0.318812    |
| heart_disease       | logistic_regression | shap_interactive        |                   |       0.00300074  |      0.2       |    0.2         |    0           |   0         |    0.408248   | 0.12       |  0.88        |            0.8      |             0.322474    |                1           |            0.35        |               0.68     |        0.0861353   |                 0.28        |              0.313865    |
| heart_disease       | logistic_regression | prototype               |                   |       0.000141068 |      0.8       |    0.751334    |    1           |   0.884669  |    0.978477   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| heart_disease       | logistic_regression | counterfactual          |                   |       0.000198444 |      0.8       |    0.286008    |    1           |   0.964583  |    0.0165156  | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| heart_disease       | logistic_regression | influence_functions     |                   |       0.0159988   |      0         |    0           |    0           |   0.441602  |    0.427895   | 0.6        |  0.304923    |            1        |             0.281592    |                0.999999    |            0.30181     |               0.835992 |        0.88192     |                 0.304923    |              0.11808     |
| heart_disease       | logistic_regression | bayesian_rule_list      |                   |       0.000472867 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.56     |        0           |                 0           |              0           |
| heart_disease       | logistic_regression | corels                  |                   |       0.000218026 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0.56     |        1           |                 2.22045e-16 |              0           |
| heart_disease       | logistic_regression | feature_ablation        |                   |       0.000380483 |      0         |    0           |    0           |   0         |    0.573283   | 0.036      |  0.908       |            1        |             0.376742    |                1           |            0.385       |               0.68     |        0.0258406   |                 0.308       |              0.374159    |
| german_credit       | decision_tree       | shap                    |                   |       0.000941718 |      0.53      |    0.045       |    0           |   0         |    0.409083   | 0.171429   |  0.881429    |            0.682692 |             0.466981    |                1           |            0.48        |               0.586    |        0.0994702   |                 0.411429    |              0.43053     |
| german_credit       | decision_tree       | lime                    |                   |       0.00991785  |      0.2       |    0.02        |    0           |   0         |    0.285168   | 0.0142857  |  0.985       |            0.945946 |             0.1         |                0.5         |            0.0990667   |               0.490469 |        0.00387243  |                 0.085       |              0.0961276   |
| german_credit       | decision_tree       | causal_shap             |                   |       0.0224179   |      0.4       |    0.0266667   |    4.44089e-18 |   0         |    0.454666   | 0.111429   |  0.948704    |            1        |             0.265224    |                1           |            0.267071    |               0.531076 |        0.0712653   |                 0.230155    |              0.228735    |
| german_credit       | decision_tree       | shapley_flow            |                   |       0.0104751   |      0.166667  |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.56     |        0           |                 0           |              0           |
| german_credit       | decision_tree       | shap_interactive        |                   |       0.0033999   |      0.4       |    0           |    0           |   0         |    0.444444   | 0          |  0.914286    |            0.75     |             0.6         |                1           |            0.6         |               0.88     |       -3.08339e-11 |                 0.514286    |              0.6         |
| german_credit       | decision_tree       | prototype               |                   |       0.000114329 |      0.645     |    0.912972    |    1           |   0.790914  |    0.362006   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| german_credit       | decision_tree       | counterfactual          |                   |       0.00011132  |      0.645     |    0.102486    |    1           |   0.836585  |    0.0348042  | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| german_credit       | decision_tree       | bayesian_rule_list      |                   |       0.000570991 |      0         |    0           |    0           |   1         |    1          | 0          |  0.857143    |            1        |             1           |                1           |            1           |               0.502    |       -5.13898e-11 |                 0.857143    |              1           |
| german_credit       | decision_tree       | corels                  |                   |       0.000333607 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             6.07153e-17 |                3.88663e-14 |            0           |               0.427    |        1           |                 0           |              0           |
| german_credit       | decision_tree       | feature_ablation        |                   |       0.000499277 |      0         |    0           |    0           |   0         |    0.39206    | 0.162857   |  0.88        |            1        |             0.476944    |                1           |            0.49        |               0.624    |        0.0979918   |                 0.42        |              0.442008    |
| german_credit       | random_forest       | shap                    |                   |       0.0312142   |      0.25      |    0.0103333   |    0           |   0         |    0.384351   | 0.0914286  |  0.918571    |            0.88172  |             0.18706     |                0.5         |            0.196667    |               0.537    |        0.086037    |                 0.168571    |              0.163963    |
| german_credit       | random_forest       | lime                    |                   |       0.0213458   |      0.14      |    0           |    0           |   0         |    0.423659   | 0.0142857  |  0.992627    |            0.976744 |             0.0385636   |                0.5         |            0.0380853   |               0.513446 |        0.006974    |                 0.0326274   |              0.033026    |
| german_credit       | random_forest       | causal_shap             |                   |       0.930861    |      0.18      |    0           |    0           |   0         |    0.426818   | 0.0942857  |  0.961339    |            1        |             0.108619    |                0.5         |            0.11113     |               0.527945 |        0.0885916   |                 0.0977658   |              0.0714084   |
| german_credit       | random_forest       | shapley_flow            |                   |       0.480191    |      0.1       |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.536667 |        0           |                 0           |              0           |
| german_credit       | random_forest       | shap_interactive        |                   |       0.174332    |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.42     |        0           |                 0           |              0           |
| german_credit       | random_forest       | prototype               |                   |       0.003619    |      0.705     |    0.728911    |    1           |   0.913145  |    0.450694   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| german_credit       | random_forest       | counterfactual          |                   |       0.00344161  |      0.705     |    0.305138    |    1           |   0.798802  |    0.24381    | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| german_credit       | random_forest       | bayesian_rule_list      |                   |       0.00434769  |      0         |    0           |    0           |   1         |    1          | 0          |  0.857143    |            1        |             1           |                1           |            1           |               0.537    |       -5.13898e-11 |                 0.857143    |              1           |
| german_credit       | random_forest       | corels                  |                   |       0.00446342  |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             6.07153e-17 |                8.13262e-14 |            0           |               0.462    |        1           |                 0           |              0           |
| german_credit       | random_forest       | feature_ablation        |                   |       0.026484    |      0         |    0           |    0           |   0         |    0.38418    | 0.102857   |  0.934286    |            1        |             0.169434    |                0.5         |            0.18        |               0.57     |        0.0736626   |                 0.154286    |              0.146337    |
| german_credit       | gradient_boosting   | shap                    |                   |       0.0020574   |      0.26      |    0.0508333   |    0           |   0         |    0.458897   | 0.0842857  |  0.935714    |            0.918605 |             0.22067     |                0.5         |            0.228333    |               0.561    |        0.0582037   |                 0.195714    |              0.201796    |
| german_credit       | gradient_boosting   | lime                    |                   |       0.0101183   |      0.1       |    0.0206667   |    0           |   0         |    0.518677   | 0.0857143  |  0.967492    |            0.909091 |             0.150002    |                0.5         |            0.148209    |               0.541071 |        0.03153     |                 0.127492    |              0.12847     |
| german_credit       | gradient_boosting   | causal_shap             |                   |       0.0525654   |      0.2       |    0.025       |    0           |   0         |    0.667881   | 0.125714   |  0.947058    |            1        |             0.152717    |                0.5         |            0.16231     |               0.530611 |        0.0808419   |                 0.142399    |              0.119158    |
| german_credit       | gradient_boosting   | shap_interactive        |                   |       0.00983105  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.42     |        0           |                 0           |              0           |
| german_credit       | gradient_boosting   | prototype               |                   |       0.000396056 |      0.715     |    0.745119    |    1           |   0.602477  |    0.399285   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| german_credit       | gradient_boosting   | counterfactual          |                   |       0.000557823 |      0.715     |    0.288858    |    1           |   0.846534  |    0.555934   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| german_credit       | gradient_boosting   | bayesian_rule_list      |                   |       0.000922465 |      0         |    0           |    0           |   1         |    1          | 0          |  0.857143    |            1        |             1           |                1           |            1           |               0.558    |       -5.13898e-11 |                 0.857143    |              1           |
| german_credit       | gradient_boosting   | corels                  |                   |       0.000614614 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             6.07153e-17 |                1.32709e-13 |            0           |               0.483    |        1           |                 0           |              0           |
| german_credit       | gradient_boosting   | feature_ablation        |                   |       0.00192     |      0         |    0           |    0           |   0         |    0.451088   | 0.0714286  |  0.951429    |            1        |             0.219057    |                0.5         |            0.223333    |               0.576    |        0.0356207   |                 0.191429    |              0.204379    |
| german_credit       | mlp                 | shap                    |                   |       0.000875371 |      0.51      |    0.0347619   |    0           |   0         |    0.395003   | 0.14       |  0.87        |            0.619048 |             0.430405    |                0.5         |            0.443333    |               0.64     |        0.111554    |                 0.38        |              0.398446    |
| german_credit       | mlp                 | lime                    |                   |       0.00981218  |      0.26      |    0           |    0           |   0         |    0.447673   | 0.0428571  |  0.981355    |            0.975    |             0.0712089   |                0.5         |            0.072071    |               0.532755 |        0.0249172   |                 0.0613548   |              0.0550828   |
| german_credit       | mlp                 | integrated_gradients    |                   |       0.0592894   |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.49     |        0           |                 0           |              0           |
| german_credit       | mlp                 | causal_shap             |                   |       0.029404    |      0.36      |    0.0116667   |    0           |   0         |    0.369288   | 0.197143   |  0.97575     |            0.960591 |             0.218595    |                1           |            0.186028    |               0.561104 |        0.186462    |                 0.163872    |              0.113538    |
| german_credit       | mlp                 | shapley_flow            |                   |       0.0129585   |      0.2       |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.49     |        0           |                 0           |              0           |
| german_credit       | mlp                 | shap_interactive        |                   |       0.00440555  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.42     |        0           |                 0           |              0           |
| german_credit       | mlp                 | prototype               |                   |       0.000224921 |      0.715     |    0.811043    |    1           |   0.936589  |    0.373332   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| german_credit       | mlp                 | counterfactual          |                   |       0.000216866 |      0.715     |    0.220696    |    1           |   0.896058  |    0.845209   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| german_credit       | mlp                 | influence_functions     |                   |       0.0220119   |      0         |    0           |    0           |   0.466211  |    0.358271   | 0.714286   |  0.317949    |            1        |             0.294594    |                0.999999    |            0.299285    |               0.73025  |        0.899197    |                 0.317949    |              0.100803    |
| german_credit       | mlp                 | bayesian_rule_list      |                   |       0.000582767 |      0         |    0           |    0           |   1         |    1          | 0          |  0.857143    |            1        |             1           |                1           |            1           |               0.565    |       -5.13898e-11 |                 0.857143    |              1           |
| german_credit       | mlp                 | corels                  |                   |       0.000298276 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             6.07153e-17 |                9.01528e-14 |            0           |               0.49     |        1           |                 0           |              0           |
| german_credit       | mlp                 | feature_ablation        |                   |       0.000631309 |      0         |    0           |    0           |   0         |    0.404622   | 0.105714   |  0.868571    |            1        |             0.37232     |                0.5         |            0.383333    |               0.65     |        0.113824    |                 0.328571    |              0.346176    |
| german_credit       | linear_regression   | lime                    |                   |       0.00950759  |      0.06      |    0.0166667   |    0           |   0         |    0.147442   | 0.0285714  |  0.991433    |            0.959184 |             0.0367317   |                0.5         |            0.0362443   |               0.52525  |        0.0111171   |                 0.0314328   |              0.0288829   |
| german_credit       | linear_regression   | causal_shap             |                   |       0.0259753   |      0.08      |    0.005       |    0           |   0         |    0.27044    | 0.0514286  |  0.985406    |            0.987395 |             0.0487958   |                0.5         |            0.0475129   |               0.525876 |        0.055749    |                 0.0429383   |              0.024251    |
| german_credit       | linear_regression   | shap_interactive        |                   |       0.00539198  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.42     |        0           |                 0           |              0           |
| german_credit       | linear_regression   | prototype               |                   |       0.000142319 |      0.725     |    0.591323    |    1           |   0.960817  |    0.916856   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| german_credit       | linear_regression   | counterfactual          |                   |       0.00015848  |      0.725     |    0.442727    |    1           |   0.866352  |    0.854927   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| german_credit       | linear_regression   | bayesian_rule_list      |                   |       0.0010009   |      0         |    0           |    0           |   1         |    1          | 0          |  0.857143    |            1        |             1           |                1           |            1           |               0.551    |       -5.13898e-11 |                 0.857143    |              1           |
| german_credit       | linear_regression   | corels                  |                   |       0.000332601 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             6.07153e-17 |                3.80182e-14 |            0           |               0.476    |        1           |                 0           |              0           |
| german_credit       | linear_regression   | feature_ablation        |                   |       0.000655332 |      0         |    0           |    0           |   0         |    0.37328    | 0.0571429  |  0.974286    |            1        |             0.0832456   |                0.5         |            0.0866667   |               0.548    |        0.0284966   |                 0.0742857   |              0.0715034   |
| german_credit       | logistic_regression | lime                    |                   |       0.00995977  |      0.08      |    0.004       |    0           |   0         |    0.934947   | 0.0285714  |  0.98532     |            1        |             0.0253503   |                0.5         |            0.0287469   |               0.535216 |        0.0233314   |                 0.0253201   |              0.0166686   |
| german_credit       | logistic_regression | causal_shap             |                   |       0.0220306   |      0.06      |    0.005       |    0           |   0         |    0.342924   | 0.0571429  |  0.985629    |            1        |             0.0565883   |                0.5         |            0.0556676   |               0.546374 |        0.0460466   |                 0.0493994   |              0.0339534   |
| german_credit       | logistic_regression | shap_interactive        |                   |       0.00383191  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.42     |        0           |                 0           |              0           |
| german_credit       | logistic_regression | prototype               |                   |       0.000142488 |      0.735     |    0.715798    |    1           |   0.724725  |    0.21887    | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| german_credit       | logistic_regression | counterfactual          |                   |       0.000142146 |      0.735     |    0.318252    |    1           |   0.831589  |    0.146136   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| german_credit       | logistic_regression | influence_functions     |                   |       0.0179161   |      0         |    0           |    0           |   0.466211  |    0.358271   | 0.714286   |  0.317949    |            1        |             0.294594    |                0.999998    |            0.299285    |               0.73025  |        0.899197    |                 0.317949    |              0.100803    |
| german_credit       | logistic_regression | bayesian_rule_list      |                   |       0.000620153 |      0         |    0           |    0           |   1         |    1          | 0          |  0.857143    |            1        |             1           |                1           |            1           |               0.565    |       -5.13898e-11 |                 0.857143    |              1           |
| german_credit       | logistic_regression | corels                  |                   |       0.000305936 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             6.07153e-17 |                3.18119e-14 |            0           |               0.49     |        1           |                 0           |              0           |
| german_credit       | logistic_regression | feature_ablation        |                   |       0.000525675 |      0         |    0           |    0           |   0         |    0.473347   | 0.0542857  |  0.971429    |            1        |             0.0789812   |                0.5         |            0.0833333   |               0.562    |        0.0326639   |                 0.0714286   |              0.0673361   |
| iris                | decision_tree       | shap                    |                   |       0.000729601 |      0.4       |    0           |    0.216667    |   0         |    0.851709   | 0.341667   |  0.875       |            1        |             0.391944    |                1           |            0.455556    |               0.793333 |        0.0166667   |                 0.341667    |              0.45        |
| iris                | decision_tree       | lime                    |                   |       0.010497    |      0.0166667 |    0           |    0           |   0         |    0.718411   | 0.25       |  0.90086     |            0.666667 |             0.261354    |                1           |            0.310233    |               0.737581 |        0.0526645   |                 0.234193    |              0.280669    |
| iris                | decision_tree       | causal_shap             |                   |       0.0151878   |      0.4       |    0           |    0.166667    |   0         |    0.754517   | 0.5        |  0.807064    |            1        |             0.429651    |                0.999998    |            0.505543    |               0.782441 |        0.231103    |                 0.390397    |              0.435564    |
| iris                | decision_tree       | shapley_flow            |                   |       0.00555902  |      0.0166667 |    0           |    0           |   0         |    0          | 0.025      |  0.991667    |            1        |             0.0288675   |                0.5         |            0.0333333   |               0.663333 |       -2.40449e-12 |                 0.025       |              0.0333333   |
| iris                | decision_tree       | shap_interactive        |                   |       0.00184994  |      0.4       |    0           |    0           |   1         |    1          | 0.3        |  1           |            1        |             0.34641     |                1           |            0.4         |               0.82     |       -2.88539e-11 |                 0.3         |              0.4         |
| iris                | decision_tree       | prototype               |                   |       8.7436e-05  |      0.933333  |    0.993671    |    1           |   0.931484  |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| iris                | decision_tree       | counterfactual          |                   |       0.000136304 |      0.933333  |    0.0271505   |    1           |   0.97579   |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| iris                | decision_tree       | bayesian_rule_list      |                   |       0.000516073 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.653333 |        0           |                 0           |              0           |
| iris                | decision_tree       | corels                  |                   |       0.000211875 |      0         |    0           |    0           |   0.0111664 |    0.485824   | 0.75       |  0.532044    |            1        |             0.513913    |                1           |            0.684097    |               0.690655 |        0.489065    |                 0.532044    |              0.510935    |
| iris                | decision_tree       | feature_ablation        |                   |       0.000338721 |      0         |    0           |    0           |   0         |    0.851709   | 0.341667   |  0.875       |            1        |             0.391944    |                1           |            0.455556    |               0.793333 |        0.0166667   |                 0.341667    |              0.45        |
| iris                | random_forest       | shap                    |                   |       0.0241829   |      0.233333  |    0.0166667   |    0.0814781   |   0         |    0.75148    | 0.191667   |  0.925       |            0.846154 |             0.218739    |                1           |            0.255556    |               0.71     |        0.0166667   |                 0.191667    |              0.25        |
| iris                | random_forest       | lime                    |                   |       0.0191179   |      0.05      |    0.0166667   |    0           |   0         |    0.836732   | 0.25       |  0.886839    |            0.647059 |             0.237611    |                1           |            0.289389    |               0.701154 |        0.0845971   |                 0.220173    |              0.248736    |
| iris                | random_forest       | causal_shap             |                   |       0.539759    |      0.2       |    0           |    0.121222    |   1         |    0.553984   | 0.5        |  0.879025    |            0.964912 |             0.387951    |                1           |            0.481539    |               0.722252 |        0.346046    |                 0.366527    |              0.32062     |
| iris                | random_forest       | shapley_flow            |                   |       0.276582    |      0.0333333 |    0.0333333   |    0           |   0         |    0          | 0.025      |  0.991667    |            1        |             0.0288675   |                0.5         |            0.0333333   |               0.64     |       -2.40449e-12 |                 0.025       |              0.0333333   |
| iris                | random_forest       | shap_interactive        |                   |       0.15171     |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.7      |        0           |                 0           |              0           |
| iris                | random_forest       | prototype               |                   |       0.00437795  |      0.9       |    0.938181    |    1           |   0.921485  |    0.80841    | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| iris                | random_forest       | counterfactual          |                   |       0.0059997   |      0.9       |    0.0886469   |    1           |   0.948151  |    0.662677   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| iris                | random_forest       | bayesian_rule_list      |                   |       0.00514615  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.63     |        0           |                 0           |              0           |
| iris                | random_forest       | corels                  |                   |       0.00379205  |      0         |    0           |    0           |   0.0111664 |    0.485824   | 0.75       |  0.532044    |            1        |             0.513913    |                1           |            0.684097    |               0.667322 |        0.489065    |                 0.532044    |              0.510935    |
| iris                | random_forest       | feature_ablation        |                   |       0.0150219   |      0         |    0           |    0           |   0         |    0.75148    | 0.191667   |  0.925       |            1        |             0.218739    |                1           |            0.255556    |               0.71     |        0.0166667   |                 0.191667    |              0.25        |
| iris                | gradient_boosting   | shap                    |                   |       0.00359786  |      0.316667  |    0           |    0.1333      |   0         |    0.734473   | 0.266667   |  0.866667    |            1        |             0.297607    |                0.999995    |            0.355556    |               0.796667 |        0.0666667   |                 0.266667    |              0.333333    |
| iris                | gradient_boosting   | lime                    |                   |       0.0117153   |      0.0166667 |    0           |    0           |   0         |    0.736728   | 0.225      |  0.908644    |            0.75     |             0.232994    |                1           |            0.277835    |               0.751145 |        0.0500292   |                 0.208644    |              0.249971    |
| iris                | gradient_boosting   | causal_shap             |                   |       0.0873608   |      0.316667  |    0           |    0.182161    |   0         |    0.574014   | 0.525      |  0.858489    |            1        |             0.41332     |                1           |            0.483953    |               0.808516 |        0.386786    |                 0.367685    |              0.313214    |
| iris                | gradient_boosting   | shap_interactive        |                   |       0.0205652   |      0         |    0           |    0           |   1         |    1          | 0.3        |  1           |            1        |             0.34641     |                1           |            0.4         |               0.82     |       -2.88539e-11 |                 0.3         |              0.4         |
| iris                | gradient_boosting   | prototype               |                   |       0.000762582 |      0.966667  |    0.993916    |    1           |   0.921485  |    0.936869   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| iris                | gradient_boosting   | counterfactual          |                   |       0.00103707  |      0.966667  |    0.0275904   |    1           |   0.992408  |    0.483623   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| iris                | gradient_boosting   | bayesian_rule_list      |                   |       0.00156333  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.676667 |        0           |                 0           |              0           |
| iris                | gradient_boosting   | corels                  |                   |       0.00100136  |      0         |    0           |    0           |   0.0111664 |    0.485824   | 0.75       |  0.532044    |            1        |             0.513913    |                1           |            0.684097    |               0.713989 |        0.489065    |                 0.532044    |              0.510935    |
| iris                | gradient_boosting   | feature_ablation        |                   |       0.00261536  |      0         |    0           |    0           |   0         |    0.734473   | 0.266667   |  0.866667    |            1        |             0.297607    |                0.999942    |            0.355556    |               0.796667 |        0.0666667   |                 0.266667    |              0.333333    |
| iris                | mlp                 | shap                    |                   |       0.00088648  |      0.216667  |    0.0166667   |    0.097665    |   0         |    0.624352   | 0.241667   |  0.841667    |            0.9      |             0.266161    |                1           |            0.322222    |               0.796667 |        0.109749    |                 0.241667    |              0.290251    |
| iris                | mlp                 | lime                    |                   |       0.0112921   |      0.0666667 |    0.00833333  |    0           |   0         |    0.730932   | 0.15       |  0.91779     |            1        |             0.121214    |                0.999999    |            0.150909    |               0.708846 |        0.0790411   |                 0.11779     |              0.120959    |
| iris                | mlp                 | integrated_gradients    |                   |       0.0390646   |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.676667 |        0           |                 0           |              0           |
| iris                | mlp                 | causal_shap             |                   |       0.0149503   |      0.183333  |    0.00833333  |    0.11441     |   0         |    0.576397   | 0.525      |  0.883693    |            1        |             0.431832    |                1           |            0.530033    |               0.795558 |        0.303338    |                 0.400994    |              0.396662    |
| iris                | mlp                 | shapley_flow            |                   |       0.00669843  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.676667 |        0           |                 0           |              0           |
| iris                | mlp                 | shap_interactive        |                   |       0.00295863  |      0         |    0           |    0           |   1         |    1          | 0.3        |  1           |            1        |             0.34641     |                1           |            0.4         |               0.82     |       -2.88539e-11 |                 0.3         |              0.4         |
| iris                | mlp                 | prototype               |                   |       0.0001333   |      0.966667  |    0.952556    |    1           |   0.946365  |    0.12336    | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| iris                | mlp                 | counterfactual          |                   |       0.000133181 |      0.966667  |    0.075953    |    1           |   0.991305  |    0.481502   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| iris                | mlp                 | influence_functions     |                   |       0.0109614   |      0         |    0           |    0           |   0.53292   |    0.556842   | 0.75       |  0.246728    |            1        |             0.23506     |                0.999999    |            0.255674    |               0.840061 |        0.888701    |                 0.246728    |              0.111299    |
| iris                | mlp                 | bayesian_rule_list      |                   |       0.00048573  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.676667 |        0           |                 0           |              0           |
| iris                | mlp                 | corels                  |                   |       0.000441448 |      0         |    0           |    0           |   0.0111664 |    0.485824   | 0.75       |  0.532044    |            1        |             0.513913    |                1           |            0.684097    |               0.713989 |        0.489065    |                 0.532044    |              0.510935    |
| iris                | mlp                 | feature_ablation        |                   |       0.000545104 |      0         |    0           |    0           |   0         |    0.624352   | 0.241667   |  0.841667    |            1        |             0.266161    |                1           |            0.322222    |               0.796667 |        0.109749    |                 0.241667    |              0.290251    |
| iris                | linear_regression   | lime                    |                   |       0.0103831   |      0.211479  |    0.383333    |    0           |   0         |    0.833804   | 0.725      |  0.644191    |            1        |             0.632999    |                1           |            0.7907      |               0.874694 |        0.335807    |                 0.610858    |              0.630859    |
| iris                | linear_regression   | causal_shap             |                   |       0.0099926   |      0.477896  |    0.533333    |    1           |   1         |    0.873563   | 0.75       |  0.830616    |            1        |             0.510455    |                0.999999    |            0.530716    |               0.787889 |        0.700268    |                 0.437176    |              0.299732    |
| iris                | linear_regression   | shap_interactive        |                   |       0.00215874  |      0.503814  |    0.2         |    1           |   1         |    1          | 0.75       |  0.920542    |            1        |             0.511619    |                1           |            0.408699    |               0.784866 |        0.775073    |                 0.361208    |              0.224927    |
| iris                | linear_regression   | prototype               |                   |       0.000262578 |      0.666667  |    0           |    1           |   0         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| iris                | linear_regression   | counterfactual          |                   |       0.000133848 |      0.666667  |    0.311538    |    1           |   0.9316    |    0.677968   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| iris                | linear_regression   | bayesian_rule_list      |                   |       0.000412019 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.7      |        0           |                 0           |              0           |
| iris                | linear_regression   | corels                  |                   |       0.000288932 |      0         |    0           |    0           |   0.0111664 |    0.485824   | 0.75       |  0.532044    |            1        |             0.513913    |                1           |            0.684097    |               0.737322 |        0.489065    |                 0.532044    |              0.510935    |
| iris                | linear_regression   | feature_ablation        |                   |       0.00035518  |      0         |    0           |    0           |   0.478533  |    0.870805   | 0.75       |  0.437176    |            1        |             0.409871    |                0.999991    |            0.530716    |               0.765315 |        0.700268    |                 0.437176    |              0.299732    |
| iris                | logistic_regression | lime                    |                   |       0.0125385   |      0.05      |    0.0222222   |    0           |   0         |    0.925376   | 0.175      |  0.904155    |            0.833333 |             0.1386      |                1           |            0.177061    |               0.688054 |        0.106213    |                 0.137489    |              0.12712     |
| iris                | logistic_regression | causal_shap             |                   |       0.0108995   |      0.166667  |    0           |    0.0677897   |   0         |    0.605826   | 0.483333   |  0.906823    |            1        |             0.430258    |                1           |            0.524479    |               0.775319 |        0.250371    |                 0.403412    |              0.416296    |
| iris                | logistic_regression | shap_interactive        |                   |       0.0030838   |      0         |    0           |    0           |   1         |    1          | 0.2        |  1           |            1        |             0.2         |                1           |            0.266667    |               0.82     |        0.2         |                 0.2         |              0.2         |
| iris                | logistic_regression | prototype               |                   |       0.00020055  |      0.933333  |    0.867848    |    1           |   0.972743  |    0.486158   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| iris                | logistic_regression | counterfactual          |                   |       0.000236257 |      0.933333  |    0.16529     |    1           |   0.967846  |    0.62935    | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| iris                | logistic_regression | influence_functions     |                   |       0.00927451  |      0         |    0           |    0           |   0.53292   |    0.556842   | 0.75       |  0.246728    |            1        |             0.23506     |                0.999999    |            0.255674    |               0.840061 |        0.888701    |                 0.246728    |              0.111299    |
| iris                | logistic_regression | bayesian_rule_list      |                   |       0.000515819 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.653333 |        0           |                 0           |              0           |
| iris                | logistic_regression | corels                  |                   |       0.000293152 |      0         |    0           |    0           |   0.0111664 |    0.485824   | 0.75       |  0.532044    |            1        |             0.513913    |                1           |            0.684097    |               0.690655 |        0.489065    |                 0.532044    |              0.510935    |
| iris                | logistic_regression | feature_ablation        |                   |       0.000346756 |      0         |    0           |    0           |   0         |    0.688656   | 0.25       |  0.85        |            1        |             0.273205    |                1           |            0.333333    |               0.773333 |        0.1         |                 0.25        |              0.3         |
| wine_quality        | decision_tree       | shap                    |                   |       0.000967247 |      0.72      |    0.0236667   |    0.0635012   |   0         |    0.358156   | 0.0836364  |  0.876515    |            0.409836 |             0.725299    |                0.999999    |            0.6881      |               0.687    |        0.16216     |                 0.626515    |              0.58784     |
| wine_quality        | decision_tree       | lime                    |                   |       0.0091293   |      0.13      |    0.02        |    0           |   0         |    0.276363   | 0.0436364  |  0.961525    |            0.771429 |             0.38        |                0.999973    |            0.376043    |               0.595709 |        0.0197592   |                 0.341525    |              0.360241    |
| wine_quality        | decision_tree       | causal_shap             |                   |       0.0336959   |      0.16      |    0.005       |    0.101911    |   0         |    0.364553   | 0.298182   |  0.96023     |            0.950704 |             0.402567    |                0.999999    |            0.364543    |               0.595159 |        0.253885    |                 0.339818    |              0.226115    |
| wine_quality        | decision_tree       | shapley_flow            |                   |       0.0158904   |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.513333 |        0           |                 0           |              0           |
| wine_quality        | decision_tree       | shap_interactive        |                   |       0.0068893   |      0.2       |    0           |    0.1         |   0         |    0.365394   | 0.418182   |  0.783636    |            0.3      |             0.884298    |                1           |            0.855238    |               0.72     |        0.347276    |                 0.783636    |              0.652724    |
| wine_quality        | decision_tree       | prototype               |                   |       0.000141038 |      0.65      |    0.892678    |    1           |   0.718302  |    0.847022   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_quality        | decision_tree       | counterfactual          |                   |       0.000153582 |      0.59      |    0.139205    |    1           |   0.788661  |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_quality        | decision_tree       | bayesian_rule_list      |                   |       0.00101725  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.462    |        0           |                 0           |              0           |
| wine_quality        | decision_tree       | corels                  |                   |       0.000596323 |      0         |    0           |    0           |   1         |    0          | 0          |  3.22974e-16 |            1        |             0           |                0.5         |            0           |               0.462    |        1           |                 0           |              0           |
| wine_quality        | decision_tree       | feature_ablation        |                   |       0.000755625 |      0         |    0           |    0           |   0         |    0.402311   | 0.0854545  |  0.882727    |            1        |             0.698922    |                0.999997    |            0.662       |               0.706    |        0.154187    |                 0.602727    |              0.565813    |
| wine_quality        | random_forest       | shap                    |                   |       0.0431237   |      0.355     |    0.0174524   |    0.00247979  |   0         |    0.297064   | 0.0954545  |  0.916364    |            0.57971  |             0.342686    |                1           |            0.337       |               0.628    |        0.107503    |                 0.306364    |              0.282497    |
| wine_quality        | random_forest       | lime                    |                   |       0.0232636   |      0.04      |    0.0025      |    0           |   0         |    0.322177   | 0.218182   |  0.933542    |            0.869565 |             0.266191    |                0.999989    |            0.254936    |               0.569774 |        0.126939    |                 0.233542    |              0.173061    |
| wine_quality        | random_forest       | causal_shap             |                   |       1.29294     |      0.2       |    0           |    0.00495959  |   1         |    0.323451   | 0.432727   |  0.986398    |            0.980392 |             0.478763    |                0.999999    |            0.442049    |               0.610936 |        0.389785    |                 0.404451    |              0.230215    |
| wine_quality        | random_forest       | shapley_flow            |                   |       0.65944     |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.513333 |        0           |                 0           |              0           |
| wine_quality        | random_forest       | shap_interactive        |                   |       0.173194    |      0.2       |    0           |    0           |   1         |    0.4        | 0          |  1           |            0.75     |             0.6         |                1           |            0.6         |               0.74     |       -2.50219e-11 |                 0.545455    |              0.6         |
| wine_quality        | random_forest       | prototype               |                   |       0.00317515  |      0.66      |    0.665843    |    1           |   0.720096  |    0.0361751  | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_quality        | random_forest       | counterfactual          |                   |       0.00343539  |      0.71      |    0.374758    |    1           |   0.823623  |    0.215331   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_quality        | random_forest       | bayesian_rule_list      |                   |       0.0039065   |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.511    |        0           |                 0           |              0           |
| wine_quality        | random_forest       | corels                  |                   |       0.00378214  |      0         |    0           |    0           |   1         |    0          | 0          |  3.22974e-16 |            1        |             0           |                0.5         |            0           |               0.511    |        1           |                 0           |              0           |
| wine_quality        | random_forest       | feature_ablation        |                   |       0.0368627   |      0         |    0           |    0           |   0         |    0.331259   | 0.0709091  |  0.938182    |            1        |             0.358548    |                0.999999    |            0.35        |               0.646    |        0.0713403   |                 0.318182    |              0.30866     |
| wine_quality        | gradient_boosting   | shap                    |                   |       0.00732594  |      0.405     |    0.0175      |    0.0010653   |   0         |    0.316416   | 0.0836364  |  0.914818    |            0.609375 |             0.389062    |                1           |            0.378778    |               0.619    |        0.108222    |                 0.344818    |              0.321778    |
| wine_quality        | gradient_boosting   | lime                    |                   |       0.0110461   |      0.05      |    0.00285714  |    0           |   0         |    0.315379   | 0.189091   |  0.929472    |            0.689655 |             0.464659    |                0.999998    |            0.449517    |               0.631892 |        0.102516    |                 0.409472    |              0.377484    |
| wine_quality        | gradient_boosting   | causal_shap             |                   |       0.226294    |      0.15      |    0.005       |    0.00139554  |   1         |    0.384756   | 0.403636   |  0.982738    |            1        |             0.467977    |                1           |            0.449106    |               0.59002  |        0.349921    |                 0.412472    |              0.250079    |
| wine_quality        | gradient_boosting   | shap_interactive        |                   |       0.025567    |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0.2         |                1           |            0.2         |               0.62     |       -8.34065e-12 |                 0.181818    |              0.2         |
| wine_quality        | gradient_boosting   | prototype               |                   |       0.000599762 |      0.705     |    0.714792    |    1           |   0.891774  |    0.821288   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_quality        | gradient_boosting   | counterfactual          |                   |       0.000662848 |      0.695     |    0.342605    |    1           |   0.97496   |    0.00536579 | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_quality        | gradient_boosting   | bayesian_rule_list      |                   |       0.00164412  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.49     |        0           |                 0           |              0           |
| wine_quality        | gradient_boosting   | corels                  |                   |       0.000975146 |      0         |    0           |    0           |   1         |    0          | 0          |  3.22974e-16 |            1        |             0           |                0.5         |            0           |               0.49     |        1           |                 0           |              0           |
| wine_quality        | gradient_boosting   | feature_ablation        |                   |       0.00534371  |      0         |    0           |    0           |   0         |    0.374875   | 0.0672727  |  0.934545    |            1        |             0.292346    |                0.999999    |            0.28        |               0.628    |        0.0934831   |                 0.254545    |              0.226517    |
| wine_quality        | mlp                 | shap                    |                   |       0.00130418  |      0.66      |    0.00533333  |    0.0590411   |   0         |    0.263423   | 0.120909   |  0.869636    |            0.369369 |             0.633388    |                1           |            0.614379    |               0.711    |        0.165365    |                 0.559636    |              0.524635    |
| wine_quality        | mlp                 | lime                    |                   |       0.00980128  |      0.04      |    0           |    0           |   0         |    0.27547    | 0.189091   |  0.931255    |            0.714286 |             0.264088    |                0.5         |            0.251247    |               0.571713 |        0.123593    |                 0.231255    |              0.176407    |
| wine_quality        | mlp                 | integrated_gradients    |                   |       0.0955218   |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.56     |        0           |                 0           |              0           |
| wine_quality        | mlp                 | causal_shap             |                   |       0.0466676   |      0.26      |    0           |    0.0077412   |   1         |    0.321098   | 0.430909   |  0.997247    |            0.952381 |             0.445377    |                1           |            0.385386    |               0.64245  |        0.450516    |                 0.353938    |              0.169484    |
| wine_quality        | mlp                 | shapley_flow            |                   |       0.0214064   |      0.0833333 |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.56     |        0           |                 0           |              0           |
| wine_quality        | mlp                 | shap_interactive        |                   |       0.00655189  |      0         |    0           |    0           |   1         |    0.397527   | 0.127273   |  1           |            0.4      |             0.758114    |                0.999998    |            0.7         |               0.94     |        0.231252    |                 0.636364    |              0.568748    |
| wine_quality        | mlp                 | prototype               |                   |       0.000183152 |      0.67      |    0.818791    |    1           |   0.793143  |    0.149993   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_quality        | mlp                 | counterfactual          |                   |       0.000252763 |      0.68      |    0.228798    |    1           |   0.771064  |    0.883818   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_quality        | mlp                 | influence_functions     |                   |       0.0206254   |      0         |    0           |    0           |   0.394837  |    0.280478   | 0.727273   |  0.370059    |            1        |             0.343281    |                0.999999    |            0.349279    |               0.827806 |        0.898149    |                 0.370059    |              0.101851    |
| wine_quality        | mlp                 | bayesian_rule_list      |                   |       0.00106913  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.504    |        0           |                 0           |              0           |
| wine_quality        | mlp                 | corels                  |                   |       0.00061064  |      0         |    0           |    0           |   1         |    0          | 0          |  3.22974e-16 |            1        |             0           |                0.5         |            0           |               0.504    |        1           |                 0           |              0           |
| wine_quality        | mlp                 | feature_ablation        |                   |       0.001188    |      0         |    0           |    0           |   0         |    0.269008   | 0.114545   |  0.865212    |            1        |             0.686692    |                1           |            0.664514    |               0.754    |        0.168699    |                 0.605212    |              0.571301    |
| wine_quality        | linear_regression   | lime                    |                   |       0.0109782   |      0.404563  |    0.364646    |    0           |   0         |    0.337895   | 0.727273   |  0.803236    |            1        |             0.944963    |                0.999945    |            0.887803    |               0.647129 |        0.385461    |                 0.803236    |              0.614539    |
| wine_quality        | linear_regression   | causal_shap             |                   |       0.0422125   |      0.587207  |    0.412727    |    0.360945    |   1         |    0.354241   | 0.727273   |  0.975264    |            1        |             0.691399    |                1           |            0.599074    |               0.541679 |        0.7755      |                 0.534278    |              0.2245      |
| wine_quality        | linear_regression   | shap_interactive        |                   |       0.00346632  |      0.543032  |    0.363636    |    0.321976    |   1         |    0.31       | 0.727273   |  1           |            1        |             0.749157    |                1           |            0.638353    |               0.459379 |        0.75514     |                 0.556496    |              0.24486     |
| wine_quality        | linear_regression   | prototype               |                   |       0.000267332 |      0.485     |    0           |    0.666667    |   0         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_quality        | linear_regression   | counterfactual          |                   |       0.000255203 |      0.525     |    0.379396    |    0.666667    |   0.686167  |    0.299547   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_quality        | linear_regression   | bayesian_rule_list      |                   |       0.00147382  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.49     |        0           |                 0           |              0           |
| wine_quality        | linear_regression   | corels                  |                   |       0.000495923 |      0         |    0           |    0           |   1         |    0          | 0          |  3.22974e-16 |            1        |             0           |                0.5         |            0           |               0.49     |        1           |                 0           |              0           |
| wine_quality        | linear_regression   | feature_ablation        |                   |       0.000798974 |      0         |    0           |    0           |   0.242505  |    0.514672   | 0.727273   |  0.534278    |            1        |             0.568015    |                1           |            0.599074    |               0.531177 |        0.7755      |                 0.534278    |              0.2245      |
| wine_quality        | logistic_regression | lime                    |                   |       0.0165905   |      0.03      |    0           |    0           |   0         |    0.256069   | 0.145455   |  0.953407    |            0.777778 |             0.173311    |                0.999998    |            0.16704     |               0.554535 |        0.0906455   |                 0.153407    |              0.109355    |
| wine_quality        | logistic_regression | causal_shap             |                   |       0.0362736   |      0.27      |    0.01        |    0           |   1         |    0.384982   | 0.503636   |  0.986692    |            1        |             0.498153    |                1           |            0.436422    |               0.667903 |        0.509193    |                 0.419214    |              0.210807    |
| wine_quality        | logistic_regression | shap_interactive        |                   |       0.00350647  |      0.2       |    0           |    0           |   1         |    0.401519   | 0.654545   |  1           |            0.25     |             0.700718    |                0.999999    |            0.72        |               0.86     |        0.548752    |                 0.654545    |              0.451248    |
| wine_quality        | logistic_regression | prototype               |                   |       0.000214385 |      0.59      |    0.646474    |    1           |   0.9308    |    0.181193   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_quality        | logistic_regression | counterfactual          |                   |       0.000276077 |      0.625     |    0.401859    |    1           |   0.821766  |    0.578039   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_quality        | logistic_regression | influence_functions     |                   |       0.0240073   |      0         |    0           |    0           |   0.394837  |    0.280478   | 0.727273   |  0.370059    |            1        |             0.343281    |                0.999999    |            0.349279    |               0.827806 |        0.898149    |                 0.370059    |              0.101851    |
| wine_quality        | logistic_regression | bayesian_rule_list      |                   |       0.000917962 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.469    |        0           |                 0           |              0           |
| wine_quality        | logistic_regression | corels                  |                   |       0.000641117 |      0         |    0           |    0           |   1         |    0          | 0          |  3.22974e-16 |            1        |             0           |                0.5         |            0           |               0.469    |        1           |                 0           |              0           |
| wine_quality        | logistic_regression | feature_ablation        |                   |       0.000809984 |      0         |    0           |    0           |   0         |    0.487483   | 0.0581818  |  0.918182    |            1        |             0.402577    |                1           |            0.394       |               0.664    |        0.0899699   |                 0.358182    |              0.35003     |
| diabetes            | decision_tree       | shap                    |                   |       0.00100332  |      0.758427  |    0.0374532   |    0.146067    |   0         |    0.321953   | 0.0314607  |  0.876854    |            0.413333 |             0.765141    |                1           |            0.723873    |               0.578652 |        0.135402    |                 0.652135    |              0.639879    |
| diabetes            | decision_tree       | lime                    |                   |       0.00899208  |      0.22      |    0.0466667   |    0           |   0         |    0.467728   | 0.07       |  0.942904    |            0.652174 |             0.5         |                1           |            0.491166    |               0.469267 |        0.0360662   |                 0.442904    |              0.463934    |
| diabetes            | decision_tree       | causal_shap             |                   |       0.0398431   |      0.39      |    0.025       |    0.1         |   1         |    0.404391   | 0.346      |  0.991895    |            1        |             0.621405    |                1           |            0.581547    |               0.478237 |        0.286045    |                 0.529729    |              0.413955    |
| diabetes            | decision_tree       | shapley_flow            |                   |       0.0140601   |      0.133333  |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.396667 |        0           |                 0           |              0           |
| diabetes            | decision_tree       | shap_interactive        |                   |       0.00394545  |      0.6       |    0           |    0           |   1         |    0.513064   | 0.42       |  1           |            1        |             0.885011    |                1           |            0.866667    |               0.58     |        0.286273    |                 0.78        |              0.713727    |
| diabetes            | decision_tree       | prototype               |                   |       0.000146635 |      0.494382  |    0.95532     |    1           |   0.915864  |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| diabetes            | decision_tree       | counterfactual          |                   |       0.000148923 |      0.494382  |    0.0499685   |    1           |   0.914067  |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| diabetes            | decision_tree       | bayesian_rule_list      |                   |       0.000882778 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.346067 |        0           |                 0           |              0           |
| diabetes            | decision_tree       | corels                  |                   |       0.000551725 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             8.67362e-17 |                5.71237e-14 |            4.44089e-16 |               0.346067 |        1           |                 0           |              0           |
| diabetes            | decision_tree       | feature_ablation        |                   |       0.000785141 |      0         |    0           |    0           |   0         |    0.337165   | 0.042      |  0.862       |            1        |             0.825826    |                0.999999    |            0.779111    |               0.588    |        0.159605    |                 0.702       |              0.680395    |
| diabetes            | random_forest       | shap                    |                   |       0.0425169   |      0.426966  |    0.0134831   |    0           |   0         |    0.304495   | 0.0786517  |  0.91236     |            0.592593 |             0.421116    |                1           |            0.414482    |               0.547191 |        0.0947116   |                 0.373034    |              0.365963    |
| diabetes            | random_forest       | lime                    |                   |       0.0250357   |      0.07      |    0           |    0           |   0         |    0.363333   | 0.112      |  0.941451    |            0.8125   |             0.230579    |                0.5         |            0.22611     |               0.477564 |        0.0910447   |                 0.201451    |              0.168955    |
| diabetes            | random_forest       | causal_shap             |                   |       1.41979     |      0.12      |    0.00222222  |    0           |   0         |    0.291538   | 0.354      |  0.963421    |            0.962963 |             0.381801    |                0.999996    |            0.330242    |               0.545055 |        0.37756     |                 0.309602    |              0.16244     |
| diabetes            | random_forest       | shapley_flow            |                   |       0.684472    |      0.0666667 |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.373333 |        0           |                 0           |              0           |
| diabetes            | random_forest       | shap_interactive        |                   |       0.177112    |      0.1       |    0           |    0           |   0         |    0.407586   | 0.38       |  0.706667    |            0.285714 |             0.797701    |                0.999999    |            0.782222    |               0.72     |        0.451741    |                 0.706667    |              0.548259    |
| diabetes            | random_forest       | prototype               |                   |       0.00320607  |      0.58427   |    0.661804    |    1           |   0.977981  |    0.43764    | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| diabetes            | random_forest       | counterfactual          |                   |       0.0033444   |      0.58427   |    0.404192    |    1           |   0.757925  |    0.3749     | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| diabetes            | random_forest       | bayesian_rule_list      |                   |       0.00371262  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.408989 |        0           |                 0           |              0           |
| diabetes            | random_forest       | corels                  |                   |       0.00352331  |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             8.67362e-17 |                4.09786e-14 |            4.44089e-16 |               0.408989 |        1           |                 0           |              0           |
| diabetes            | random_forest       | feature_ablation        |                   |       0.0391908   |      0         |    0           |    0           |   0         |    0.309151   | 0.074      |  0.914       |            1        |             0.358486    |                1           |            0.348889    |               0.554    |        0.104396    |                 0.314       |              0.295604    |
| diabetes            | gradient_boosting   | shap                    |                   |       0.00648251  |      0.483146  |    0.0327715   |    0.00736483  |   0         |    0.310918   | 0.0741573  |  0.904045    |            0.416667 |             0.484163    |                1           |            0.467451    |               0.532584 |        0.113078    |                 0.420899    |              0.403776    |
| diabetes            | gradient_boosting   | lime                    |                   |       0.0111081   |      0.11      |    0.0210238   |    0           |   0         |    0.34277    | 0.266      |  0.892751    |            0.642857 |             0.484564    |                1           |            0.464019    |               0.477454 |        0.182697    |                 0.412751    |              0.337303    |
| diabetes            | gradient_boosting   | causal_shap             |                   |       0.203902    |      0.37      |    0.0133333   |    0.0300381   |   1         |    0.329324   | 0.574      |  0.9975      |            0.9      |             0.676399    |                1           |            0.594877    |               0.570646 |        0.507171    |                 0.550747    |              0.332829    |
| diabetes            | gradient_boosting   | shap_interactive        |                   |       0.0269971   |      0.2       |    0           |    0           |   1         |    0.366845   | 0.4        |  1           |            1        |             0.854733    |                1           |            0.8         |               0.58     |        0.431672    |                 0.72        |              0.568328    |
| diabetes            | gradient_boosting   | prototype               |                   |       0.00063804  |      0.539326  |    0.77335     |    1           |   0.810043  |    0.707711   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| diabetes            | gradient_boosting   | counterfactual          |                   |       0.000716785 |      0.539326  |    0.291188    |    1           |   0.942838  |    0.6844     | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| diabetes            | gradient_boosting   | bayesian_rule_list      |                   |       0.00125593  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.377528 |        0           |                 0           |              0           |
| diabetes            | gradient_boosting   | corels                  |                   |       0.000903392 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             8.67362e-17 |                3.35529e-14 |            4.44089e-16 |               0.377528 |        1           |                 0           |              0           |
| diabetes            | gradient_boosting   | feature_ablation        |                   |       0.00524195  |      0         |    0           |    0           |   0         |    0.305175   | 0.08       |  0.9072      |            1        |             0.446765    |                1           |            0.429841    |               0.536    |        0.115967    |                 0.3872      |              0.364033    |
| diabetes            | mlp                 | shap                    |                   |       0.00125338  |      0.685393  |    0.0093633   |    0.0525015   |   0         |    0.280145   | 0.182022   |  0.848464    |            0.32381  |             0.636069    |                0.999999    |            0.629186    |               0.530337 |        0.186482    |                 0.567566    |              0.532619    |
| diabetes            | mlp                 | lime                    |                   |       0.00906971  |      0.14      |    0.00222222  |    0           |   0         |    0.311004   | 0.266      |  0.858703    |            0.708333 |             0.346419    |                0.999993    |            0.348828    |               0.384029 |        0.238923    |                 0.318703    |              0.221077    |
| diabetes            | mlp                 | integrated_gradients    |                   |       0.0829881   |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.326667 |        0           |                 0           |              0           |
| diabetes            | mlp                 | causal_shap             |                   |       0.0379194   |      0.39      |    0.00694444  |    0.0378996   |   1         |    0.336105   | 0.438      |  0.998105    |            1        |             0.451522    |                1           |            0.384463    |               0.467431 |        0.485118    |                 0.360621    |              0.174882    |
| diabetes            | mlp                 | shapley_flow            |                   |       0.0182317   |      0.1       |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.326667 |        0           |                 0           |              0           |
| diabetes            | mlp                 | shap_interactive        |                   |       0.00519166  |      0.2       |    0           |    0           |   1         |    0.502942   | 0.38       |  1           |            0.2      |             0.613836    |                0.999999    |            0.6         |               0.72     |        0.631672    |                 0.54        |              0.368328    |
| diabetes            | mlp                 | prototype               |                   |       0.000107982 |      0.449438  |    0.815212    |    1           |   0.941738  |    0.218574   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| diabetes            | mlp                 | counterfactual          |                   |       0.000164972 |      0.449438  |    0.241208    |    1           |   0.908253  |    0.810797   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| diabetes            | mlp                 | influence_functions     |                   |       0.0197205   |      0         |    0           |    0           |   0.393972  |    0.288676   | 0.7        |  0.334291    |            1        |             0.308224    |                1           |            0.305041    |               0.596603 |        0.906816    |                 0.334291    |              0.0931843   |
| diabetes            | mlp                 | bayesian_rule_list      |                   |       0.000857292 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.314607 |        0           |                 0           |              0           |
| diabetes            | mlp                 | corels                  |                   |       0.000494384 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             8.67362e-17 |                8.97248e-14 |            4.44089e-16 |               0.314607 |        1           |                 0           |              0           |
| diabetes            | mlp                 | feature_ablation        |                   |       0.00106723  |      0         |    0           |    0           |   0         |    0.285286   | 0.198      |  0.855267    |            1        |             0.597364    |                1           |            0.592543    |               0.54     |        0.184886    |                 0.535267    |              0.495114    |
| diabetes            | linear_regression   | lime                    |                   |       0.0131901   |      0.288134  |    0.754857    |    0           |   0         |    0.372729   | 0.56       |  0.750352    |            1        |             0.829595    |                1           |            0.828029    |               0.576453 |        0.416354    |                 0.750352    |              0.583646    |
| diabetes            | linear_regression   | causal_shap             |                   |       0.0270279   |      0.577109  |    0.446       |    0.377473    |   0         |    0.463213   | 0.7        |  0.999587    |            1        |             0.648636    |                1           |            0.503168    |               0.539307 |        0.814838    |                 0.483189    |              0.185162    |
| diabetes            | linear_regression   | shap_interactive        |                   |       0.00297503  |      0.69345   |    0.36        |    0.472057    |   0         |    0.444848   | 0.7        |  0.995867    |            1        |             0.661316    |                1           |            0.53856     |               0.582312 |        0.799718    |                 0.501811    |              0.200282    |
| diabetes            | linear_regression   | prototype               |                   |       0.000187212 |      0.550562  |    0           |    1           |   0         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| diabetes            | linear_regression   | counterfactual          |                   |       0.000114355 |      0.550562  |    0.405356    |    1           |   0.954367  |    0.468775   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| diabetes            | linear_regression   | bayesian_rule_list      |                   |       0.000831668 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.424719 |        0           |                 0           |              0           |
| diabetes            | linear_regression   | corels                  |                   |       0.000391191 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             8.67362e-17 |                7.75581e-14 |            4.44089e-16 |               0.424719 |        1           |                 0           |              0           |
| diabetes            | linear_regression   | feature_ablation        |                   |       0.000565071 |      0         |    0           |    0           |   0.351284  |    0.552891   | 0.7        |  0.483189    |            1        |             0.462402    |                1           |            0.503168    |               0.490062 |        0.814838    |                 0.483189    |              0.185162    |
| diabetes            | logistic_regression | lime                    |                   |       0.00965023  |      0.06      |    0           |    0           |   0         |    0.343597   | 0.168      |  0.908002    |            0.958333 |             0.19729     |                0.999999    |            0.200747    |               0.474921 |        0.150266    |                 0.188002    |              0.129734    |
| diabetes            | logistic_regression | causal_shap             |                   |       0.028679    |      0.26      |    0           |    4.44089e-18 |   0         |    0.353275   | 0.378      |  0.986411    |            0.901961 |             0.380085    |                1           |            0.3099      |               0.602838 |        0.427875    |                 0.293872    |              0.132125    |
| diabetes            | logistic_regression | shap_interactive        |                   |       0.00333781  |      0.1       |    0           |    0           |   0.188841  |    0.4896     | 0.5        |  0.514286    |            0.2      |             0.518072    |                0.999999    |            0.567901    |               0.72     |        0.688066    |                 0.514286    |              0.311934    |
| diabetes            | logistic_regression | prototype               |                   |       0.000135103 |      0.651685  |    0.687997    |    1           |   0.955126  |    0.335008   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| diabetes            | logistic_regression | counterfactual          |                   |       0.000135363 |      0.651685  |    0.378017    |    1           |   0.97613   |    0.789959   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| diabetes            | logistic_regression | influence_functions     |                   |       0.0143735   |      0         |    0           |    0           |   0.393972  |    0.288676   | 0.7        |  0.334291    |            1        |             0.308224    |                0.999999    |            0.305041    |               0.701603 |        0.906816    |                 0.334291    |              0.0931843   |
| diabetes            | logistic_regression | bayesian_rule_list      |                   |       0.000701122 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.45618  |        0           |                 0           |              0           |
| diabetes            | logistic_regression | corels                  |                   |       0.000367087 |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             8.67362e-17 |                1.0254e-13  |            4.44089e-16 |               0.45618  |        1           |                 0           |              0           |
| diabetes            | logistic_regression | feature_ablation        |                   |       0.000840535 |      0         |    0           |    0           |   0         |    0.31713    | 0.084      |  0.897       |            1        |             0.429381    |                1           |            0.418519    |               0.592    |        0.124239    |                 0.377       |              0.355761    |
| wine_classification | decision_tree       | shap                    |                   |       0.00140454  |      0.388889  |    0.0277778   |    0.152778    |   0         |    0.388889   | 0          |  0.965812    |            0.916667 |             0.444444    |                1           |            0.444444    |               0.794444 |       -1.73276e-11 |                 0.410256    |              0.444444    |
| wine_classification | decision_tree       | lime                    |                   |       0.0112664   |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.661111 |        0           |                 0           |              0           |
| wine_classification | decision_tree       | causal_shap             |                   |       0.0420441   |      0.333333  |    0           |    0.222222    |   0         |    0.563041   | 0.0192308  |  0.936342    |            1        |             0.694444    |                1           |            0.662093    |               0.821505 |        0.12138     |                 0.613937    |              0.573065    |
| wine_classification | decision_tree       | shapley_flow            |                   |       0.0164846   |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.653333 |        0           |                 0           |              0           |
| wine_classification | decision_tree       | shap_interactive        |                   |       0.00456176  |      0.2       |    0           |    0.1         |   0         |    0.550897   | 0          |  0.928205    |            1        |             0.6         |                0.999998    |            0.57        |               0.74     |        0.103679    |                 0.528205    |              0.496321    |
| wine_classification | decision_tree       | prototype               |                   |       9.33409e-05 |      0.944444  |    0.959767    |    1           |   0.978159  |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_classification | decision_tree       | counterfactual          |                   |       0.000113388 |      0.944444  |    0.0657999   |    1           |   0.92333   |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_classification | decision_tree       | bayesian_rule_list      |                   |       0.00089758  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.661111 |        0           |                 0           |              0           |
| wine_classification | decision_tree       | corels                  |                   |       0.000544104 |      0         |    0           |    0           |   1         |    0          | 0          |  1.36643e-16 |            1        |             0           |                0.5         |            3.33067e-16 |               0.661111 |        1           |                 0           |              0           |
| wine_classification | decision_tree       | feature_ablation        |                   |       0.000999285 |      0         |    0           |    0           |   0         |    0.388889   | 0          |  0.965812    |            1        |             0.444444    |                1           |            0.444444    |               0.794444 |       -1.73276e-11 |                 0.410256    |              0.444444    |
| wine_classification | random_forest       | shap                    |                   |       0.0465866   |      0.0972222 |    0           |    0           |   0         |    0.429628   | 0          |  0.987179    |            1        |             0.138889    |                1           |            0.136574    |               0.741667 |        0.00750662  |                 0.126068    |              0.131382    |
| wine_classification | random_forest       | lime                    |                   |       0.0191209   |      0.0277778 |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.7      |        0           |                 0           |              0           |
| wine_classification | random_forest       | causal_shap             |                   |       1.53104     |      0.0833333 |    0           |    0.102229    |   0         |    0.349156   | 0.356838   |  0.935735    |            1        |             0.612741    |                1           |            0.553764    |               0.836285 |        0.324824    |                 0.509872    |              0.341843    |
| wine_classification | random_forest       | shapley_flow            |                   |       0.751249    |      0.0333333 |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.7      |        0           |                 0           |              0           |
| wine_classification | random_forest       | shap_interactive        |                   |       0.163007    |      0.3       |    0           |    0           |   0         |    0.290879   | 0          |  0.9         |            1        |             0.59685     |                1           |            0.538889    |               0.88     |        0.189167    |                 0.5         |              0.410833    |
| wine_classification | random_forest       | prototype               |                   |       0.00519076  |      1         |    0.926606    |    1           |   0.98108   |    0.424639   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_classification | random_forest       | counterfactual          |                   |       0.00367902  |      1         |    0.158452    |    1           |   0.871258  |    0.750871   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_classification | random_forest       | bayesian_rule_list      |                   |       0.0039854   |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.7      |        0           |                 0           |              0           |
| wine_classification | random_forest       | corels                  |                   |       0.00368557  |      0         |    0           |    0           |   1         |    0          | 0          |  1.36643e-16 |            1        |             0           |                0.5         |            3.33067e-16 |               0.7      |        1           |                 0           |              0           |
| wine_classification | random_forest       | feature_ablation        |                   |       0.0445544   |      0         |    0           |    0           |   0         |    0.429628   | 0          |  0.987179    |            1        |             0.138889    |                1           |            0.136574    |               0.741667 |        0.00750662  |                 0.126068    |              0.131382    |
| wine_classification | gradient_boosting   | shap                    |                   |       0.00713822  |      0.152778  |    0           |    0.110543    |   0         |    0.443452   | 0          |  0.982906    |            0.875    |             0.222222    |                1           |            0.222222    |               0.727778 |       -8.66381e-12 |                 0.205128    |              0.222222    |
| wine_classification | gradient_boosting   | lime                    |                   |       0.0105334   |      0         |    0           |    0           |   0         |    0.382227   | 0.0192308  |  0.980805    |            0.736842 |             0.222222    |                0.5         |            0.219585    |               0.721735 |        0.0119428   |                 0.203027    |              0.210279    |
| wine_classification | gradient_boosting   | causal_shap             |                   |       0.239421    |      0.0694444 |    0           |    0.124444    |   1         |    0.596935   | 0.0747863  |  0.981291    |            0.979021 |             0.638889    |                1           |            0.608593    |               0.792853 |        0.129823    |                 0.562528    |              0.509066    |
| wine_classification | gradient_boosting   | shap_interactive        |                   |       0.0257226   |      0.1       |    0           |    0.0960062   |   1         |    0.641532   | 0          |  0.984615    |            1        |             0.8         |                1           |            0.75        |               0.8      |        0.162143    |                 0.692308    |              0.637857    |
| wine_classification | gradient_boosting   | prototype               |                   |       0.000569622 |      0.944444  |    0.960956    |    1           |   0.943835  |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_classification | gradient_boosting   | counterfactual          |                   |       0.000867267 |      0.944444  |    0.0669884   |    1           |   0.95058   |    0.570153   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_classification | gradient_boosting   | bayesian_rule_list      |                   |       0.00190831  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.661111 |        0           |                 0           |              0           |
| wine_classification | gradient_boosting   | corels                  |                   |       0.00131868  |      0         |    0           |    0           |   1         |    0          | 0          |  1.36643e-16 |            1        |             0           |                0.5         |            3.33067e-16 |               0.661111 |        1           |                 0           |              0           |
| wine_classification | gradient_boosting   | feature_ablation        |                   |       0.00789607  |      0         |    0           |    0           |   0         |    0.443452   | 0          |  0.982906    |            1        |             0.222222    |                1           |            0.222222    |               0.727778 |       -8.66381e-12 |                 0.205128    |              0.222222    |
| wine_classification | mlp                 | shap                    |                   |       0.00167846  |      0.111111  |    0           |    0.00544044  |   0         |    0.346841   | 0.0320513  |  0.965812    |            0.823529 |             0.115903    |                1           |            0.113426    |               0.741667 |        0.0518474   |                 0.104701    |              0.0870415   |
| wine_classification | mlp                 | lime                    |                   |       0.0106345   |      0.0277778 |    0           |    0           |   0         |    0.328796   | 0.0769231  |  0.972982    |            0.777778 |             0.159975    |                1           |            0.150895    |               0.726568 |        0.0543558   |                 0.139648    |              0.112311    |
| wine_classification | mlp                 | integrated_gradients    |                   |       0.11417     |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.7      |        0           |                 0           |              0           |
| wine_classification | mlp                 | causal_shap             |                   |       0.0496933   |      0.0833333 |    0           |    0.10204     |   1         |    0.317882   | 0.386752   |  0.99171     |            0.965517 |             0.524902    |                1           |            0.449992    |               0.838513 |        0.410811    |                 0.419802    |              0.228078    |
| wine_classification | mlp                 | shapley_flow            |                   |       0.0212584   |      0.0333333 |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.7      |        0           |                 0           |              0           |
| wine_classification | mlp                 | shap_interactive        |                   |       0.00495086  |      0         |    0           |    0           |   1         |    0.331745   | 0.384615   |  1           |            0.25     |             0.802982    |                1           |            0.766667    |               1        |        0.498796    |                 0.707692    |              0.501204    |
| wine_classification | mlp                 | prototype               |                   |       0.000111116 |      1         |    0.942231    |    1           |   0.983403  |    0.693891   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_classification | mlp                 | counterfactual          |                   |       0.000120554 |      1         |    0.10252     |    1           |   0.912485  |    0.778263   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_classification | mlp                 | influence_functions     |                   |       0.0166373   |      0         |    0           |    0           |   0.342061  |    0.240949   | 0.692308   |  0.365822    |            1        |             0.334844    |                1           |            0.333983    |               0.983674 |        0.90877     |                 0.365822    |              0.0912303   |
| wine_classification | mlp                 | bayesian_rule_list      |                   |       0.000891633 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.7      |        0           |                 0           |              0           |
| wine_classification | mlp                 | corels                  |                   |       0.000718832 |      0         |    0           |    0           |   1         |    0          | 0          |  1.36643e-16 |            1        |             0           |                0.5         |            3.33067e-16 |               0.7      |        1           |                 0           |              0           |
| wine_classification | mlp                 | feature_ablation        |                   |       0.0025294   |      0         |    0           |    0           |   0         |    0.346841   | 0.0320513  |  0.965812    |            1        |             0.115903    |                1           |            0.113426    |               0.741667 |        0.0518474   |                 0.104701    |              0.0870415   |
| wine_classification | linear_regression   | lime                    |                   |       0.0121455   |      0.462324  |    0.335979    |    0           |   0         |    0.435587   | 0.653846   |  0.828009    |            1        |             0.990486    |                1           |            0.924864    |               0.762704 |        0.36185     |                 0.828009    |              0.63815     |
| wine_classification | linear_regression   | causal_shap             |                   |       0.0380853   |      0.579441  |    0.480769    |    0.782028    |   1         |    0.508346   | 0.692308   |  1           |            1        |             0.761563    |                0.999999    |            0.642003    |               0.732591 |        0.760431    |                 0.570195    |              0.239569    |
| wine_classification | linear_regression   | shap_interactive        |                   |       0.00345597  |      0.703643  |    0.492308    |    0.870018    |   1         |    0.537912   | 0.692308   |  1           |            1        |             0.81674     |                1           |            0.664025    |               0.721863 |        0.737156    |                 0.574615    |              0.262844    |
| wine_classification | linear_regression   | prototype               |                   |       0.000215848 |      0.583333  |    0           |    1           |   0         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_classification | linear_regression   | counterfactual          |                   |       0.000177224 |      0.583333  |    0.340533    |    1           |   0.982747  |    0.255631   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_classification | linear_regression   | bayesian_rule_list      |                   |       0.000914786 |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.602778 |        0           |                 0           |              0           |
| wine_classification | linear_regression   | corels                  |                   |       0.000539687 |      0         |    0           |    0           |   1         |    0          | 0          |  1.36643e-16 |            1        |             0           |                0.5         |            3.33067e-16 |               0.602778 |        1           |                 0           |              0           |
| wine_classification | linear_regression   | feature_ablation        |                   |       0.000784159 |      0         |    0           |    0           |   0.316796  |    0.55778    | 0.692308   |  0.570195    |            1        |             0.627951    |                1           |            0.642003    |               0.703137 |        0.760431    |                 0.570195    |              0.239569    |
| wine_classification | logistic_regression | lime                    |                   |       0.00856584  |      0.0555556 |    0           |    0           |   0         |    0.399407   | 0.0769231  |  0.963891    |            0.789474 |             0.175502    |                1           |            0.168389    |               0.70693  |        0.0714681   |                 0.158335    |              0.122976    |
| wine_classification | logistic_regression | causal_shap             |                   |       0.0382032   |      0.0972222 |    0           |    0.0967768   |   1         |    0.314934   | 0.34188    |  0.99469     |            1        |             0.488336    |                1           |            0.422162    |               0.806454 |        0.365896    |                 0.394301    |              0.217437    |
| wine_classification | logistic_regression | shap_interactive        |                   |       0.0030046   |      0         |    0           |    0           |   1         |    0.358754   | 0.261538   |  1           |            0.333333 |             0.859065    |                1           |            0.833333    |               0.86     |        0.373301    |                 0.769231    |              0.626699    |
| wine_classification | logistic_regression | prototype               |                   |       0.00016025  |      0.972222  |    0.936907    |    1           |   0.95944   |    0.741601   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_classification | logistic_regression | counterfactual          |                   |       0.000258029 |      0.972222  |    0.123498    |    1           |   0.877076  |    0.779989   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| wine_classification | logistic_regression | influence_functions     |                   |       0.00958978  |      0         |    0           |    0           |   0.342061  |    0.240949   | 0.692308   |  0.365822    |            1        |             0.334844    |                1           |            0.333983    |               0.948674 |        0.90877     |                 0.365822    |              0.0912303   |
| wine_classification | logistic_regression | bayesian_rule_list      |                   |       0.00122282  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.680556 |        0           |                 0           |              0           |
| wine_classification | logistic_regression | corels                  |                   |       0.000935786 |      0         |    0           |    0           |   1         |    0          | 0          |  1.36643e-16 |            1        |             0           |                0.5         |            3.33067e-16 |               0.680556 |        1           |                 0           |              0           |
| wine_classification | logistic_regression | feature_ablation        |                   |       0.000847379 |      0         |    0           |    0           |   0         |    0.308886   | 0.034188   |  0.965812    |            1        |             0.116748    |                0.999998    |            0.113426    |               0.722222 |        0.0538219   |                 0.104701    |              0.085067    |
| digits              | decision_tree       | shap                    |                   |       0.00663521  |      0.684492  |    0.164167    |    0.0177778   |   0.08         |    0.150467   | 0          |  0.976903    |            0.210526 |             0.93        |                1           |            0.920391    |               0.832    |        0.103216    |                 0.906903    |              0.826784    |
| digits              | decision_tree       | lime                    |                   |       0.00977457  |      0.177     |    0.02        |    0           |   0.07         |    0.166172   | 0          |  0.992677    |            0.714286 |             0.4         |                1           |            0.399358    |               0.672503 |        0.0131814   |                 0.392677    |              0.386819    |
| digits              | decision_tree       | causal_shap             |                   |       0.212497    |      0.552643  |    0.056881    |    0.0699696   |   1         |    0.175523   | 0          |  1           |            1        |             0.9         |                1           |            0.869741    |               0.83     |        0.266733    |                 0.857512    |              0.633267    |
| digits              | decision_tree       | shapley_flow            |                   |       0.0831333   |      0.1575    |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.583333 |        0           |                 0           |              0           |
| digits              | decision_tree       | shap_interactive        |                   |       0.00726509  |      0.588571  |    0.2         |    0           |   1         |    0.355973   | 0          |  1           |            1        |             0.8         |                1           |            0.793523    |               0.94     |        0.0710235   |                 0.781944    |              0.728977    |
| digits              | decision_tree       | prototype               |                   |       0.000266458 |      0.835     |    0.909077    |    1           |   0.929677  |    0.34          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| digits              | decision_tree       | counterfactual          |                   |       0.000404361 |      0.84      |    0.132032    |    1           |   0.952961  |    0.12          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| digits              | decision_tree       | bayesian_rule_list      |                   |       0.00391365  |      0         |    0           |    0           |   1         |    0.56          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.553    |        0           |                 0           |              0           |
| digits              | decision_tree       | corels                  |                   |       0.00616098  |      0         |    0           |    0           |   1         |    0.65          | 0          |  0           |            1        |             6.93889e-17 |                7.66837e-15 |            2.22045e-16 |               0.553    |        1           |                 0           |              5.33904e-17 |
| digits              | decision_tree       | feature_ablation        |                   |       0.00386136  |      0         |    0           |    0           |   0         |    0.162409   | 0          |  0.975507    |            1        |             0.94        |                1           |            0.92914     |               0.842    |        0.11206     |                 0.915507    |              0.82794     |
| digits              | random_forest       | shap                    |                   |       0.196954    |      0.0693294 |    0.0166667   |    0           |   0         |    0.13084    | 0          |  0.996563    |            0.545455 |             0.12        |                1           |            0.118413    |               0.701    |        0.0119499   |                 0.116562    |              0.10805     |
| digits              | random_forest       | lime                    |                   |       0.0189523   |      0.0533333 |    0           |    0           |   0         |    0.164787   | 0.06       |  0.98523     |            1        |             0.137602    |                0.999998    |            0.130031    |               0.697688 |        0.0635512   |                 0.12523     |              0.0764488   |
| digits              | random_forest       | causal_shap             |                   |       8.10424     |      0.258746  |    0           |    0.0101644   |   1         |    0.146164   | 0.538125   |  1           |            1        |             0.93873     |                1           |            0.805937    |               0.936327 |        0.578499    |                 0.779586    |              0.361501    |
| digits              | random_forest       | shapley_flow            |                   |       4.16893     |      0.0222222 |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.7      |        0           |                 0           |              0           |
| digits              | random_forest       | shap_interactive        |                   |       0.420347    |      0         |    0           |    0           |   0         |    0          | 0          |  0.996875    |            1        |             0.2         |                1           |            0.2         |               0.76     |       -4.80898e-12 |                 0.196875    |              0.2         |
| digits              | random_forest       | prototype               |                   |       0.00312084  |      0.965     |    0.827735    |    1           |   0.971011  |    0.277986   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| digits              | random_forest       | counterfactual          |                   |       0.0039226   |      0.965     |    0.368917    |    1           |   0.892587  |    0.935744   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| digits              | random_forest       | bayesian_rule_list      |                   |       0.00735547  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.665    |        0           |                 0           |              0           |
| digits              | random_forest       | corels                  |                   |       0.0101869   |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             6.93889e-17 |                3.72299e-15 |            2.22045e-16 |               0.665    |        1           |                 0           |              5.33904e-17 |
| digits              | random_forest       | feature_ablation        |                   |       0.202961    |      0         |    0           |    0           |   0         |    0.200447   | 0          |  0.995938    |            1        |             0.14        |                1           |            0.138095    |               0.728    |        0.0119499   |                 0.135937    |              0.12805     |
| digits              | gradient_boosting   | shap                    |                   |       0.0447617   |      0.234004  |    0.0209649   |    0.00886805  |   0         |    0.228398   | 0.00703125 |  0.98876     |            0.363636 |             0.319526    |                1           |            0.313503    |               0.754    |        0.0400262   |                 0.30876     |              0.279974    |
| digits              | gradient_boosting   | lime                    |                   |       0.0140082   |      0.04      |    0           |    0           |   0         |    0.122863   | 0.075      |  0.979172    |            1        |             0.198015    |                0.999992    |            0.184435    |               0.687167 |        0.0905373   |                 0.179172    |              0.109463    |
| digits              | gradient_boosting   | causal_shap             |                   |       1.72992     |      0.462825  |    0.001       |    0.0873478   |   1         |    0.145196   | 0.365938   |  1           |            1        |             0.918329    |                1           |            0.821697    |               0.926169 |        0.491268    |                 0.802308    |              0.428732    |
| digits              | gradient_boosting   | shap_interactive        |                   |       0.068044    |      0.16      |    0           |    0           |   1         |    0.507937   | 0          |  1           |            1        |             0.8         |                1           |            0.8         |               0.94     |       -1.92359e-11 |                 0.7875      |              0.8         |
| digits              | gradient_boosting   | prototype               |                   |       0.000863123 |      0.945     |    0.91107     |    1           |   0.931367  |    0.709519   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| digits              | gradient_boosting   | counterfactual          |                   |       0.00110794  |      0.95      |    0.165525    |    1           |   0.985046  |    0.289493   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| digits              | gradient_boosting   | bayesian_rule_list      |                   |       0.00487691  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.658    |        0           |                 0           |              0           |
| digits              | gradient_boosting   | corels                  |                   |       0.0081046   |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             6.93889e-17 |                4.09463e-15 |            2.22045e-16 |               0.658    |        1           |                 0           |              5.33904e-17 |
| digits              | gradient_boosting   | feature_ablation        |                   |       0.0504794   |      0         |    0           |    0           |   0         |    0.324478   | 0          |  0.993478    |            1        |             0.28        |                1           |            0.277785    |               0.756    |        0.0186025   |                 0.273478    |              0.261398    |
| digits              | mlp                 | shap                    |                   |       0.00700543  |      0.0373056 |    0           |    0           |   0         |    0.14515    | 0          |  0.997031    |            0.4      |             0.06        |                0.5         |            0.0579365   |               0.697    |        0.0136165   |                 0.0570312   |              0.0463835   |
| digits              | mlp                 | lime                    |                   |       0.0104954   |      0.005     |    0           |    0           |   0         |    0.122273   | 0.06       |  0.986182    |            1        |             0.119951    |                0.5         |            0.108655    |               0.692362 |        0.0606306   |                 0.106182    |              0.0593694   |
| digits              | mlp                 | integrated_gradients    |                   |       0.542131    |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.7      |        0           |                 0           |              0           |
| digits              | mlp                 | causal_shap             |                   |       0.277812    |      0.0494444 |    0           |    0.0710856   |   0         |    0.121803   | 0.684688   |  1           |            1        |             0.84927     |                0.999999    |            0.664074    |               0.965248 |        0.718058    |                 0.661088    |              0.221942    |
| digits              | mlp                 | shapley_flow            |                   |       0.123502    |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.7      |        0           |                 0           |              0           |
| digits              | mlp                 | shap_interactive        |                   |       0.0102489   |      0         |    0           |    0           |   0.135399  |    0.376977   | 0.6875     |  0.801085    |            1        |             0.744891    |                0.999999    |            0.681018    |               1        |        0.748332    |                 0.69677     |              0.251668    |
| digits              | mlp                 | prototype               |                   |       0.0002021   |      0.985     |    0.923148    |    1           |   0.970893  |    0.887254   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| digits              | mlp                 | counterfactual          |                   |       0.000396897 |      0.98      |    0.1478      |    1           |   0.975256  |    0.678556   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| digits              | mlp                 | influence_functions     |                   |       0.0205166   |      0         |    0           |    0           |   0.355535  |    0.550953   | 0.75       |  0.473945    |            1        |             0.439499    |                0.999999    |            0.441508    |               1        |        0.905295    |                 0.473945    |              0.0947046   |
| digits              | mlp                 | bayesian_rule_list      |                   |       0.00373788  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.679    |        0           |                 0           |              0           |
| digits              | mlp                 | corels                  |                   |       0.00626015  |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             6.93889e-17 |                3.81567e-15 |            2.22045e-16 |               0.679    |        1           |                 0           |              5.33904e-17 |
| digits              | mlp                 | feature_ablation        |                   |       0.00623291  |      0         |    0           |    0           |   0         |    0.0226281  | 0          |  0.999062    |            1        |             0.04        |                0.5         |            0.0396825   |               0.698    |        0.00333333  |                 0.0390625   |              0.0366667   |
| digits              | linear_regression   | lime                    |                   |       0.0211142   |      0.214069  |    0.414497    |    0           |   0         |    0.18605    | 0.75       |  0.816281    |            1        |             0.990696    |                0.999996    |            0.877548    |               0.147702 |        0.635497    |                 0.816281    |              0.364503    |
| digits              | linear_regression   | causal_shap             |                   |       0.238425    |      0.341299  |    0.357705    |    0.172676    |   0         |    0.19117    | 0.75       |  1           |            1        |             0.853477    |                1           |            0.667705    |               0.412    |        0.81398     |                 0.651829    |              0.18602     |
| digits              | linear_regression   | shap_interactive        |                   |       0.00713267  |      0.214868  |    0.344262    |    0.24331     |   0         |    0.137513   | 0.75       |  1           |            1        |             0.870472    |                1           |            0.680183    |               0.3      |        0.812409    |                 0.651783    |              0.187591    |
| digits              | linear_regression   | prototype               |                   |       0.000319542 |      0.185     |    0           |    1           |   0         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| digits              | linear_regression   | counterfactual          |                   |       0.000439688 |      0.215     |    0.0264678   |    1.1         |   0.909291  |    0.171989   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| digits              | linear_regression   | bayesian_rule_list      |                   |       0.00504314  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.133    |        0           |                 0           |              0           |
| digits              | linear_regression   | corels                  |                   |       0.00816267  |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             6.93889e-17 |                5.95151e-15 |            2.22045e-16 |               0.133    |        1           |                 0           |              5.33904e-17 |
| digits              | linear_regression   | feature_ablation        |                   |       0.00456481  |      0         |    0           |    0           |   0.432594  |    0.827281   | 0.75       |  0.651829    |            1        |             0.697486    |                1           |            0.667705    |               0.412    |        0.81398     |                 0.651829    |              0.18602     |
| digits              | logistic_regression | lime                    |                   |       0.0145471   |      0         |    0           |    0           |   0         |    0.115197   | 0.135      |  0.964214    |            1        |             0.256444    |                0.999997    |            0.231905    |               0.688249 |        0.136569    |                 0.224214    |              0.123431    |
| digits              | logistic_regression | causal_shap             |                   |       0.216134    |      0.157111  |    0.000526316 |    0.0684205   |   1         |    0.136715   | 0.664062   |  1           |            1        |             0.863414    |                1           |            0.688955    |               0.934923 |        0.676226    |                 0.675192    |              0.243774    |
| digits              | logistic_regression | shap_interactive        |                   |       0.00725107  |      0.188571  |    0           |    0           |   1         |    0.248625   | 0          |  1           |            0.166667 |             0.8         |                1           |            0.778099    |               0.8      |        0.209447    |                 0.767865    |              0.590553    |
| digits              | logistic_regression | prototype               |                   |       0.000176775 |      0.965     |    0.910861    |    1           |   0.971369  |    0.0117864  | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| digits              | logistic_regression | counterfactual          |                   |       0.00043645  |      0.97      |    0.174185    |    1           |   0.988469  |    0.593827   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| digits              | logistic_regression | influence_functions     |                   |       0.0165327   |      0         |    0           |    0           |   0.355535  |    0.550953   | 0.75       |  0.473945    |            1        |             0.439499    |                0.999999    |            0.441508    |               0.965    |        0.905295    |                 0.473945    |              0.0947046   |
| digits              | logistic_regression | bayesian_rule_list      |                   |       0.00451257  |      0         |    0           |    0           |   1         |    0          | 0          |  1           |            1        |             0           |                0.5         |            0           |               0.665    |        0           |                 0           |              0           |
| digits              | logistic_regression | corels                  |                   |       0.0075582   |      0         |    0           |    0           |   1         |    0          | 0          |  0           |            1        |             6.93889e-17 |                5.34812e-15 |            2.22045e-16 |               0.665    |        1           |                 0           |              5.33904e-17 |
| digits              | logistic_regression | feature_ablation        |                   |       0.00387777  |      0         |    0           |    0           |   0         |    0.0622677  | 0.014375   |  0.991652    |            1        |             0.117709    |                1           |            0.1135      |               0.708    |        0.0294415   |                 0.111652    |              0.0905585   |
| mnist               | cnn                 | prototype               |                   |       0.00151482  |      0.975     |    0.658702    |    1           |   0.879469  |    0.133046   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| mnist               | cnn                 | counterfactual          |                   |       0.00392525  |      0.975     |    0.463766    |    1           |   0.527591  |    0.679416   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| mnist               | cnn                 | tcav                    |                   |       0           |      0         |    0           |    0           |   0         |    0          | 0          |  0           |          nan        |           nan           |              nan           |          nan           |             nan        |      nan           |               nan           |            nan           |
| mnist               | cnn                 | concept_bottleneck      |                   |       0           |      0         |    0           |    0           |   0         |    0          | 0          |  0           |          nan        |           nan           |              nan           |          nan           |             nan        |      nan           |               nan           |            nan           |
| mnist               | cnn                 | occlusion               |                   |       0.0262311   |      0         |    0           |    0           |   0         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| mnist               | vit                 | tcav                    |                   |       0           |      0         |    0           |    0           |   0         |    0          | 0          |  0           |          nan        |           nan           |              nan           |          nan           |             nan        |      nan           |               nan           |            nan           |
| mnist               | vit                 | concept_bottleneck      |                   |       0           |      0         |    0           |    0           |   0         |    0          | 0          |  0           |          nan        |           nan           |              nan           |          nan           |             nan        |      nan           |               nan           |            nan           |
| mnist               | vit                 | occlusion               |                   |       0.093974    |      0         |    0           |    0           |   0         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| mnist               | resnet              | prototype               |                   |       0.00716317  |      0.93      |    0.67764     |    1           |   0.808944  |    0.772879   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| mnist               | resnet              | counterfactual          |                   |       0.00757879  |      0.93      |    0.489901    |    1           |   0.808252  |    0.801461   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| cifar10             | cnn                 | prototype               |                   |       0.00378728  |      0.475     |    0.785471    |    1           |   0.550549  |    0.592905   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| cifar10             | cnn                 | counterfactual          |                   |       0.0467237   |      0.49      |    0.761747    |    1           |   0.954946  |    0.213222   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| cifar10             | cnn                 | tcav                    |                   |       0           |      0         |    0           |    0           |   0         |    0          | 0          |  0           |          nan        |           nan           |              nan           |          nan           |             nan        |      nan           |               nan           |            nan           |
| cifar10             | cnn                 | concept_bottleneck      |                   |       0           |      0         |    0           |    0           |   0         |    0          | 0          |  0           |          nan        |           nan           |              nan           |          nan           |             nan        |      nan           |               nan           |            nan           |
| cifar10             | cnn                 | occlusion               |                   |       0.0913628   |      0         |    0           |    0           |   0         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| cifar10             | vit                 | prototype               |                   |       0.00486374  |      0.145     |    0.748913    |    0.8         |   0.700019  |    0.146424   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| cifar10             | vit                 | counterfactual          |                   |       0.0484495   |      0.13      |    0.846048    |    0.7         |   0.875853  |    0.204568   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| cifar10             | vit                 | tcav                    |                   |       0           |      0         |    0           |    0           |   0         |    0          | 0          |  0           |          nan        |           nan           |              nan           |          nan           |             nan        |      nan           |               nan           |            nan           |
| cifar10             | vit                 | concept_bottleneck      |                   |       0           |      0         |    0           |    0           |   0         |    0          | 0          |  0           |          nan        |           nan           |              nan           |          nan           |             nan        |      nan           |               nan           |            nan           |
| cifar10             | vit                 | occlusion               |                   |       0.294884    |      0         |    0           |    0           |   0         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| cifar10             | resnet              | prototype               |                   |       0.00767135  |      0.395     |    0.749387    |    1           |   0.872459  |    0.913149   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| cifar10             | resnet              | counterfactual          |                   |       0.0518093   |      0.395     |    0.66737     |    1           |   0.919187  |    0.024721   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| fashion_mnist       | cnn                 | prototype               |                   |       0.00137794  |      0.87      |    0.851157    |    1           |   0.505974  |    0.928742   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| fashion_mnist       | cnn                 | counterfactual          |                   |       0.00578199  |      0.875     |    0.313382    |    1           |   0.890981  |    0.248793   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| fashion_mnist       | cnn                 | tcav                    |                   |       0           |      0         |    0           |    0           |   0         |    0          | 0          |  0           |          nan        |           nan           |              nan           |          nan           |             nan        |      nan           |               nan           |            nan           |
| fashion_mnist       | cnn                 | concept_bottleneck      |                   |       0           |      0         |    0           |    0           |   0         |    0          | 0          |  0           |          nan        |           nan           |              nan           |          nan           |             nan        |      nan           |               nan           |            nan           |
| fashion_mnist       | cnn                 | occlusion               |                   |       0.0190032   |      0         |    0           |    0           |   0         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| fashion_mnist       | vit                 | tcav                    |                   |       0           |      0         |    0           |    0           |   0         |    0          | 0          |  0           |          nan        |           nan           |              nan           |          nan           |             nan        |      nan           |               nan           |            nan           |
| fashion_mnist       | vit                 | concept_bottleneck      |                   |       0           |      0         |    0           |    0           |   0         |    0          | 0          |  0           |          nan        |           nan           |              nan           |          nan           |             nan        |      nan           |               nan           |            nan           |
| fashion_mnist       | vit                 | occlusion               |                   |       0.0857112   |      0         |    0           |    0           |   0         |    0          | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| fashion_mnist       | resnet              | prototype               |                   |       0.00583652  |      0.775     |    0.829821    |    1           |   0.872919  |    0.710857   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| fashion_mnist       | resnet              | counterfactual          |                   |       0.0111974   |      0.77      |    0.300529    |    1           |   0.911402  |    0.525025   | 0          |  0           |            1        |             0           |                0.5         |            0           |               0        |        0           |                 0           |              0           |
| imdb                | bert                | lime                    |                   |       0.056978    |      0.84      |    0.0100449   |    0.229556    |   0.30979   |    0.539306   | 0.555      |  0.738539    |            1        |             0.461302    |                0           |            0.450684    |               0.594062 |        0.90484     |                 0.448796    |              0.0951603   |
| imdb                | bert                | text_occlusion          |                   |       0.0579967   |      0         |    0.00964866  |    0.222065    |   0.300614  |    0.0578532  | 0.0035     |  0.84376     |            1        |             0.0889948   |                0           |            0.0824242   |               0.636    |        0.213716    |                 0.0816      |              0.0662839   |
| imdb                | bert                | attention_visualization |                   |       0.143287    |      0         |    0.0578132   |    0.371515    |   0.762451  |    0.0972172  | 0.709981   |  0.0392428   |            1        |             0.0360352   |                0           |            0.00554291  |               0.588018 |        0.999406    |                 0.0380659   |              0.00059366  |
| imdb                | lstm                | lime                    |                   |       0.0614532   |      0.8       |    0.00668869  |    0.229581    |   0.309757  |    0.544374   | 0.555      |  0.737443    |            1        |             0.522256    |                0           |            0.501594    |               0.567903 |        0.889007    |                 0.474999    |              0.110993    |
| imdb                | lstm                | text_occlusion          |                   |       0.0350408   |      0         |    0.0121254   |    0.222446    |   0.295708  |    0.0566207  | 0.0029     |  0.84898     |            1        |             0.173424    |                0           |            0.163838    |               0.65     |        0.244949    |                 0.1622      |              0.135051    |
| imdb                | lstm                | attention_visualization |                   |       0.0863567   |      0         |    0.0579823   |    0.37127     |   0.761745  |    0.0968388  | 0.708865   |  0.0404643   |            1        |             0.0371159   |                0           |            0.00585971  |               0.560019 |        0.999376    |                 0.038458    |              0.000623848 |
| imdb                | roberta             | lime                    |                   |      17.0277      |      0.88      |    0           |    0           |   0.11187   |    0.128267   | 0.74       |  0.438618    |            1        |             0.447604    |                0           |            0.441213    |               0.621256 |        0.911329    |                 0.438618    |              0.0886714   |
| imdb                | roberta             | text_occlusion          |                   |      15.0937      |      0         |    0           |    0           |   0         |    0.0464711  | 0.0002     |  0.916137    |            1        |             0.101005    |                0           |            0.097118    |               0.652    |        0.105887    |                 0.0961368   |              0.0741127   |
| imdb                | roberta             | attention_visualization |                   |      48.1745      |      0         |    0           |    0           |   0.714222  |    0.0948323  | 0.704748   |  0.0380763   |            1        |             0.0357704   |                0           |            0.00535819  |               0.616017 |        0.999431    |                 0.0380763   |              0.000569402 |
| imdb                | naive_bayes_text    | lime                    |                   |       0.114825    |      0.82      |    0.00655354  |    0.231286    |   0.309952  |    0.569781   | 0.555      |  0.733388    |            1        |             0.459049    |                0           |            0.455002    |               0.579473 |        0.905894    |                 0.453102    |              0.094106    |
| imdb                | naive_bayes_text    | text_occlusion          |                   |       0.0597765   |      0         |    0.0117962   |    0.211763    |   0.272464  |    0.0686004  | 0.00395    |  0.87537     |            1        |             0.184053    |                0           |            0.171742    |               0.64     |        0.176884    |                 0.169902    |              0.123116    |
| imdb                | naive_bayes_text    | attention_visualization |                   |       0.15084     |      0         |    0.0565965   |    0.371386    |   0.762108  |    0.0973869  | 0.709712   |  0.0399573   |            1        |             0.0378735   |                0           |            0.00628801  |               0.574021 |        0.999322    |                 0.0399019   |              0.000677785 |
| imdb                | svm_text            | lime                    |                   |       0.213527    |      0.76      |    0.00984158  |    0.229735    |   0.307537  |    0.543511   | 0.555      |  0.738298    |            1        |             0.46001     |                0           |            0.453038    |               0.537579 |        0.904387    |                 0.455504    |              0.0956131   |
| imdb                | svm_text            | text_occlusion          |                   |       0.13866     |      0         |    0.00960539  |    0.217464    |   0.285929  |    0.0626345  | 0.0032     |  0.860705    |            1        |             0.069419    |                0           |            0.0620202   |               0.58     |        0.216879    |                 0.0614      |              0.043121    |
| imdb                | svm_text            | attention_visualization |                   |       0.329897    |      0         |    0.0574652   |    0.371224    |   0.761736  |    0.096902   | 0.710509   |  0.0407733   |            1        |             0.0362694   |                0           |            0.00588889  |               0.532019 |        0.999372    |                 0.0386581   |              0.000628202 |
| imdb                | xgboost_text        | lime                    |                   |       0.198102    |      0.74      |    0.0100889   |    0.22657     |   0.309726  |    0.522172   | 0.555      |  0.740444    |            1        |             0.403613    |                0           |            0.370478    |               0.539637 |        0.877261    |                 0.406672    |              0.122739    |
| imdb                | xgboost_text        | text_occlusion          |                   |       0.106566    |      0         |    0.0127345   |    0.240483    |   0.344004  |    0.032496   | 0.00255    |  0.783983    |            1        |             0.223439    |                0           |            0.219798    |               0.602    |        0.171866    |                 0.217557    |              0.208134    |
| imdb                | xgboost_text        | attention_visualization |                   |       0.249861    |      0         |    0.0580796   |    0.371362    |   0.762687  |    0.0973031  | 0.708257   |  0.0380956   |            1        |             0.0359206   |                0           |            0.00536409  |               0.518017 |        0.999431    |                 0.0375866   |              0.000568738 |
| 20newsgroups        | bert                | lime                    |                   |       0.10264     |      0.491358  |    0.00925646  |    0.244485    |   0.257008  |    0.507191   | 0.2775     |  0.825643    |            1        |             0.620306    |                0           |            0.589102    |               0.462915 |        0.803352    |                 0.550091    |              0.176648    |
| 20newsgroups        | bert                | text_occlusion          |                   |       0.0375817   |      0         |    0.078356    |    0.198476    |   0.213816  |    0.0585392  | 0.00533333 |  0.913188    |            1        |             0.230544    |                0           |            0.220021    |               0.542857 |        0.13594     |                 0.213571    |              0.190591    |
| 20newsgroups        | bert                | attention_visualization |                   |       0.09881     |      0         |    0.254923    |    0.370485    |   0.476312  |    0.184049   | 0.707271   |  0.0505967   |            1        |             0.0498079   |                0           |            0.0138006   |               0.458351 |        0.998125    |                 0.0482937   |              0.00187457  |
| 20newsgroups        | lstm                | lime                    |                   |       0.0949421   |      0.68      |    0.00886234  |    0.245279    |   0.255012  |    0.507622   | 0.2775     |  0.825137    |            1        |             0.581799    |                0           |            0.556103    |               0.491755 |        0.80796     |                 0.531061    |              0.17204     |
| 20newsgroups        | lstm                | text_occlusion          |                   |       0.0408899   |      0         |    0.0752372   |    0.192337    |   0.190616  |    0.0582042  | 0.004      |  0.928714    |            1        |             0.166048    |                0           |            0.158037    |               0.526531 |        0.119349    |                 0.154191    |              0.125548    |
| 20newsgroups        | lstm                | attention_visualization |                   |       0.104019    |      0         |    0.256112    |    0.371182    |   0.46928   |    0.183897   | 0.708646   |  0.0472801   |            1        |             0.0476534   |                0           |            0.012645    |               0.473102 |        0.998358    |                 0.0471583   |              0.0016425   |
| 20newsgroups        | roberta             | lime                    |                   |      52.9093      |      0.78      |    0           |    0           |   0         |    0.209928   | 0.666      |  0.498086    |            1        |             0.483358    |                0           |            0.458279    |               0.557712 |        0.839457    |                 0.478086    |              0.140543    |
| 20newsgroups        | roberta             | text_occlusion          |                   |      10.3211      |      0         |    0.0668141   |    0.180553    |   0.113304  |    0.0998025  | 0.017741   |  0.955421    |            1        |             0.0970159   |                0           |            0.0957663   |               0.587755 |        0.0173301   |                 0.0900131   |              0.0847107   |
| 20newsgroups        | roberta             | attention_visualization |                   |      33.8771      |      0         |    0.253729    |    0.371077    |   0.481537  |    0.18511    | 0.707839   |  0.0482298   |            1        |             0.0494733   |                0           |            0.0144297   |               0.559159 |        0.997957    |                 0.0500622   |              0.00204299  |
| 20newsgroups        | naive_bayes_text    | lime                    |                   |       0.112432    |      0.68      |    0.00914578  |    0.247635    |   0.258285  |    0.509078   | 0.27744    |  0.822449    |            1        |             0.503757    |                0           |            0.482057    |               0.487477 |        0.833697    |                 0.492957    |              0.146303    |
| 20newsgroups        | naive_bayes_text    | text_occlusion          |                   |       0.0507786   |      0         |    0.0686709   |    0.182612    |   0.151541  |    0.0676381  | 0.00441026 |  0.955701    |            1        |             0.068422    |                0           |            0.0613466   |               0.502041 |        0.0597585   |                 0.0597406   |              0.0422823   |
| 20newsgroups        | naive_bayes_text    | attention_visualization |                   |       0.122163    |      0         |    0.256197    |    0.371326    |   0.485382  |    0.183564   | 0.707765   |  0.046435    |            1        |             0.0438573   |                0           |            0.00994115  |               0.472729 |        0.998746    |                 0.0457155   |              0.00125437  |
| 20newsgroups        | svm_text            | lime                    |                   |       0.18929     |      0.8       |    0.00883916  |    0.24656     |   0.25789   |    0.507846   | 0.27748    |  0.824116    |            1        |             0.531461    |                0           |            0.505024    |               0.572752 |        0.826614    |                 0.505186    |              0.153386    |
| 20newsgroups        | svm_text            | text_occlusion          |                   |       0.0809797   |      0         |    0.0714226   |    0.188997    |   0.186781  |    0.0616501  | 0.00415385 |  0.937982    |            1        |             0.244898    |                0           |            0.237394    |               0.630612 |        0.0397693   |                 0.231206    |              0.205129    |
| 20newsgroups        | svm_text            | attention_visualization |                   |       0.203533    |      0         |    0.25391     |    0.370145    |   0.466997  |    0.183447   | 0.707585   |  0.0505018   |            1        |             0.0511674   |                0           |            0.0142985   |               0.558473 |        0.998173    |                 0.0499176   |              0.00182696  |
| 20newsgroups        | xgboost_text        | lime                    |                   |       0.210455    |      0.7       |    0.00846661  |    0.235517    |   0.24962   |    0.468552   | 0.27747    |  0.834387    |            1        |             0.683892    |                0           |            0.647077    |               0.549217 |        0.686362    |                 0.589575    |              0.293638    |
| 20newsgroups        | xgboost_text        | text_occlusion          |                   |       0.0771799   |      0         |    0.0788193   |    0.20652     |   0.240768  |    0.0326767  | 0.00454791 |  0.880998    |            1        |             0.290405    |                0           |            0.281818    |               0.608163 |        0.164407    |                 0.273239    |              0.264165    |
| 20newsgroups        | xgboost_text        | attention_visualization |                   |       0.199089    |      0         |    0.25476     |    0.370813    |   0.485212  |    0.183898   | 0.708293   |  0.0478038   |            1        |             0.0500584   |                0           |            0.0137784   |               0.4866   |        0.998233    |                 0.0475489   |              0.00176658  |
| ag_news             | bert                | lime                    |                   |       0.0878817   |      0.84      |    0           |    0.260355    |   0.431697  |    0.861835   | 0          |  0.957438    |            1        |             0.634018    |                0           |            0.595383    |               0.599175 |        0.820708    |                 0.590126    |              0.179292    |
| ag_news             | bert                | text_occlusion          |                   |       0.0215066   |      0         |    0.13527     |    0.174027    |   0.191429  |    0.0671837  | 0          |  0.986268    |            1        |             0.16        |                0           |            0.155058    |               0.636    |        0.0259535   |                 0.150629    |              0.134047    |
| ag_news             | bert                | attention_visualization |                   |       0.0653065   |      0         |    0.463516    |    0.370046    |   0.134119  |    0.735026   | 0.705025   |  0.0517027   |            1        |             0.045842    |                0           |            0.00983961  |               0.58906  |        0.998716    |                 0.0483495   |              0.00128373  |
| ag_news             | lstm                | lime                    |                   |       0.0923779   |      0.82      |    0           |    0.260327    |   0.432108  |    0.861813   | 0.74       |  0.591969    |            1        |             0.621946    |                0           |            0.592827    |               0.584381 |        0.823585    |                 0.591969    |              0.176415    |
| ag_news             | lstm                | text_occlusion          |                   |       0.0189082   |      0         |    0.136868    |    0.177964    |   0.196338  |    0.0777348  | 0.00367647 |  0.980844    |            1        |             0.18        |                0           |            0.168826    |               0.628    |        0.0490573   |                 0.164386    |              0.130943    |
| ag_news             | lstm                | attention_visualization |                   |       0.0758251   |      0         |    0.462081    |    0.370048    |   0.133821  |    0.735138   | 0.706121   |  0.0530761   |            1        |             0.0477444   |                0           |            0.0111296   |               0.574815 |        0.998542    |                 0.0503824   |              0.0014578   |
| ag_news             | roberta             | lime                    |                   |      15.3733      |      0.88      |    0           |    0.265483    |   0.43016   |    0.866849   | 0.74       |  0.529605    |            1        |             0.499464    |                0           |            0.495152    |               0.622497 |        0.858834    |                 0.529605    |              0.141166    |
| ag_news             | roberta             | text_occlusion          |                   |       4.12863     |      0         |    0.122375    |    0.170175    |   0.198786  |    0.126269   | 0.00893815 |  0.990652    |            1        |             0.04        |                0           |            0.04        |               0.628    |       -1.12312e-12 |                 0.0388571   |              0.04        |
| ag_news             | roberta             | attention_visualization |                   |      13.84        |      0         |    0.46578     |    0.371573    |   0.134324  |    0.734726   | 0.703832   |  0.0471213   |            1        |             0.0417101   |                0           |            0.00767208  |               0.616612 |        0.998987    |                 0.0452342   |              0.00101325  |
| ag_news             | naive_bayes_text    | lime                    |                   |       0.10875     |      0.86      |    0           |    0.263324    |   0.435581  |    0.863462   | 0          |  0.954866    |            1        |             0.568012    |                0           |            0.553808    |               0.610473 |        0.836931    |                 0.571695    |              0.163069    |
| ag_news             | naive_bayes_text    | text_occlusion          |                   |       0.0184531   |      0         |    0.127335    |    0.171902    |   0.211644  |    0.0967134  | 0          |  0.988517    |            1        |             0.06        |                0           |            0.0580952   |               0.62     |        0.00855811  |                 0.0563454   |              0.0514419   |
| ag_news             | naive_bayes_text    | attention_visualization |                   |       0.0738044   |      0         |    0.464077    |    0.370879    |   0.133919  |    0.7351     | 0.704117   |  0.0504249   |            1        |             0.0424511   |                0           |            0.00788178  |               0.602676 |        0.998956    |                 0.045932    |              0.00104407  |
| ag_news             | svm_text            | lime                    |                   |       0.152668    |      0.86      |    0           |    0.26231     |   0.435618  |    0.861878   | 0          |  0.956179    |            1        |             0.587311    |                0           |            0.566922    |               0.61114  |        0.833064    |                 0.576266    |              0.166936    |
| ag_news             | svm_text            | text_occlusion          |                   |       0.0360582   |      0         |    0.132796    |    0.174095    |   0.213377  |    0.066695   | 0          |  0.986388    |            1        |             0.16        |                0           |            0.157157    |               0.65     |        0.017724    |                 0.152419    |              0.142276    |
| ag_news             | svm_text            | attention_visualization |                   |       0.12501     |      0         |    0.463339    |    0.37033     |   0.134058  |    0.735278   | 0.704351   |  0.051975    |            1        |             0.0486273   |                0           |            0.0120857   |               0.603101 |        0.998461    |                 0.0493953   |              0.00153948  |
| ag_news             | xgboost_text        | lime                    |                   |       0.208056    |      0.776372  |    0           |    0.249149    |   0.413333  |    0.859328   | 0          |  0.96403     |            1        |             0.713343    |                0           |            0.673166    |               0.522949 |        0.74945     |                 0.637195    |              0.25055     |
| ag_news             | xgboost_text        | text_occlusion          |                   |       0.0410993   |      0         |    0.148671    |    0.17559     |   0.199566  |    0.0599269  | 0.0101864  |  0.976652    |            1        |             0.395411    |                0           |            0.382571    |               0.61     |        0.0632515   |                 0.371141    |              0.336749    |
| ag_news             | xgboost_text        | attention_visualization |                   |       0.149399    |      0         |    0.461171    |    0.369125    |   0.133531  |    0.735366   | 0.703611   |  0.0562513   |            1        |             0.0567804   |                0           |            0.0157636   |               0.491685 |        0.99799     |                 0.0555373   |              0.0020096   |

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

