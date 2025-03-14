Files explained:-

1.ANN_MODEL_FINAL(1)-Contains code for standardization decomposition of input and its visualization  log transformation standardization of target as well for training the model and saving the model
2. prediction.ipynb- uses the saved model where we may give any one value as input and get the output corresponding to it.
3.scaler.pkl- standardizer used for input features 
4. pca – pca component used on input features for reducing/decomposing them
5. Output scaler- used for standardizing the target variable.
6.best lstm model-  Saved model based on lstm which had r2 score of 54 percent. This has been used in the app.
7. Model.h5- Based on ANN , best model so far had an r2 score of 74 percent 
8. Appcode.ipynb – Used to run the app before that we need to unzip ankit file . 
9.ankit zip file- contains all the necessary files, models ,styling for flask app


Dependencies

1.For using model we need to have right version of tensorflow and keras. TensorFlow Version: 2.18.0 and Keras Version: 3.8.0
2.To use the app go on ngrok and register and get authentication code and enter it in the code and once we run the entire code the hyperlink created need to be pasted on chrome
