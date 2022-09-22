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
- We then do the required pre-processing for the data to make it compatible with the model to be built.
- Essentially , the approach used in this worksheet is to try out multiple algorithms to build the classifier and choose the best contender
- Multiple 'traditional' ML algorithms like LR,KNN,SVM,Random Forest,Ada Boost, Gradient Boostare tried and results are documented
- We then try deep learning algorithms like ANN and a CNN(build both the ANN and CNN ourselves) and try to solve the problem at hand .Results are documented
- Finally we evaluate our model on Test data with the chosen metric as mAp.
- Refer **python worksheet  Project_P1_FaceMaskDetection.ipynb** for the solution

## Sample Ouput/Prediction :
Here is a sample result/output from the program/model 

![image](https://user-images.githubusercontent.com/68383273/191735599-d115c8f4-ccf3-4458-bf31-95b052ef4262.png)
![image](https://user-images.githubusercontent.com/68383273/191736008-b66da155-c404-499c-ab10-bd1cf2860f35.png)


## Result
- We have obtained a .80 MAP on Train Set & a 0.681 on Test Set
- Further training of model would have given us better results 
- This can be considered as an extesion to improec the performace of this model
