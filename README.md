# Driver Drowsiness Detection

![Driver Drowsiness Detection](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTbZqH9poqqWN53B93CPid6VZyADodQ4qJ4AQ&usqp=CAU)

### Abstract

With this Python project, we will be making a drowsiness detection system. A countless number of people drive on the highway day and night. Taxi drivers, bus drivers, truck drivers and people traveling long-distance suffer from lack of sleep. Due to which it becomes very dangerous to drive when feeling sleepy.The majority of accidents happen due to the drowsiness of the driver. So, to prevent these accidents we will build  an image classifer that can detect if the person is drowsy or not based and will be using CNN model.

### Content

[Poject Proposal](https://github.com/Rawanawh/DriverDrowsinessDetection-DeepLearning/blob/main/Driver%20DrowsinessPP.pdf)

[Minimum Valuable Product](https://github.com/Rawanawh/DriverDrowsinessDetection-DeepLearning/blob/main/DriverDrowsinessMVP.pdf)

[The Code](https://github.com/Rawanawh/DriverDrowsinessDetection-DeepLearning/blob/main/CNN-Driver-Drowsiness.ipynb)

[Presentation](https://github.com/Rawanawh/DriverDrowsinessDetection-DeepLearning/blob/main/DriverDrowsiness_slides.pdf)

[WriteUp](https://github.com/Rawanawh/DriverDrowsinessDetection-DeepLearning/blob/main/DriverDrowsinessWriteup%20.pdf)

### Model Building  

We’ve used sequential model because it allows us to build the model layer by layer 

We’ve built 4 convolutional layer we started first layer with 256 node followed by the second layer of 128 node, the third 32 node, and the last convolutional layer with 32 node and leakyrelu activation function 
And applied max pooling layer, flatten layer 
And the last dense layer with soft max activation function 

#### Compiling the model 

we used ‘Adam’ as an optimizer, used ‘categorical_crossentropy’ for our loss function, used the ‘accuracy’ metric to see the accuracy score on the validation set when we train the model. 
Training the model we fit our training data and validation data and number of epochs For our model, we will set the number of epochs to 50. 
Printed Classification Report for every class ("yawn", "no_yawn", "Closed", “Open”) 
Using our model to make predictions the model can predict image class (0,1,2,3)

### Communication 
In addition, we made a dashboard to use our model to make predictions of the image class (0,1,2,3)

