# HospitalAI — Brain Tumor Detection

An end-to-end medical AI system for brain tumor detection from MRI scans.

## Live Demo
- Frontend: https://huggingface.co/spaces/vishishtgupta2006/hospitalai-frontend
- Backend API: https://huggingface.co/spaces/vishishtgupta2006/hospitalai-backend

## Model
- Architecture: EfficientNetB0 (Transfer Learning + Fine-tuning)
- Dataset: Brain MRI Images for Brain Tumor Detection (Kaggle - navoneel)
- Training: Google Colab T4 GPU, PyTorch

## Results
| Metric | Score |
|---|---|
| Validation Accuracy | 92% |
| Tumor Recall | 94% |
| Test Accuracy | 81% |

## Features
- Brain tumor classification (Tumor / No Tumor)
- Grad-CAM heatmap visualization
- FastAPI backend deployed on Hugging Face Spaces
- Real-time MRI analysis via web interface

## Tech Stack
- PyTorch, EfficientNetB0, Grad-CAM
- FastAPI, Hugging Face Spaces
- HTML/CSS/JS frontend

## Project Structure
