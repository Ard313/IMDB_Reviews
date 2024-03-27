# IMDB_Reviews  :Binary Sentiment Classification for IMDB Movie Review dataset 
![8b955864-7307-4d41-8ded-c194170f5305-2729152590](https://github.com/Ard313/IMDB_Reviews/assets/122507060/70149068-4804-4a39-a489-118031c592ab)
## Introduction
The IMDB dataset comprises 50,000 movie reviews suitable for natural language processing or text analytics tasks. It's designed for binary sentiment classification, providing 25,000 reviews for training and 25,000 for testing. The goal is to predict the sentiment (positive or negative) of each review using classification or deep learning algorithms.

## Dataset Description
### Columns: 
- Review: Textual content of the movie review.
- Sentiment: Label indicating the sentiment of the review, either positive or negative.

### **Problem Statement**
Given the dataset, the task is to predict the number of positive and negative reviews using classification or deep learning algorithms. The analysis involves preprocessing the textual data, encoding sentiment labels, and applying machine learning techniques for classification.
## **Quick Overview**
### **Preprocessing**

-Checked for null values and class imbalance.
*Utilized the Neattxt library for text preprocessing, including operations like lowercasing, removing punctuation, stopwords, and special characters.

### **Exploratory Data Analysis**

-Utilized Seaborn to create count plots to visualize the distribution of positive and negative sentiment labels.

### **Feature Engineering**

-Generated word clouds to visualize the most common words in positive and negative reviews.
![pos](https://github.com/Ard313/IMDB_Reviews/assets/122507060/4b58db29-46e9-432c-ab78-fe791f4a714d)
![Neg](https://github.com/Ard313/IMDB_Reviews/assets/122507060/6dd281d1-dfea-41c4-9b38-86500e77036d)

-Encoded sentiment labels using LabelEncoder.

### **Model Training**
-Converted text data into TF-IDF vectors.
-Split the data into training and testing sets (80-20 split).
-Applied Logistic Regression achieving 89% accuracy.

### **Model Evaluation**
-Generated a heatmap of the confusion matrix to assess model performance.
![Con](https://github.com/Ard313/IMDB_Reviews/assets/122507060/89e6ccff-586d-4d7d-9fa3-9697416b6761)
<img width="890" alt="all" src="https://github.com/Ard313/IMDB_Reviews/assets/122507060/2094ef7c-86ed-4dd1-9234-b145c3204d0c">

### **Dependencies**:
-pandas
-matplotlib
-seaborn
-neattxt
-numpy
