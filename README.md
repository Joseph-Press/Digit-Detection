#Digit Recognizer
Digit recognizer, training a model on the MNIST dataset

Developing a GUI App for users to handwrite digits and recognize the output (currently averages around 50% accuracy, so still in progress)

**In 75 Epochs, we reached a 90% accuracy in train_digit_recognizer.py**

## MNIST
The MNIST dataset contains 60,000 training images of handwritten digits from zero to nine and 10,000 images for testing

In our use, the MNIST dataset has 10 different classes. The handwritten digits images are represented as a 28×28 matrix where each cell contains grayscale pixel value

## Model
Our CNN model works well in this project due to the way that data is represented in grid structures. 

## Prerequisites
numpy, tensorflow, keras, pillow

For eventual gui app: tkinter, pywin32
