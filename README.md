# 🩺 SkinScan AI
### Fast, Offline, and Intelligent Burn & Wound Classification System

![License](https://img.shields.io/badge/License-MIT-green)
![Build](https://img.shields.io/badge/Build-.NET%208-blue)
![AI](https://img.shields.io/badge/AI-TensorFlow%20%7C%20PyTorch-orange)
![Status](https://img.shields.io/badge/Status-Active-success)

---

## 🧠 Overview

**SkinScan AI** is an innovative, AI-powered diagnostic system designed to classify and assess **burn and wound conditions** through advanced image analysis.

It assists **healthcare professionals**, **first responders**, and **clinics** in performing **fast, accurate, and offline-capable** wound assessment — even in **low-resource environments**.

This project bridges **Deep Learning**, **.NET Backend Services**, and **Cross-Platform Frontend Technologies** to deliver a complete, reliable, and ethical healthcare solution.

SkinScan AI supports the **United Nations Sustainable Development Goal (SDG 3)**: *Good Health and Well-being*, by improving access to diagnostic support tools and ensuring that early treatment decisions are informed and data-driven.

---

## 💡 Key Features

- 🔍 **AI-Based Burn Classification** – CNN-based image classification models trained on publicly available burn datasets.  
- ⚙️ **Offline Capability** – Works without continuous internet access to support field operations and remote clinics.  
- 🧩 **.NET Backend API** – ASP.NET Core Web API managing inference requests, image processing, and local data storage.  
- 📱 **Cross-Platform Frontend** – Integrates with Flutter or web-based clients for user-friendly diagnosis.  
- 🔒 **Privacy-First Architecture** – Handles all processing locally to ensure data security and compliance with healthcare ethics.  
- 📊 **Analytics Dashboard (Optional)** – Insights into model accuracy, usage frequency, and performance trends.

---

## 🏗️ System Architecture

The system is composed of **three main modules**:

### 1. AI Engine (Python / TensorFlow / PyTorch)
- Trains, validates, and exports the deep learning model for burn & wound classification.  
- Model exported in **ONNX** or **TensorFlow Lite** format for backend integration.

### 2. Backend (.NET Core API)
- Provides **RESTful API endpoints** for image uploads, inference, and result retrieval.  
- Runs local inference using **ML.NET** or **Python.NET** integration.  
- Handles data logging, performance tracking, and optional authentication.  
- Built with scalability and modular microservice design in mind.

### 3. Frontend (Flutter / Web)
- Simple and intuitive UI for clinicians and medical staff.  
- Displays classification results, probability distributions, and confidence levels.  
- Suggests next steps or triage recommendations.

---

## ⚙️ Technology Stack

| Layer | Technology Used | Description |
|:------|:----------------|:-------------|
| **AI Model** | TensorFlow / PyTorch | Burn & wound image classification |
| **Backend** | ASP.NET Core 8.0 Web API | REST endpoints for inference |
| **Database** | SQLite / PostgreSQL | Local or cloud data storage |
| **Frontend** | Flutter / Web | UI for diagnosis & visualization |
| **Deployment** | Docker, GitHub Actions | Containerized CI/CD setup |
| **Documentation** | Markdown, OpenAPI | Developer & user documentation |

---

## 🚀 Getting Started

### Prerequisites
Before running the system, ensure you have the following installed:

- .NET 8 SDK  
- Python 3.10+  
- Git  
- Docker *(optional)*  

---

### Installation

Clone the repository:
```bash
git clone https://github.com/MohamedEl-sadek/Project_SkinScan-AI.git     
cd Project_SkinScan-AI
```
---

### Backend Setup
```bash
cd backend
dotnet restore
dotnet run
```
---

### AI Model Setup
```bash
cd ai_model
pip install -r requirements.txt
python model_inference.py
```
---

### 🧩 Folder Structure
```bash
SkinScan AI/
│
├── backend/                # ASP.NET Core API backend
│   ├── Controllers/
│   ├── Models/
│   ├── Services/
│   └── appsettings.json
│
├── ai_model/               # AI model training and inference
│   ├── dataset/
│   ├── model/
│   ├── train.py
│   └── inference.py
│
├── frontend/               # Flutter or web client (optional)
│
├── data/                   # Example images and metadata
│
├── docs/                   # Architecture and documentation files
│
├── LICENSE
└── README.md
```
---

## 🧪 Model Training & Evaluation

The AI model is trained on publicly available datasets (e.g., **Kaggle Burn Dataset**).  
The training process includes:

- 🌀 **Data Augmentation** (rotation, normalization, contrast enhancement)  
- 🧠 **CNN-Based Architecture** (EfficientNet / ResNet)  
- 📊 **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score  
- 🚀 **Model Export:** TensorFlow Lite / ONNX  

✅ **Model Accuracy:** > 95% on validation sets  
⚡ **Inference Time:** < 1 second per image on standard hardware  

---

## 📈 Pilot Deployment

During the pilot phase:

- 🏥 Deployed in selected clinics with anonymized wound images  
- 👩‍⚕️ Medical staff provide feedback via surveys and interviews  
- 🧩 Feedback used to improve **usability**, **model accuracy**, and **integration workflow**

---

## 🤝 Contributing

We welcome contributions from the open-source community!  
You can:

- 🔧 Submit pull requests  
- 💡 Suggest new features  
- 🐞 Report issues through GitHub  

Please read the [`CONTRIBUTING.md`](CONTRIBUTING.md) and [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) for collaboration guidelines.

---

## 📜 License

This project is licensed under the **MIT License**.  
All creative works and documentation are licensed under **CC-BY 4.0 International**.

---

## 🌍 Acknowledgments

- 🩹 Open-source medical image datasets from [Kaggle](https://www.kaggle.com)  
- 💪 Contributors supporting ethical healthcare AI innovation  
- 🧠 **AI Sandbox Challenge** for promoting open innovation and transparency  

---

## 🧭 Future Plans

- 🔗 Integration with **EHR (Electronic Health Record)** systems  
- 🩸 Expand classification to **chronic wounds and ulcers**  
- 📱 Deploy lightweight mobile versions using **ONNX Runtime**  
- 🌐 Build a **multilingual AI assistant** for triage and treatment support  

---

> **SkinScan AI** — Empowering healthcare through intelligent, ethical, and accessible technology.


