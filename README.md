# Skin Disease Detection using CNN 🩺

Skin Disease Detection is a deep learning based web application that uses a Convolutional Neural Network (CNN) to classify skin diseases from uploaded images and provide related information.

---

## 🚀 Live Demo

https://soudahimavamsi.github.io/Skin_disease_detector_CNN/

---

## ✨ Features

- Upload skin images for disease prediction
- CNN-based skin disease classification
- Disease description and medication information
- Diet recommendations based on the predicted condition
- PDF report generation
- Save prediction and prescription details to Firebase Firestore
- Send reports through WhatsApp using Twilio
- Find nearby doctors, clinics, and hospitals using OpenStreetMap

---

## 🛠️ Tech Stack

### Frontend

- HTML
- CSS
- JavaScript

### Backend

- Python
- Flask
- Flask-CORS

### Machine Learning

- TensorFlow
- Keras
- CNN
- NumPy
- Pillow

### Database

- Firebase Firestore

### Other

- ReportLab (PDF Generation)
- Twilio (WhatsApp Integration)
- OpenStreetMap Nominatim
- OpenStreetMap Overpass API

---

## 🧠 Supported Diseases

The model supports the following 10 disease categories:

- Atopic Dermatitis
- Basal Cell Carcinoma (BCC)
- Benign Keratosis-like Lesions (BKL)
- Eczema
- Melanocytic Nevi (NV)
- Melanoma
- Psoriasis, Lichen Planus and related diseases
- Seborrheic Keratoses and other Benign Tumors
- Tinea, Ringworm, Candidiasis and other Fungal Infections
- Warts, Molluscum and other Viral Infections

---

## 📱 Application Workflow

```text
Upload Skin Image
        ↓
Image Preprocessing
        ↓
CNN Model Prediction
        ↓
Predicted Skin Disease
        ↓
Disease Information
        ↓
PDF Report / Firestore / WhatsApp
```

---

## 📂 Project Structure

```text
Skin_disease_detector_CNN/
│
├── app.py                 # Flask backend
├── index.html             # Frontend
├── model.keras            # Trained CNN model
├── README.md
└── ...
```

---

## ⚠️ Disclaimer

This project is developed for educational and informational purposes. It is not intended to replace professional medical diagnosis or treatment.

---

## 👨‍💻 Author

Souda Himavamsi

GitHub: https://github.com/SoudaHimavamsi

LinkedIn: https://www.linkedin.com/in/himavamsi-2027-vitap/
