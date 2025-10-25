# 📊 Social Media Shares vs Viral Score — Linear Regression

This project analyzes the relationship between **Social Media Shares** and **Viral Score** using **Exploratory Data Analysis (EDA)** and a **Linear Regression Model**.

---

## ✅ Project Workflow

1. **Import Libraries**

   * numpy, pandas — data handling
   * matplotlib, seaborn — visualization
   * sklearn — model training & evaluation

2. **Load Dataset**

   ```python
   df = pd.read_csv('Social_Media_vs_Viral_Content.csv')
   ```

3. **Exploratory Data Analysis (EDA)**

   * View shape, columns, dtypes, summary stats
   * Check for missing values
   * Sample data inspection
   * Histogram & scatter plot visualizations

4. **Train-Test Split**

   ```python
   X_train, X_test, y_train, y_test = train_test_split(x, y, test_size=0.3)
   ```

5. **Model Training — Linear Regression**

   ```python
   lm.fit(X_train, y_train)
   predictions = lm.predict(X_test)
   ```

6. **Model Evaluation**
   Metrics used:

   * Mean Absolute Error (MAE)
   * Mean Squared Error (MSE)
   * Root Mean Squared Error (RMSE)

---

## 📦 Requirements

Install necessary dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 📁 Dataset

File used: **`Social_Media_vs_Viral_Content.csv`**
Make sure it exists in project root folder before running.

---

## 📈 Output

* Histogram distribution of features
* Scatter plot showing relationship between social shares and viral score
* MAE, MSE, RMSE values printed after evaluation

---

## 🧠 Model Used

* **Linear Regression** from `sklearn.linear_model`

---

## 📌 Future Improvements

* Add multiple features instead of single variable
* Try other regression models (Ridge, Lasso, RandomForest)
* Deploy model using Flask/Streamlit
* Add feature scaling and outlier treatment

---

## 👨‍💻 Author

**Aniket Mishra**

---
