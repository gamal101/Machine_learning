Emotion Recognition using HOG Features
This repository contains code for performing emotion recognition using Histogram of Oriented Gradients (HOG) features and Logistic Regression.

Overview
The project aims to:

Perform emotion classification on facial images using HOG features.
Train Logistic Regression models on raw pixel data and extracted HOG features.
Evaluate model performance using accuracy metrics, confusion matrices, and ROC curves.
Requirements
Python 3.x
Libraries:
pandas
scikit-learn
skimage
numpy
seaborn
matplotlib
Setup
Clone the repository:
bash
Copy code
git clone <repository-url>
cd emotion-recognition-hog
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Download the dataset:
Ensure you have the dataset dataset.csv available.

Run the code:
Execute the main script:

bash
Copy code
python emotion_recognition.py
Usage
emotion_recognition.py contains the main code for:
Loading the dataset.
Extracting HOG features.
Training Logistic Regression models.
Evaluating model performance.
Visualizing results.
Results
The code generates:
Accuracy scores for models trained on raw data and HOG features.
Confusion matrices for both models.
Receiver Operating Characteristic (ROC) curve for HOG-based model.
Note
Update paths or filenames as necessary within the code.
Ensure the dataset is correctly formatted and accessible.
Author
Jamal Sayed

