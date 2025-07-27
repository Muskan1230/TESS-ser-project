# TESS-ser-project

**Speech Emotion Recognition using Ensemble Learning** This project focuses on recognizing human emotions from speech using a machine learning-based approach. It uses feature extraction techniques and applies multiple classifiers with a Voting Ensemble Model to improve accuracy.

**Dataset Used:** TESS (Toronto Emotional Speech Set) → Contains 2800 audio files in .wav format, spoken by two female actors and categorized into 7 emotions (angry, disgust, fear, happy, pleasant surprise, sad, neutral).

**Objective:-** To build a Speech Emotion Recognition (SER) system using extracted audio features and train it using SVM, KNN, and Random Forest, combined through an ensemble Voting Classifier.

**Methodology:-** Feature Extraction Extracted key audio features using librosa: MFCC (Mel-frequency cepstral coefficients) ZCR (Zero Crossing Rate) HNR (Harmonics to Noise Ratio) Spectral Contrast

**Model Training & Evaluation Used GridSearchCV for hyperparameter tuning on:** Support Vector Machine (SVM) K-Nearest Neighbors (KNN) Random Forest Classifier Combined best models using a Voting Classifier

**Testing-** Evaluated on unseen test data with accuracy, classification report, and confusion matrix.

**Results:-** Ensemble model performed better than individual classifiers with accuracy of 99.91%. High accuracy achieved on emotion classification

**Project Structure Speech_Emotion_Recognition** Contains downloaded datasets (e.g., RAVDESS) ├── features/  Extracted features like MFCC, ZCR, HNR, Spectral Contrast ├── models/  Trained model files or model scripts ├── main.py Main script to run training, testing, and evaluation ├── requirements.txt├── README.md

Note: The data/ folder is not included in the repository. Please download the dataset manually from the official source. License: This project is private and not open for reuse.
