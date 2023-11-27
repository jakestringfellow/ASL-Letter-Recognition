# ASL-Letter-Recognition

<img align="right" src="" width="360px" alt="picture">

<img align="center" src="" width="360px" alt="picture">

## Introduction:
* This project is designed to recognize hand gestures using the American Sign Language (ASL) alphabet in real time. It includes a hand tracking module, a main application script (main.py), and a model training script (modelTraining.py), all working together to achieve accurate gesture recognition.

## Key Components: 
* handTrackingModule.py: Utilizes MediaPipe for real-time hand landmarks detection and tracking..
* main.py: The core script that integrates the trained CNN model for live gesture prediction using a webcam.
* modelTraining.py: Responsible for building, training, and analyzing the CNN on the Sign-MNIST dataset for hand gesture recognition.

## modelTraining.py Overview
* Data Loading & Preprocessing: Loads and preprocesses the Sign-MNIST dataset, including label adjustments and image normalization.
* Neural Network Architecture: Builds a sequential CNN model with layers optimized for gesture recognition.
* Visualization: Provides visualization of the dataset and training process, aiding in understanding the model's learning and performance.
* Model Training: Compiles and trains the CNN model, employing accuracy metrics and loss functions tailored to the task.
* Model Evaluation & Saving: Evaluates the model's performance on test data and saves the trained model for real-time recognition tasks.
                       
## Technologies used:  
* Python: For scripting and model training.
* TensorFlow & Keras: For building and training the CNN.
* Pandas & NumPy: For data handling and manipulations.
* Matplotlib: For data visualization.

## Installation and Setup: 
* download repository locally
*                         - Have the following files in the current directory for model training and saving: 
                        		- modelTraining.py
                        		- support/signData/sign_mnist_test.csv
                        		- support/signData/sign_mnist_train.csv
                        		- support/sign.names
                      
*			- In Pycharm, run the current file (while in modelTraining.py)
*			- have the following files in the current directory for program running:
				- handTrackingModule.py
  			 	- main.py
				- support/ASL_Model (created by the modelTraining run)
                        	- support/sign.names
*                   	- Run the main file

## Acknowledgements:
* Sign MNIST dataset: https://www.kaggle.com/datasets/datamunge/sign-language-mnist

