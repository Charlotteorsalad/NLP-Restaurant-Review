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

### Model Metrics 
<img width="500" src="https://github.com/user-attachments/assets/ae4ea2bc-1d97-4aa3-bc0a-abf09be26524">

### Top 10 Restaurant based on POSITIVE predictions
<img width="365" alt="top10" src="https://github.com/Charlotteorsalad/NLP-Restaurant-Review/assets/86924148/3b3a119b-9819-4082-aa3d-fe972094ad4a">


## License

This project is licensed under the MIT License.
