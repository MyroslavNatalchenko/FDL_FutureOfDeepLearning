# Lab01: PyTorch Tensors Basics

In Lab01, we covered the fundamental concepts of PyTorch tensors, which are the core data structures used in PyTorch for deep learning

# Lab02: Simple Feed-Forward Neural Network

Lab02 focused on implementing a simple Feed-Forward Neural Network using PyTorch

## Model Performance Analysis

Based on the training results and analysis, the following conclusions were drawn:

#### Interpretation of Graphs:
1. Training loss decreases in almost every epoch
2. Validation loss also systematically decreases
3. The accuracy level on both the training and test sets is quite high. Based on these observations, it can be concluded that the model does not show signs of overfitting

#### Conclusions:
1. **Batch Size Impact**: With smaller batch sizes, the model achieved higher accuracy in the best epoch (though performance degrades with excessively small batches)
2. **Activation Function Choice**: After researching non-linear functions, ReLU was identified as one of the best choices for this task due to its speed compared to Sigmoid and Tanh functions. ReLU allows for quick verification of dataset suitability for learning
3. **Epoch Management**: A larger number of epochs usually improves model accuracy on training data, but can lead to overfitting if the model trains for too long on the same data