# 🎒 SchoolLens

## AI-Powered School Supplies Identifier

![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)

**ITE120 Final Project · CSUCC**

**Regie A. Salabit**  
IT Student | Caraga State University – Cabadbaran Campus (CSUCC)

---

## 📘 About

**SchoolLens** is an intelligent mobile application that uses **TensorFlow Lite** to identify
**school supplies** (such as notebooks, pens, pencils, erasers, rulers, calculators) using a
smartphone camera.

The app is built with **Flutter** for smooth cross-platform performance and integrated with
**Firebase** for real-time cloud synchronization.

### Highlights
- 🎯 High-accuracy school supplies classification  
- ⚡ Fast on-device inference (under 2 seconds)  
- ☁️ Cloud-synced scan history  

---

## 📦 Project Resources

| Resource | Description |
|--------|------------|
| 💻 **Full Project Code** | Complete Flutter source code including all screens and logic |
| 🧠 **Assets & Resources** | TensorFlow Lite model, datasets, screenshots, and assets |

---

## ✨ Features

### 📸 Real-Time Scanning
Instant identification of school supplies using the device camera with live preview and autofocus.

### 🤖 AI Classification
On-device **TensorFlow Lite** model ensures fast, private, and offline-capable recognition.

### 🖼 Gallery Support
Analyze images selected from the device gallery with the same AI accuracy.

### 📊 Smart Dashboard
Displays total scans, accuracy rates, and daily activity in real time.

### 🗂 Scan History
View previous scans with thumbnails, timestamps, item names, and confidence scores.

### ☁️ Cloud Sync
Automatic Firebase backup ensures secure data storage and accessibility.

---

## 🖼 Screenshots

| Home | Scanner | Gallery | Results | Predictions | History |
|-----|--------|---------|---------|-------------|---------|
| Dashboard & stats | Live camera scan | Pick from gallery | Accuracy & graph | Probability ranking | Cloud-synced logs |

---

## ⚙️ Prerequisites

- Flutter SDK 3.0+
- Dart SDK 3.0+
- Android Studio / Xcode
- Firebase account (for cloud features)

---

## 🔄 How It Works

1. **Capture** – Take a photo or select an image from the gallery  
2. **Process** – TensorFlow Lite analyzes image features  
3. **Classify** – AI predicts the school supply with confidence score  
4. **Save** – Results are stored automatically in Firebase  
5. **Track** – View statistics and scan history anytime  

---

## 🧩 Screen Details

- 🏠 **Home Dashboard** – Scan overview and statistics  
- 📷 **Camera Scanner** – Live scanning interface  
- 🖼 **Gallery Selection** – Choose images from device storage  
- ✅ **Results & Predictions** – Confidence score and probability chart  
- 🗂 **Scan History** – Timestamped and cloud-synced records  

---

## 🗃 Source Code Overview

- `main.dart` – Main application entry point  
- `tflite_helper.dart` – AI model loading and inference  
- `firebase_options.dart` – Firebase configuration  

---

## 📬 Contact

📧 **Email:** regie.salabit@csucc.edu.ph  
🎓 **Project:** ITE120 Final Project  

---

> *SchoolLens – Making school supplies recognition smarter with mobile AI.*
