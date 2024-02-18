# CancerDetection_CNN
Histopathological Cancer Detection on tissue scans

[Histopathologic Cancer Detection](https://www.kaggle.com/competitions/histopathologic-cancer-detection/overview)

The purpose of this project is to utilize Convolution Neural Network architecture to aid in detecting metastatic cancerous cells in small image patches taken from larger digital pathology scans. We are tasked with building a model that predicts which scans contain cancerous cells and which contain benign cells. The dataset consists of over 200,000 images that were previously classified. This project was also completed as part of the Introduction to Deep Learning course at University of Colorado Boulder for Week 3 content. 

The data is taken from the Kaggle Competition which evaluates test submissions by area under the ROC curve between the predicted probability and the observed target.

The Best model trained from the project have the following hyper parameters:
Architecture: Model 6 CNN	
Learning rate: 0.00002	
Final Activation Layer: Sigmoid
Optimizer: RMSprop	
Epochs: 10
Batch size: 64
Regularization: Dropout + in Dense Layers
Regularization: 0.2
Public leaderboard score: 80.44
Private leaderboard score: 74

<img width="621" alt="Screen Shot 2024-02-17 at 7 47 13 PM" src="https://github.com/ancr8790/CancerDetection_CNN/assets/95835246/7f0e2c5f-4dec-4c05-b965-374766ea01fd">



