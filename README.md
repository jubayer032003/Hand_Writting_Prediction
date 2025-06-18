# Handwritten Digit Recognition with CNN (MNIST)

This project uses a Convolutional Neural Network (CNN) to recognize handwritten digits (0–9) from the MNIST dataset. The model is built with TensorFlow and Keras, and achieves over **95% accuracy**.

##Project Overview

- **Dataset**: MNIST (60,000 training and 10,000 test images of 28x28 grayscale digits)
- **Goal**: Accurately classify digit images using a deep learning model
- **Tech Stack**: Python, NumPy, Matplotlib, Seaborn, PIL, TensorFlow, Keras

##Features

- Convolutional Neural Network (CNN) architecture
- Data preprocessing and augmentation
- Dropout for overfitting reduction
- Confusion matrix and training accuracy/loss visualization
- Real handwritten digit prediction using PIL

##Results

- **Accuracy**: Over 95% on the test set
- Clear performance visuals with training curves and confusion matrix
- Real-world digit input tested with custom images

##Installation


```bash
git clone https://github.com/yourusername/handwritten-digit-cnn.git
cd handwritten-digit-cnn
pip install -r requirements.txt
