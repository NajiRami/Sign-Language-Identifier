# 🖐 Sign Language Identifier (Digits 0–5)

This project is a **Sign Language Digit Identifier**🤩🤩 that recognizes hand gestures representing digits from *0 to 5* using **computer vision** and **deep learning**.  
It aims to assist in bridging communication between people with hearing impairments and digital systems❤️.

---

## 📸 Overview

The model takes an image or live video frame as input and classifies the hand gesture into one of six classes:

| Digit | Gesture | One-Hot Encoding |
|:------:|:--------:|:----------------:|
| 0 | ✋ | [1, 0, 0, 0, 0, 0] |
| 1 | ☝ | [0, 1, 0, 0, 0, 0] |
| 2 | ✌ | [0, 0, 1, 0, 0, 0] |
| 3 | 👌 | [0, 0, 0, 1, 0, 0] |
| 4 | 🖖 | [0, 0, 0, 0, 1, 0] |
| 5 | 🖐 | [0, 0, 0, 0, 0, 1] |

> 🔍 Below is a sample visualization showing all gestures (0–5) and their one-hot encodings.

![Sign Language Digits Example](./images/SIGNS.png)

---

## 🧠 Project Description

The *Sign Language Identifier* uses a *Convolutional Neural Network (CNN)* model trained on a dataset of hand gesture images representing digits 0–5.  
The goal is to *detect and classify* the gesture shown by the user in real-time or from static images.

### ✨ Key Features

- Recognizes digits *0–5* in sign language.
- Built with *TensorFlow / Keras* for training and inference.
- Supports *real-time detection* via webcam.
- Uses *one-hot encoded labels* for clear class separation.
- Includes *data preprocessing* and *augmentation* for improved accuracy.

---
## ⚙ Technologies Used
- 🐍 Python
- 🧠 TensorFlow / Keras
- 👁 Computer Vision (CV)
- 📊 Deep Learning (CNN)

---

## ⚙ Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/SignLanguageIdentifier.git
cd SignLanguageIdentifier
python -m venv venv
source venv/bin/activate      # On Linux/Mac
venv\Scripts\activate         # On Windows
pip install -r requirements.txt
