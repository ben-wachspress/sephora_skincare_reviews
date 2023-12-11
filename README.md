# Skincare Product Recommendation Analysis 

This repo contains the Jupyter notebook `WHAT_DO_YOU_RECOMMEND__AN_ANALYSIS_OF_SKINCARE_PRODUCT_REVIEWS.ipynb` with the analysis underpinning the paper "What Do You Recommend? An Analysis of Skincare Product Reviews". This notebook explores how to use product reviews to predict user recommendations and ratings of products. 

The notebook includes:
- Imports for various libraries and packages that are required to run the notebook
- Data reading and cleaning of Sephora product and review data
- Exploratory data analysis including the spread of data, correlations between features, and overall trends in the data
- Text vectorization with TF-IDF
- Sentiment analysis of reviews
- Modeling with Logistic Regression, K-Nearest Neighbors, Elastic Net Regression, Random Forest, and Naive Bayes
- Evaluation of model accuracy, precision and recall

**Key finding**: TF-IDF text vectorization outperformed sentiment-based features for predicting recommendations. Logistic regression was the best
performing model with 0.80 precision, recall and accuracy.

## Running the Analysis

To rerun the analysis:  
1. Ensure libraries imported in the first notebook cell are installed 
2. Download the Sephora product and reviews datasets from Kaggle (https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews/data)
3. Update the data file paths in the notebook  
4. Run notebook cells end-to-end
