# Face Mask Detection using Keras
This project demonstrates the implementation of a face mask detection system using Python, leveraging the Keras, TensorFlow, and OpenCV libraries. The system is designed to identify whether a person is wearing a mask or not using deep learning techniques.
## Project Structure
The project is organized into several key stages, each documented in corresponding Jupyter notebooks:
1. Data Preprocessing (1.0 data preprocessing.ipynb):
This notebook handles the initial data preprocessing steps. It includes loading the dataset, resizing images, normalizing pixel values, and preparing the data for training. The preprocessed data is saved as data.npy and target.npy.
2. Training the CNN (2.0 training the CNN.ipynb):
This notebook outlines the process of building and training a Convolutional Neural Network (CNN) using Keras and TensorFlow. The model is trained on the preprocessed dataset to classify images into masked and unmasked categories.
3. Mask Detection (3.0 detecting Masks.ipynb):
This notebook covers the implementation of the face mask detection system. It involves loading the trained CNN model and applying it to detect masks in real-time using OpenCV for video capture.
## Dataset
The dataset used in this project is originally prepared by Prajna Bhandary and is available on GitHub. It contains images of people with and without face masks, categorized into appropriate folders.
## Dependencies
To run this project:
1. Clone this repository to your local machine.
```bash
git clone https://github.com/Gayathri-Selvaganapathi/face_mask_detection.git
```
2. Create the environment
```bash
conda env create -f environment.yml
```
3. Running the Project
    * Data Preprocessing: Start by running the 1.0 data preprocessing.ipynb notebook to preprocess the data.
    * Model Training: Then, run the 2.0 training the CNN.ipynb notebook to train the CNN model.
    * Mask Detection: Finally, use the 3.0 detecting Masks.ipynb notebook to test the model and detect face masks in real-time.
