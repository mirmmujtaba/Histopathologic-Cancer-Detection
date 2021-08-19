# Histopathologic-Cancer-Detection
In this dataset we are provided with a large number of small pathology images to classify. Files are named with an image id. 
The train_labels.csv file provides the ground truth for the images in the train folder. We are predicting the labels for the images in the test folder. 
A positive label indicates that the center 32x32px region of a patch contains at least one pixel of tumor tissue. Tumor tissue in the outer region of 
the patch does not influence the label. This outer region is provided to enable fully-convolutional models that do not use zero-padding, to ensure 
consistent behavior when applied to a whole-slide image.
