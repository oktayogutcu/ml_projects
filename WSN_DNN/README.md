# WSN_DNN
The purpose of this work is to employ a Convolutional Neural Network (CNN) model to accurately predict the lifetime of wireless sensor networks (WSNs) within an acceptable timeframe, even for networks with varying densities of sensor nodes.

A dataset that includes 300 WSN samples, indicates node locations on Cartesian Coordinates in a selected area of 200x200 units, and its lifetime found by employing MIP has been given. In the dataset, the variety of sensor numbers is 20, 30, 40, 50, 60, and 70 each having 50 sample WSN data.

Before the learning process, the dataset should be preprocessed to fit the NN input layer. Location data has been converted to images. Each image represents a WSN with all the nodes.

<img width="667" alt="image" src="https://github.com/oktayogutcu/ml_projects/assets/46667326/634f0e77-f268-41e5-89d1-0473c1513ea8">
Fig. Example data binarized on the left(dot) and kernelized data on the right.

# System Model
The designed CNN model includes 13 hidden layers including 3 convolution blocks as shown in Figure 11. Each convolution block has a convolutional layer, a rectified linear unit (relu) layer, and finally a pooling layer. The convolutional layer not only indicates that this NN can be defined as a CNN it also applies filters to input images and does a convolution operation to bring forward features of images before relu uses an activation function to concretize those features. The last layer of the convolutional block is the pooling layer which pools the features and makes it clear that a feature can appear anywhere in the image. To illustrate, assume a CNN designed to recognize a face should work at any angle and any image that includes the face even that was not centered.

<img width="275" alt="image" src="https://github.com/oktayogutcu/ml_projects/assets/46667326/04558550-1c80-430f-8ef4-2180059fefa2">
Fig. CNN model layers.

<img width="430" alt="image" src="https://github.com/oktayogutcu/ml_projects/assets/46667326/524ae62d-94cd-4c6b-b0c0-657fd9bae978">
Fig. 32 CNN filter of first convolutional block.

<img width="453" alt="image" src="https://github.com/oktayogutcu/ml_projects/assets/46667326/c5f5ff9f-33c8-4a88-b354-2921df672660">
Fig. Trained with whole data set and tested with different node number data (increasing node number in x axis).


With the popularity of Wireless Sensor Networks, we tackled the lifetime estimation problem from a different perspective. Due to lack of access, these devices run on battery power consequently lifetime plays a dramatic role in WSN's future. In this respect, we proposed a CNN model to predict the lifetime of a given WSN instantly.
