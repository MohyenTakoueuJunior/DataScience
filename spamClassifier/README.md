# Spam Detection Classifier

This project is a simple email spam classifier built using Python and Jupyter Notebook. It leverages the `Multinomial Naive Bayes` algorithm to identify spam emails based on word frequency patterns. The dataset used for training and evaluation is sourced from Kaggle.

## Project Overview
The main objectives of this project are:
- To preprocess text data and transform it into a structured format using `CountVectorizer`.
- To train a Naive Bayes classifier for detecting spam messages.
- To evaluate the model’s performance using metrics such as accuracy.

The dataset contains labeled messages categorized as `spam` or `ham` (not spam).

## Project Structure
- `spamClassifier.ipynb`: The main Jupyter Notebook containing the code for data loading, preprocessing, model training, and evaluation.
- `README.md`: Project overview and instructions.
- `requirements.txt`: List of dependencies required to run the notebook.

## Requirements
To run this project, install the necessary libraries using:
```bash
pip install -r requirements.txt
```

2. **Run the Jupyter Notebook**:
   Open `spamClassifier.ipynb` in Jupyter Notebook to execute and experiment with the code.
