# Classification of offensive tweets

This project classifies offensive tweets into three categories using natural language processing (NLP) and deep learning. The dataset is sourced from Kaggle and labeled based on offensiveness level. 

## Technologies Used:
- **Python**
- **TensorFlow** & **Keras** (for building the LSTM model)
- **Scikit-learn** (for model evaluation and optimization)
- **Imbalanced-learn** (for handling class imbalance with SMOTEENN)

## Approach:
- **Data Preprocessing**: The dataset is preprocessed, including text tokenization and balancing using SMOTEENN.
- **Model**: LSTM-based neural network for classification.
- **Evaluation**: Cross-validation, confusion matrix, and MAE metrics to assess model performance.

## Getting Started:
1. Clone the repository.
2. Install dependencies in your enviroment
3. Run model_implementation.ipynb to train the model and evaluate performance.

## Results:
- The model is trained and tested on the Kaggle dataset and evaluated for accuracy in predicting offensive tweets.
