# FacialEmotionRecognition
## Abstract
Facial Emotion Recognition (FER) is a cutting-edge technology that involves the identification and interpretation of human emotions through analyzing facial expressions. Leveraging advancements in computer vision and machine learning, FER systems detect and categorize emotions such as happiness, sadness, anger, and surprise, offering a powerful tool for applications ranging from human-computer interaction to mental health monitoring. This technology holds significant promise in enhancing our understanding of emotional cues, enabling more empathetic and responsive artificial intelligence systems.

## Introduction
Facial emotion recognition refers to identifying expressions that convey basic emotions such as fear, happiness, and disgust, etc. It plays an important role in human-computer interactions and can be applied to digital advertisement, online gaming, customer feedback assessment, and healthcare. With advancements in computer vision, high emotion recognition accuracy has been achieved in images captured under controlled conditions and consistent environments, rendering this a solved problem. Challenges persist in emotion recognition under naturalistic conditions due to high intra-class variation and low inter-class variation, e.g. changes in facial pose and subtle differences between expressions.

## Model developed

![image](https://github.com/kowshik4/FacialEmotionRecognition/assets/28788453/692dff3a-7f70-4196-abe7-1d4c9d0df699)

The network consists of 4 convolutional stages and 3 fully connected layers. Each of the convolutional stages contains two convolutional blocks and a max-pooling layer. The convolution block consists of a convolutional layer, a ReLU activation, and a batch normalization layer. Batch normalization is used here to speed up the learning process, reduce the internal covariance shift, and prevent gradient vanishing or explosion. The first two fully connected layers are followed by a ReLU activation. The third fully connected layer is for classification. The convolutional stages are responsible for feature extraction, dimension reduction, and non-linearity. The fully connected layers are trained to classify the inputs as described by extracted features.

## Testing on a sample image 
<img width="671" alt="Screenshot 2024-02-26 at 1 09 09 PM" src="https://github.com/kowshik4/FacialEmotionRecognition/assets/28788453/15e55659-b6ca-423d-8ed9-b21fb3ab59b9">

<img width="546" alt="Screenshot 2024-02-26 at 1 11 41 PM" src="https://github.com/kowshik4/FacialEmotionRecognition/assets/28788453/232c83a0-2a8f-4ff5-b911-8dc121da0ce8">


## Testing on real time face capturing image

<img width="704" alt="Screenshot 2024-02-26 at 1 13 38 PM" src="https://github.com/kowshik4/FacialEmotionRecognition/assets/28788453/87eaa74c-942e-476e-bb8e-a74b38fd6ebf">


