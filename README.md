# 🎙️ Emotion Detection from Speech

A Speech Emotion Recognition (SER) project that classifies human emotions from speech recordings using Deep Learning.

## Project Overview

This project detects emotions from speech audio files such as:

- 😊 Happy
- 😢 Sad
- 😠 Angry
- 😐 Neutral
- 😨 Fear
- 🤢 Disgust
- 😲 Surprise

The model is trained on a speech emotion recognition dataset and can predict the emotion from any supported WAV audio file.

##  Repository Structure

```
Emotion-Detection-Speech-/
│
├── models/                 # Trained model files
├── HBD.wav                 # Sample audio
├── demo_audio.wav          # Demo file
├── male.wav                # Demo file
├── README.md
```

##  Dataset

The dataset is hosted on Hugging Face.

👉 https://huggingface.co/datasets/nsr51324/Speech_Emotion_Recognition

Dataset Information

- Format: WAV Audio
- Size: 1.07 GB
- Samples: 2556 audio files
- Task: Speech Emotion Recognition

## Features

- Speech Emotion Recognition
- Deep Learning Model
- Audio Classification
- WAV Audio Support
- Ready for inference

## Technologies Used

- Python
- TensorFlow / Keras
- Librosa
- NumPy
- Scikit-learn
- Hugging Face Datasets

## How to Run

Clone the repository

```bash
git clone https://github.com/nsr51324/Emotion-Detection-Speech-.git
```

Install requirements

```bash
pip install -r requirements.txt
```

Run prediction

```bash
python predict.py
```

---

## Model

The trained model is available inside the `models/` directory.

## Author

Nasr Mohamed

AI Developer | Machine Learning | Deep Learning

GitHub:
https://github.com/nsr51324

Hugging Face:
https://huggingface.co/nsr51324
