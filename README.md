# AMIP
Andrew's Medical Image Project. Referred to Udemy course: Modern AI Masterclass, instructed by Dr. Ryan Ahmed.

##### This project referred to the Udemy Course: Modern Artifical Intelligence Masterclass: Build Six Projects, link https://www.udemy.com/course/modern-artificial-intelligence-applications/learn/lecture/21159926#overview
##### The data is retrieved from Kaggle Brain MRI Segmentation, link: https://www.kaggle.com/mateuszbuda/lgg-mri-segmentation

## Inspiration
As a BME(biomedical engineering) undergraduate student, I'm enthusiastic about the application of AI in medical imaging. This project is my exploration of using AI to segment tumors in MRI images.

## What it does
This project will visualize the data (images) first, and display the mask, which will indicate the existence of tumors.
Also, ResNet will help this project to improve accuracy. 

## How I built it
I majorly used Python for this project and referred to an online class by Dr. Ryan Ahmed.

## Challenges I ran into
1. Running big datasets on GCP is time-consuming. I'm not very familiar with GCP, which increased the difficulty.
2. I don't have GPU. Although we can rent one on GCP, I chose to run it locally, which consumed more time.
3. Deploying ResNet to make predictions is not easy.

## Accomplishments that I'm proud of
1. This project will help operators to visualize brain tumors.
2. The accuracy of this model is decent: more than 97% on the training dataset.

## What I learned
1. How to train and deploy a neural network
2. How to combine different models to boost accuracy.

## What's next for AMIP -- Andrew's Medical Image Project
Make predictions with CNN and further improve accuracy.

## Image Gallery
![Sample](https://user-images.githubusercontent.com/43218650/105607530-3bbd1d00-5d6d-11eb-94e2-6ad22b656907.jpg)

