# ♻️ AI-Based Waste Segregation System

## 📖 Overview

The AI-Based Waste Segregation System is a Deep Learning project that automatically classifies waste into different categories using images. The goal of this project is to support better waste management by reducing manual sorting and improving recycling efficiency.

The model is built using **MobileNetV2** with **Transfer Learning** and optimized with **Intel Extension for TensorFlow (ITEX)** for better CPU performance.

---

## ✨ Features

- ♻️ Automatically classifies waste from images
- 🧠 Uses Deep Learning with Transfer Learning
- 📸 Supports image-based waste detection
- 🚀 Optimized using Intel ITEX for faster inference
- 📊 Classifies waste into 10 different categories
- 📈 Provides high accuracy and real-time performance

---

## 🛠️ Technologies Used

- Python
- TensorFlow 2.15
- Intel Extension for TensorFlow (ITEX)
- Keras
- MobileNetV2
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset

The model is trained using the **Large-Scale Garbage Dataset**, which contains **11,318 images** across **10 waste categories**.

### Waste Categories

- 🔋 Battery
- 🌿 Biological
- 📦 Cardboard
- 👕 Clothes
- 🍾 Glass
- 🥫 Metal
- 📄 Paper
- 🧴 Plastic
- 👟 Shoes
- 🗑️ Trash

**Dataset Split**
- Training: 80%
- Validation: 20%

---

## 🧠 How It Works

1. The dataset is cleaned and prepared.
2. Images are resized and preprocessed.
3. MobileNetV2 is used as the base model with Transfer Learning.
4. The model is trained and fine-tuned for better accuracy.
5. Intel ITEX improves CPU inference performance.
6. The trained model predicts the waste category of a new image.

---

## 📊 Results

| Metric | Performance |
|---------|-------------|
| Accuracy | **93.36%** |
| Precision | **92.81%** |
| Recall | **92.90%** |
| F1-Score | **92.78%** |
| ROC-AUC | **0.9963** |
| Inference Speed | **240 FPS** |

---

## 📁 Project Structure

```text
AI-Waste-Segregation/
│
├── screenshots/
├── .gitignore
├── AI_Waste_Groq.html
├── README.md
├── Requirements.txt
└── main.ipynb
```

---

## 🚀 Getting Started

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Run the notebook step by step.
5. Train the model or use the saved model for prediction.

---

## 🌍 Applications

This project can be used in:

- Smart waste bins
- Recycling plants
- Smart city solutions
- Educational demonstrations
- Waste management research
- AI and Computer Vision projects

---

## 🔮 Future Improvements

- Add more waste categories
- Deploy on Raspberry Pi
- Build a mobile application using TensorFlow Lite
- Support real-time webcam detection
- Improve performance using advanced Deep Learning models
- Deploy the project on the cloud

---

## 👥 Team

- **Ananya Verma**
- **Anisha Boken**

---

## 📄 License

This project is developed for educational and research purposes.
