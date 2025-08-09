# Deep Audio Classification CNN 🎵🔊

An end-to-end **environmental sound classification system** powered by a custom **ResNet-style Convolutional Neural Network (CNN)**. The model is trained on the **ESC-50 dataset** and uses **Mel Spectrograms** as input features, with GPU-accelerated inference through a FastAPI backend and an upcoming responsive Next.js dashboard.

---

## 🚀 Features
- **Custom ResNet-style CNN** for audio classification  
- **ESC-50 dataset** integration (50 classes of environmental sounds)  
- **Mel Spectrogram preprocessing** with robust data augmentation  
- **GPU-accelerated inference** using PyTorch  
- **FastAPI backend** with Pydantic validation  
- **uv-based project setup** for fast dependency management and reproducible environments  

## 📂 Project Structure
```
.
├── .gitignore
├── .python-version
├── README.md
├── main.py          # FastAPI entry point for inference
├── model.py         # Model architecture and loading utilities
├── pyproject.toml   # uv project configuration
├── train.py         # Training loop and data pipeline
└── uv.lock          # uv dependency lock file
```
---

## 🛠️ Tech Stack
- **Languages**: Python, JavaScript (Next.js dashboard in progress)  
- **ML/DL Frameworks**: PyTorch, torchaudio  
- **Backend**: FastAPI, Pydantic  
- **Environment Management**: uv  
- **Deployment**: Modal (planned)  

---

## 📊 Dataset
The project uses the [ESC-50 dataset](https://github.com/karoldvl/ESC-50), a labeled collection of 2,000 environmental audio recordings organized into 50 semantic classes (e.g., dog bark, rain, engine).  

---

## 📌 Roadmap
- [x] Model architecture and training pipeline  
- [x] Mel Spectrogram preprocessing and augmentation  
- [ ] Frontend Next.js dashboard for real-time predictions  
- [ ] Modal GPU deployment  
- [ ] Accuracy benchmarking and performance metrics  

---
