# Fashion_MNIST_Database
working on the fashion mnist using google colab. 

Follow steps below to run the file on your side using google colab 

1. downlaod the file on your local machine. 
2. open google colab 
3. uplaod the file and you can using it. 


### tasks that I did in this project 
1.	What are the dimensions of train_images, train_labels, test_images, and test_labels?
2.	What are the lengths of train_labels and test_labels?
3.	Please show some of train and test labels.
4.	Please show the digital content of image index 5 in the training dataset.
5.	Please plot the image of the index 5 in the training dataset.
6.	What is the label for the index 5 in the train_label and looking up in the above list, what does it mean?
7.	Please show the digital content of image index 500 in the testing dataset.
8.	Please plot the image of the index 500 in the testing dataset.
9.	What is the label for the index 500 in the test_label and looking up in the above list, what does it mean?
10.	Please import models and layers from the keras library.
11.	Define a sequential model and call it myNetwork.
12.	Reshape the images from 28x28 to one column with 784 neurons (flattening) (use 2 methods, one from the book and one from the 20-minute video).
13.	Also, please normalize the image by dividing the image by 255 (use 2 methods, one from the book and one from the 20-minute video).
14.	Add one hidden layer that has 512 neurons, using ‘relu’ activation function.
15.	Add another hidden layer that has 128 neurons, using ‘relu’ activation function.
16.	Add the last layer as a 10-neuron dense layer that uses the ‘softmax’ as the activation function. Why we use softmax for the last layer? How does it work under the hood?
17.	Use the following two settings for the compiler and run them separately and see what the differences are. 
•	Optimizer   adam,  loss 'sparse_categorical_crossentropy', metrics[‘accuracy’]
•	Optimizer   ramsprop,  loss 'categorical_crossentropy', metrics[‘accuracy’]
18.	Now after the compilation, please try to find the pattern using the fit command. The epochs need to be 10 for this example.
19.	How do you compare the fashion_MNIST with what we learned in the class using the MNIST? What can we infer from the differences in the accuracy? What could be the reasons for that?
20.	Use the evaluate to calculate the achieved accuracy and loss over the test images and labels. Do we have overfitting? 


### link for the youtube video that I explain the code 

https://youtu.be/PDdcDg1kZno 
