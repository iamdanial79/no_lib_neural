This Python script builds a simple neural network without using deep learning libraries like TensorFlow or PyTorch. It is designed to classify images from the TinyMNIST dataset, a smaller version of MNIST.
1. Data Loading and Preprocessing

    The dataset is loaded using pandas, extracting images and labels.
    Pixel values are normalized to the range [0,1][0,1] for better convergence.
    Labels are one-hot encoded for multi-class classification.

2. Activation Functions

    Implements ReLU and tanh for hidden layers.
    Uses softmax in the output layer to convert logits into probabilities.

3. Forward and Backward Propagation

    Computes weighted sums at each layer.
    Applies activation functions.
    Computes gradients using backpropagation and updates weights via gradient descent.

4. Model Training

    Iteratively optimizes weights to minimize classification loss.
    Uses cross-entropy loss for training.

This implementation provides an educational example of neural network fundamentals without relying on external machine-learning libraries.
