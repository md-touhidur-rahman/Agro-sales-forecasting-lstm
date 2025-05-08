# 🧠 Time Series Forecasting of Agricultural Product Sales using LSTM

This project implements a deep learning-based time series forecasting model to predict agricultural product sales. It supports data-driven decision-making for agro-based businesses by anticipating future demand using historical sales data.

📄 **Published by IEEE | [Read the paper](./paper/Time_Series_Forecasting_Agro_Sales_IEEE.pdf)**  
🔬 **Presented at:** 14th International Conference on Computing, Communication and Networking Technologies (ICCCNT 2023), IIT Delhi  
👨‍💻 **Lead Author:** [Md. Touhidur Rahman](https://www.researchgate.net/profile/Md-Touhidur-Rahman?ev=hdr_xprf)

---

## 📊 Problem Statement

> How can we leverage LSTM (Long Short-Term Memory) models to forecast agricultural product sales at a regional and product-specific level?

---

## 🧰 Tech Stack

- Python, Pandas, NumPy, Matplotlib, Seaborn
- TensorFlow / Keras (for LSTM)
- Jupyter / Google Colab

---

## 📁 Files

| File | Description |
|------|-------------|
| `notebooks/time_series_forecasting_agro_sales.ipynb` | Implementation of the time series LSTM forecasting |
| `paper/Time_Series_Forecasting_Agro_Sales_IEEE.pdf` | The full IEEE-published research paper |
| `README.md` | This documentation |
| `LICENSE` | MIT license for open use |

---

## 🔍 Highlights

- ✅ Real-world dataset from a Bangladeshi agro company (Win Agro)
- 📈 Multi-step LSTM time series forecasting model
- 📉 Final MAE: ~8339.66 (aggregated sales value)
- 📊 Visualization of product-wise, region-wise, and packet-size sales trends
- 🧠 Used feature engineering like cyclical encoding for months

---

## 🧪 How to Run

1. Clone the repo:
```bash
git clone https://github.com/md-touhidur-rahman/Agro-sales-forecasting-lstm.git
cd agro-sales-forecasting-lstm
