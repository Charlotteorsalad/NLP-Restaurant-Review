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
<img width="678" alt="labeldistributions" src="https://github.com/Charlotteorsalad/NLP-Restaurant-Review/assets/86924148/bfc56700-f35b-419b-b5cd-93d7f826d1dc">

### Model Metrics Visualization
<img width="604" alt="metrics" src="https://github.com/Charlotteorsalad/NLP-Restaurant-Review/assets/86924148/26711029-ba40-4e48-abf3-c3a5da5b87ce">

### Heat Map
<img width="550" alt="heatmap" src="https://github.com/Charlotteorsalad/NLP-Restaurant-Review/assets/86924148/ac73897f-4fac-4fdf-9746-6999c968e4b6">

### Confusion Matrix
<img width="484" alt="confusionmatrix" src="https://github.com/Charlotteorsalad/NLP-Restaurant-Review/assets/86924148/5be4fe04-9683-4d5c-8c6d-6ee0c9384d1c">

### Top 10 Restaurant based on POSITIVE predictions
<img width="365" alt="top10" src="https://github.com/Charlotteorsalad/NLP-Restaurant-Review/assets/86924148/3b3a119b-9819-4082-aa3d-fe972094ad4a">


## License

This project is licensed under the MIT License.
