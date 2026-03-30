# ML-EVERLASTING-CROP-SUGGESTER
# **🌾 AIRTIFICIAL INTELLIGENCE AND MACHINE LEARNING CROP SUGESSTER **

A machine learning project that recommends the most suitable crop to grow based on soil and climate conditions — built as part of the **Fundamentals of AI and ML** course capstone (BYOP).

---

## 📌 Problem Statement

Farmers in India often struggle to decide which crop to grow for a given season. Wrong crop selection leads to poor yield, wasted resources, and financial loss. This project uses Machine Learning to recommend the best crop based on measurable soil and weather inputs.

---

## 🚀 Features

- Trains a **Random Forest Classifier** on soil & climate data
- Predicts the best crop from **10 crop types**
- Achieves **~97.7% accuracy** on test data
- Displays feature importance so farmers understand what drives the recommendation
- Includes a prediction demo with sample inputs                                                                                                                                                
       ---

## 🛠️ Setup & Installation

### Prerequisites
- Python 3.8 or higher
- pip

### Step 1 — Clone the repository
```bash
git clone https://github.com/<your-username>/crop-recommendation.git
cd crop-recommendation
```

### Step 2 — Install dependencies
```bash
pip install -r requirements.txt
```

### Step 3 — Run the project
```bash
python crop_recommendation.py
```

That's it! The script will:
1. Generate the dataset
2. Train the model
3. Print accuracy and classification report
4. Show feature importance
5. Demonstrate predictions for 3 sample inputs

---

## 📦 Requirements

```
pandas
numpy
scikit-learn
```

Save the above as `requirements.txt` in your project folder.

---

## 🌱 Crops Supported

| Crop | Key Growing Conditions |
|------|------------------------|
| Rice | High humidity, high rainfall |
| Wheat | Moderate temp, low rainfall |
| Maize | Warm, moderate rainfall |
| Cotton | High temp, low rainfall |
| Sugarcane | Warm, high N, good rainfall |
| Mung Bean | Warm, moderate humidity |
| Lentil | Cool, dry, low N |
| Pomegranate | Hot, dry, low N |
| Mango | Tropical, warm |
| Banana | Humid, high N, P, K |

---

## 🔢 Input Features

| Feature | Description | Unit |
|---------|-------------|------|
| N | Nitrogen content in soil | mg/kg |
| P | Phosphorus content in soil | mg/kg |
| K | Potassium content in soil | mg/kg |
| temperature | Average temperature | °C |
| humidity | Relative humidity | % |
| ph | Soil pH value | 0–14 |
| rainfall | Annual rainfall | mm |

---

## 📊 Model Performance

- **Algorithm**: Random Forest Classifier (100 trees)
- **Accuracy**: ~97.7%
- **Train/Test Split**: 80% / 20%

---

## 💡 How to Make Your Own Prediction

Edit the `sample_inputs` list at the bottom of `crop_recommendation.py`:

```python
sample_inputs = [
    {"N": 90, "P": 42, "K": 43, "temperature": 21,
     "humidity": 82, "ph": 6.5, "rainfall": 202},
]
```

Replace the values with your actual soil and climate readings and run the script.

---

## 📚 Course Context

This project was developed for the **Fundamentals of AI and ML** evaluated course (BYOP).  
It applies the following course concepts:
- Supervised Learning (Classification)
- Decision Trees & Ensemble Methods (Random Forest)
- Train/Test Split & Model Evaluation
- Feature Engineering and Importance

---

## 👤 Author

**[MIDHUN KESHAV JT]**  
Registration No: [25BCE10589]  


