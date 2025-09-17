ve# Xbox Prediction Project

## Overview
The Xbox Prediction project is a machine learning application designed to predict product SKUs based on user queries. This project utilizes natural language processing techniques to preprocess text data and employs machine learning models, specifically RandomForestClassifier and LogisticRegression, to classify the queries.

## Files
- **Xbox_Prediction.ipynb**: A Jupyter notebook containing the code for loading datasets, preprocessing data, training machine learning models, and evaluating their performance.
- **requirements.txt**: A file listing the necessary Python packages to run the notebook.
- **README.md**: This documentation file providing an overview and instructions for the project.

## Setup Instructions
1. **Clone the Repository**
   Clone this repository to your local machine using:
   ```
   git clone https://github.com/MrGupa/Xbox_Prediction.git
   ```

2. **Create a Virtual Environment**
   It is recommended to create a virtual environment to manage dependencies:
   ```
   python -m venv venv
   ```

3. **Activate the Virtual Environment**
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```

4. **Install Required Packages**
   Install the necessary packages using pip:
   ```
   pip install -r requirements.txt
   ```

## Running the Notebook
After setting up the environment and installing the required packages, you can run the Jupyter notebook:
```
jupyter notebook Xbox_Prediction.ipynb
```

## Datasets
The project uses two datasets:
- `train.csv`: The training dataset containing user queries and their corresponding SKUs.
- `test.csv`: The test dataset for evaluating the model's performance.

You can get this dataset from [Kaggle - ACM SF Chapter Hackathon Small](https://www.kaggle.com/competitions/acm-sf-chapter-hackathon-small/overview).

## Models Implemented
- **RandomForestClassifier**: A robust ensemble learning method used for classification tasks.
- **LogisticRegression**: A statistical model that uses a logistic function to model a binary dependent variable.

## Evaluation
The models are evaluated using metrics such as accuracy, precision, recall, and F1-score, which are reported in the classification reports generated during the notebook execution.
