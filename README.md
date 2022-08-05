# CIFAR_10_CNN_Model

1.Imported required libraries 
2.Loaded the CIFAR-10 dataset and splitted the dataset into test and train 
3.Preprocessed input data by reducing input size of X_train and X_test by 225  and flatten the y_train and y_test  
4.Built Convoultion Network Model using 'Adam' as optimizer, loss as 'sparse categorical crossentropy' and metrics as accuracy
5.Fitted the training data on the model with epoch of 20 6.To improve accuracy used data augmentation again fitted the newly made data into our model
7.Successfully built model with the Train accuracy of 93.87 % and Test accuracy of 87.07 % and tested the model with a test image  and saved the model
