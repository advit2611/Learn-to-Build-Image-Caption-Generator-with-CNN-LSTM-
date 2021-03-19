# Learn to Build Image Caption Generator with CNN & LSTM 

# Description
The objective of our project is to learn the concepts of a CNN and LSTM model and build a working model of Image caption generator by implementing CNN with LSTM. 

In this Python project, we will be implementing the caption generator using CNN (Convolutional Neural Networks) and LSTM (Long short term memory). The image features will be extracted from Xception which is a CNN model trained on the imagenet dataset and then we feed the features into the LSTM model which will be responsible for generating the image captions. 

 # Dataset
 https://www.kaggle.com/adityajn105/flickr8k?select=captions.txt
 
 # Model
 
 So, to make our image caption generator model, we will be merging these architectures. It is also called a CNN-RNN model. 

CNN is used for extracting features from the image. We will use the pre-trained model Xception. 

LSTM will use the information from CNN to help generate a description of the image. 


What is CNN?

Convolutional Neural networks are specialized deep neural networks which can process the data that has input shape like a 2D matrix. Images are easily represented as a 2D matrix and CNN is very useful in working with images.

CNN is basically used for image classifications and identifying if an image is a bird, a plane or Superman, etc.

What is LSTM?

LSTM stands for Long short term memory, they are a type of RNN (recurrent neural network) which is well suited for sequence prediction problems. Based on the previous text, we can predict what the next word will be. It has proven itself effective from the traditional RNN by overcoming the limitations of RNN which had short term memory. LSTM can carry out relevant information throughout the processing of inputs and with a forget gate, it discards non-relevant information.

# Prerequisites

Make sure you have installed all the following necessary libraries:

  pip install tensorflow<br/>
keras<br/>
pillow<br/>
numpy<br/>
tqdm<br/>
jupyterlab

#Summary

In this advanced Python project, we have implemented a CNN-RNN model by building an image caption generator. Some key points to note are that our model depends on the data, so, it cannot predict the words that are out of its vocabulary. We used a small dataset consisting of 8000 images. For production-level models, we need to train on datasets larger than 100,000 images which can produce better accuracy models.
