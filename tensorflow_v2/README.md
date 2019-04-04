## TensorFlow v2 Examples

*** More examples to be added later... *** 

#### 0 - Prerequisite
- [Introduction to Machine Learning](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/tensorflow_v2/notebooks/0_Prerequisite/ml_introduction.ipynb).
- [Introduction to MNIST Dataset](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/tensorflow_v2/notebooks/0_Prerequisite/mnist_dataset_intro.ipynb).

#### 1 - Introduction
- **Hello World** ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/tensorflow_v2/notebooks/1_Introduction/helloworld.ipynb)). Very simple example to learn how to print "hello world" using TensorFlow v2.
- **Basic Operations** ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/tensorflow_v2/notebooks/1_Introduction/basic_operations.ipynb)). A simple example that cover TensorFlow v2 basic operations.

#### 2 - Basic Models
- **Linear Regression** ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/notebooks/2_BasicModels/linear_regression.ipynb)). Implement a Linear Regression with TensorFlow v2.
- **Logistic Regression** ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/notebooks/2_BasicModels/logistic_regression.ipynb)). Implement a Logistic Regression with TensorFlow v2.

#### 3 - Neural Networks
##### Supervised

- **Simple Neural Network** ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/tensorflow_v2/notebooks/3_NeuralNetworks/neural_network.ipynb)). Use TensorFlow v2 'layers' and 'model' API to build a simple neural network to classify MNIST digits dataset.
- **Simple Neural Network (low-level)** ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/tensorflow_v2/notebooks/3_NeuralNetworks/neural_network_raw.ipynb)). Raw implementation of a simple neural network to classify MNIST digits dataset.
- **Convolutional Neural Network** ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/tensorflow_v2/notebooks/3_NeuralNetworks/convolutional_network.ipynb)). Use TensorFlow v2 'layers' and 'model' API to build a convolutional neural network to classify MNIST digits dataset.
- **Convolutional Neural Network (low-level)** ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/tensorflow_v2/notebooks/3_NeuralNetworks/convolutional_network_raw.ipynb)). Raw implementation of a convolutional neural network to classify MNIST digits dataset.

##### Unsupervised
- **Auto-Encoder** ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/tensorflow_v2/notebooks/3_NeuralNetworks/autoencoder.ipynb)). Build an auto-encoder to encode an image to a lower dimension and re-construct it.
- **DCGAN (Deep Convolutional Generative Adversarial Networks)** ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/tensorflow_v2/notebooks/3_NeuralNetworks/tensorflow_v2/dcgan.ipynb). Build a Deep Convolutional Generative Adversarial Network (DCGAN) to generate images from noise.

#### 4 - Utilities
- **Save and Restore a model** ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/tensorflow_v2/notebooks/4_Utils/save_restore_model.ipynb)). Save and Restore a model with TensorFlow v2.
- **Build Custom Layers & Modules** ([notebook](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/tensorflow_v2/notebooks/4_Utils/build_costum_layers.ipynb)). Learn how to build your own layers / modules and integrate them into TensorFlow v2 Models.

## Installation

To install TensorFlow v2, simply run:
```
pip install tensorflow==2.0.0a0
```

or (if you want GPU support):
```
pip install tensorflow_gpu==2.0.0a0
```