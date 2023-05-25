# <b> Deep Facial Verification Using Siamese Neural Network (DFV-SNN)</b>

### <b><i>This project is done as part of curriculum for Data science course at Jawaharlal Nehru Technological University Hyderabad </i></b>


## Overview
DFV-SNN (Deep Face Verification with Siamese Neural Networks) is a project that aims to implement face verification using Siamese Neural Networks. The project utilizes captured positive images as the reference and verifies them against a given image to check for a match. The methodology for this project is based on the research paper titled <b>"Siamese Neural Networks for One-shot Image Recognition"</b> by Gregory Koch, Richard Zemel, and Ruslan Salakhutdinov from Department of Computer Science, University of Toronto. Toronto, Ontario, Canada.
  
This research paper serves as the primary reference for the implementation of DFV-SNN (https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf). 

In this project, we will be using negative images downloaded from http://vis-www.cs.umass.edu/lfw/#download as the non-matching images to train our model.</i>

## Problem Statement
In recent years, there has been a growing need for accurate and secure facial recognition systems, particularly in the field of biometrics. However, many existing systems struggle to accurately verify a person's identity when only one sample image is available, known as "one-shot" verification. This project aims to address this challenge by developing a deep learning model that can perform one-shot facial verification using a Siamese Neural Network architecture.

## Objectives
The main objectives of this project are:

- To develop a deep learning model that can perform one-shot facial verification using a Siamese Neural Network architecture.
- To evaluate the accuracy and performance of the model on a dataset of positive and negative images of faces.
- To compare the performance of the model with existing methods and state-of-the-art models for one-shot facial verification.
## Methodology
The methodology of this project involves the following steps:

  - Collection and pre-processing of the dataset of positive and negative images of faces.
      
      <i>(I captured positive images myself while implementation but downloaded the negatives.)</i>
  - Implementation of the Siamese Neural Network architecture using a deep learning framework such as PyTorch or TensorFlow.
  - Training and evaluation of the model on the dataset.
  - Comparison of the performance of the model with existing methods and state-of-the-art models for one-shot facial verification.
## Algorithm
The deep learning model used in this project is a Siamese Neural Network (SNN) architecture. SNNs are a type of neural network that consist of two identical sub-networks, known as "branches". These branches are used to process two separate inputs and compare their representations to make a prediction. In the case of DFV-SNN, the two inputs are the anchor image and the positive or negative image to be verified.

The SNN architecture used in DFV-SNN consists of three main components:

- Two branches, each consisting of a series of convolutional and fully connected layers, that process the anchor and positive/negative images and generate feature representations of the images.
- A contrastive loss function that measures the similarity between the feature representations generated by the two branches and updates the weights of the branches during training.
- An output layer that makes the final prediction of whether the images match or not based on the similarity between the feature representations.
## Implementation
The implementation of DFV-SNN involves the following steps:

- Collection and pre-processing of the dataset of positive and negative images of faces.
- Implementation of the Siamese Neural Network architecture using a deep learning framework such as PyTorch or TensorFlow.
- Training and evaluation of the model on the dataset using the contrastive loss function and a suitable evaluation metric such as accuracy or F1 score.
## Future Scope
This project provides a face verification system using Siamese Neural Network (SNN) which can be used as a starting point for further research and development in the field of face recognition. With the rapid advancement in computer vision and deep learning, there are many opportunities to enhance the performance of this system. Here are some potential areas for future improvement:

- The performance of the model can be improved by incorporating advanced deep learning architectures such as Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks.

- The system can be integrated into a mobile or web app, making it more accessible and user-friendly. 
    <i> (ps: I will be doing this in the Future) </i>

- The system can be trained on a larger and more diverse dataset to improve its accuracy and ability to handle different face shapes and poses.

- The system can be integrated with other biometric authentication techniques such as iris recognition, fingerprint recognition, and voice recognition to provide multi-factor authentication.

- The system can be used as a basic building block for developing a face lock technology.

Overall, this project provides a solid foundation for further research and development in the field of face recognition and verification.

## Disclaimer 
This project outline is from the internet and a speical thinks to NicholasRenotte for explaining this project in everystep.
