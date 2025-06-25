# 🔮 Realm – Real-time Voice Authenticity & Manipulation Detection System

Realm is an AI-powered cybersecurity tool designed to detect fake, manipulated, or AI-generated voices in real-time or from uploaded audio files. With advanced features like watermarking, hidden command detection, and spectrogram-based deep learning models, Realm aims to combat the rising threat of voice deepfakes and voice-based attacks. 🛡️🎙️

---

## 🚀 Features

### 🎤 1. Real-Time Voice Analysis
- Users can speak directly through the system to instantly verify if the voice input is genuine or synthetic.
- Live analysis powered by deep learning models and audio signal processing.

### 📂 2. Upload & Analyze Audio Files
- Upload `.wav`, `.mp3`, or other supported formats.
- Automatically runs tests to detect voice authenticity, manipulation, or hidden threats.

### 🕵️‍♂️ 3. Hidden Command Detection
- Detects covert or embedded commands in the audio often used in stealth attacks.
- Ideal for smart assistants and voice-controlled devices.

### 💧 4. Digital Audio Watermarking
- Embed unique, imperceptible watermarks in voices to authenticate sources.
- Extract and verify these watermarks to ensure content origin and prevent spoofing.

### 📊 5. Spectrogram + Deep Learning
- Audio is visualized into spectrograms.
- Convolutional Neural Networks (CNNs) and other ML models classify audio authenticity with high accuracy.

### 🎬 6. Live Demo Mode
- Interactive demo feature allows users to test the system by speaking live.
- See instant results on whether the voice is real, AI-generated, or altered.

---

## 🧰 Tech Stack

| Component              | Technology                     |
|------------------------|--------------------------------|
| Language               | Python                         |
| Audio Processing       | Librosa, PyDub                 |
| Machine Learning       | PyTorch / TensorFlow           |
| Spectrograms           | Matplotlib, NumPy              |
| Watermarking           | Custom DSP Techniques / APIs   |
| Web Interface (optional) | Streamlit / Flask / React     |

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/realm-voice-analyzer.git
cd realm-voice-analyzer
pip install -r requirements.txt
