# Bird-Image-Classification

An image classification model capable of predicting 20 bird species is to be built using the [Bird Species dataset](https://www.kaggle.com/datasets/umairshahpirzada/birds-20-species-image-classification/data) from Kaggle.

The dataset is compromised of:
- 3208 training images
- 100 test images (5 images per species)
- 100 validation images (5 images per species)
- Each image is of size 224 x 224 x 3 color in JPG format

The dataset also provides a folder with 6 images to predict which will be used to evaluate the performance of the final model.

This project will create a model based off the VGG16 pretrained model from tensorflow.keras.applications. The accuracy will be monitored in hopes of achieving a model performance of atleast 85%.
The final model will be saved and implemented into an output function for use on the 6 prediction images.
