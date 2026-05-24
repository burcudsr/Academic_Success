# 🎓 Academic Success Prediction

This project focuses on predicting student academic success (dropout, academic failure, or success) using machine learning. The model is based on comprehensive student data, developed during the **Kaggle Playground Series - Season 4, Episode 6**.

### 🚀 Live Demo & Interactive App
Explore the interactive prediction model and test it in real-time:
https://academicsuccessmodel-4jgbqvdibfuz399xmvfq7n.streamlit.app/

### 📊 Dataset & Preprocessing
The dataset provides deep insights into student demographics, socioeconomic factors, and academic performance. Key preprocessing steps include:
* **Feature Selection**: To prevent data leakage and ensure model relevance, the `id` column was excluded from training, as it holds no predictive power.
* **Missing Value Imputation**: All missing values were systematically identified and addressed to maintain high data quality.
* **Feature Engineering**: Relevant academic and socioeconomic indicators were selected to enhance the model's ability to identify patterns leading to different student outcomes.
* **Categorical Encoding**: Categorical variables were converted into numerical formats to ensure compatibility with classification algorithms.

### 🤖 Model Performance
Various classification models were evaluated to determine the most effective approach for predicting academic outcomes. The final model demonstrates strong predictive consistency:

| Accuracy | Precision | Recall | F1-Score |
| :--- | :--- | :--- | :--- |
| 0.825 | 0.830 | 0.822 | 0.824 |
