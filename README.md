# 🚗 Car Price Predictor

![Image](https://github.com/user-attachments/assets/b5414fd6-c37e-4961-8c5d-3a00e1e0d520)

A simple yet effective machine learning web app that predicts the resale price of used cars based on user input like brand, model, fuel type, kilometers driven, and more. This project combines data preprocessing, regression modeling, and a user-friendly Flask web interface to deliver instant car price predictions.

![Prediction Demo](predict.png)

---

## 📚 Table of Contents

- [📌 Brief Description](#-brief-description)
- [🚀 Live Demo](#-live-demo)
- [🧰 Tech Stack](#-tech-stack)
- [🗃️ Project Structure](#️-project-structure)
- [📈 Dataset Info](#-dataset-info)
- [⚙️ How to Run Locally](#️-how-to-run-locally)
- [🔍 Model Performance](#-model-performance)
- [🖼️ Screenshots](#️-screenshots)
- [📄 License](#-license)
- [🙌 Acknowledgements](#-acknowledgements)
- [👨‍💻 Author](#-author)

---

## 📌 Brief Description

This project aims to estimate the resale price of a used car using a machine learning model trained on real-world data scraped from Quikr.com. The application is built with Python, Flask, and scikit-learn, and it is deployed online for quick access. Users can select the car brand, model, fuel type, and enter usage details to receive an estimated selling price.

---

## 🚀 Live Demo

- 🔗 **Website**: [Car Price Predictor (Heroku)](https://car-price-price.herokuapp.com)
- ▶️ **Demo Video**: [YouTube](https://youtu.be/HEaFU68WAPM)

---

## 🧰 Tech Stack

- **Frontend**: HTML, CSS (Bootstrap)
- **Backend**: Python, Flask
- **ML Model**: Linear Regression (scikit-learn)
- **Deployment**: Heroku

---

## 🗃️ Project Structure
```bash
car_price_predictor/
├── application.py
├── requirements.txt
├── Procfile
├── LinearRegressionModel.pkl
├── quikr_car.csv
├── Cleaned_Car_data.csv
├── Quikr Analysis.ipynb
├── templates/
│   └── index.html
├── static/
│   └── css/
│       └── style.css
├── demo.png
├── predict.png
└── README.md
```



---

## 📈 Dataset Info

- **Source**: Scraped from [Quikr.com](https://www.quikr.com)
- **Features used**:
  - Company
  - Model
  - Year of Purchase
  - Fuel Type
  - Kilometers Driven
  - Price

---

## ⚙️ How to Run Locally

1. **Clone the repository**

```bash
git clone https://github.com/Akshay8087/car_price_predictor.git
cd car_price_predictor
```


2. **Install dependencies**
   
```bash
pip install -r requirements.txt\
```

3. **Run the Flask app**
```bash
python application.py
```
4. **Open in browser**
```bash
Visit: http://127.0.0.1:5000/
```
## 🔍 Model Performance
 
**Model:** Linear Regression  
**R² Score:** 0.92 (on test data)  
**Notebook:** All model training and evaluation steps are available in [`Quikr Analysis.ipynb`](Quikr Analysis.ipynb)  
