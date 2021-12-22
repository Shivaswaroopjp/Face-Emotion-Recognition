# Project Name : Face Emotion Recognition


<a id="p1"></a> 
# Description:

In a physical classroom during a lecturing teacher can see the faces and assess the emotion of the
class and tune their lecture accordingly, whether he is going fast or slow. He can identify students who
need special attention. Digital classrooms are conducted via video telephony software program (exZoom) where it’s not possible for medium scale class (25-50) to see all students and access the mood. Because of this drawback, students are not focusing on content due to lack of surveillance.


## What does Emotion Recognition mean?

Emotion recognition is a technique used in software that allows a program to "read" the emotions on a human face using advanced image processing. Companies have been experimenting with combining sophisticated algorithms with image processing techniques that have emerged in the past ten years to understand more about what an image or a video of a person's face tells us about how he/she is feeling and not just that but also showing the probabilities of mixed emotions a face could has.

<a id="p2"></a> 
# Installations:

Install dependencies using requirements.txt

```shell
pip install -r requirements.txt
```

<a id="p3"></a> 
# Usage:

The program will creat a window to display the scene capture by webcamera and a window representing the probabilities of detected emotions.

> Demo

python camera_input.py


<a id="p4"></a> 
# Dataset:

This model has been trained on [this](https://www.kaggle.com/c/3364/download-all) dataset

The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image. The task is to categorize each face based on the emotion shown in the facial expression in to one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).

# Outputs: 

## Prediction of Angry face
![](https://github.com/Shivaswaroopjp/Face-Emotion-Recognition/blob/main/emotions/arngry.jpg)

## Prediction of disgusted face
![](https://github.com/Shivaswaroopjp/Face-Emotion-Recognition/blob/main/emotions/disgust.jpg)

## Prediction of happy face
![](https://github.com/Shivaswaroopjp/Face-Emotion-Recognition/blob/main/emotions/happy.png)

## Prediction of Neutral Face
![](https://github.com/Shivaswaroopjp/Face-Emotion-Recognition/blob/main/emotions/neutral.jpg)

## Prediciton of Sad Face
![](https://github.com/Shivaswaroopjp/Face-Emotion-Recognition/blob/main/emotions/sad.png)

## Prediciton of Scared Face
![](https://github.com/Shivaswaroopjp/Face-Emotion-Recognition/blob/main/emotions/scared.png)

# Prediction of Surprised Face
![](https://github.com/Shivaswaroopjp/Face-Emotion-Recognition/blob/main/emotions/surprised.png)


## The model has been deployed on AWS(Amazon Web Service Servers) 
    The deployed model can be seen [here](https://ec2-18-218-107-203.us-east-2.compute.amazonaws.com/)




