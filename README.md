# MNIST-Tensorflow-mini--project
This project implements a two-layer neural network using TensorFlow to classify handwritten digits from the MNIST dataset. It covers data preprocessing, model definition, training with cross-entropy loss and SGD optimizer, and evaluation of the model's accuracy, concluding with a visualization of predictions.


This project implements a basic two-layer neural network using TensorFlow to classify handwritten digits from the MNIST dataset. It covers the following steps:

1. Data Loading and Preprocessing: The MNIST dataset is loaded, images are flattened, converted to float32, and normalized.
2. Model Definition: A neural network with two hidden layers (128 and 256 neurons, respectively) and sigmoid activation functions is defined. The output layer uses softmax for classification.
3. Weight and Bias Initialization: Weights and biases for each layer are initialized.
4. Training Setup: Cross-entropy is used as the loss function, and an SGD optimizer is set up. An accuracy metric is also defined.
5. Training Process: The model is trained over a specified number of steps, updating weights and biases using gradient descent. Loss and accuracy are periodically printed during training.
6. Evaluation: The trained model's accuracy is evaluated on the test dataset.
7. Prediction Visualization: The model makes predictions on a few test images, and these images are displayed along with the model's predicted labels.
