# Image_Classification
Build an Image classification model for flower species


## Objective of this notebook
- The purpose of this notebook is to build a Image classifier which would be capable of predicting the species of flowers 
- Details of the **problem statement**  , **data set** ,  **summary of the code/solution**  , **sample output/Prediction** from the program and **final result** of the project are listed in the sections to follow.

## Problem Statement 
Computer Vision can be used to classify images .In this partcular use case , a university conducting research involving the understanding of the characteristics of flowers,require an automation which can create a classifier capable of determining a flower’s species from a photo


## Data Description:
The dataset comprises of images from 17 plant species. It can be downloaded from TensorFlow [tflearn.datasets.oxflower17 as oxflower17 ]

## Domain:
Botanical research

## Summary of the Solution/Code:
The code aims at building a image classfifier
- We begin by doing an Exploratory Data analyses and Visualisation/viewing of the images 
- We then do the required pre-processing for the data to make it compatible with the various models to be built.Each model would require the data to be prepared         specifically for that model to ensure compatibility.
- Essentially , the approach used in this worksheet is to try out multiple algorithms to build the classifier and choose the best contender
- Multiple 'traditional' ML algorithms like LR,KNN,SVM,Random Forest,Ada Boost, Gradient Boostare tried and results were recorded
- We then try deep learning algorithms like ANN and a CNN(build custom ANN & CNN networks) and try to solve the problem at hand .Results are recorded
- Finally we try two pretrained CNN with a base of  VGG16 and RESNET50 respectively and observe that CNN with base VGG16 gives us the best results
- Pre-trained CNN(on ImageNet) with  VGG16 Network as a base performed the best giving us 87% on Test Data
- Refer **python worksheet  Project_P4_ImageClassfication_BotanicalResearch_Flowers.ipynb** for the solution

## Sample Ouput/Prediction :
Here is a sample result/output from the program/model 

[![image]
[![image]]


## Result
![image](https://user-images.githubusercontent.com/68383273/191816229-0b4ca2ba-5119-467f-b7c6-0460f40243e0.png)

