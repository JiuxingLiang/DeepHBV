# DeepHBV
DeepHBV was designed for detection of HBV virus in DNA integration by deep learning. The data provided here is for the model of DeepHBV with HBV integration sequences + TCGA Pan Cancer.

Run ‘Data_Process.py’ to get one-hot encoding test data and labels.
Run ‘DeepHBV_Test.py’ to detect DNA sequence of HBV virus.

Framework:
DeepHBV framework model contains input layer, 1st convolution1D layer, 1st max pooling layer, 2nd convolution1D layer, 2nd max pooling layer, 1st dropout layer, 2nd dropout layer, attention layer, 1st dense layer (fully connected layer), 2nd dense layer, concatenate layer, classifier layer.

Dependency:
Keras library 2.2.4. 
scikit-learn 0.22. 

If you have any questions, please contact me.

Email: liangjiuxing@m.scnu.edu.cn
