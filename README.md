# AlexNet_Implementation
The Alexnet has eight layers with learnable parameters. The model consists of five layers with a combination of max pooling followed by 3 fully connected layers and they use Relu activation in each of these layers except the output layer.  They found out that using the relu as an activation function accelerated the speed of the training process by almost six times. They also used the dropout layers, that prevented their model from overfitting. Further, the model is trained on the Imagenet dataset. The Imagenet dataset has almost 14 million images across a thousand classes.
#summery
It has 8 layers with learnable parameters.
The input to the Model is RGB images.
It has 5 convolution layers with a combination of max-pooling layers.
Then it has 3 fully connected layers.
The activation function used in all layers is Relu.
It used two Dropout layers.
The activation function used in the output layer is Softmax.
The total number of parameters in this architecture is 62.3 million.
