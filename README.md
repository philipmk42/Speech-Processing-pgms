# Speech-Processing-pgms

This repository contains Python and Jupyter Notebook programs for various Speech Processing laboratory exercises.  
It covers fundamental concepts such as audio handling, feature extraction, spectral analysis, speech enhancement, and real-time speech recognition.

---

## 📂 Lab Program Descriptions

### **Spr_lab1.ipynb — Introduction to Speech Processing**
Basic audio operations: loading sound files, visualizing waveforms, understanding sampling rate, duration, amplitude, and simple time-domain analysis.

### **lab2_spr.ipynb — Framing, Windowing & Basic Features**
Introduces speech preprocessing steps such as framing, applying window functions, and extracting basic features like short-term energy and zero-crossing rate.

### **sr_lab3.py — Real-Time Speech Recognition (Streamlit App)**
A working speech-to-text application using Streamlit.  
Features:
- Live microphone transcription  
- Audio file transcription  
- Online (Google) and offline (Sphinx) recognition  

### **Spr_lab4.ipynb — Spectral Analysis**
Uses FFT and spectrograms to study speech in the frequency domain.  
Focuses on pitch, formants, and spectral characteristics.

### **SPR_lab5.ipynb — MFCC Feature Extraction**
Implements the full pipeline for Mel-Frequency Cepstral Coefficients (MFCCs), a key feature set in speech recognition systems.

### **SPR_lab6.ipynb — Speech Classification Basics**
Builds a simple ML-based classification system using extracted features (e.g., MFCCs).  
Includes training, testing, and evaluating accuracy.

### **spr_lab7.ipynb — Speech Enhancement**
Introduces noise reduction techniques such as spectral subtraction and smoothing to improve noisy speech signals.

### **Spr_lab8.ipynb — Mini End-to-End Speech Processing Project**
Combines multiple concepts to create a small pipeline for analyzing or recognizing speech from raw audio.

### **spr_lab9.ipynb — Final Speech Recognition Experiment**
A capstone experiment involving feature extraction, model training/testing, and analyzing performance metrics for speech recognition.

---

## 🚀 Running the Jupyter Notebooks

Install Jupyter if needed:

```bash
pip install jupyter
