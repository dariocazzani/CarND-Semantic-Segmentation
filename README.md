# Semantic Segmentation
### Introduction
Semantic segmentation is understanding an image at pixel level. We want to assign a label for each pixel in an image.
The goal of this project is to label the pixels of a road in images using a Fully Convolutional Network (FCN).

--------------------

### Theory
Please refer to the original paper: [Fully Convolutional Networks for Semantic Segmentation](https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf)

--------------------

### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

--------------------

### Start

#### Requirements

```
pip install -r requirements.txt
```

##### Run
Run the following command to run the project:
```
python main.py
```

--------------------

### Results

Please check the following images taken from the test set.

![image1](https://github.com/dariocazzani/CarND-Semantic-Segmentation/blob/master/images/um_000000.png)
![image1](https://github.com/dariocazzani/CarND-Semantic-Segmentation/blob/master/images/um_000007.png)
![image1](https://github.com/dariocazzani/CarND-Semantic-Segmentation/blob/master/images/umm_000042.png)
![image1](https://github.com/dariocazzani/CarND-Semantic-Segmentation/blob/master/images/uu_000085.png)
