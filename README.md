# Weather Type Recognition Model

A convolutional neural network designed and trained with the Keras API to predict the weather type into the classes 'rain', 'lightning', or 'snow' in a provided image.

## Motivation

This is my first independent Machine Learning project and its goal was to familiarise myself with the Keras API and apply what I have learnt at university and in my independent study to a real-world project. I used Jupyter Notebook running on my local machine to explain, justify, and test my code as it was written.

The biggest challenge was designing the structure of the model so that it wouldn't overfit the training data. I was inspired by the structure of other successful CNN models such as the VGG16 model and settled on three sets of Convolutional and Max Pooling layers followed by a Flatten layer and, finally, a Dense layer with 3 output neurons for the final classification.

## How to use

To run this model locally, start an instance of Jupyter Notebook and open the file 'weather_type_recognition_model.ipynb'. Ensure you have the required Python modules installed (tensorflow, numpy, sklearn, matplotlib).

The data used in this model was downloaded from https://www.kaggle.com/datasets/jehanbhathena/weather-dataset and not all weather types were used. Instructions for which to delete and where to store the data are included in the notebook.