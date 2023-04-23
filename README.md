# RUHA Voice Assistant

## Project Description
This project aims to train 5 different classifiers on the RUHA dataset using the scikit-learn library. The dataset is an audio dataset, and I will explore different machine learning algorithms and techniques to train the classifiers. After training the classifiers, I will evaluate their performance by displaying the confusion matrix, accuracy, recall, precision, and F1-measure.
The most important part of the project is to create a web application using Flask, a Python web framework. I will deploy our project on the web application, where users can interact with it by providing input and getting the output. For example, a user can input "Ruha lights band kardo" on the website, and the 5 trained classifiers will predict the result, which will be creatively displayed on the webpage.
After displaying the result, I will provide a result analytics button that will redirect the user to another webpage, where the complete result will be displayed, including how the 5 classifiers performed on the dataset.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
You will need to have Python 3.x installed on your machine. You can download the latest version of [Python](https://www.python.org/downloads/) here.
</br>
You will also need to have Anaconda on your machine. You can download the latest version of [Anaconda](https://www.anaconda.com/) here.

### Installing
Clone this repository onto your local machine.
```
git clone https://github.com/MuhammadAhmedSuhail/RUHA-Voice-Assistant.git
```
Install the required packages.
```
pip install -r requirements.txt
```
Run the web app.
```
python app.py
```
### Dataset
The RUHA dataset contains audio samples in Urdu language.

## Training the Classifiers
I used the scikit-learn library to train 5 different classifiers on the RUHA dataset such as Decision Tree, Random Forest, SVM, Naive Bayes, etc. After training the classifiers, I evaluated their performance using the confusion matrix, accuracy, recall, precision, and F1-measure.

## Web Application
I will created a web application using Flask, a Python web framework. The web application will allow users to record a statement in Urdu language, and the 5 trained classifiers will predict the result.

## Conclusion
In this project, I explored different machine learning algorithms to train 5 different classifiers on the RUHA dataset. I also created a web application using Flask, which allows users to interact with the classifiers by providing input and getting the output.

## Author:
- Muhammad Ahmed Suhail

## Acknowledgments:
- This project was completed as a project for **Introduction to Data Science** at FAST - NUCES Islamabad.







