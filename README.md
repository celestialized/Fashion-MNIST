Required Packages: Pytorch, TorchVision, Matplotlib, Numpy
A Convolutional Neural Network (CNN) is a type of neural network that is mainly used in Image/Pattern recognition applications. It detects patterns by forming kernels (an NxN matrix) and mapping it to an area of the image (called the reception) by doing bitwise multiplication and then summation. The resulting matrix generated is called a feature map. We have many kernels applied to the original image to generate multiple feature maps. The feature maps are then compressed in size through a process called downsampling/pooling which is of 2 types:

Max pooling
Average pooling
Here, 2 convolutional layers are used for our network.
