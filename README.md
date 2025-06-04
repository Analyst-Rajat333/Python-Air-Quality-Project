# 🌫️ Python Air Quality Forecasting Project

This project is a **forecasting and data analysis case study** on **air quality (Relative Humidity - RH)** using Python. It explores future RH values using time-series predictions, highlights uncertainty ranges, and compares actual vs predicted values. Key metrics are also presented using custom visual cards.

---

## 📂 Dataset Summary

The dataset (`Air_Quality_Data.csv`) contains timestamped environmental data with the following key columns:

- 🗓️ `ds` – Date and Time  
- 💧 `rh` – Actual Relative Humidity (%)  
- 📉 `yhat` – Forecasted RH value  
- 🔺 `yhat_upper` – Upper confidence interval  
- 🔻 `yhat_lower` – Lower confidence interval

---

## 📊 Key Visualizations & Purpose

1. **Forecast Over Time (Line Chart)**  
   → Shows how `yhat` (predicted RH) changes over time (`ds`).

   ![forecast_line_chart](https://github.com/user-attachments/assets/9a11f20b-827b-4eb0-8888-cd8e49c3015e)


2. **Uncertainty Band (Area Chart)**  
   → Displays confidence range between `yhat_upper` and `yhat_lower`.

   ![uncertainty_area_chart](https://github.com/user-attachments/assets/dac74629-6bff-4df5-9963-44efc20d2799)


3. **Actual vs Predicted RH (Comparison Chart)**  
   → Compares real RH (`rh`) with predicted (`yhat`) to evaluate model accuracy.

   ![rh_vs_yhat_comparison_chart](https://github.com/user-attachments/assets/9e19a2fa-2223-4748-887b-704af10f7df8)


4. **Key Metrics Cards (Matplotlib Text Cards)**  
   → Summarizes:  
   - Average RH  
   - Average Forecast  
   - Maximum yhat_upper  
   - Minimum yhat_lower

   ![key_metrics_cards](https://github.com/user-attachments/assets/f0a54b27-45d9-460f-bb40-226396b2abb6)


---

## 🛠 Technologies Used

- **Python 3**
- **Pandas** – Data loading & manipulation  
- **Plotly (Express & Graph Objects)** – Interactive charts  
- **Matplotlib** – For card-style KPI visuals  
- **NumPy** – Used for any numerical operations  

---

## 📈 Example Insights

- The forecast model tracks RH variations effectively with confidence ranges.
- Most predictions stay within bounds defined by `yhat_lower` and `yhat_upper`.
- Actual RH values align well with forecasted trends in many time periods.
- Summary statistics provide quick understanding of prediction range.

---

## 🔗 GitHub Repository Link

[https://github.com/Analyst-Rajat333/Python-Air-Quality-Project](https://github.com/Analyst-Rajat333/Python-Air-Quality-Project)

---

## 👨‍💻 Author

**Rajat Saxena**  
📧 **Email**: [rajatsaxena950@gmail.com](mailto:rajatsaxena950@gmail.com)  
🔗 **GitHub**: [Analyst-Rajat333](https://github.com/Analyst-Rajat333)
