# Credit Card Fraud Detection

This project aims to build a model for detecting credit card fraud using machine learning. It utilizes a dataset of credit card transactions and explores various algorithms to identify fraudulent activities.

## Dataset

The project uses the "Credit Card Fraud Detection" dataset available on Kaggle: [https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

The dataset contains anonymized credit card transactions labeled as either fraudulent or genuine.

## Methodology

1. **Data Loading and Preprocessing:** The dataset is loaded using Pandas, and features like 'Amount' and 'Time' are preprocessed using RobustScaler to handle outliers and normalize the data.
2. **Data Splitting:** The data is split into training, validation, and testing sets to evaluate the model's performance.
3. **Model Training:** Various machine learning models are trained, including:
    - Logistic Regression
    - Shallow Neural Network
    - Random Forest
    - Gradient Boosting
    - Linear Support Vector Classifier (SVC)
4. **Model Evaluation:** The models are evaluated using metrics like precision, recall, F1-score, and accuracy on the validation and testing sets.
5. **Balancing the Dataset:** Due to the imbalanced nature of the dataset (more genuine transactions than fraudulent ones), techniques like oversampling and undersampling are explored to improve model performance on fraud detection.

## Results

The performance of different models is compared based on the evaluation metrics. The project focuses on achieving a high recall and F1-score for the "Fraud" class to ensure that fraudulent transactions are effectively identified.

## Usage

1. Download the dataset from the Kaggle link provided above.
2. Install the required libraries: `pandas`, `scikit-learn`, `tensorflow`, etc.
3. Run the Python script to train and evaluate the models.
4. The results and classification reports will be printed to the console.

## Conclusion

This project demonstrates the application of machine learning techniques for credit card fraud detection. The results highlight the importance of choosing appropriate models and handling imbalanced datasets to achieve satisfactory performance.

## Future Work

- Explore more advanced techniques for handling imbalanced datasets, such as SMOTE.
- Experiment with hyperparameter tuning to optimize model performance.
- Deploy the model for real-time fraud detection.
