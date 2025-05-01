# 🖼️ Image Captioning with Audio Output Using Deep Learning Techniques 🎙️

## 🔍 Project Overview
This project implements a deep learning-based image captioning system that not only generates accurate and descriptive captions for images but also converts them into speech using text-to-speech synthesis. It is designed to improve accessibility for visually impaired individuals by transforming visual content into an audible format.

The system uses the **BLIP (Bootstrapped Language-Image Pre-training)** model for caption generation and **gTTS (Google Text-to-Speech)** for audio output. A user-friendly interface built with **Gradio** allows users to upload images and receive both textual and spoken descriptions.

---

## 🧠 Techniques Used

- **Multimodal Learning**: Combining vision (images) and language (text) representations using the BLIP model.
- **Transfer Learning**: Leveraging pre-trained models (BLIP, CNNs) for efficient training and improved performance.
- **Natural Language Generation (NLG)**: Using Transformers for sequence generation in image captioning.
- **Speech Synthesis**: Using Google TTS (gTTS) to convert generated text into natural-sounding speech.
- **Interactive UI**: Built with Gradio for real-time testing and deployment.

---

## 🛠️ Methodology

### Dataset
- **MS COCO**: Over 120,000 images, each with 5 manually written captions.

### Preprocessing
- Data Cleaning
- Image Normalization (0-1 range)
- Data Augmentation (flipping, rotation, cropping)
- Feature Extraction using CNN encoders (e.g., ResNet)

### Model Architecture
- **BLIP Model**
  - Vision Encoder (CNN)
  - Transformer-based Language Decoder
- **TTS Engine**
  - gTTS (Google Text-to-Speech)
- **Interface**
  - Gradio-based upload and output system

### Training & Optimization
- 20 epochs
- Batch size: 32
- Optimizer: Adam
- Loss: Cross-Entropy
- Regularization: Dropout, Batch Normalization

---

## 📊 Results

| Metric       | Score |
|--------------|-------|
| Accuracy     | 85%   |
| Precision    | 0.82  |
| Recall       | 0.80  |
| F1-Score     | 0.81  |
| AUC (ROC)    | 0.89  |

The system performs robustly on a variety of image types, including realistic, unseen, and mythological categories. The generated captions are both semantically accurate and contextually relevant. The addition of audio output greatly improves the accessibility for blind or visually impaired users.

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/image-caption-audio.git
   cd image-caption-audio
---
## 🧑‍💻 Authors
>Ayush Kumar
>Md Faizal

Supervisor: Dr. Anjani Gupta
