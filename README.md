# 🌾 Crop Recommendation System using Machine Learning (Command Line Interface)

This project predicts the most suitable crop to grow based on soil and weather conditions using a Machine Learning model. The application is designed to run directly from the **Command Line**, making it lightweight and efficient for basic systems.

---

## 📌 Features

- Takes input from user via command line
- Predicts crop using a trained Random Forest Classifier
- Easy to run without any GUI or web deployment
- Works on low-end machines

---

## 🧠 Model Information

- **Algorithm**: Random Forest Classifier
- **Dataset**: [Crop Recommendation Dataset from Kaggle](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)
- **Features Used**:
  - N (Nitrogen)
  - P (Phosphorus)
  - K (Potassium)
  - Temperature
  - Humidity
  - pH
  - Rainfall

---

## ⚙️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/samiera12/crop-recommendation-cli.git
cd crop-recommendation-cli
```

## Install Dependencies

```bash
pip install pandas scikit-learn joblib
```

## Train the model

```bash
python train_model.py
```

## Run the crop recommender

```bash
python recommend_crop.py
```

## Project Structure

```bash
crop-recommendation-cli/
│
├── Crop_recommendation.csv         # Dataset
├── train_model.py                  # Model training script
├── recommend_crop.py               # CLI-based prediction script
├── crop_recommendation_model.pkl   # Saved model (after training)
└── README.md                       # Project info
```

## Sample Input and Output
-Nitrogen (N): 90
-Phosphorus (P): 42
-Potassium (K): 43
-Temperature (°C): 25
-Humidity (%): 80
-pH: 6.5
-Rainfall (mm): 120

-Output : rice

