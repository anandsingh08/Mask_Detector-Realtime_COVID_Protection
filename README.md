# Mask_Detector-Realtime_COVID_Protection

## About :
This Android App is built for Real Time detection whether a person is wearing mask or not. It uses both front as well as rear camera to analyse result ,
which user can switch as per their convinience. 

## Technlogy Stacks used:
We used here ML Kit and Tensorflow lite model (which was converted from Keras to .tflite ) and already generated datasets , to recognise the face and whether the 
face is having mask on it or not. This code is modified from the TensorFlow's object detection canonical example, to be used with the face mask model .
Most of the work will consist in splitting the detection, first the face detection and second the mask detection. For the face detection step we are going to use the Google ML kit.
For the second step .tflite model does its work of detecting mask on a face.
