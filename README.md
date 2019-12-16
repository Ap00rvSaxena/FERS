#RealTime Facial Emotion Recognition System

The goal of the project is to identify 7 key human emotions: HAPPY, NEUTRAL, SAD, SURPRISE, ANGER, DISGUST and FEAR, the project uses FER2013 dataset to train a classification Convolutional neural networks (CNN) model which takes a grayscale images of faces and predicts the most probable emotion in the output layer. The trained model was then used as the baseline to classify a facial emotion in the real-time application which was implemented using OpenCV, we extract the detected face from image frames in a real-time video then offer it to the model to predict and print the emotion in real-time.

### Dataset
Available at kaggel: [FER2013](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)

### Online Model Available at Google Colab
Available at Colab: [FERSystem](https://colab.research.google.com/drive/1-2ski0YhOa4v0FZJcT1ifDwMY27JJTCI)

### Demo
![](../master/images/neutral.png)
> Neutral Face

![](../master/images/sad.png)
> Sad Face

![](../master/images/angry.png)
> Angry Face

![](../master/images/surprised.png)
> Surprised Face
![](../master/images/happy.png)
> Happy Face