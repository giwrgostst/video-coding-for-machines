# Video Coding for Machines

This project explores a novel paradigm in video compression: **Video Coding for Machines (VCM)**. Unlike traditional methods that optimize for human perception (e.g., PSNR or SSIM), VCM aims to preserve features essential to machine learning models performing inference on visual data.

## 📄 Contents

- `Research.pdf` – Detailed research report discussing objectives, methods, evaluation metrics, and potential implementations for VCM.

## 🧠 Key Concepts

- **Region of Interest (ROI)**-based encoding
- **Inference-aware bitrate allocation**
- Feature-preserving compression
- Trade-offs between visual fidelity and model performance

## 🛠️ Technologies Discussed

- Deep Learning (CNNs, Object Detection)
- Video Encoding Standards (HEVC, AV1, custom)
- Feature extractors (e.g., YOLO, ResNet)

## 🎯 Objectives

- Reduce video transmission cost while maintaining high machine inference accuracy
- Prioritize compression of semantically meaningful areas
- Align encoding decisions with downstream model behavior

## 🚀 How to Use

This is a research-oriented project. The `Research.pdf` document includes theoretical analysis and experimental design. This repo is best suited for:
- Academic study
- Project proposals
- Discussion in ML/video compression communities
