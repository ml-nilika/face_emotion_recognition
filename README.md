#  Face Emotion Recognition Project

This is a deep learning project I built to recognize human facial emotions in real-time using a webcam, powered by **Python**, **OpenCV**, and **TensorFlow/Keras**.

##  Dataset

I used the [Facial Expression Recognition Dataset](https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset) from Kaggle. It includes:
- Grayscale face images categorized into 7 emotions
- Training and testing sets in the following format:
  - `images/train/`
  - `images/test/`

I used these images to train a CNN model to classify facial expressions.

##  Tools & Libraries Used

- Python
- NumPy
- OpenCV
- TensorFlow / Keras
- Matplotlib (for plotting)
- CNN (Convolutional Neural Network)

##  What This Project Does

- Preprocesses face images (resizing, grayscale, normalization)
- Trains a CNN to classify emotions
- Loads the trained model and uses webcam input to:
  - Detect a face
  - Predict the emotion in real time
  - Display the predicted label and confidence

##  How to Use

1. Clone the repo or download the code
2. Install the required libraries:


##  Whai I learned
Through this project, I learned:
How to preprocess image data for CNNs

How to train a model using TensorFlow/Keras

How to use OpenCV for face detection and real-time webcam feed

How to save and load models using .h5 and .json
