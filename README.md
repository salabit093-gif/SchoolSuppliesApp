<div align="center">

# 🎒 SchoolLens
### AI-Powered School Supplies Identifier

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

**ITE120 Final Project · CSUCC**

[Features](#-features) • [Screenshots](#-screenshots) • [Tech Stack](#-tech-stack) • [Installation](#-installation)

</div>

<br>

<div align="center">

### Regie A. Salabit
**IT Student | Caraga State University – Cabadbaran Campus (CSUCC)**

Passionate about building intelligent solutions using mobile AI for everyday tasks.

<br>

### 🛠️ Skills

| Category | Technologies |
|:---:|:---|
| **Mobile Dev** | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) |
| **Backend** | ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) ![Firestore](https://img.shields.io/badge/Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black) |
| **AI / ML** | ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![TFLite](https://img.shields.io/badge/TFLite-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) |
| **Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white) |

<br>

📧 **Contact**: [regie.salabit@csucc.edu.ph](mailto:regie.salabit@csucc.edu.ph)  
🎓 **Project**: ITE120 Final Project  

</div>

<br>

## 📖 About

**SchoolLens** is an intelligent mobile app that uses **TensorFlow Lite** to identify school supplies (notebooks, pens, pencils, erasers, rulers, calculators) through your smartphone camera.  

Built with **Flutter** for smooth cross-platform performance and integrated with **Firebase** for real-time cloud synchronization.

> 🎯 **High accuracy** in school supplies classification  
> ⚡ **Under 2 seconds** processing time  
> ☁️ **Cloud-synced** scan history  

---

## 📦 Project Resources

| Resource | Description |
|--------|------------|
| 💻 **Full Project Code** | Complete Flutter source code including all screens and logic |
| 🧠 **Assets & Resources** | TensorFlow Lite model, datasets, screenshots, and project assets |
| ![Home](https://raw.githubusercontent.com/salabit093-gif/SchoolSuppliesApp/main/Home.jpg) | ![Gallery](https://raw.githubusercontent.com/salabit093-gif/SchoolSuppliesApp/main/Gallery.jpg) | ![Camera](https://raw.githubusercontent.com/salabit093-gif/SchoolSuppliesApp/main/Camera.jpg) | ![History](https://raw.githubusercontent.com/salabit093-gif/SchoolSuppliesApp/main/History.jpg) |

---

## ✨ Features

### 📸 Real-Time Scanning
Identify school supplies instantly using the device camera with live preview and autofocus.

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

## 📸 Screenshots

<div align="center">

| 🏠 Home | 🖼 Gallery | 📷 Camera | 📜 History |
|:---:|:---:|:---:|:---:|
| Dashboard & stats | Image selection from gallery | Live camera scan | Cloud-synced scan logs |

</div>

---

## ⚙️ Prerequisites

- Flutter SDK 3.0+
- Dart SDK 3.0+
- Android Studio / Xcode
- Firebase account (for cloud features)

---

## 🔄 How It Works

```mermaid
graph LR
    A[📱 Launch App] --> B[📸 Capture/Select Image]
    B --> C[🤖 TFLite Processing]
    C --> D[✅ AI Classification]
    D --> E[📊 Display Results]
    E --> F[☁️ Save to Firebase]
    F --> G[📜 Update History]
