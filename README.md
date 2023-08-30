# CaptionGenerator

The image caption generator can be used to generate captions for new images.

## Overview

An image caption generator is a machine learning model that can generate captions for images. It works by first extracting features from the image using a pre-trained model, such as InceptionV3. Then, it uses a recurrent neural network (RNN) to generate a sequence of words that describes the image.

To install all the necessary packages, you can run the following command: 

`pip install -r requirements.txt` 

This will install all the required packages in your Python environment.\
Download and extract all the files of Flickr 8k dataset into Flickr directory.

## Steps involved

1. Load the image-caption mappings. This is a set of data that contains pairs of images and captions.
2. Clean the text. This involves removing punctuation, stop words, and other noise from the captions.
3. Create a vocabulary. This is a set of all the unique words that appear in the captions.
4. Add start and end tokens to the captions. This helps the RNN to know where the beginning and end of the caption are.
5. Split the data into train, validation, and test sets. This is done to ensure that the model does not overfit to the training data.
6. Extract features from the images. This can be done using a pre-trained model, such as InceptionV3.
7. Create a data generator. This is a function that generates batches of image features and captions.
8. Create an RNN model. This is a type of neural network that can learn to generate sequences of text.
9. Train the RNN model.
    - Generating caption using two methods - greedy search and beam search
    - Comparing Bleu Scores with beam width varying from 1 to 3.
    - Generating captions for images in the test set.
11. Evaluate the RNN model. This is done by feeding the model the test set and evaluating the accuracy of the generated captions.

## Applications

Image caption generators can be used for a variety of applications, such as:

* Generating descriptions for images in a search engine.
* Creating captions for videos.
* Helping people with visual impairments understand images.
* Generating creative text content.

## Challenges

There are a few challenges in building an image caption generator:

* The data is often noisy and inconsistent. This can make it difficult for the model to learn the correct relationships between images and captions.
* The problem is computationally expensive to solve. This is because the model needs to be trained on a large dataset of images and captions.
* The model can be biased towards the data it is trained on. This can lead to the model generating captions that are not accurate or objective.

## Future work

There are a number of areas where future work on image caption generators could be focused, such as:

* Developing better ways to clean the data and remove noise.
* Finding more efficient ways to train the models.
* Reducing the bias in the models.
* Developing models that can generate more creative and informative captions.

I hope this helps!
