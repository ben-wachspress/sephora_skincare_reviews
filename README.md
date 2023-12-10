# Skincare Product Recommendation Analysis 

This repo contains a single Jupyter notebook `skincare_recommendation.ipynb` with the full analysis pipeline for the paper "What Do You Recommend? An Analysis of Skincare Product Reviews".

The notebook includes:

- Importing necessary libraries
- Loading and preprocessing Sephora product and review data 
- Exploratory data analysis
- Text vectorization with TF-IDF  
- Modeling with Logistic Regression, Random Forest, and Naive Bayes
- Evaluation of model accuracy, precision and recall

Key finding: TF-IDF text vectorization outperformed sentiment-based features for predicting recommendations. Logistic regression achieved 0.80 precision, recall and accuracy.

## Running the Analysis

To rerun the analysis:  

1. Ensure libraries imported in first notebook cell are installed 
2. Download the Sephora product metadata and reviews datasets from Kaggle
3. Update the data file paths in the notebook  
4. Run notebook cells end-to-end

Let me know if any other details would be helpful to include!
