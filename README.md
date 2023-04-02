# Automatic Ticket Classification using NLP and ML

For a financial company, customer complaints are crucial as they provide insights into the shortcomings of their products and services. Resolving complaints efficiently and on time can reduce customer dissatisfaction and strengthen their loyalty. Additionally, it allows companies to continuously improve their services to attract more customers.

However, evaluating and assigning each customer support ticket to the relevant department can become a tedious task, especially as the company grows and has a large customer base. This is where natural language processing (NLP) and machine learning (ML) can come to the rescue.

This project aims to automate the customer support ticket system of a financial company using NLP and ML techniques. The goal is to accurately identify and categorize support tickets based on their content and assign them to the relevant team for swift resolution.

## Problem Statement- [Automatic Ticket Classification using NLP and ML](#automatic-ticket-classification-using-nlp-and-ml)

- [Automatic Ticket Classification using NLP and ML](#automatic-ticket-classification-using-nlp-and-ml)
  - [Problem Statement- Automatic Ticket Classification using NLP and ML](#problem-statement--automatic-ticket-classification-using-nlp-and-ml)
  - [Solution](#solution)
  - [Features](#features)
  - [Model Evaluation Metrics](#model-evaluation-metrics)
  - [Technologies](#technologies)
  - [Conclusion](#conclusion)

In this case study, you will be working as an NLP engineer for a financial company that wants to automate its customer support tickets system. As a financial company, the firm has many products and services such as credit cards, banking, and mortgages/loans. Customer complaints are often an indicator of the shortcomings in their products and services, and resolving these complaints efficiently is critical for retaining customer satisfaction and loyalty. However, customer complaints are unstructured text data, and traditionally, companies need to allocate the task of evaluating and assigning each ticket to the relevant department to multiple support employees.

## Solution

To automate the customer support ticket system, we will use NLP techniques to process and analyze the text data. We will apply ML algorithms to classify support tickets based on their content and assign them to the relevant team. The ML component of this project utilizes a powerful algorithm that predicts the ticket's category based on the content of the ticket, achieving high accuracy rates.

## Features

- Automatic ticket classification using NLP and ML algorithms
- Accurate identification and categorization of support tickets
- Efficient assignment of support tickets to the relevant team for swift resolution
- Comprehensive documentation and step-by-step guide for using and integrating the system with existing support workflows
- Open-source codebase for customization and enhancement of the system to fit specific needs.

## Model Evaluation Metrics

The following table summarizes the evaluation metrics for each of the models used in this project:

| Model                   | Accuracy | Precision | Recall | F1 Score | ROC AUC Score |
|-------------------------|---------|-----------|--------|----------|--------------|
| Logistic Regression     | 0.91    | 0.91      | 0.91   | 0.91     | 0.99         |
| DecisionTreeClassifier  | 0.78    | 0.78      | 0.78   | 0.78     | 0.86         |
| RandomForestClassifier  | 0.82    | 0.83      | 0.82   | 0.81     | 0.97         |
| MultinomialNB           | 0.71    | 0.74      | 0.71   | 0.67     | 0.94         |
| XGBClassifier           | 0.91    | 0.91      | 0.91   | 0.91     | 0.99         |

These metrics provide a measure of how well each model performed on the test dataset. The metrics used to evaluate the models are:

- Accuracy: The proportion of true results (both true positives and true negatives) among the total number of cases examined.
- Precision: The proportion of true positives among the total number of cases predicted as positive.
- Recall: The proportion of true positives among the total number of actual positive cases.
- F1 Score: The harmonic mean of precision and recall.
- ROC AUC Score: The area under the Receiver Operating Characteristic (ROC) curve, which measures the performance of the model at different classification thresholds.

Based on these metrics, the Logistic Regression and XGBClassifier models performed the best, with high accuracy, precision, recall, F1 score, and ROC AUC score. The DecisionTreeClassifier and RandomForestClassifier models also performed reasonably well, with an accuracy of 0.78 and 0.82, respectively. The MultinomialNB model had the lowest performance, with an accuracy of 0.71.

## Technologies

- Python
- Natural Language Processing
- Machine Learning
- Data Science

## Conclusion

"Automatic Ticket Classification using NLP and ML" is a valuable resource for any organization seeking to streamline their support ticket classification and resolution process. The automation of the customer support ticket system using NLP and ML techniques allows companies to efficiently identify and categorize support tickets, assign them to the relevant team for swift resolution, and continuously improve their products and services.
