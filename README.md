# Semantic Segmentation
### Introduction
In this project, you'll label the pixels of a road in images using a Fully Convolutional Network (FCN).

### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)

##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

##### Run
Run the following command to run the project:
```
python3 main.py
```

##### Output

These are examples from a network trained for 10 epochs with a minibatch size of 1.  Overall, the results are surprisingly good.  Shadows cause noticeable difficulties.  Training with contrast and brightness augmentation may help.

![example inference 1](runs/1512347338.3891246/um_000007.png)

![example inference 2](runs/1512347338.3891246/um_000018.png)

![example inference 3](runs/1512347338.3891246/um_000054.png)

![example inference 3](runs/1512347338.3891246/um_000070.png)

![example inference 3](runs/1512347338.3891246/um_000073.png)

![example inference 3](runs/1512347338.3891246/um_000074.png)

![example inference 3](runs/1512347338.3891246/um_000075.png)
![example inference 3](runs/1512347338.3891246/um_000081.png)
![example inference 3](runs/1512347338.3891246/umm_000034.png)
![example inference 3](runs/1512347338.3891246/umm_000035.png)

4 Epochs with minibatch of 1
![example inference 3](runs/1512367659.1442187/um_000056.png)
![example inference 3](runs/1512367659.1442187/um_000066.png)

1 Epoch with minibatch of 1
![example inference 3](runs/1512275048.2048123/um_000008.png)
