# Image Classification with CIFAR-10 Dataset

This is an Image Classification Project using the CIFAR-10 dataset with MobileNetV2. The Model is trained to recognize and classify the images into 10 classes. Also, the trained model is converted into various formats such as **SavedModel**, **TensorFlow Lite (TFLite)**, and **TensorFlow.js** to enable easy deployment across different platform. 

## Feature
- The dataset used is [this](https://www.tensorflow.org/datasets/catalog/cifar10).
- Image classification into 10 classes: 
  - airplane
  - automobile
  - bird
  - cat
  - deer
  - dog
  - frog
  - horse
  - ship
  - truck
- Based on MobileNetV2 architecture.
- The trained model is saved in multiple formats:
  - SavedModel
  - TFLite
  - TensorFlow.js

## Folder Structure
```
|   notebook.ipynb
|   notebook.py
|   best_model.h5
|   bird.jpg
|   requirements.txt
|   
+---saved_model
|   |   fingerprint.pb
|   |   saved_model.pb
|   |   
|   \---variables
|           variables.data-00000-of-00001
|           variables.index
|           
+---tfjs_model
|       group1-shard1of3.bin
|       group1-shard2of3.bin
|       group1-shard3of3.bin
|       model.json
|       
\---tflite
        label.txt
        model.tflite
```

## Requirement
Install the requirements before running the program:
```bash
pip install -r requirements.txt
```
