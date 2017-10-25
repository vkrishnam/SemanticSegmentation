# **Semantic Segmentation**
### Introduction
In this project, used VGG16 as Encoder and created a decoder with layers of 1x1 Convolution, Upscaling and addition of skip layers to do Two class prediction (Road/Non-Road) at every pixel in the input image resolution.


[//]: # (Image References)
[image1]: ./runs/uu_000063.png "Example Segmentation Result"


 ![alt text][image1]

### Setup
##### Dependent Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

### Start
##### Run
Run the following command to run the project:
```
python main.py
```
