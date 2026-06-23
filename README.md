[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/114Osvf4MMC-MKV-y8GTzG_Y9c1OlXhqM?usp=sharing)

# 🎙️ Emotion Recognition from Speech

An deep learning project that recognizes human emotions from speech audio.

## 📌 Task
CodeAlpha Internship — Task 2

## 🧠 Approach
- Dataset: RAVDESS (1440 audio files, 8 emotions)
- Feature Extraction: MFCCs (Mel-Frequency Cepstral Coefficients)
- Model: Convolutional Neural Network (CNN)

## 🎭 Emotions Detected
`neutral` `calm` `happy` `sad` `angry` `fearful` `disgust` `surprised`

## 🛠️ Tech Stack
- Python, Librosa, TensorFlow/Keras
- Scikit-learn, NumPy, Pandas, Matplotlib

## 🚀 How to Run
1. Open `emotion_recognition.ipynb` in Google Colab
2. Add RAVDESS dataset via Kaggle API
3. Run all cells — enable T4 GPU for faster training

## 📊 Results
- Test Accuracy: ~70%
- Includes confusion matrix and per-class classification report
