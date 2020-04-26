# SageMaker Deployment Project

## Project Overview

Welcome to the SageMaker deployment project! In this project you will construct a recurrent neural network for the purpose of determining the sentiment of a movie review using the IMDB data set. You will create this model using Amazon's SageMaker service. In addition, you will deploy your model and construct a simple web app which will interact with the deployed model.

## Project Instructions

The notebook and Python files provided here, once completed, result in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. This project assumes some familiarity with SageMaker, the mini-project, Sentiment Analysis using XGBoost, should provide enough background.

Please see the [README](https://github.com/udacity/sagemaker-deployment/tree/master/README.md) in the root directory for instructions on setting up a SageMaker notebook and downloading the project files (as well as the other notebooks). 

For the solutions only clone this repository:
```
cd SageMaker
git clone https://github.com/ChitraChaudhari/SageMaker-Deploying-Sentiment-Analysis
exit
```
### GPU acess
The deployment project which you will be working on is intended to be done using Amazon's SageMaker platform. In particular, it is assumed that you have a working notebook instance in which you can clone the deployment repository.

In this project you will be training a recurrent neural network which means that you will most likely want access to a GPU enabled instance for training. It should be possible to train your model without using a GPU instance, however, the length of time required to do so will likely be very long.

A ml.t2.medium is used to launch the notebook and is available by default. Inside the notebook ml.p2.xlarge is used for training a model and ml.m4.xlarge is used for deployment. These instance may not be available to all users by default. 

Depending on the default region that was used during the creation of your AWS account the default number of instances allowed may be 0.

You can view your limit by looking at the EC2 Service Limit report which can be found here: https://console.aws.amazon.com/ec2/v2/home?#Limits.

Scroll down and check your current limit.


## Web app final result

The final project will be executed in a simple html page which can be deployed anywhere.

Here are few sample results:

![alt text](https://github.com/ChitraChaudhari/SageMaker-Deploying-Sentiment-Analysis/blob/master/movie%20review1.JPG)

![alt text](https://github.com/ChitraChaudhari/SageMaker-Deploying-Sentiment-Analysis/blob/master/movie%20review2.JPG)

![alt text](https://github.com/ChitraChaudhari/SageMaker-Deploying-Sentiment-Analysis/blob/master/movie%20review3.JPG)

<a href="https://www.youtube.com/watch?v=Oe-cx9FbvS4&feature=youtu.be" target="_blank"><img src="https://www.youtube.com/watch?v=Oe-cx9FbvS4&feature=youtu.be" alt="Link to output video" width="240" height="180" border="10" /></a>
