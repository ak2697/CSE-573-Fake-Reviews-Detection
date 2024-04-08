# CSE 573 Fake Review Detection on Yelp Dataset

## Overview
This project aims to detect fake reviews in the Yelp dataset, leveraging both traditional machine learning algorithms and advanced deep learning techniques. It addresses the critical issue of trust in online review platforms by developing a robust classification system to distinguish between genuine and fake reviews.

## Dataset
The dataset comprises 788,469 unique rows, including 780,168 true/real reviews and 8,301 fake reviews, from 35,429 unique reviewers across 250,078 unique restaurants. The Yelp dataset can be downloaded from (https://www.kaggle.com/datasets/ahmeddheyaa/prereviewscsv?resource=download).

## System Architecture
The project employs a comprehensive approach, starting from data preparation and augmentation, through to visualization, model training, and evaluation. It utilizes a range of techniques to ensure the effective handling and analysis of the dataset.

## Files Description
- `Data_augmentation.ipynb`: Code for data augmentation and feature engineering, focusing on adding reviewer-centric reviews.
- `new_visualisation.ipynb`: Visualisation and analysis of the dataset.
- `users_analysis.ipynb`: Analysis of reviewer's data.
- `ver_1.ipynb`: Implementation of RandomForest, KNN, LogisticRegression, and a basic Feed Forward Neural Network on the dataset.
- `bert.ipynb`: Training and analysis using the BERT model.
- `gpt_2.ipynb`: Training and analysis using the GPT-2 model.

## Installation
- `requirements.txt`: Install all the required packages mentioned in this file and you are good to go.

## Evaluation and Results
The project explores various models, with the BERT and GPT-2 models achieving an accuracy of 92%. Deep learning architectures showed superior performance, with particular strengths in classifying real and fake reviews.

## Contributors
- Ashish Kumar
- Gaurav Verma
- Saurav Kumar
- Freney Jigneshbhai Hirpara
- Kaustubh Tripathi
- Vishal Kanwar
