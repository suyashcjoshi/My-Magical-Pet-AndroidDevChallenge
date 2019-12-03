# My-Magical-Pet #AndroidDevChallenge
An Android App for interacting with a Virtual Pet in AR

# Tell us what your idea is. 

This application will allow any Android User to interact and play with with a Virtual Pet (Talking Dog) in a magical way using Gestures (Finger), Natural Langauge (voice commands) in Augmented Reality. The app leverages Android AR Core and Google MLKit and Media Pipe open soure project to create this exprience on the edge.

![AR Core Tracking](https://lh6.googleusercontent.com/SUyTSqwCRU_3bHsbHQnic91HuyGJFj_z2B6H4EmWQiaytg4ht5YdOBRzStBYLh8Vi_gXrh6oOSO_gAL-HW_kjPgBRjK0_W15ItBpKNb-sU3KgSXcBvg=w371)

![Finger Tracking](https://github.com/google/mediapipe/blob/master/mediapipe/docs/images/mobile/hand_tracking_3d_android_gpu_small.gif?raw=true)

# Tell us how you plan on bringing it to life. 
Project Plan :

Technologies & Sample Code : 
	
1. Media Pipe (TensorFlow Lite) by Google to build Android Model for Hand Tracking that will be used to interact with the Pet : https://github.com/suyashjoshi/mediapipe

2. ARCore (Android SDK & Sceneform) : AR is the main User Experience and I will be leveraing AR Core Android SDK and SceneForm fraemwork to create AR Experience for this app https://developers.google.com/ar/develop/java/quickstart 

3. Audio & Speech Recogniton : Audio is a big driver in order to create immersive experiences, the visual creates will not only produce sound but users will also be able to speak to them using natural langauge. I will be leveraging this project to train the model and use Speech Recognition https://github.com/tensorflow/examples/tree/master/lite/examples/speech_commands/android

I have started to play with #1 MediaPipe in order to build an Android Model for my hand tracking and have started to communicate with the project engineers on Github. I would love to get help on the same from Google ML Researchers.

# Tell us about you. 

I have been a full time software developer for about 10 years now and bring background in Android, Web and Deep Learning technologies. Previously I've also been invited to speak on State of Mobile AR at MIT : and on Deep Learning for Java Developers : https://www.youtube.com/watch?v=SORF-lNCfLU , https://www.youtube.com/watch?v=y0vHB4YfvWs

I'm very excited to take part in this cahllenge and build this app and make it open source as later use it as teaching project for other developers.
