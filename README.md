🫀 Comprehensive Machine Learning Full Pipeline on Heart Disease UCI Dataset

Python scikit-learn pandas numpy matplotlib seaborn

This project builds a heart disease prediction system using the UCI Heart Disease dataset. It includes data preprocessing, exploratory analysis, PCA for dimensionality reduction, supervised learning (Logistic Regression, KNN, SVM, Decision Trees, Random Forest, Gradient Boosting) with hyperparameter tuning, and clustering (K-Means & Hierarchical). The best-performing model (SVM) is selected via GridSearchCV and deployed as a FastAPI service, allowing real-time predictions.

Project Workflow

⿡ Data Preprocessing

• Handled missing values and categorical encodings

• Standardized features (important for ML models and PCA)

• Performed dimensionality reduction with PCA to retain variance while reducing noise

⿢ Exploratory Data Analysis (EDA)

• Visualized feature distributions and correlations

• Analyzed important medical features such as chest pain type, blood pressure, cholesterol, and ST segment slope

• Compared class distributions (healthy vs. heart disease)

⿣ Supervised Learning (Classification Models)

• Trained and compared multiple models:

  • Logistic Regression
  
  • K-Nearest Neighbors (KNN)
  
  • Support Vector Machine (SVM)
  
  • Decision Tree
  
  • Random Forest
  
  • Gradient Boosting
Each model was evaluated on training vs testing accuracy to check for overfitting or underfitting.

⿤ Hyperparameter Tuning

• Applied GridSearchCV with cross-validation for each model

• Identified the best parameters and highest accuracy model

• Compared tuned model performances

⿥ Clustering (Unsupervised Learning)

• Applied K-Means Clustering (with elbow method)

• Applied Hierarchical Clustering (with dendrogram analysis)

• Compared clustering results against true disease labels using Adjusted Rand Index and Silhouette Score
