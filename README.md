# 🌿 Plant Disease Detection System

[![Hugging Face Spaces](https://img.shields.io/badge/Running%20on-Hugging%20Face-blue?logo=huggingface)](https://huggingface.co/spaces/komalg11/Plant_Disease_Detection)
[![Streamlit](https://img.shields.io/badge/Built%20with-Streamlit-orange?logo=streamlit)](https://streamlit.io)

🚀 A machine learning web app that detects plant diseases from leaf images using a TFLite model and Streamlit — hosted on Hugging Face Spaces.

---

## 🔬 How It Works
- Upload a photo of a leaf 🌱
- The app uses a TensorFlow Lite model to classify it into one of **38 plant disease categories**
- Built with:
  - TensorFlow Lite for inference
  - OpenCV for image preprocessing
  - Streamlit for UI
  - Docker for containerization
  - Hugging Face Spaces for deployment

---

## 📷 Supported Plant Classes

Examples include:
- Apple Scab
- Tomato Late Blight
- Grape Leaf Blight
- Orange Citrus Greening
- Potato Early Blight
- ...and many more!

(Full list in the app sidebar 📋)

---

## 🚀 Run Locally

#bash
git clone https://github.com/yourusername/Plant_Disease_Detection
cd Plant_Disease_Detection

# Optional: Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install -r requirements.txt

streamlit run src/streamlit_app.py
