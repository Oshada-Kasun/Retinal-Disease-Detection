# Retinal-Disease-Detection
This project is designed for automated pathology detection for Medical Images in a relalistic setup, each image may have multiple pathologies/disorders.
The goal, is to design models and methods to predictively detect pathological images and explain the pathology sites in the image data.

### * ResNet50 used as baseline model with initial weights from ImageNet and will retrain all layers for this project.
### * Augmenting images, will have more data and make the training set become more regularize. In Keras ImageDataGenerator has used to feed image to the model.
### * Instead of average pooling to try with max pooling.
### * Two callbacks were added to the training to save the best model on validation set and reduce learning rate during training.
### * Visualizing the heatmap/saliency/features to demonstrate what regions of interest contribute to Diabetic Retinopathy and Glaucoma, respectively.
### * Using the unlabelled data set in the 'test' folder augmenting the training data (semi-supervised learning) and reporting the variation in classification performance on test data set.



