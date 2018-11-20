## Devanagari-Handwritten-Character-Recognition
### This repo explains the recognition of Devanagari handwritten characters
#### INCEPTION V3 PRE-TRAINED Model is used for training the classifier
[Link](https://archive.ics.uci.edu/ml/datasets/Devanagari+Handwritten+Character+Dataset#) to the dataset
#### The images are of 32x32 size
##### The whole is dataset is divided into 60, 20, 20 percentages for training, testing and validation.
#### For reducing computational complexity and time complexity trasnsfer learning is used by making use of a pre-trained [INCEPTION V3 Model](http://download.tensorflow.org/models/image/imagenet/inception-2015-12-05.tgz)

## Requirements
- GPU (For faster computation) or
- Google Colaboratory
- Tensorflow
- NumPy

#### Bottlenecks files are created for each image and these values are used for training purpose
#### During the training these bottleneck values are taken at random from training set and fed to the pre-trained model

