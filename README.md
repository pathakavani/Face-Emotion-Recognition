# Face-Emotion-Recognition
A deep learning model for recognition of facial emotions

This notebook consists of capturing/giving input an image and detecting which emotion does the face exhibit. 
The entire flow is as follows:
1. Giving image as input
2. Converting the image to grey-scale
3. Face Detection using haarcascade_frontalface_default.xml file
4. Resizing the image
5. Result - Predict Emotion (Happy, Sad, Fear, Angry, Surprise, Disgust, Neutral) using the pre-trained model 

Tech Stack:
1. Python3
2. Keras (CNN Model)
3. OpenCV
