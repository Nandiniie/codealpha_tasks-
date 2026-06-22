# 🎙️ Emotion Recognition from Speech

Detects human emotions from audio using Machine Learning.

## Emotions Detected
Neutral | Calm | Happy | Sad | Angry | Fearful | Disgust | Surprised

## Tech Stack
- Python, Google Colab
- Librosa (MFCC, Mel Spectrogram, Chroma features)
- Scikit-learn (MLP Classifier)
- Dataset: RAVDESS (1440 audio samples)

## Results
- Accuracy: XX% (put your actual accuracy here)
- Evaluation: Confusion Matrix + Classification Report

## How to Run
1. Open the .ipynb file in Google Colab
2. Run all cells top to bottom
3. Model predicts emotion from any .wav file

## Project Structure
├── emotion_recognition.ipynb  # Main notebook
├── emotion_model.pkl           # Trained model
├── scaler.pkl                  # Feature scaler
└── label_encoder.pkl           # Label encoder
