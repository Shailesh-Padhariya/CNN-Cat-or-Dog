CNN - Cat or Dog Classifier
Overview:
This project uses a Convolutional Neural Network (CNN) to classify images of cats and dogs. The model is trained on a labeled dataset of cat and dog images. By preprocessing the images and applying data augmentation techniques, the goal is to create a model that can accurately predict whether a given image contains a cat or a dog.

The dataset used in this project contains images organized into two classes: cats and dogs. The model's performance is evaluated using a separate test set, and it is capable of classifying new images as either "cat" or "dog."
datset link for training and validation: https://drive.google.com/drive/folders/1IOK195J-IswP0e9pJKtNm7ZXNL559IgY?usp=drive_link
Required Libraries:
This project requires the following Python libraries:

TensorFlow: For building and training the CNN model.
NumPy: For handling arrays and numerical operations.
Keras: For building the neural network layers.
ImageDataGenerator: For image preprocessing and augmentation.


Data Preprocessing:
The dataset is divided into training and testing sets, each containing two subfolders: cats and dogs. The images are resized to a consistent size (64x64 pixels), normalized, and augmented using techniques such as horizontal flipping, zooming, and shearing to improve model generalization.

How It Works:
Training the Model: The CNN is trained using the training dataset, and the model is validated on the test dataset.
Prediction: Once trained, the model can classify new images as either a cat or a dog.
Use Case: Given a new image, the model will predict the class (cat or dog) based on its learned features.
