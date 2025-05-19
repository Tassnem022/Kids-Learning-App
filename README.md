# 📚 Kids-Learning-App

An **interactive educational app** designed to engage children through **voice recognition** and **real-time feedback**. Using deep learning and gamification, the app teaches kids about **numbers**, **motions**, and **animals** in a fun and intuitive way.

---

## 🚀 Demo

🎥 [Watch Demo on Google Drive](https://drive.google.com/file/d/1zcCEzl31m7wtXugfqp6fDwqZU4BCrbCs/view?usp=drive_link)

---

## ✨ Features

### 🎙️ Voice-Activated Learning Modules
- Three engaging modules:
  - **Learn Numbers**
  - **Learn Motions**
  - **Learn Animals**
- Kids interact by speaking answers, which are recognized using **custom-trained deep learning models** built with **TensorFlow**, **CNNs**, and **Librosa**.

### 💬 Dynamic Feedback System
- Instant on-screen feedback:
  - ✅ **Correct!** displayed in green
  - ❌ **Wrong, try again!** in red
- Automatically updates content on correct responses.

### 🧍 Interactive Animations
- In the **Learn Motions** module, kids can control a character (**Dora**) using voice commands like:
  - `"Up"`, `"Down"`, `"Left"`, `"Right"`

### 🎨 Kid-Friendly Interface
- Colorful and vibrant design
- Simple layout with large buttons and easy-to-read text

### 🎮 Gamified Elements
- Changing images for animals and numbers after correct answers
- Real-time animated character movement based on voice commands

---

## 🛠️ Technologies Used

- **Python**
- **Jupyter Notebook**
- **TensorFlow** – for building and training custom speech recognition models
- **CNN (Convolutional Neural Networks)** – for audio classification
- **Librosa** – for audio feature extraction and preprocessing
- **sounddevice** – for microphone input handling 
- **OpenCV** – for real-time image handling
- **Pygame** – for gui, animations and rendering 

---

## 📦 Installation

Follow these steps to set up the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Kids-Learning-App.git
cd Kids-Learning-App
