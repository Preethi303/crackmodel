# 🪨 Rockfall Risk Detection using Deep Learning

An AI-powered rockfall and crack severity classification system built using Deep Learning and Transfer Learning techniques with TensorFlow/Keras.

The model classifies crack images into three categories:

- ✅ Safe
- ⚠️ Warning
- 🚨 High Risk

This project uses the powerful ResNet50V2 pretrained architecture to achieve high accuracy in crack severity detection.

---

# 📌 Features

- Automatic dataset upload and extraction
- Duplicate and corrupt image removal
- RGB image conversion
- Automatic train-validation split
- Data augmentation pipeline
- Transfer Learning using ResNet50V2
- Two-phase model training
- Class imbalance handling using class weights
- Early stopping and learning rate scheduling
- Confusion matrix generation
- Accuracy and loss visualization
- Final trained model export

---

# 🛠 Technologies Used

- Python
- TensorFlow / Keras
- ResNet50V2
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Pillow (PIL)

---

# 📂 Dataset Structure

```bash
dataset/
│
├── Safe/
├── Warning/
└── High Risk/
