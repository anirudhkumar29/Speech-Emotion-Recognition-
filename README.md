# Speech-Emotion-Recognition-

**Speech Emotion Detection using Python Deep Learning**
This repository contains code for a Speech Emotion Detection project implemented using Python and deep learning techniques. The project utilizes the RAVDESS dataset, which is a commonly used dataset for speech emotion analysis.

**Introduction**
Speech Emotion Detection is the process of recognizing the underlying emotional state or sentiment from spoken words. It has various applications, such as in customer service, healthcare, and human-computer interaction. This project aims to build a model that can accurately classify emotions from speech signals.

The project utilizes deep learning algorithms implemented in Python, specifically using popular libraries such as TensorFlow and Keras. The RAVDESS dataset, which consists of emotional speech recordings from different actors, is used to train and evaluate the model.

**Prerequisites**
Before running the code in this repository, make sure you have the following dependencies installed:

Python (version 3.6 or higher)
TensorFlow (version 2.0 or higher)
Keras (version 2.3 or higher)
NumPy
pandas
librosa
matplotlib
You can install the required dependencies using the following command:

**bash**
pip install -r requirements.txt

**Dataset**
The RAVDESS dataset (Ryerson Audio-Visual Database of Emotional Speech and Song) contains speech recordings by professional actors, expressing various emotions. It consists of 24 actors (12 male, 12 female) speaking in different emotional states such as calm, happy, sad, angry, etc.

To use the RAVDESS dataset, please visit the official website and follow the instructions for downloading and organizing the dataset: RAVDESS Dataset

Once you have downloaded and organized the dataset, make sure the file structure is as follows:

Copy code
dataset/
├── Actor_01/
│   ├── 03-01-01-01-01-01-01.wav
│   ├── 03-01-01-01-01-02-01.wav
│   └── ...
├── Actor_02/
│   ├── 03-01-02-01-01-01-02.wav
│   ├── 03-01-02-01-01-02-02.wav
│   └── ...
├── ...
└── Actor_24/
    ├── 03-01-08-01-01-01-24.wav
    ├── 03-01-08-01-01-02-24.wav
    └── ...

**Data set** - https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio
