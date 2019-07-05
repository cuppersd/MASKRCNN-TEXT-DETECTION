# MASKRCNN-TEXT-DETECTION
MASKRCNN TEXT DETECTION

# Mask R-CNN for Text Detection
### Introduction
This is an implementation of [Mask R-CNN](https://arxiv.org/abs/1703.06870) on Python 3, Keras, and TensorFlow. The model generates bounding boxes and segmentation masks for each instance of an object in the image. It's based on Feature Pyramid Network (FPN) and a ResNet101 backbone.

![Instance Segmentation Sample](assets/img_202.jpg)

### Contents
1. [Installation](#installation)
2. [Download](#download)
2. [Demo](#demo)
3. [Test](#train)
4. [Train](#test)
5. [Examples](#examples)

### Installation
* Python 3.6
* Tensorflow v1.8.0+
* Keras
* opencv-python 3.4+

### Download
Models trained on ICDAR 2017 (training set) + ICDAR 2019 (training set): [Download link](https://rrc.cvc.uab.es/)

### Test
If you've downloaded the pre-trained model, you can run

```
python test.py 
```

a text file will be then written to the output path.

### Train
