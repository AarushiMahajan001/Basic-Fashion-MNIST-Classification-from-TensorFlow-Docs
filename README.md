# Basic-Fashion-MNIST-Classification-from-TensorFlow-Docs
A look at neural network: basic classification using tf.keras¶ This notebook trains a neural network model to classify images of clothing, like sneakers and shirts.

This notebook uses tf.keras, a high-level API to build and train models in TensorFlow.

Fashion MNIST is intended as a drop-in replacement for the classic MNIST dataset—often used as the "Hello, World" of machine learning programs for computer vision. The MNIST dataset contains images of handwritten digits (0, 1, 2, etc) in an identical format to the articles of clothing we'll use here.

This guide uses Fashion MNIST for variety, and because it's a slightly more challenging problem than regular MNIST. Both datasets are relatively small and are used to verify that an algorithm works as expected. They're good starting points to test and debug code.

We will use 60,000 images to train the network and 10,000 images to evaluate how accurately the network learned to classify images. You can access the Fashion MNIST directly from TensorFlow, just import and load the data:
