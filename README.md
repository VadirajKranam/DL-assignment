
Parameter tying and parameter sharing are concepts in machine learning and neural networks that refer to ways of reusing or constraining parameters in a model. Both approaches aim to reduce the number of trainable parameters, which can lead to more efficient training and better generalization in certain cases.

1.Parameter Tying:

Definition: Parameter tying involves explicitly setting constraints on certain parameters in a model to be equal or related in some way.
Example: In a neural network, you might tie the weights of different neurons in different layers to be the same. This means that the weights for a particular connection are shared across multiple parts of the network.
Advantages: Reducing the number of unique parameters can lead to a more parsimonious model, which may be less prone to overfitting, especially in situations where data is limited.

2.Parameter Sharing:

Definition: Parameter sharing is a broader concept where parameters are shared across different parts of a model without explicitly enforcing constraints on their values. It's a more general form of tying, where the shared parameters might be learned jointly by multiple components.
Example: In convolution

Problem:
Build a CNN for image classification on the CIFAR-10 dataset, a dataset of 60,000 32x32 color images in 10 different classes. We will explore parameter sharing in the convolutional layers to improve model efficiency.


Name: Vadiraj Karanam
USN: 4NI20IS123
