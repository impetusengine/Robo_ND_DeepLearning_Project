# Robo_ND_DeepLearning_Project

This is the fourth project of the Robotics Software Engineering Nanodegree. The goal of this project is to implement a fully convolutional network to train a drone to recognize a target. The FCN that was used is an architecture based on the Xception and ResNet models and was trained on over 4,000 images containing the target, not containing the target, and containing the target with other people. The code in model_training.ipynb shows the network architecture used for training the drone to identify the target. Further, model_weights.h5 saves the model that has the final weighted IOU score of 0.42. 
