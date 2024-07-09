# NLP-Restaurant-Review

This repository contains the code and analysis for my AI-NLP assignment.

## Project Overview

The project involves the following tasks:
1. Loading and preprocessing a cleaned dataset of Google reviews.
2. Balancing the dataset using SMOTE.
3. Feature extraction using TF-IDF.
4. Training a Naive Bayes classifier with hyperparameter tuning using GridSearchCV.
5. Evaluating the model performance using classification reports, confusion matrices, and visualizations.

## Repository Structure

- `NaiveBayesRestaurantReviewAnalysis3.ipynb`: The main script that executes the data loading, preprocessing, training, and evaluation steps.
- `GoogleReview_data_cleaned.csv`: The cleaned dataset used for training and evaluation.
- `README.md`: This file contains project information and instructions.

## How to Run

1. Ensure you have Python and the required libraries installed. You can install the required libraries using:
    ```bash
    pip install -r requirements.txt
    ```

2. Run the `NaiveBayesRestaurantReviewAnalysis3.ipynb` script:
    ```bash
    python NaiveBayesRestaurantReviewAnalysis3.ipynb.py
    ```

## Results

The project includes visualizations of the data balancing process, model metrics, and confusion matrix.

### Data Balancing Visualization
![Data Balancing](images/data_balancing.png)

### Model Metrics Visualization
![Model Metrics](images/model_metrics.png)

### Confusion Matrix
<img width="484" alt="confusionmatrix" src="https://github.com/Charlotteorsalad/NLP-Restaurant-Review/assets/86924148/5be4fe04-9683-4d5c-8c6d-6ee0c9384d1c">


## License

This project is licensed under the MIT License.
