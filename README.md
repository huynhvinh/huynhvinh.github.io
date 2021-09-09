# Van Vinh Huynh - GitHub Projects

## Automatic Classification of American Football Plays

In this project, we develop a computer vision model to classify videos of football plays by type. This model will be incorporated in a web application where users can upload new videos and receive the prediction. This service aims to reduce the need for human intervention when classification is needed.

We obtained the video datasets from the Georgia Tech Stadium-IoPT at http://estadium.gatech.edu/. We then used OpenCV to split each video into static frames and represent each play with numpy arrays. We also convert labels in a one-hot encoding format. Then we developed a CNN-RNN model for image classification using ResNet50/VGG16 and LSTM networks. Finally we developed an web application which integrates with machine learning model to predict the football plays using video inputs. An overall architect can be found here 

<img src="/images/football_architect.png" alt="football_architect" width="500"/>

Source Code can be found[ here](https://github.com/huynhvinh/football_plays_video_recognition)

More details about the project: [click here](https://docs.google.com/presentation/d/1d4isbu5wujBa6oj3CAjtQQiMlrNS8Jlu/edit#slide=id.p7)

## MRI scan using semi supervised Learning

MRI is one of the most pervasive imaging techniques. However, it is expensive to generate MRI scans. Previous attempts to use deep learning required large amounts of supervised data. However, this supervised data necessarily requires that a huge number of full MRI scans are resolved. Thus, the amount of unlabeled data far exceeds the amount of labeled data. 

In this project, we investigated the effects of several self supervised models that make use of unlabeled data to the fastMRI problem. We could get similar results as baseline using Barlow Twins and are able to obtain significantly better results than the baseline using Fixmatch. Barlow Twins Pipeline is shown below:

<img src="/images/barlow_pipeline.png" alt="Barlow Twins Pipeline" width="500"/>

Source Code can be found[ here](https://github.com/huynhvinh/fastMRI)

## Experimenting group behaviour in Pacman ghosts

This is an interesting final project for Game AI class, in which we applied Artificial Intelligent into an simple old-fashioned Pacman game engine.

In this project, we experiment with different behaviours for the ghosts in Pacman game. The goal is to give users different levels of difficulty when playing the game. In Pacman, the player makes Pacman, a yellow disc, move around a maze. The goal is to eat every yellow pellet (circles) while notgetting caught by the ghosts/monsters.

We are using the Pacman game engine developed for UC Berkeley’s introductory artificial intelligence course. The engine provides other basic functionality like moving the Pacman, adding walls, pelletsand APIs for a lot of other things. 

We aim at trying out different coordinated ghost behaviours. By talking with each other, the ghosts will be able to determine what to do to targets based on different attacking strategies: 
1. Prowl: Lock Pacman in a region
2. Corner: Attack Pacman from 4 directions or cover exit points to trap it
3. Barrage: Come at Pacman from one direction
We also implement leading attacks using bfs based on Pacman current direction. 

One of our attacking strategies to trap Pacman in a corner: 

<img src="/images/edited_pac.png" alt="edited_pac" width="500"/>

Reach out to me for the[ source code](https://github.com/huynhvinh/Smart-Pacman-Ghosts)

## The X-Factor: A Machine Learning model to predict popularity of an input song

While most of the current machine learning research on music focuses on building recommendation systems, auto-generating music tracks and personalizing music tracks, few have tackled the problem of providing feedback on tracks to improve popularity.

In our group project, we will build a system using both supervised and unsupervised techniques with a two-fold goals

1. To gain insight into the features that are most important in determining the popularity of a song, as determined by the public. This will require an analysis of both the commonly observed traits of hit songs and the commonly unobserved traits of unpopular songs.
2. We also aim to build a model that can accurately forecast the popularity of a song [1]. We suggest minimal changes to the song based on our findings from the previous step, and aim to give a quantifiable increase in popularity by incorporating the aforementioned changes.


<img src="/images/X-factor.png" alt="X-factor" width="500"/>

More details about the project: [click here](https://huynhvinh.github.io/X-Factor.github.io/)

