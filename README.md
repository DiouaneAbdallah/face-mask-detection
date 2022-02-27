# face-mask-detection
Face Mask Detection system based on computer vision and deep learning using OpenCV and Tensorflow/Keras.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DiouaneAbdallah/face-mask-detection/blob/main/faceMaskDetection.ipynb)

This project uses a Deep Neural Network, more specifically a Convolutional Neural Network, to differentiate between images of people with and without masks. The CNN manages to get an accuracy of 99.8% on the training set and 99.2% on the test set. 

Then this CNN are used to classify as mask or no mask, using OpenCV.

## 📁 Dataset



The dataset we’ll be using here was created by [Prajna Bhandary](https://github.com/prajnasb/observations).

This dataset consists of 1,376 images belonging to two classes:

with_mask: 690 images
without_mask: 686 images

## 🎯 Results

Our model gave an accuracy of 99.8% on the training set and 99.2% on the test set.

We got the following accuracy/loss training curve plot

![results](https://github.com/DiouaneAbdallah/face-mask-detection/blob/main/images/results.png)

## 🔍 test the model

With Mask

![With Mask results](https://github.com/DiouaneAbdallah/face-mask-detection/blob/main/images/results2.png)

No Mask

![No Mask results](https://github.com/DiouaneAbdallah/face-mask-detection/blob/main/images/results1.png)







