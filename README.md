# **Sign-Language-Recognition**
Real-Time Sign Language Recognition (RTSLG) employs technology to convert hand motions into text or voice as they are signed. This help us in bridging the communication gap between the deaf and hearing communities. Hands carry a rich tapestry of information, allowing people with disabilities to express themselves meaningfully while improving communication for everyone. However, precisely understanding these transient hand gestures in real time presents a challenge. This is an important challenge for the hearing-impaired group, which often depends on hand signals to convey their ideas and feelings yet obtains minimal understanding from the general public. Recognizing this important necessity, hand gesture recognition technologies have gained popularity in recent years. Our analysis of the literature recognized limitations in existing sign language recognition approaches. Some gestures have been eliminated from their datasets, particularly dynamic ones, restricting their ability to record these subtle movements. Additionally, these systems often battled with accuracy as a result of differences in the background lighting. To address these restrictions, we created a unique mechanism that solves them.The suggested architecture uses a deep learning model created using Python, TensorFlow, OpenCV, and Keras. This RTSLG system analyzes motions of the hand collected by a recording device using image detection, computer vision, and, in particular, Convolutional Neural Networks (CNNs). We were able to recognize and transform motions into text with an outstanding accuracy of 95% after deploying our technique.

## **Methodology**
Key steps of the System Design are:

1) Image Acquisition: • Employs a camera or webcam to capture hand gestures made by the user.

2) Image Pre-processing: • Processes the captured image as input.

• Involves techniques like image enhancement and restoration.

• Converts the input image into grayscale and applies interpolation.

3) Image Segmentation: • Isolates the Region Of Interest (ROI), typically the user’s hand.

• Uses techniques like edge detection, thresholding, region-based, clustering, or artificial neural networks.

4) Feature Extraction: • Extracts relevant hand features for comparison with the dataset.

5) Classification and Recognition: • Classifies the extracted features against the sign language dataset.

• Generates the corresponding output for the captured hand gesture.

## **Repository Content**
data/: This directory contains datasets used for training and evaluating the deep learning model.

model/: Here lies the trained deep learning model that performs sign language recognition.

data_collection/: Includes scripts or tools used to collect and preprocess data, such as capturing hand gestures and preparing them for model training.

test/: Contains scripts for testing and evaluating the performance of the model.
