# 🛒 Store Sales Prediction

## 📌 Demo

Click on the Live Demo:

> 🔗 [Live Demo]() <!-- App link -->

This project is a **Machine Learning Regression Model** designed to predict the sales of products at various Store outlets. Using historical sales data, the system learns patterns and helps forecast sales based on factors such as item characteristics, outlet types, and pricing.

## 📌 Project Objective

- Predict sales of products at retail outlets using historical data.
- Build an accurate regression model using various ML techniques.
- Analyze patterns and perform feature engineering.
- Deploy the model as an interactive **Streamlit** web application.

## 📁 Dataset

- **Source:** [Store Sales Dataset on Kaggle](https://www.kaggle.com/datasets/brijbhushannanda1979/bigmart-sales-data)
- **Files:**
  - `Train.csv` – historical data for training the model
  - `Test.csv` – data without sales values, for prediction

### Dataset Features

- `Item_Identifier`, `Item_Weight`, `Item_Fat_Content`
- `Item_Visibility`, `Item_Type`, `Item_MRP`
- `Outlet_Identifier`, `Outlet_Establishment_Year`, `Outlet_Size`
- `Outlet_Location_Type`, `Outlet_Type`
- `Item_Outlet_Sales` *(Target Variable)*

## 🛠️ Tech Stack

| Component      | Tools Used                                       |
|----------------|--------------------------------------------------|
| Language       | Python                                           |
| Libraries      | Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn |
| Visualization  | Matplotlib, Seaborn                              |
| ML Algorithms  | Linear Regression, Ridge, Random Forest, XGBoost |
| Web App        | Streamlit                                        |
| Deployment     | Streamlit Cloud                                  |

## 🔄 Project Pipeline

1. **Data Collection** – Download from Kaggle
2. **Data Cleaning** – Handle null values, format corrections
3. **EDA** – Visualizations to understand data behavior
4. **Feature Engineering** – Encode categorical data, create new features
5. **Model Building** – Train multiple regression models
6. **Model Evaluation** – Compare using metrics like RMSE and R²
7. **Prediction Interface** – Build frontend using Streamlit
8. **Deployment** – Launch via Streamlit Cloud

## 🧹 Preprocessing Steps

- Fill missing values in `Item_Weight`, `Outlet_Size`
- Combine or clean categories (e.g., unify `Item_Fat_Content`)
- Convert categorical columns using Label/One-Hot Encoding
- Scale/normalize numerical features if needed
- Split training data for validation
- Tune hyperparameters using cross-validation

## 🚀 How to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/Shahzain333/Store-Sale-Prediciton
   cd Store-Sale-Prediciton
   ```

2. Install Dependencies:
   
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Streamlit App:

   ```bash
   streamlit run app.py
   ```

## 🤝 Acknowledgments

* [Kaggle](https://www.kaggle.com) for providing high-quality datasets
* [Scikit-learn](https://scikit-learn.org/stable/) for versatile ML libraries
* [Streamlit](https://streamlit.io/) for rapid app development and deployment
