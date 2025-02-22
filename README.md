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

Challenges Faced:
Limited Computational Capacity: Due to the hardware limitations, training the model on a larger dataset was not feasible. This restricted the ability to experiment with more complex architectures or longer training times, which could have improved the model's performance further.

Dataset Size: Only 10,000 images were used for training and validation, which is a relatively small dataset for image classification tasks. While this size was sufficient to achieve a decent level of accuracy, a larger dataset could have improved the model's ability to generalize and reduced overfitting.

Model Accuracy: While the model performs fairly well, it is not perfect. Given the dataset's size and the computational limitations, the accuracy is limited, and the model does not achieve 100% precision in classifying images. More training time, data, and possibly a more advanced architecture would likely be needed to achieve higher accuracy.
