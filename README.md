# srm-techno-hackathon-2023-

Deep Object Damage Analysis:


To develop an automated system using deep learning techniques for detecting and analyzing damage on cars caused by objects. 
The system uses a convolutional neural network (CNN) to analyze images of damaged cars and identify the location of the damage. The CNN is trained on a dataset of annotated images to improve its accuracy!


PSEUDO CODE

Deep Object Damage Analysis:
To develop an automated system using deep learning techniques for detecting and analyzing damage on cars caused by objects. 
The system uses a convolutional neural network (CNN) to analyze images of damaged cars and identify the location of the damage. The CNN is trained on a dataset of annotated images to improve its accuracy


the link to the actual code can be found [here](https://drive.google.com/drive/folders/18GXoh2G9ECo1kQMzqGq-JwlAEltBpNr5?usp=share_link).


About The Project


The code implements a Convolutional Neural Network (CNN) using the Keras API on top of TensorFlow. The purpose of the model is to classify images of cars into two categories (binary classification): "damaged" or "undamaged". The dataset is split into training and validation sets, and data augmentation is applied to the training set to increase the size of the dataset and improve the robustness of the model. The CNN architecture consists of three Conv2D layers with increasing number of filters, followed by max pooling layers to reduce the size of the feature maps, a Flatten layer to convert the 2D feature maps into a 1D vector, and two fully connected (Dense) layers with ReLU activation functions. The output layer has a sigmoid activation function, which outputs a probability between 0 and 1 for the binary classification. The model is trained using the Adam optimizer and binary cross-entropy loss function, and the accuracy is monitored during training. After training, the model is evaluated on the validation set, and the accuracy is printed. Finally, the model is saved as an h5 file for future use.




