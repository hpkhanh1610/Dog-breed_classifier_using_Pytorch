[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"

# Dog-breed Classifier using Pytorch

## Project Overview

This project uses Convolutional Neural Networks (CNN) with Pytorch framework to classify dog breeds. Given an image of a dog, this algorithm will identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed. And if there's no dog nor human, an error will be shown telling us to check the input image.

This project is a part of my learning path with [Udacity Deep Learning Nanodegree](https://www.udacity.com/course/deep-learning-nanodegree--nd101).

![Sample Output][image1]


## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.

2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.

3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 

4. Make sure you have already installed the necessary Python packages such as numpy, matplotlib, ... and especially [Pytorch](https://pytorch.org).

5. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.

