# Dog-Breed-Identification
This project builds an end-to-end multi-class image classifier using TensorFlow 2.5.0 and TensorFlow Hub.

## 1. Problem
Identifing the breed of dog using a given image of the dog. When I'm sitting in a cafe and I take a photo of a dog, I want to know what breed of dog it is.

## 2. Data
The data that we are using is from Kaggle's Dog Breed Identification competition. https://www.kaggle.com/c/dog-breed-identification/data

## 3. Evaluation
Submissions are evaluated on Multi Class Log Loss between the predicted probability and the observed target. https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

For each image in the test set, you must predict a probability for each of the different breeds. The file should contain a header and have the following format:

id,affenpinscher,afghan_hound,..,yorkshire_terrier 000621fb3cbb32d8935728e48679680e,0.0083,0.0,...,0.0083 etc.

## 4. Features
Some information about the data:

We're dealing with images (unstructured data), so it's probably best we use Deep Learning / Transfer Learning.
There are 120 breeds of dogs (This means there are 120 different classes.
There are around 10,000+ images in the training set (These images have labels).
There around 10,000+ images in the test set (these images will have no labels, because we want to predict them).
