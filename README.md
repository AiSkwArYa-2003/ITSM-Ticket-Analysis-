# ITSM-Ticket-Analysis-
This project applied machine learning to ITSM data to automate ticket prioritization, forecast incident volume, auto-tag departments, and predict RFC needs—delivering actionable insights and highlighting areas for process improvement.
# ITSM Machine Learning Project

## Project Overview
This project leverages machine learning to improve IT Service Management (ITSM) by automating ticket classification, prioritization, and resolution prediction. The goal is to enhance service efficiency and reduce manual workload.

## Objectives
- Automatically classify IT service tickets into categories.
- Predict ticket priority levels.
- Estimate resolution times to optimize resource allocation.

## Dataset
The dataset contains historical ITSM tickets with fields like:
- Ticket ID
- Description
- Category
- Priority
- Created and Resolved timestamps
- Resolution status

Data preprocessing includes cleaning, missing value handling, and feature engineering.

## Approach
- Data preprocessing & feature engineering
- Text processing with NLP techniques on ticket descriptions
- Training various ML models (Random Forest, Logistic Regression, SVM)
- Model evaluation using accuracy, precision, recall, and F1 score
- Cross-validation for robustness

## Technologies Used
- Python 3.x
- Pandas, NumPy
- Scikit-learn
- NLTK / SpaCy (for NLP)
- Matplotlib, Seaborn (visualization)
- Jupyter Notebook

## Results
- Model achieved an accuracy of **XX%** on test data
- Successfully classifies tickets and predicts priority with good precision and recall
- Enables better decision-making for IT support teams

## Getting Started

### Prerequisites
- Python 3.7+
- pip

### Installation
1. Clone this repo:
