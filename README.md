Task objectives - 

The primary objective of this project is to develop a machine learning model using an Artificial Neural Network (ANN) to accurately classify iris flowers into one of three species: Setosa, Versicolor, and Virginica. Given a set of four numerical features (sepal length, sepal width, petal length, and petal width), the model should learn patterns and relationships in the data to make precise predictions.

About the dataset - 

The Iris Flower Dataset is a well-known dataset in machine learning, widely used for classification tasks. It consists of 150 samples of iris flowers from three species:

Iris Setosa
Iris Versicolor
Iris Virginica
Each sample is described using four numerical features:

Sepal Length (cm)
Sepal Width (cm)
Petal Length (cm)
Petal Width (cm)
The goal of this classification task is to predict the correct species of an iris flower based on these four features. The dataset is balanced, with 50 samples per class, making it suitable for machine learning models without requiring extensive preprocessing.

Since the dataset is relatively small and well-structured, it provides a great benchmark for testing different classification models, including Artificial Neural Networks (ANNs).

Steps to run my project - 


1. import the dataset by giving the path to the iris.csv file.
2. run the preliminary analysis code for seeing the basic data information
3. I have preprocessed the data a little bit to increase accuracy so run that code before splitting the dataset
4. also I have also created a heatmap to identify the features that influence the outcome so, include only those features whose correlation with the target output is greator than 0.6.
5. Split the dataset into training and test
6. Train the model on training data and observe the training accuracy at run time. The same should be done for testing accuracy and losses
7. plotting the results and using evaluation metrics, evaluate the performance of the model.

