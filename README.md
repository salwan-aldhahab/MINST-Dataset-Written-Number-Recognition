MNIST-Dataset-Written-Number-Recognition
This project demonstrates a handwritten digit recognition application using the MNIST dataset and a trained neural network model. The application is built using Python, Pygame, OpenCV, and Keras.

Table of Contents
* Introduction
* Requirements
* Installation
* Usage
* Model Training

- Introduction
This project uses a pre-trained neural network model to recognize handwritten digits drawn on a Pygame canvas. The model is trained on the MNIST dataset, which consists of 28x28 grayscale images of handwritten digits from 0 to 9.

- Requirements
1- Python 3.6 or higher
2- Pygame
3- OpenCV
4- Keras
5- TensorFlow
6- NumPy

- Installation
Clone the repository:
git clone https://github.com/yourusername/MNIST-Dataset-Written-Number-Recognition.git
cd MNIST-Dataset-Written-Number-Recognition

Install the required packages:
pip install pygame opencv-python keras tensorflow numpy

Download the pre-trained model:
Important ---> Ensure you have the bestmodel.keras file and change the directory in the app code to ensure it the app runs without any errors.

- Usage
1- Run the application: python app.py
2- Draw a digit: Click and hold the mouse button to draw a digit on the canvas.
3- Predict the digit: Release the mouse button to see the predicted digit displayed with a red boundary around the drawn area.
4- Clear the canvas: Press the "r" key to clear the canvas and start drawing a new digit.

- Model Training: Jupyter Notebook file provided for model training
