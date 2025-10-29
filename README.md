Overview

This project investigates how adjusting false positive and false negative rates affects the performance and fairness of machine learning credit scoring models. Using the Uwezo Fund dataset from South Rift Kenya and comparing it with the German Credit dataset, the study evaluates how balancing these error types can lead to more reliable credit decisions.

Objectives

Examine model performance before and after class balancing (SMOTE, NearMiss)

Analyze the effects of threshold tuning on false positive and false negative trade-offs

Compare traditional and optimized models on fairness and accuracy metrics

Key Experiments

Baseline models: Evaluate Logistic Regression, MLP, SVM, and Random Forest using default thresholds.

Data balancing: Apply SMOTE and NearMiss to handle class imbalance.

Threshold tuning: Optimize cut-off points to minimize both false positives and false negatives.

Trade-off visualization: Plot FPR-FNR curves and highlight optimal balance points.

Expected Outcome

Identify models that maintain fairness while minimizing misclassification costs.

Demonstrate that threshold tuning improves decision reliability.

Provide reproducible evaluation framework for future credit scoring research.

Datasets

Uwezo Fund Dataset: Custom dataset based on Kenyan demographics.

German Credit Dataset: Benchmark dataset for comparison.

Author

Chepkemoi Zipporah
MSc Researcher — Machine Learning in Credit Scoring & Fairness
