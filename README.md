# Street View Housing Number Recognition
## Objective
The objective of this project is to develop a Convolutional Neural Network (CNN) model that accurately recognizes and classifies digits from images of house numbers taken from street views. The model aims to achieve high accuracy in predicting the digits present in these images, making it useful for applications such as automated address recognition systems.

## Brief Description
This project leverages the SVHN (Street View House Numbers) dataset, which consists of grayscale images of house numbers in various conditions. The process includes:

### Data Preprocessing: 
Loading and preparing the dataset, including normalizing the images and encoding the labels.
### Exploratory Data Analysis:
Visualizing the class distributions and examples of digits to understand the dataset better.
### Model Development: 
Building multiple CNN architectures, employing techniques like batch normalization and dropout to enhance performance and prevent overfitting.
### Model Training:
Training the models on the training set and validating on a separate validation set, monitoring metrics such as accuracy and loss.
### Model Evaluation:
Testing the models on the test dataset, evaluating performance through accuracy scores, confusion matrices, and classification reports.
## The main models developed include:

A primary CNN model with several convolutional and dense layers.
An improved model incorporating batch normalization.
A further enhanced model with additional convolutional layers.
## Conclusion
The project successfully demonstrated the capabilities of CNNs in recognizing and classifying digits from street view images. The final model achieved a commendable accuracy on the test set, showcasing the effectiveness of deep learning techniques for image recognition tasks. Future improvements could involve experimenting with advanced architectures like ResNet or using transfer learning with pre-trained models. This project not only highlights the importance of image data in machine learning but also provides a foundation for developing systems that can interpret street-level data in real-time applications.
