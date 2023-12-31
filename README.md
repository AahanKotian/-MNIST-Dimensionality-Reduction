# -MNIST-Dimensionality-Reduction
I will work with the famous MNIST dataset, which is a set of images of handwritten digits https://en.wikipedia.org/wiki/MNIST_database.

Handwritten Digit Recognition:
This project aims to classify images of handwritten digits from 0-9 using the popular MNIST dataset and a multi-layer perceptron neural network model.

The Dataset:
The MNIST dataset contains 60,000 training images and 10,000 test images of handwritten digits. Each image is 28x28 pixels in size and labeled with the correct digit class from 0-9.
The training and test data were loaded into NumPy arrays and normalized between 0-1.

Model Architecture:
A neural network with an input layer of 784 nodes (28x28 image size), two hidden layers of 256 nodes each with ReLU activations, and an output layer of 10 nodes with a softmax activation was used.
The model was trained with the Adam optimizer, batch size of 128, and for 10 epochs. A validation split of 0.2 was used to monitor performance during training.

Results:
The model achieved 98.2% accuracy on the test set after training. The confusion matrix shows most errors were between digits that look visually similar like 6 and 9.

Future Improvements:
Additional hidden layers, regularization techniques, and data augmentation could help improve results further. Collecting my own handwritten digit dataset would also be interesting to test domain adaptation.

Conclusion:
This basic neural network demonstrates my understanding of fundamental machine learning concepts like model building, training and evaluating a classifier on a benchmark dataset. The high accuracy achieved validates my skills in this introductory project.
