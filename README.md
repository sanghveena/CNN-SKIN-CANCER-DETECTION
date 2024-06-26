# CNN-SKIN-CANCER-DETECTION
# CNN_assignment To build a CNN based model which can accurately detect melanoma.
# CNN-MELANOMA
Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
Motivation: To create a multiclass classification model using a custom convolutional neural network in tensorflow

Data Summary:

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to
the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

1. Actinic keratosis 2.Basal cell carcinoma 3.Dermatofibroma 4.Melanoma 5.Nevus 6.Pigmented benign keratosis 7.Seborrheic keratosis 8.Squamous cell carcinoma 9.Vascular lesion
   NOTE:

You don't have to use any pre-trained model using Transfer learning. All the model building processes should be based on a custom model.
Some of the elements introduced in the assignment are new, but proper steps have been taken to ensure smooth learning. You must learn from the base code provided and implement the same for your problem statement.
The model training may take time to train as you will be working with large epochs. 

Project Pipeline Data Reading/Data Understanding → Defining the path for train and test images Dataset Creation→ Create train & validation dataset from the train directory with a batch size of 32.
Also, make sure you resize your images to 180*180. 
Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset Model Building & training : Create a CNN model, which can accurately detect 9 classes 
present in the dataset. While building the model rescale images to normalize pixel values between (0,1).The RGB channel values are in the [0, 255] range. Here, it is good to standardize values to be in the [0, 1]
Choose an appropriate optimiser and loss function for model training Train the model for ~20 epochs Write your findings after the model fit, 
see if there is evidence of model overfit or underfit Choose an appropriate data augmentation strategy to resolve underfitting/overfitting Model Building & training on the augmented data :
Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1). Choose an appropriate optimiser 
and loss function for model training Train the model for ~20 epochs Write your findings after the model fit, see if the earlier issue is resolved or not? **Class distribution: ** Examine the current 
class distribution in the training dataset Which class has the least number of samples? Which classes dominate the data in terms of the proportionate number of samples? 
Handling class imbalances: Rectify class imbalances present in the training dataset with Augmentor library. Model Building & training on the rectified class imbalance data: Create a CNN model,
which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1). Choose an appropriate optimiser and loss function for 
model training Train the model for ~30 epochs Write your findings after the model fit, see if the issues are resolved or not? The model training may take time to train and hence you can use Google colab.

CONCLUSION 
There are 9 classes of skin cancer but not evenly distributed , class melanoma and pigmented benihen keratosis are having high number of images and class seborheic keratosis has least images.
the model performed well with train and validation data.

tools used 
-keras from tensorflow
-Augmentor

created by sanghveena 
