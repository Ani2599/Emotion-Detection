# Emotion-Detection
This project explores the implementation and comparison of Convolutional Neural Networks (CNN) architectures for image classification tasks. Three CNN architectures, namely ResNet50, VGG16, and a custom CNN, are utilized and evaluated for their performance.

The deployement is done using Gradio for which the code present inside(.ipynb) file.

There are two other deployement files one is test.py and other is emotion_app.py in which the deployement is done using cv2

Note:- Two model files "Custom_CNN_model.keras" and "Final_Resnet50_Best_model.keras" are not uploaded here because of its large size.

# Data Set-

Kaggle - https://www.kaggle.com/datasets/msambare/fer2013
The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centred and occupies about the same amount of space in each image.

The task is to categorize each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral)
