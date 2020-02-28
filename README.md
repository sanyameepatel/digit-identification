# Identification of Handwritten Digits
Identifying Handwritten Digits using PyTorch
Logistic Regression is a very commonly used statistical method that allows us to predict a binary output from a set of independent variables. The various properties of logistic regression are used and implementation is done in PyTorch. 
In our dataset, the image size is 28*28. Thus, our input size is 784. Also, 10 digits are present in this and hence, we can have 10 different outputs. Thus, we set num_classes as 10. Also, we shall train for five times on the entire dataset. Finally, we will train in small batches of 100 images each so as to prevent the crashing of the program due to memory overflow.

Another implementation using tensorflow for better accuracy can be found in this repository.
