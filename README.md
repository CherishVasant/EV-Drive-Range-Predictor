# 🔋 Electric Vehicle Range Prediction using Machine Learning 🚗📊

This project uses various Machine Learning models to predict the **range of Electric Vehicles (EVs)** based on input features like battery capacity, vehicle weight, and other technical specifications.


---

## 🚀 Objectives

- Apply and compare multiple **regression algorithms** for EV range prediction.
- Use **GridSearchCV** for **hyperparameter tuning** 🧪.
- Evaluate model performance using **R² Score** and **Mean Absolute Error (MAE)** 📉.
- Visualize results using **Seaborn** and **Matplotlib**.

---

## 🧠 Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor
- K-Nearest Neighbors Regressor
- Support Vector Regressor

All models are fine-tuned and evaluated on a separate **test set**.

---

## 📊 Evaluation Metrics

Each model is evaluated using:

- **R² Score** (`r2_score`) 📈
- **Mean Absolute Error** (`mean_absolute_error`) 📉

Final evaluation is stored and printed for comparison.

---

## 📦 Requirements

Install the dependencies using:

```bash
pip install -r requirements.txt


How to Run
- Clone the repo:
git clone https://github.com/your-username/EV-ML-Range-Predictor.git

- Navigate to the folder:
cd EV-ML-Range-Predictor

- Open ev_range_predictor.ipynb and run all cells.




Future Work
- Deploy model with a web interface using Streamlit or Flask
- Incorporate real-time data or IoT integration
