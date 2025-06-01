# Emotion-Detector-From-Audio-Input

# 🎤 Emotion Recognition from Speech  
**Using Audio Feature Extraction and Neural Networks**  
*By Aryaman Parashar Behera and Nirmal Praful Modi*  

---

## 📌 Overview
This project implements a deep learning-based system that classifies emotions from human speech using audio features. It aims to enhance human-computer interaction by enabling machines to understand emotional cues embedded in speech signals.

The model uses **MFCCs**, **Chroma Vectors**, and **Mel Spectrograms** with a Multi-Layer Perceptron (MLP) classifier to detect four emotional states:  
- 😌 Calm  
- 😊 Happy  
- 😱 Fearful  
- 🤢 Disgust  

Achieved **74.48% accuracy** on the RAVDESS dataset.

---

## 🧠 Key Features
- 🎙️ Audio Preprocessing: Amplitude normalization, spectral noise reduction  
- 🔍 Feature Extraction: MFCC (40), Chroma (12), Mel Spectrogram (128)  
- 🧮 Model: 4-layer MLP (200-200-100-50 nodes) using ReLU and Softmax  
- ⚙️ Optimizer: Adam with adaptive learning rate and early stopping  
- 📊 Evaluation: Confusion matrix and ablation studies for architecture tuning  

---

## ⚙️ Tech Stack

| Area        | Technologies |
|-------------|--------------|
| Language    | Python       |
| Libraries   | librosa, scikit-learn, numpy, matplotlib |
| Model       | MLPClassifier (scikit-learn) |
| Dataset     | RAVDESS      |
| Environment | Jupyter / VS Code |

---

## 🧪 Skills Gained

- Audio signal processing and speech feature extraction  
- Multi-layer neural network design and tuning  
- Dataset preparation and stratified splitting  
- Experimental design and ablation studies  
- Optimization techniques like early stopping, L2 regularization  
- Model evaluation through metrics and visualization  

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/emotion-speech-recognition.git
   cd emotion-speech-recognition


![image](https://github.com/user-attachments/assets/479a5633-3a79-4bd4-b090-98882219d061)

