# 🚗 Car Price Predictor

This is a Machine Learning project that predicts the **price of used cars** based on input features like:

- Brand
- Mileage
- Engine Capacity
- Transmission Type
- Seating Capacity
- Maximum Power

The model is trained using **Linear Regression** and deployed as a web app using **Streamlit**.

---

## 🧠 Workflow

1. **Data Collection** – Gathered car dataset with prices and features.
2. **Preprocessing** – Handled missing and duplicate records.
3. **Feature Selection** – Kept only relevant columns.
4. **Model Training** – Used 80% training and 20% testing data.
5. **Deployment** – Created a simple UI using Streamlit to predict prices.

---

## 🔧 Tech Stack

- **Python Libraries**: pandas, numpy, scikit-learn, pickle, streamlit

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
streamlit run carapp.py

