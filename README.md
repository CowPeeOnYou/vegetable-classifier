# Vegetable Classifier

## Description
This repository is a machine learning project that classifies vegetables using computer vision techniques. The project employs a convolutional neural network (CNN) and compares its performance against the MobileNetV3Small model. The vegetable image dataset used in this project was obtained from Kaggle and contains images of different types of vegetables.

Models compared: CNNs, MobileNetV3Small

##Prerequisites
Python 3.7 or higher <br/>
TensorFlow 2.4 or higher <br/>
Keras 2.4 or higher <br/>
Numpy 1.19 or higher <br/>
Matplotlib 3.2 or higher <br/>

## Technology
Dataset: Vegetable Image Dataset (https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset) <br/>
Technology: Python, NumPy, pandas, Tensorflow

## Conclusions
he results of the comparison between the CNN and the MobileNetV3Small models showed that the MobileNetV3Small model outperformed the CNN model. The CNN model had a training accuracy of 98%, but a validation accuracy of only 58%. On the other hand, the MobileNetV3Small model had a training accuracy of 100% and a validation accuracy of 99.5%. The MobileNetV3Small model was able to achieve such high accuracy due to its efficient architecture, which includes depthwise seperate convolutions, squeeze-and-excitation modules, and efficient residual blocks. These findings got the author interested in exploring these architectural decisions further to improve the performance of the CNN model.
