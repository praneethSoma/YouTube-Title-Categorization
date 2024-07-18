# YouTube Title Categorization

## Project Overview
This project implements a Natural Language Processing (NLP) pipeline to automatically categorize YouTube video titles. It uses machine learning techniques to classify titles into predefined categories, demonstrating text preprocessing, vectorization, and multi-class classification.

## Features
- Text preprocessing of YouTube video titles
- Vectorization of processed text data
- Multi-class classification using Logistic Regression
- Evaluation of model performance

## Technologies Used
- Python
- NLTK (Natural Language Toolkit)
- scikit-learn
- pandas (for data handling)
- NumPy

## Usage
  1. Prepare your dataset of YouTube video titles and their corresponding categories.
  2. Run the main script:
  3. The script will preprocess the titles, train the model, and output the classification accuracy.

## Project Structure
  - `categorize_titles.py`: Main script containing the NLP pipeline and classification model
  - `data/`: Directory containing the dataset (if applicable)
  - `requirements.txt`: List of required Python packages

## Methodology

1. Data Preprocessing:
   - Splitting video titles
   - Removing stopwords and non-alphabetic characters
   - Converting text to lowercase
   - Applying stemming using Porter Stemmer

2. Feature Extraction:
   - Utilizing CountVectorizer to convert preprocessed text into numerical vectors
   - Setting maximum features to 1600 for dimensionality control

3. Model Training and Evaluation:
   - Implementing Logistic Regression with One-vs-Rest strategy for multi-class classification
   - Splitting data into 80% training and 20% testing sets
   - Training the model on the prepared dataset
   - Evaluating model performance using accuracy score

## Results
  The model achieves an accuracy of 82.6% in classifying YouTube video titles into their respective categories.

## Future Improvements
  - Experiment with different classification algorithms
  - Implement more advanced NLP techniques like word embeddings
  - Expand the dataset for better generalization

