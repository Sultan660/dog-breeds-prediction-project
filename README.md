# dog-breeds-prediction-project

Project in Data Scientist Nanodegree of Udacity - Message Classification 

This project uses 8351 dog images of 133 breeds to classify dogs with a neural network. Convolutional neural networks CNN is used to improve our classification algorithm, because it works well with images detection. CNN has convolutional and pooling layers connected and activation function. 

### Table of Contents

1. [Installation](#installation)
2. [Project Overview](#overview)
3. [File Descriptions](#files)
4. [Outputs](#outputs)
5. [Licensing & Acknowledgements](#licensing)

## Installation <a name="installation"></a>
This project built by Python version 3.* while it contains many python pachages such as matplotlib, random, keras, numpy, PIL, glob, sklearn, cv2, and tqdm.

## Project Overview<a name="overview"></a>

This project uses 8351 dog images of 133 breeds to classify dogs with a neural network. Convolutional neural networks CNN is used to improve our classification algorithm, because it works well with images detection. CNN has convolutional and pooling layers connected and activation function. 

## File Descriptions <a name="files"></a>

* **bottleneck_features**: It has the bottleneck features used, which cannot be uploaded because the size is too big.
* **haarcascades**: OpenCV, pre-train face detector. 
* **images**: images used in the tests.
* **dog_app.ipynb**: a notebook that was used to run the project experiment.
* **dog_app.html**: a html page that shows the project experiment.
* **extract_bottleneck_features.py**: all needed functions to compute bottleneck features.

## Outputs<a name="outputs"></a>
Furtunetly, the test accuracy around 78%, which could be acceptable. The app should returns the dog breed if the image was passed is a gog. But, if the image has a human face, it should return resembling dog breed. While, other than that, it should return no dog or human detected in the image. The full experiemnt steps and test result can be found on blog [here](https://sultands.home.blog/2020/02/15/dog-breeds-classification/)

## Licensing & Acknowledgements<a name="licensing"></a>
Udacity has the credit by providing the start code and resources for this project. 
