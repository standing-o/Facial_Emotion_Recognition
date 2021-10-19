# Facial Emotion Recognition
- Facial emotion recognition (FER) using convolutional neural networks
- Xception, CNN
- Sep. 16, 2021 ~ Oct. 13, 2021

### First project with the 3rd generation of data analysis club
- This repo is maintained by 오서영, 최규진, 박지원

| [Presentation](https://github.com/OH-Seoyoung/Facial_Emotion_Recognition/blob/master/20211013_FER_landmark.pdf) |

## Process
### 1. Facial emotion classification | [Code1](https://github.com/OH-Seoyoung/Facial_Emotion_Recognition/blob/master/FER_using_Xception.ipynb) | [Code2](https://github.com/OH-Seoyoung/Facial_Emotion_Recognition/blob/master/FER_using_CNN.ipynb)  
- Xception architecture pre-trained on ImageNet dataset
- Custom designed CNN  
--> We achieved up to 60.01% test accuracy with color image dataset and 65.71% with grayscale one.

### 2. Training the face landmark points | [Code](https://github.com/OH-Seoyoung/Facial_Emotion_Recognition/blob/master/Face_landmark_using_CNN.ipynb)  
- Custom designed CNN  
--> We achieved up to 117.1117 test MSE

### 3. Analysis of the landmarks of FER2013 | [Code](https://github.com/OH-Seoyoung/Facial_Emotion_Recognition/blob/master/Visualization_of_Face_landmark.ipynb)  
- Statistics of data
- Euclidean distance of the center points

## Dataset
```
[1] MMA FACIAL EXPRESSION, https://www.kaggle.com/mahmoudima/mma-facial-expression
[2] FER-2013, https://www.kaggle.com/msambare/fer2013
[3] Face Images with Marked Landmark Points, 
https://www.kaggle.com/drgilermo/face-images-with-marked-landmark-points
```
