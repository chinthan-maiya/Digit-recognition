Contains jupyter notebook with code to recognize digits of mnist dataset.
The MNIST dataset is first loaded from keras.
The 28*28 images are first flattened to get arrays of size 784.
The labels are one-hot encoded.
The model consists of 2 hidden layers with 256 neurons each. 
Batch size of 128 and epochs=10 are chosen to train the model.
Testing is done on the test dataset.
