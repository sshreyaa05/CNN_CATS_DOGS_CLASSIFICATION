### CNN Cats vs Dogs Classification

#### Overview:
This project focuses on classifying images of cats and dogs using a Convolutional Neural Network (CNN). The process includes unzipping the dataset, preparing image paths, and preprocessing the images for training. Using an ImageDataGenerator, the data is augmented and split into training and testing sets. The CNN model is then built, trained, and evaluated on the test data, achieving a test accuracy of 0.5.

#### Steps:

1. Dataset Upload and Unzipping:
Uploaded a zipped folder containing the dataset and unzipped it.

2. Data Preprocessing:
Manually created paths for images, rescaled them, and preprocessed using ImageDataGenerator for augmentation.

3. Train and Test Data Generation:
Used ImageDataGenerator to generate and stored the training and test images.

4. CNN Model Construction:
Built a CNN model with convolutional, pooling, and fully connected layers.

5. Model Training and Prediction:
Fitted the model on training data, and evaluated it on both train and test data to predict image classes.

6. Results:
The model achieves a test accuracy of 0.5 in classifying cats and dogs.
