# Dogs vs Cats classifier using convolutional neural nets
The dogs vs cats dataset is one of the first datasets that showed the advantages of using a convolutional neural network for computer vision tasks. 

**Resources Used**
-Python 2.7
-Tensor flow 2.0
-packages : numpy,matplotlib

**Model**
A convolutional neural net loosely based on the Lenet5 architecture was used with Batch Normalization and Dropuout regularization to prevent overfitting . relu activations are used in the intermediate layers and a sigmoid activation to calssify at the last layer
the model was only trained for 55 epochs with a batch size of 20 using the adam optimizer without learning rate deccay. 

![alt text](images/model.png)

