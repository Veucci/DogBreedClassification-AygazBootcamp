# DogBreedClassification-AygazBootcamp
Aygaz Derin Öğrenme Bootcamp Project. 

# Dog Breed Classification with TensorFlow
This Python script demonstrates a simple dog breed classification using TensorFlow and Convolutional Neural Networks (CNNs). The dataset used for training is based on a CSV file (labels.csv) containing information about dog breeds and corresponding image file paths.

## Data Loading and Preprocessing:
Reads the CSV file (labels.csv) containing information about dog breeds and image file paths.
Encodes the breed labels using LabelEncoder.
Prepares training and validation datasets.

## Image Loading and Normalization:
Reads and resizes images from the specified file paths.
Normalizes pixel values to the range [0, 1].

## Model Definition:
Defines a CNN model using TensorFlow's Keras API.
Compiles the model with the Adam optimizer and sparse categorical crossentropy loss.

## Model Training:
Trains the model using the training dataset.
Validates the model using the validation dataset.

## Training History Visualization:
Plots training and validation accuracy.
Plots training and validation loss.

## Model Evaluation:
Evaluates the model on both training and validation datasets.
Prints the results.
