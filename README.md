# 🫀 Heart Attack Risk Prediction
- This project applies machine learning algorithms to predict the risk of a heart attack based on medical, lifestyle, and demographic factors.
- The goal is to explore different models and evaluate their effectiveness in identifying patients at higher risk.
- Using classification algorithms, the model identifies risk patterns and provides insights into key factors contributing to heart disease.

# 📊 Dataset Feature
- 🔗 Dataset Source: *https://www.kaggle.com/datasets/m1relly/heart-attack-prediction/data*
- ⚠️ Note: This dataset is synthetic and not collected from real patients.
- The dataset includes 8,000+ patient records with features such as: Age, Sex, Smoking, Diabetes, Heart Problems and others.
- Target variable: Heart Attack Risk (0 = No Risk, 1 = At Risk)

# 🔬 Approach
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Model Training & Evaluation
- Splitting dataset
- Model Training
- Evaluated with Accuracy, Precision, Recall, and F1-score

# ⚙️ Models Implemented
- Support Vector Machine (SVM)
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
- *📌 Best performing model: Decision Tree with ~65% accuracy.*

# 📈 Results
- Accuracy across models: 64–65%
- Balanced tradeoff between recall and precision was challenging due to class overlap.

# 📝 Key Learnings
- Applied EDA with Plotly for interactive visualization.
- Understood the impact of imbalanced data on classification models.
- Compared multiple algorithms and evaluated using accuracy, precision, recall, and F1-score.

# 🚀 Future Improvements
- Collect more balanced medical datasets
- Experiment with ensemble models (Random Forest, XGBoost)
- Apply feature selection for higher accuracy


