# Sentiment Analysis Review

![image](https://github.com/LadyStellah/SentimentAnalysisReview/assets/158798838/6776ec9e-77ec-4828-9370-1afca86227f3)


## Table of Content
- [Project Overview](#project-overview)
- [Project Objective](#project-objective)
- [Data Source](#data-source)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning](#machine-learning)
- [Evaluation Metrics](#evaluation-metrics)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)


## Project Overview
This analysis uses natural language processing (NLP) techniques and machine learning algorithms to classify text as positive, negative or neutral. The goal is to gain insights into public opinion, customer satisfaction, or market trends by analyzing the emotions and attitudes conveyed in the text. This review can help businesses improve their products, services and customer engagement strategies by understanding the sentiments and feedback from their audience.

## Project Objective
The objective of this project is to develop a comprehensive sentiment analysis model to evaluate customer reviews. This process will be carried out by leveraging natural language processing (NLP) techniques and machine learning algorithms, the project seeks to enhance the understanding of customer feedback, ultimately aiding in strategic decision making and improving overall customer experience.

## Data Source
The data source for this sentiment analysis was obtained from Ali Express, a leading e-commerce platform. Ali Express vast repository of customer reviews provides a rich and diverse dataset, offering insights across a wide range of product and services. These reviews include star ratings and textual feedback, serve as an excellent basis for training and evaluating the sentiment analysis model.

## Data Preprocessing
This is a crucial step to ensure that the model can accurately interpret and classify sentiments. These process involve several key steps like; Data Cleaning (this involves removing irrelevant information such as special characters, misspelled words and missing values); Tokenization (this involves breaking down the text into individual words); Stop words removal (these are removal of commonly used words like "and", "the", "is") these words do not carry significant meaning; Stemming and Lemmatization (these are techniques used to reduce words to their base or root form (e.g. "running" to "run); Feature Extraction (these involves converting text into numerical features that can be used by machine learning algorithms), techniques like TF-IDF or Word Vectorizer.

## Machine Learning
The sentiment analysis review is built using both Supervised and Unsupervised machine learning approach. The training and test data was split 60:40. These are the classification algorithm experimented with;

- Naive Bayes
- Logistic Regression
- Random Forest Classifier
- Vader Sentiment

## Evaluation Metrics
To access the performance of the machine learning model, the following evaluation metrics were used:

- **Accuracy:** The proportion of correctly classified instances (positive, negative or neutral) out of the total instances.
- **Precision:** The ratio of true positive predictions to the total positive predictions made by the model.
- **Recall:** The ratio of true positive predictions to the actual positive in the dataset.
- **F1 Score:** The harmonic mean of precision and recall.

These metrics help in understanding different aspects of the model's performance, ensuring a comprehensive evaluation.

## Key Insights

- The purpose of this project is to understand the proportion of positive, negative and neutral sentiments among the reviews, providing a general sense of customer satisfaction.
- To pick out frequently mentioned words or topics in the reviews using word cloud, indicating what aspects of the product are most important to customers and also understand customers emotions through these words.
- To point out specific features or attributes that customers consistently praise or criticize by highlighting areas of strength and potential improvement.
- To understand the trends over time which can reveal how customer perceptions are evolving and the impact of recent changes or events.
- To get insights on the sentiment towards the products and compares with competitors, identifying competitive advantages or disadvantages.

These insights will help the business to understand customer opinions more deeply, guiding strategic decisions to improve the products and overall customer service.

## Conclusion
The sentiment analysis review reveals crucial insights into customer perceptions and satisfaction. By analyzing a comprehensive dataset of Amazon reviews, we identified the overall sentiment distribution, highlighting a predominance of positive feedback. Common theme and topics were extracted, showcasing key strength such as product quality and customer service, while also pinpointing areas needing improvement like delivery times and packaging. Trends over time indicate a gradual enhancement in customer sentiment, reflecting positively on recent changes and initiatives. Additionally, demographic analysis offers tailored insights for different customer segments. These findings provide actionable intelligence for refining products, enhancing customer experiences, and maintaining a competitive edge in the market.










