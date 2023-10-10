### K means clustering project 

This Python project focuses on the application of K means clustering algorithm from Scikit-learn. The dataset contains information about universities with several features as well as the label wether the university is private or public. K means clustering is an unsupervised learning algorith, meaning that in real life scenarios, we don't have the labels to evaluate whether the clustering was correct or not. However, here as a simulation of K means clustering, I attend to classify the universities into two clusters (private or public) and I use evaluation metrics to measure the performance (by taking advantage of the existing labels). 

## Libraries
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

## Getting Started
Follow these steps:

1. Clone the Repository: Clone this GitHub repository to your local machine.

2. Install Dependencies: Ensure you have the required Python libraries installed. You can install them using the following command:
``````
pip install pandas numpy matplotlib seaborn scikit-learn
``````
For Jupyter notebooks :
``````
!pip install pandas numpy matplotlib seaborn scikit-learn
``````
3. Data File: A .csv file is stored in the /data folder. 

4. Run the Code.

## Exploratory Data Analysis (EDA)
Visualize the distribution of the features of the dataset and explore relationships between features and the target (private or not). 

## K means clustering 
Application of K means clustering algorithm with two clusters

## Evaluation metrics
Since we have the labels, we can use confusion matrix and classification report to evaluate wether the clustering correctly predicted Private or Public university.

## Acknowledgments
This project was developed as part of the "Python for Data Science and Machine Learning Bootcamp" course from Udemy, instructed by Jose Portilla and Pierian Data.
