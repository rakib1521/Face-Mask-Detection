# Face-Mask-Detection
This model can identify if some one wearing mask from image. 
this is a binary classification model. created using tensorflow and keras.

# Here  a Convolutional Neural Network is used to recognize face mask.

A convolutional neural network is one of the main categories to do images recognition, images classifications. Objects detections recognize faces, etc., are some of the areas where CNNs are widely used. 
In this model, there are 4 convolution layer followed boy max-pooling layer and in each layer. 
Stride: 1
Padding: valid 
activation : Relu

After 4 convolution layer, there is a flatten layer then there is 5 fully connected dense layer.
Activation :Relu

In the output layer as there is two output as it is a binary classification and activation is sigmoid.

# Summary of Model:
![Summary of Model](https://github.com/rakib1521/Face-Mask-Detection/blob/master/model.PNG)

# Training and validation accuracy:
![accuracy](https://github.com/rakib1521/Face-Mask-Detection/blob/master/Training%20and%20validation%20accuracy.png)

# Training and validation loss:
![loss](https://github.com/rakib1521/Face-Mask-Detection/blob/master/Training%20and%20validation%20loss.png

# output:
  ![result](https://github.com/rakib1521/Face-Mask-Detection/blob/master/result.PNG)

