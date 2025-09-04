# 🧠 AI-Based Medical Diagnosis System

An **AI-powered web application** that assists healthcare professionals in diagnosing diseases using **deep learning**.  
The system can analyze **medical images** (X-rays, MRIs) and **bio-signals** (like ECG) to provide accurate, timely, and explainable diagnoses.  

---

## 📌 Problem Statement
Accurate and timely medical diagnosis is a critical challenge.  
- Manual analysis of medical scans/signals is **time-consuming**, **error-prone**, and **subjective**.  
- There is a shortage of diagnostic experts, especially in rural/underserved areas.  
- Rising patient loads make fast, scalable diagnosis essential.  

This project aims to **bridge this gap** using **AI-based automation**.

---

## 🎯 Objectives
- Develop a **web-based AI diagnostic platform**.  
- Automate detection of diseases from **medical images & ECG signals**.  
- Provide **explainable AI outputs** (Grad-CAM heatmaps, saliency maps).  
- Ensure **scalability** and **accessibility** through a responsive frontend.  

---

## ⚙️ Technology Stack
**Frontend:** HTML, CSS, Tailwind CSS, JavaScript  
**Backend:** Python, Flask  
**AI Frameworks:** TensorFlow/Keras, OpenCV  
**Preprocessing:** NumPy, pydicom, Scikit-learn  
**Deployment:** AWS Cloud  

---

## 🏗️ System Architecture
1. **Frontend** → Upload X-ray/MRI/ECG files, view results.  
2. **Backend (Flask)** → Handles uploads, runs AI models, returns predictions.  
3. **AI Models**  
   - CNN (ResNet-50) → Image-based diagnosis  
   - RNN/LSTM → ECG-based analysis  
4. **Explainability Layer** → Grad-CAM/Attention heatmaps for transparency.  
5. **Output Layer** → Displays diagnosis + confidence score.  

---

## 🚀 Features
- Upload **X-ray, MRI, or ECG** for automated analysis.  
- **CNN-based detection** of pneumonia, tumors, etc.  
- **RNN/LSTM-based detection** of cardiac anomalies.  
- **Explainable AI outputs** with visualization.  
- Multi-page responsive design: `Home`, `Team`, `Tool`.  

---

## 📊 Dataset
- **NIH Chest X-ray Dataset** (pneumonia, lung conditions)  
- **MIT-BIH ECG Arrhythmia Dataset**  

---

## 📈 Results
- CNN (ResNet-50) achieved ~90% accuracy on chest X-ray validation.  
- Explainable predictions improved **trust and usability**.  
- Web-based UI provides **accessibility across devices**.  

---

## 🔮 Future Enhancements
- Cloud deployment with GPU acceleration.  
- User authentication & patient history storage.  
- Multi-disease classification (TB, COVID-19, cardiomegaly).  
- Real-time ECG monitoring with wearable integration.  
- Speech-to-text for faster doctor interaction.  

---

## 🖥️ Installation & Setup
Clone the repo and run locally:

```bash
# Clone repository
git clone https://github.com/your-username/ai-medical-diagnosis.git
cd ai-medical-diagnosis

# Install dependencies
pip install -r requirements.txt

# Run Flask server
python app.py
