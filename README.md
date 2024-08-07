# Twitter Data - Sentiment-Analysis
  This repository contains a sentiment analysis project leveraging machine learning techniques to classify text data into different sentiment categories. The dataset used in this project consists of 1.6 million data points and is fetched using the Kaggle API. We are implementing a Logistic Regression model to perform sentiment classification and evaluate their performance.

  In this project, we are preprocessing the data, training and evaluating the model, and saving the trained model for future uses.

## Requirements
1. Python 3.x
2. Kaggle
3. Numpy
4. Pandas
5. Scikit-learn
6. nltk
7. Pickle

## Setup
#### 1. Install Dependencies
Install all the libraries and packages provided in the requirements section above.

#### 2. Kaggle API setup
Here we are using a dataset called " Sentiment140 dataset " which contains about 1.6 million tweet data. We are using Kaggle API to fetch the dataset directly into the workspace.
 1. Go to your Kaggle account settings.
 2. Scroll down to the API section and click "Create New API Token". This will download a file named " kaggle.json ".
 3. Place kaggle.json in the ~/.kaggle/ directory (create this directory if it doesn’t exist).
    ```
    mkdir -p ~/.kaggle
    mv kaggle.json ~/.kaggle/
    ```


#### 3. Clone the Repository
```
https://github.com/DawnJo123/Sentiment-Analysis-using-Twitter-Data.git
```
```
cd Sentiment-Analysis-using-Twitter-Data
```
#### 4. Fetch Data
The dataset can be fetched using the Kaggle API. Run the following command to download the dataset:
```
!kaggle datasets download -d kazanova/sentiment140
```
This command will download the dataset into your workspace in zip form. We are using zipfile library to unzip the data.
Or you can download the dataset directly from [here](https://www.kaggle.com/datasets/kazanova/sentiment140)
#### 5. Run the Project
#### 6. Save the model 
You can save the model using Pickle library in .pkl format. You can reuse this .pkl file to predict sentiments based on your input.
