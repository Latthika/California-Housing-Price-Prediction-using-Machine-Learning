# California-Housing-Price-Prediction-using-Machine-Learning
This project is part of the Machine Learning Crash Course under the International Institute of Medical Science &amp; Technology Council (IIMSTC). The goal is to build and deploy a supervised regression model using the California Housing dataset to predict median house prices based on location and housing features.
# 🏡 California Housing Price Prediction using Machine Learning

This project is part of the **Machine Learning Crash Course** under the *International Institute of Medical Science & Technology Council (IIMSTC)*. The goal is to build and deploy a supervised regression model using the **California Housing dataset** to predict median house prices based on location and housing features.

---

## 🔍 Project Summary

We trained a regression model using **Linear Regression** on the California Housing dataset available in `scikit-learn`. After training and evaluation, we deployed the model using **Streamlit** to allow users to interactively predict housing prices.

---

## ⚙️ Features

- 📊 Real-time predictions using user inputs  
- 📈 Evaluation metrics displayed (MAE, RMSE, R² Score)  
- 🧠 Feature importance bar chart for interpretability  
- 💻 Deployed locally via Streamlit  

---

## 🗂️ Dataset

- **Source:** `sklearn.datasets.fetch_california_housing()`
- **Features Used:**  
  - MedInc, HouseAge, AveRooms, AveBedrms, Population, AveOccup, Latitude, Longitude

---

## 🧪 Model Performance

|
| Metric | Value |
|--------|--------|
| MAE (Mean Absolute Error) | ~0.53 |
| RMSE (Root Mean Squared Error) | ~0.74 |
| R² Score | ~0.60 |

---

## 🛠️ How to Run the App

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit App

```bash
streamlit run app.py
```

---

## 📁 Project Structure

```
├── app.py                # Streamlit app

```


---

## 📌 Additional Notes

- The model and scaler are saved using `joblib` for reuse.
- This project is a part of the **IIMSTC Internship Machine Learning Assignment**.

--
