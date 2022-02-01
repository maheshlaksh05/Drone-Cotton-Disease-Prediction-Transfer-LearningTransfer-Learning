# Drone-Cotton-Disease-Prediction-TransferLearning-DeepLearning
The identity and convolution blocks coded in the notebook are then combined to create a ResNet-50 model with the architecture shown below:

ResNet-50 Model
The ResNet-50 model consists of 5 stages each with a convolution and Identity block. Each convolution block has 3 convolution layers and each identity block also has 3 convolution layers. The ResNet-50 has over 23 million trainable parameters.
I have tested this model on the signs data set which is also included in my Github repo. This data set has hand images corresponding to 6 classes. We have 1080 train images and 120 test images.
![image](https://user-images.githubusercontent.com/97341259/151925281-4f824e23-994e-47f0-a9ff-75419907c1d0.png)
Skip Connection — The Strength of ResNet
ResNet first introduced the concept of skip connection. The diagram below illustrates skip connection. The figure on the left is stacking convolution layers together one after the other. On the right we still stack convolution layers as before but we now also add the original input to the output of the convolution block. This is called skip connection
![image](https://user-images.githubusercontent.com/97341259/151925380-dd96c4df-bfd6-40dc-b672-4b8ff49db996.png)
So, What is Transfer Learning?
Simply put, transfer learning is the phenomenon which allows you to transfer what state-of-the-art machine learning models have learnt, and you use it for your custom problem.

The following flow chart represents how transfer learning works in practice. Deep learning model 1 transfers the knowledge it learnt(weights, biases) which can be then used by deep learning model 2.

![image](https://user-images.githubusercontent.com/97341259/151925651-0aef10a6-96fa-41ee-aa69-013a74a08805.png)
