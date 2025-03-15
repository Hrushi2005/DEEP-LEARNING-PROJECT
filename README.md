# DEEP-LEARNING-PROJECT
COMPANY: CODTECH IT SOLUTIONS

NAME: Y.HRUSHI VENKATA TRINADH

INTERN ID::CODHC233

DOMAIN: Data Science

DURATION: 6 WEEEKS

MENTOR: NEELA SANTOSH

This code builds a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify the CIFAR-10 dataset, a set of 60,000 images belonging to 10 categories. The data is first normalized to scale pixel values between 0 and 1 for better model performance. 

The CNN comprises a convolutional layer (`Conv2D`) for feature extraction, followed by a max-pooling layer to downsample the features. Flattening converts the 2D features into a 1D array, which is passed to a dense layer for further processing. The final output layer uses a softmax activation function, providing probabilities for each class.

The model is compiled with the Adam optimizer, sparse categorical crossentropy as the loss function, and accuracy as a metric. It's trained for 5 epochs on a batch size of 64, with the test data used for validation. Post-training, the model's accuracy on the test set is evaluated, and predictions on the first 5 test images are visualized alongside their predicted labels. This end-to-end pipeline demonstrates a basic CNN workflow for image classification.

*output*:https://github.com/Hrushi2005/DEEP-LEARNING-PROJECT/issues/1#issue-2922399804
