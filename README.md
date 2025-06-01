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

![image](https://github.com/user-attachments/assets/479a5633-3a79-4bd4-b090-98882219d061)

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

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   
3.**Prepare the Dataset**

4.**Run the file**

---

## 🔭 Future Scope

The project can be extended and improved in the following directions:

- 🎯 **Advanced Neural Architectures**:  
  Explore models like LSTM, Bi-GRU, or Transformers to better capture the temporal dynamics in speech.

- 🤝 **Multimodal Emotion Recognition**:  
  Combine speech with facial expressions, gestures, or physiological signals (like EEG) for more accurate emotion detection.

- 🧪 **Cross-Corpus Validation**:  
  Test the model across datasets such as EMODB or IEMOCAP to evaluate generalizability to different speakers, accents, and environments.

- 🔊 **Data Augmentation Techniques**:  
  Apply methods like pitch shifting, time-stretching, or noise injection to make the model robust against real-world conditions.

- ⚡ **Real-Time Implementation**:  
  Optimize the system for low latency to enable use in live applications like call centers, virtual assistants, or mental health monitoring.

- 📱 **Edge Deployment**:  
  Reduce model size using pruning or quantization and deploy on edge devices such as Raspberry Pi, smartphones, or IoT systems.

- 🧠 **Explainability in AI (XAI)**:  
  Integrate explainable AI techniques to understand which audio features influence emotion prediction and increase model transparency.

- 🌐 **Cultural and Linguistic Adaptation**:  
  Adapt the system for different languages and cultural contexts where emotional expression varies significantly.

- 🧍‍♂️ **Personalized Models**:  
  Train individual-specific models that adapt to a user's vocal and emotional style, improving accuracy and user experience.

- 🤖 **Human-Robot Interaction**:  
  Embed the emotion recognition engine into robots or virtual agents to support emotionally intelligent dialogue systems.

---

**Conclusion**

Our MLP-based emotion recognition system demonstrates
three key advancements:
Feature Fusion Effectiveness: Combining spectral (MFCC),
harmonic (Chroma), and perceptual (Mel) features yields
15-25% accuracy improvements over individual features.
Efficient Architecture: The 4-layer MLP achieves 74.48%
accuracy with only 152k parameters, enabling real-time
deployment (4.7ms per sample).
Robust Generalization: Speaker-independent evaluation
shows consistent performance across genders (Δaccuracy <
2.3%) and intensity levels.





