# Punjabi Automatic Speech Recognition using XLSR (Wav2Vec2)

This project implements an end-to-end Automatic Speech Recognition (ASR) system for Punjabi by fine-tuning Facebook's XLSR-Wav2Vec2 model on the Mozilla Common Voice dataset.

The model is trained using Connectionist Temporal Classification (CTC) loss and evaluated using Word Error Rate (WER).

---

## 🚀 Project Overview

- Fine-tuned multilingual XLSR (Wav2Vec2) for Punjabi speech recognition
- Built complete preprocessing pipeline (audio resampling + text normalization)
- Implemented custom tokenizer for Punjabi vocabulary
- Trained using HuggingFace Trainer API
- Evaluated performance using WER metric
- Optimized GPU usage in Google Colab (CUDA)

---

## 🧠 Model Architecture

- Base Model: `facebook/wav2vec2-large-xlsr-53`
- Framework: PyTorch
- Training Strategy: CTC Loss
- Dataset: Mozilla Common Voice (Punjabi)

---

## 🛠 Tech Stack

- Python
- PyTorch
- HuggingFace Transformers
- HuggingFace Datasets
- Google Colab (GPU)
- CUDA

---

## 📊 Evaluation Metric

- Word Error Rate (WER)

WER is used to measure transcription accuracy between predicted and actual text.

---

## 📂 Repository Structure


punjabi-asr-xlsr/
│── FINAL XLSR METHOD PUNJABI DATA.ipynb
│── README.md


---

## 🔥 Key Learnings

- Transformer-based speech models
- CTC-based sequence modeling
- GPU memory optimization
- Audio preprocessing pipelines
- Fine-tuning large pretrained models

---

## 📌 Future Improvements

- Hyperparameter tuning
- Data augmentation
- Deployment via FastAPI
- Real-time inference API
