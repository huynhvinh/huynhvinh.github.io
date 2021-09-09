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

