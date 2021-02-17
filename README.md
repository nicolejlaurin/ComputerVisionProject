# COMP4102 Project Proposal – Facial Recognition Program


## Team Members:
  - Nicole Laurin: 101043422
  - Cameron Slupeiks: 101013794
  
## Summary: 
The goal of our project will be to develop a facial recognition program to detect known and unknown subjects. We will be using a convolutional neural network, deep metric learning and some facial recognition libraries to detect and identify human faces. Through the use of facial feature extraction and facial encoding, we will be able to identify whether the subjects detected in a livestream video are identifiable or not.

## Background:
The field of applying computer vision and neural networks into the development and implementation of facial detection and recognition has been developing for many years and has much progress to make. Modern software has demonstrated new and improved uptakes in facial recognition.
We will be making use of a Convolutional Neural Network (CNN) for face detection found in dlib. The purpose of using CNN is to use algorithms that will recognize and memorize facial patterns and features from different angles. The CNN is more costly in runtime compared to the HOG based detector because it creates and recognizes non-frontal facial features. We will be specifically using neural networks from dlib as it has already been trained on over 3 million images. The dlib library includes many algorithms that will help us detect features from pictures and live streaming videos. In order to use dlib (a C++ library), we will be using the face_recognition library. This library acts as a wrapper for dlib’s facial recognition functionality, and it is easy to use in practice.
For livestream recognition testing, we will be using the 720p FaceTime HD camera that is built-in to a MacBook Pro (Mid-2015). This camera generally performs well in good lighting, but it is known to have poor white balance and it skews colours (e.g. a green wall may look blue or brown). It also does not perform well in low-light - the frames that are produced are extremely grainy, which means our livestream facial recognition script may not be as efficient in the dark. 


## The Challenge: 
### Accuracy
A big challenge we might face will be to gain accurate results. Through the use of machine learning, it is important that we are able to differentiate features that uniquely represent each individual. We must be able to train the data to gain the best outcome for classifying the individuals based on facial recognition. 

### Computing Power
We will be focusing on using colab in order to use the GPU, which will create more computing power and can handle more processes per second. When running a more demanding and costly model like such, using a GPU-powered server will save us time when it comes to handling image encoding because it can help handle more tasks simultaneously. Unfortunately, we will be testing our livestreaming facial recognition script on a MacBook Pro. This will likely result in a lower FPS rate, as this laptop does not contain a GPU to handle graphics-related processes.

## Goals and Deliverables: 
### Describe what success looks like and how it can be evaluated.
Success for us, would require our program to accurately detect and recognize a person by their facial features. To elaborate, we will be able to detect each feature, learn the features, match them to their respective candidate and be able to output the proper name based on a set of algorithms. Through this, our program will thus be able to take in as input, a picture or live streaming video of a person to fulfill its given task. Success can be evaluated by properly accepting input and providing us with valid output in a non-costly timeframe. 

### How realistic is it for your team to get what it needs to get done within the allotted time? 
Very realistic to accomplish our project as we both have experience and a background in implementing neural networks, classifying features and training given data. We also have experience using colab and github during a collaborative project. 
 
 
 



