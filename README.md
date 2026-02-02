# 🚗 Car Price Predictor – Flask ML Web App

Live Demo 👉 [https://car-price-predictor-0ei9.onrender.com/](https://car-price-predictor-0ei9.onrender.com/)

---

## 📌 Project Overview

Car Price Predictor is a machine learning based web application built using **Flask** that predicts the selling price of a used car based on:

* Car Company
* Car Model
* Year of Purchase
* Fuel Type
* Kilometers Driven

The application uses a trained **Linear Regression model** and provides real-time predictions through a clean and user-friendly web interface.

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS (Custom UI)
* **Backend:** Flask (Python)
* **Machine Learning:** Scikit-learn (Linear Regression)
* **Data Handling:** Pandas, NumPy
* **Deployment:** Render

---

## 📂 Project Structure

```
Car Price Prediction Regressor/
│
├── application.py              # Flask backend
├── LinearRegressionModel.pkl  # Trained ML model
├── cleaned_car.csv            # Cleaned dataset
├── requirements.txt           # Project dependencies
│
├── templates/
│   └── index.html             # Frontend HTML
│
└── static/
    └── css/
        └── style.css          # Custom styling
```

---

## ⚙️ How It Works

1. User enters car details in the web form
2. Data is sent to Flask backend using AJAX
3. ML model predicts the car price
4. Result is displayed instantly on the UI

User-friendly messages are shown for invalid or unsellable predictions.

---

## 🚀 Run Locally

### 1️⃣ Clone the repository

```
git clone https://github.com/vishwajeet-Gitsmasher/car-price-predictor.git
cd car-price-predictor
```

### 2️⃣ Create virtual environment (optional)

```
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Run the app

```
python application.py
```

Open browser and visit:

```
http://127.0.0.1:5000
```

---

## 🌍 Deployment

The project is deployed on **Render** using Gunicorn server.

Start command used:

```
gunicorn application:app
```

---

## 📈 Machine Learning Model

* Algorithm: Linear Regression
* Trained on cleaned used car dataset
* Features used:

  * Company
  * Model
  * Year
  * Fuel Type
  * Kilometers Driven

---

## ✨ Features

✔ Real-time price prediction
✔ Clean modern UI
✔ User-friendly validation
✔ Production deployment
✔ Lightweight & fast

---

## 📸 Live Preview

Visit the live app here:

👉 [https://car-price-predictor-0ei9.onrender.com/](https://car-price-predictor-0ei9.onrender.com/)

---

## 🙌 Author

**Vishwajeet Walekar**

---

## 📄 License

This project is for educational and learning purposes.

---

⭐ If you like this project, feel free to star the repository!
