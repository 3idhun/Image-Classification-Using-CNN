<h1>Mamukka Lalettan Classifier</h1>
This repository contains code for training a convolutional neural network (CNN) to classify images of malayalam actors Mammootty and Mohanlal. The classifier distinguishes between the two actors and provides predictions with high accuracy.

<h2>Disclaimer</h2>
<b>The images used in this project have been collected from various sources from the internet and are used solely for educational purposes. We do not claim ownership of these images, and they are included here only to demonstrate the functionality of the classifier.</b>

<h2>Overview</h2>
The classifier is built using the Keras deep learning framework with a TensorFlow backend. It utilizes a CNN architecture to extract features from images and make predictions based on those features.

<h2>Dataset</h2>
The training and testing data consist of images of Mamukka and Lalettan collected from various sources. The dataset is divided into two directories: train and test, each containing subdirectories for each actor.

<h2>Model Architecture</h2>
The CNN model consists of three convolutional layers followed by max-pooling layers, a dropout layer for regularization, and fully connected layers for classification. The model is trained using the Adam optimizer with a learning rate of 0.000001.

<h2>Evaluation</h2>
The model achieves a training accuracy of 90.22% and a validation accuracy of 92.50% after 500 epochs of training. Evaluation metrics such as precision, recall, and F1-score demonstrate the model's effectiveness in distinguishing between Mamukka and Lalettan.

<h2>Prediction</h2>
The trained model can be used to predict the actor in unseen images.

<h2>Usage</h2>
<b>To use the classifier, follow these steps:</b>

<h3>Clone the repository:</h3>
git clone https://github.com/3idhun/image-classification-using-CNN.git

<h3>Navigate to the project directory</h3>
cd mamukka-lalettan-classifier

<h3>Install the required dependencies</h3>
pip install -r requirements.txt

<h3>Train the model</h3>
python train.py

<h3>Evaluate the model</h3>
python evaluate.py

<h3>Make predictions</h3>
python predict.py path/to/image.jpg

<h2>License</h2>
This project is licensed under the MIT License - see the LICENSE file for details.
