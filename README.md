

# 🌱 SmartHarvest Engine – Crop Yield & Price Predictor

**“AI-powered decision support for smarter farming.”**

SmartHarvest Engine is a machine learning web application that helps farmers and agri-enthusiasts predict **crop yield and estimated market price** using soil, climate, and farming inputs.

It also includes an **AI Agri-Advisor chatbot** for real-time farming guidance.

---

# 🎯 Problem Statement

Farmers often rely on guesswork or past experience to estimate yield and profit.

SmartHarvest Engine helps answer:
👉 *“What yield and price can I expect based on my farm conditions?”*

By combining **data science + AI**, the system supports more informed agricultural planning.

---

# ✨ Features

## Core Intelligence

### 1️⃣ Yield Prediction

Predicts crop yield (tons/hectare) using:

* Soil pH
* Rainfall
* Temperature
* Humidity
* Fertilizer & pesticide usage
* Planting density
* Crop & soil type
* Irrigation method
* Previous crop

---

### 2️⃣ Price Prediction

Estimates crop price using ML and supply-demand simulation logic.

---

### 3️⃣ AI Agri Chatbot

Provides:

* Crop suggestions
* Soil & irrigation advice
* Best farming practices
* General agriculture Q&A

Powered by Groq + Llama 3.

---

### 4️⃣ Simple Web Interface

* Dropdown selections
* Interactive sliders
* Instant predictions
* Built with Gradio

---

# 🛠️ Technology Stack

## Machine Learning

* Scikit-learn
* Random Forest Regressor
* Pipelines & ColumnTransformer
* OneHotEncoder & StandardScaler

## Frontend

* Gradio

## AI Integration

* Groq API
* Llama-3 model

## Data Processing

* Pandas
* NumPy

## Environment

* Google Colab / Python

---

# ⚙️ How It Works

```
1. Load agricultural dataset
2. Clean and preprocess data
3. Generate synthetic price data
4. Train ML models:
   - Yield Model
   - Price Model
5. User inputs farm details
6. Models predict yield & price
7. Chatbot provides advice
```

---

# 📂 Project Structure

```
SmartHarvest/
│
├── Crop_Prediction_Tool.ipynb
├── dataset.csv
├── model_training
├── gradio_ui
└── README.md
```

---

# 📊 Dataset

Includes:

* Crop types
* Soil characteristics
* Climate data
* Farming inputs
* Yield values

*Price is synthetically generated for modeling purposes.*

---

# 🌟 Key Highlights

✅ Real-world agriculture use case
✅ ML + AI combined in one system
✅ Clean and interactive UI
✅ Beginner-friendly architecture
✅ Easily extendable

---

# 🚀 Future Improvements

* Live weather API integration
* Real market price data
* Mobile-friendly app version
* Multi-language farmer support
* Larger real-world datasets
* Advanced ML models

---

# ⚠️ Disclaimer

This project is for **educational and experimental use only.**
Predictions may not reflect actual market or farm outcomes.

---

**Empowering smarter farming with AI 🌾**

---

