# Multiclass-dog-breed-clssification
This notebook builds an end-to-end multi-class classifier using TensorFlow 2.0 and TensorFlow Hub.

1.Problem Definition
* Identiying dog breed given the image of a dog.

2.Data
* The data used is from Kaggle https://www.kaggle.com/c/dog-breed-identification/data

3.Evaluation
* Submissions are evaluated on Multi Class Log Loss between the predicted probability and the observed target.

* Submission File For each image in the test set, we must predict a probability for each of the different breeds.

https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

4.Features
* Some information about the data.

a. Unstructured data, so its best to use deep learning/transfer learning methods.
b. There are 120 different dog breeads to classify.
c. There are 10000+ images in the training set. (these images have labels)
d. There are 10000+ images in the test set. (these images have no labels)
