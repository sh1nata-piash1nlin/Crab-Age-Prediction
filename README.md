# Basic-Machine-Learning-Project
# Crab Age Prediction
#### This is only for practice purposes.
# OVERVIEW AND INSPIRATION 
+ The “Regression with a crab age dataset” project is motivated by a crucial challenge in the fields of biology and aquaculture: estimating the age of crabs based on their biological characteristics. This is significant because assessing the age of crabs can provide important information about their development cycle and reproductive capability, thereby aiding in the effective management of aquatic resources.
+ A little exception here is that this practice helps me gain a better insight into more coding algorithms of Machine Learning. 
# DATASET 
+ The dataset I collected is from Kaggle.
+ For more information: https://www.kaggle.com/competitions/playground-series-s3e16
# MODEL
I use 4 models in this problem: 
+ GradientBoosting </br>
  Gradient Boosting Regressor is a machine learning algorithm that belongs to the ensemble learning family. Specifically, it is part of the gradient boosting framework, which builds a series of weak learners (typically decision trees) sequentially, with each one attempting to correct the errors made by the previous ones. The weak learners are combined to create a strong predictive model. Here is the GradientBoosting’s  algorithm: 
+ Extreme Gradient Boosting (XGBoost) </br>
  XGBoost (Extreme Gradient Boosting) is a powerful and widely used machine learning library that belongs to the gradient boosting family. It’s specifically designed for speed and performance, making it one of the most popular algorithms in machine learning competitions and real-world applications. It can be used for both classification and regression tasks.
+  Histogram-based Gradient Boosting (HistGradientBoosting) </br>
  HistGradientBoosting algorithm is specifically designed to handle large datasets efficiently by utilizing histogram-based techniques during the training process. This technique involves discretizing the feature space into bins, the algorithms compute histograms for each feature. This approach allows for faster training times, especially when dealing with large datasets. The histogram-based approach also contributes to memory efficiency. By working with binned representations of the data rather than individual data points, the algorithm can reduce memory requirements.
+ Light Gradient Boosting Machine (LGBM) </br>
  LightGBM is a gradient-boosting framework based on decision trees to increase the efficiency of the model and reduces memory usage. It uses a technique call Gradient-based One Side Sampling Technique (GOSS). 
