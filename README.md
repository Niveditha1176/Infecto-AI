# 🌱 Infecto-AI

**Intelligent Pesticide Sprinkling System Based on Plant Infection Level**

> *Smart India Hackathon (SIH) – Internal Hackathon Idea Submission*

---

## 📌 Overview

**Infecto-AI** is an AI + IoT–based smart agriculture solution designed to **detect plant diseases early** and **automatically control pesticide spraying** based on the severity of infection. The system aims to reduce pesticide overuse, minimize crop damage, and support farmers with data-driven decision-making.

This repository serves as a **project showcase and documentation** since the original prototype was built using **Rocket AI**, which does not allow direct code export. The README preserves the **concept, architecture, and implementation approach** for academic and portfolio purposes.

🔗 **Live Preview (Rocket AI):**
[https://preview.builtwithrocket.new/infecto-ai-d45tv86](https://preview.builtwithrocket.new/infecto-ai-d45tv86)

---

## 🏆 Hackathon Details

* **Event:** VITISH 2025 (SIH Internal Hackathon)
* **Problem Statement ID:** 25015
* **Problem Statement Title:** Intelligent pesticide sprinkling system determined by the infection level of the plant
* **Theme:** Agriculture, FoodTech & Rural Development
* **Category:** Hardware + Software (AI + IoT)
* **Team Name:** ByteBots

---

## 🚜 Problem Statement

Traditional pesticide spraying methods are:

* Manual and inefficient
* Prone to overuse of chemicals
* Environmentally harmful
* Costly for farmers

There is a need for an **automated, intelligent system** that:

* Detects plant diseases accurately
* Assesses infection severity
* Sprays pesticides **only when required** and **in optimal quantities**

---

## 💡 Solution Approach

Infecto-AI combines **computer vision**, **IoT hardware**, and **cloud-based analytics** to create a closed-loop smart farming system.

### 🔄 Workflow

1. Camera captures plant images
2. AI model detects disease and infection level
3. Decision engine determines pesticide quantity
4. Automated sprayer activates via IoT controller
5. Data syncs to mobile & web dashboards

---

## 🧠 Core Technologies

### 📱 Mobile Application

* React Native + Expo
* i18next for multilingual support
* Farmer-friendly UI for disease alerts & recommendations

### 🌐 Web Dashboard

* Next.js 14
* Tailwind CSS
* Mapbox / Leaflet (field visualization)
* Chart.js / Recharts (analytics & trends)

### ⚙ Backend

* Node.js + Express / Next.js API Routes
* Firebase Authentication
* Firestore Database
* Cloud Storage
* Offline-first data sync support

### 🤖 AI Layer

* TensorFlow Lite
* Image-based plant disease detection
* Mocked inference for prototype demonstration

### 🔌 IoT Hardware

* Raspberry Pi / ESP32
* Camera module
* Solenoid valve–based pesticide sprayer
* Micro-SD card for local caching

---

## 📐 System Architecture

```
[Camera] → [AI Disease Detection]
                ↓
        [Infection Severity]
                ↓
        [Decision Engine]
                ↓
      [IoT Sprayer Control]
                ↓
 [Mobile App & Web Dashboard]
```

---

## ✅ Feasibility & Viability

* Uses **low-cost, easily available hardware**
* Scalable from small farms to large agricultural fields
* Works with **limited internet connectivity**
* Reduces pesticide costs and crop loss

---

## 🌍 Impact & Benefits

* 🌱 Reduced chemical usage
* 💰 Lower farming costs
* 📈 Improved crop yield
* 🌎 Environmentally sustainable
* 👨‍🌾 Data-driven farming decisions

---

## 📊 Data & Research References

### 📂 Dataset

* Plant Disease Dataset (Kaggle):
  [https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)

### 📚 Research Paper

* Journal of Big Data – Plant Disease Detection using AI:
  [https://journalofbigdata.springeropen.com/articles/10.1186/s40537-023-00863-9](https://journalofbigdata.springeropen.com/articles/10.1186/s40537-023-00863-9)



## 📎 Notes

* Source code is unavailable due to **Rocket AI platform limitations**
* This repository exists for **documentation, evaluation, and portfolio use**
* Future work includes full-stack reimplementation with open-source tools

---

## 👩‍💻 Team – ByteBots

Smart India Hackathon 2025 | VIT

---


> *Built with innovation for sustainable agriculture.* 🌾
