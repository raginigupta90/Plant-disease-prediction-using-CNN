# Plant Disease Prediction using CNN

This project detects and classifies plant diseases from leaf images using a Convolutional Neural Network (CNN) model.

# Features

Identifies plant diseases from leaf images.

Uses image preprocessing (resizing, normalization).

Trains a deep learning CNN for multi-class classification.

Provides accurate predictions for early plant disease detection.

# Technologies Used

Python

TensorFlow/Keras – CNN implementation

NumPy, Pandas – Data processing

Matplotlib, Seaborn – Visualization

OpenCV – Image handling (optional)

# Installation

Clone the repository:

git clone https://github.com/yourusername/plant-disease-prediction.git
cd plant-disease-prediction


Install dependencies:

pip install -r requirements.txt

# Usage

Prepare the dataset (train & test folders with labeled plant disease images).

Train the model:

python train_model.py


Predict plant diseases from new images:

python predict.py --image path_to_leaf_image.jpg

Dataset

Publicly available datasets such as PlantVillage are commonly used.

Each class represents a specific plant disease.

# Model Architecture

Convolutional layers with ReLU activation

MaxPooling layers for feature extraction

Fully connected Dense layers

Softmax activation for multi-class classification

# Example Output

Input: Leaf image of tomato plant

Prediction: Tomato Leaf Blight – 96% confidence

# Future Enhancements

Deploy as a mobile/web app for farmers.

Add real-time prediction via camera input.

Expand dataset for more plant species.
