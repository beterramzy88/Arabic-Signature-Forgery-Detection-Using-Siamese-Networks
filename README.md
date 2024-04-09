# Arabic-Signature-Forgery-Detection-Using-Siamese-Networks
# Overview
This GitHub repository contains a deep learning model that can detect
signature forgeries accurately as Many people still use their handwritten
signatures as a primary form of
authentication for a wide range of
transactions
# Dataset
Each student have two folders inside the dataset. The first
folder  contain at least 15 different images of the student’s real
Arabic signature, and the folder’s name is the student’s ID.
The second folder contain at least 10 different images of the
student’s forged signature, and its name is the student’s ID
with “_forged” (e.g. 20200000_forged) the result is a total of about 750 images
# project steps
1-Loading the raw images

2-data preprocessing
    .reshaping size of images, normalizing images and solving the prolem of undersapmling

3-generating pairs of images
    .generating pairs of images to be suitable for siamese network the pairs are postitive 
    pairs that are consist of two original images and negative pairs that consist of one 
    original image and one forged image.

4-split the dataset into train and test sets

5-building siamese network with binary cross-entropy as the loss function.

6-Train the model on the train set.

7- Evaluate the performance of the model on the test set using different
metrics.


    



