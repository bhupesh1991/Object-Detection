# Object-Detection


TensorFlow Object Detection 

Step 1
For this step, I included the task of downloading the model to the virtual environment proposed by Colaboratory. The rest of the libraries, like TensorFlow, are already available when connecting the environment, which is not a concern for this implementation.

Step 2
Now let’s set all the necessary imports to execute the object detection example. Pay special attention to the object detection utilities.

Step 3
This step is very important because we can change the detection model for a more accurate one, but we can also greatly affect the performance of our future detection functions. Pay attention to MODEL_NAME.

In addition, we execute some elements to use an already established and saved model. Finally we set a conversion function for the image to a numpy array.

Step 4
In this segment of the implementation, we establish the test images to be used. Part of the official example of the Object Detection model.

Step 5
We execute the TensorFlow session. We iterate the images and proceed to the detection of elements.
