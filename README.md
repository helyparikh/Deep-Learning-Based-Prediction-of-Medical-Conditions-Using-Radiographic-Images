# Deep-Learning-Based-Prediction-of-Medical-Conditions-Using-Radiographic-Images
# Abstract
Dataset Link: https://physionet.org/content/mimic-cxr-jpg/2.0.0/

Predicting and diagnosing diseases reliably and correctly have been challenging tasks in the
healthcare domain. Early machine learning techniques such as Support Vector Machines (SVM)
and decision trees, failed to yield satisfactory results from complex raw data. However, recent
deep learning approaches such as Convolutional Neural Networks (CNN), have been proven to be
effective methods for analyzing visual imagery in image classification and medical image analysis.
In this project, we demonstrated the suitability of using a deep learning approach in the healthcare
domain, where a CNN model takes a medical image as its input and passes it through a series of
convolutional, nonlinear pooling and fully connected layers to produce the output. We used a
medical data set containing thousands of radiographic images, which are chest x-rays for
identifying acute and chronic cardiopulmonary conditions. A test script has been developed to
preprocess the raw data set, and divide processed data set into small batches as inputs of an CNN
model for the training purpose. The CNN model contains multiple inputs as each observation
comes with a couple of images that are mapped to one of 14 target labels corresponding to various
medical conditions. Different parameters of gradient decent are tested in order to create a
reasonable loss function that decreases the global optimum threshold value and increases the
accuracy. A learning rate scheduler has also been developed to adjust the loss function when the
CNN model is stuck at a local optimum threshold. The experimental results show that the classifier
can achieve 86.8% training accuracy and 86.6% validation accuracy. This indicates that our deep
learning model not only performs well for the training data set, but can also effectively predict
medical conditions using new data points from the test data set. 
