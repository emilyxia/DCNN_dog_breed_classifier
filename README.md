# Deep CNN for dog breed classification
Hello, welcome to this project repository. Here, I implemented two machine learning models based on deep convolutional neural network to perform dog breed classification. The pipeline can be used within either a web or mobile app to process real-world, user-supplied images. If given an image of a dog, the algorithm will identify an estimate of the canine’s breed. If given an image of a human, the code will identify the resembling dog breed. 

## 1. Dataset

The dataset used here are provided by Udacity and is similar to Stanford Dog Dataset. The dataset is saved under S3 in Amazon Web Service.

This link https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip provides the images for human and can be used to train a human face detector. 

This link https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip provides the images for dog and can be used to trainning of dog related model .

## 2. Model training

The models are built upon PyTorch and was trained using GPU acceleration. 
