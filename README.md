# Alphabet Hand Gesture Recognition 

<img width="745" alt="Screen Shot 2022-11-30 at 1 00 26 AM" src="https://user-images.githubusercontent.com/89675323/204740073-3faf5262-41a2-42f7-a20e-e72a3ac4090f.png">

Gesture recognition is a topic in computer science and language technology with the aim of interpreting human gestures via mathematical algorithms.

The goal of this project is to custom train a Machine Learning algorithm capable of detecting images of different hand gestures of the American_Sign_Language Alphabet. Here you will find a complete process from creating our custom data to making object detection inferences.

1-	Collection and label: The first phase of this project is to collect data using the computer webcam, label each image individually and create a label_map annotation of the alphabet set. 

2-	SignLanguage_Alphabet_DeepLearning: The second and the core part of the project that will go over installing TensorFlow Object Detection, making hand gesture recognitions, evaluating/saving/exporting the model, and making images/video inferences.

The zipped folder [colab] contains the data created by me and some other data that I installed from GitHub as well divided into two folders [test] and [train], you will also find python scripts needed for the TF detection, annotations, and the downloaded pipeline of the TFOD pre-trained model “MobileNet V2 FPNLite” downloaded from the TFOD zoo. The folder is only missing the video as it was too big to upload (you can use any video of your choice).


## Evaluation Results: 

   
        
![image](https://user-images.githubusercontent.com/89675323/204734197-beda2365-8557-4981-8da5-552cb9e70aa0.png)
     

## Summary:

The model was successfully developed using the TensorFlow2 Mobilenetv2, but it produces accurate prediction under certain conditions of light intensity, angle/rotation, distance, and transition.
