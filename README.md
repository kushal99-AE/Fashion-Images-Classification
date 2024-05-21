Fashion MNIST Images Classification Model
Multi-layer Perceptron Model Description:
Number of Layers:
4 layers:
1. Input Layer
2. Hidden Layer - 1
3. Hidden Layer – 2
4. Output Layer
Nodes on each Layer:
1. Input Layer – It has 28 X 28 Images as input which is flattened to make it 784 neurons
2. Hidden Layer 1 – 12 neurons
3. Hidden Layer 2 – 10 neurons
4. Output Layer – 10 neurons
Activation function used on each Layer:
1. Hidden Layer 1 – ReLu Activation function
2. Hidden Layer 2 – ReLu Activation function
3. Output Layer – SoftMax Activation function
Description of Loss function used:
• “Sparse Categorical Cross Entropy” is a loss function used for multiclass classification
problems where labels are provided as integers.
• In this case the labels are given as integers from 0 – 9 corresponding to these labels:
class_names = ["T-shirt/top", "Trouser", "Pullover", "Dress", "Coat",
"Sandal", "Shirt", "Sneaker", "Bag", "Ankle boot"]
Output Layer Activation Function used:
• “SoftMax Activation” is used as Output Layer Activation function.
• Output of the SoftMax Activation Function is a probability distribution over the classes.
• Each value is between 0 and 1, and the sum of all values is 1.
• For example, for one of the testing images in the dataset it has given the probabilities for all
10 classes,
array([[0. , 0. , 0. , 0. , 0. , 0.03, 0. , 0.01, 0. , 0.96]])
Training Accuracy:
• After training with the above model, the training accuracy is 87.17%
Validation Accuracy:
• After training with the above model, when validation dataset is passed it got an accuracy of
86.86%
Model Performance prediction if subject to unseen data:
• When model is evaluated on unseen test data it got an accuracy of 84.80 %.
