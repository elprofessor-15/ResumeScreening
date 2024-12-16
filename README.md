# ResumeScreening
This repository automates resume classification using machine learning. It preprocesses resume data, cleans text, and extracts features using TF-IDF vectorization. A K-Nearest Neighbors (KNN) classifier with OneVsRest strategy is used to categorize resumes, providing an efficient solution for resume screening.
# Resume Screening using Machine Learning

This repository contains an end-to-end machine learning pipeline to classify resumes into various categories. It uses Natural Language Processing (NLP) techniques to preprocess and clean text data and machine learning algorithms for classification.

## Project Overview
The goal of this project is to automatically classify resumes into different predefined categories, such as 'Software Engineer', 'Data Scientist', etc. This can significantly reduce the manual effort in the hiring process by automating resume screening.

## Dataset
The dataset contains resumes labeled with their respective job categories. The resumes are preprocessed to remove irrelevant information like URLs, mentions, and hashtags.

## Techniques Used
- **Text Preprocessing**: Cleaning resumes by removing stopwords, special characters, and irrelevant sections.
- **TF-IDF Vectorization**: Converting resumes into feature vectors.
- **K-Nearest Neighbors (KNN)**: Classifier used for multi-class classification.
- **OneVsRestClassifier**: Applied to handle multiple categories in the classification task.

## Steps:
1. Load the dataset.
2. Clean and preprocess the text.
3. Extract features using TF-IDF Vectorization.
4. Train a classifier (KNN with OneVsRest).
5. Evaluate the model using accuracy and classification report.

