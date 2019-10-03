# digit-recognition-keras
Handwritten digit recognition using Keras CNN with MNIST data

# Dataset
You can download the train and main test dataset from the kaggle website here - https://www.kaggle.com/c/digit-recognizer/data

Make sure to update the path for train and test file accordinly. You can download the dataset from kaggle and store in similar path like below-

PATH_TRAIN = "../Image_Classification/digit-recognizer/dataset/train.csv"

PATH_TEST = "../Image_Classification/digit-recognizer/dataset/test.csv"

# Model
Keras Conv2D

# Accuracy
Test Data Accuracy = 0.9952 (Top 20% in Kaggle)

# TODO:
Write argparse functions to let the user input data_input_path, model_params (like epochs, batch_size) and model_save_path
