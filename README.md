# SentimentAnalysisFromComments

This project involves a machine learning model for performing sentiment analysis on product reviews. The reviews are labeled as positive or negative, and the model is trained to predict the sentiment of new input sentences.

## About the Project

The project is developed to train a deep learning model using the data available in the **comments.csv** file. The comments are labeled as "1" (positive) and "0" (negative). The trained model predicts whether a new sentence is positive or negative when provided as input.

## Technologies and Libraries Used

The project uses the following Python libraries:

- **numpy**: Used for numerical computations and data manipulation.
- **pandas**: A data processing and analysis library.
- **tensorflow.keras**: Used for building and training the deep learning model.

## Installation

To run the project, follow these steps:

1. **Clone the repository:**

   ```
   git clone https://github.com/efeozkesici/SentimentAnalysisFromComments.git
   cd sentiment-analysis

2. **Install the required libraries:**

Install the necessary Python libraries using the requirements.txt file:

``pip install -r requirements.txt``

## Dataset
The dataset is available in a file named ``comments.csv``. If rating is 1, comment is positive, if rating i 0, comment is negative.

## Model Training
To train the model, follow these steps:

1. **Load and preprocess the data**: Load the data from comments.csv and apply preprocessing (cleaning, tokenization, etc.).
2. **Build and train the model**: Use TensorFlow Keras to create a deep learning model and train it on the data.
3. **Save and load the model**: The trained model is saved for future use.

