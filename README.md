# Vegetable Classifier

## Description
Comparison of classification models of vegetables using deep learning <br/>

Algorithms compared: CNNs, MobileNetV3Small


## Technology
Dataset: Vegetable Image Dataset (https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset) <br/>
Technology: Python, NumPy, pandas, Tensorflow

## Conclusions
The pretrained model score 98% during training but failed miserable during validation with 58%. In contrast, the MobileNetV3Small model scored 100% during training with 99.5% during validation. Notwithstanding the fact that the MobileNetV3 model was trained on a larger dataset, the architecture is more efficient due to the depthwise seperate convolutions, squeeze-and-excitation modules and efficient residual blocks, which got me interested in improving my model to match its performance through more exploration of these architectural decisions.
