# Financial-Analysis-and-Valuation-of-Broadcom-Inc.

# Financial Analysis and Valuation of Broadcom Inc. (AVGO) 📊🚀

This repository contains a project focused on financial analysis, financial statement projection, and corporate valuation of **Broadcom Inc. (AVGO)**. The study utilizes historical data (2017-2024) to generate projections up to the year 2029 by leveraging Deep Learning models (**LSTM**) and traditional valuation methods (**DCF**).

## 📂 Repository Contents

### 1. Source Code 🐍
* **`Model.ipynb`**: Main Jupyter Notebook containing:
    * Data preprocessing.
    * Training of Recurrent Neural Networks (LSTM) for time series forecasting.
    * Comparison between manual projections and model predictions.
    * Calculation of WACC (Weighted Average Cost of Capital).
    * Discounted Cash Flow (DCF) valuation to estimate the share price.

### 2. Historical Data (2017-2024) 📅
CSV files containing the base financial information extracted for the analysis:
* **`AVGO_Balance_2017_2024.csv`**: Historical Balance Sheet.
* **`AVGO_Estado_Flujo_Efectivo_2017_2024.csv`**: Cash Flow Statement.
* **`tabla_estados_F_2017.csv`**: Income Statement (Profit and Loss).
* **`Ratios_Financieros_2017.csv`**: Key financial ratios and indicators (Liquidity, Solvency, Profitability).

### 3. Projections (2025-2029) 📈
Files used to compare model predictions with manual/analyst projections:
* **`estado_resultados_proyecciones.csv`**: Income Statement Projections.
* **`estado_situacion_financiera_proyecciones.csv`**: Balance Sheet Projections.

---

## 🛠️ Methodology

The project is divided into the following phases:

1.  **Exploratory Analysis:** Review of key historical metrics such as Revenue, EBITDA, Net Income, and Financial Ratios (ROE, ROA, Gross Margin).
2.  **AI Modeling (LSTM):**
    * Implementation of a Recurrent Neural Network (LSTM - Long Short-Term Memory) using `Keras`/`TensorFlow`.
    * **Objective:** Predict future financial metrics based on sequential historical patterns.
    * **Data:** Data was scaled using `MinMaxScaler` and time sequences were created for training.
3.  **Financial Valuation:**
    * Calculation of **WACC** (Weighted Average Cost of Capital).
    * Calculation of historical and projected **FCF** (Free Cash Flow).
    * Determination of **Terminal Value** and **Enterprise Value**.
    * Estimation of the **Target Share Price**.

---

## 📊 Technologies Used

The project was developed in Python using the following libraries:

* **Pandas** & **NumPy**: Data manipulation and analysis.
* **Matplotlib**: Visualization of historical and projected data.
* **Scikit-learn**: Data preprocessing (Scaling).
* **TensorFlow / Keras**: Construction and training of the Deep Learning model (LSTM).

## 🚀 How to Run

1.  Clone this repository.
2.  Ensure you have the necessary dependencies installed:
    ```bash
    pip install pandas numpy matplotlib scikit-learn tensorflow
    ```
3.  Open the file `PYTHON MONOGRAFIA 2 G8 BROADCOM.ipynb` in Google Colab or Jupyter Notebook.
4.  Make sure to upload the CSV files to the correct directory (or your Google Drive if using Colab) and adjust the file paths in the code if necessary.
5.  Run the cells to see the model training, comparative charts, and valuation results.

---

## 📈 Key Results

The notebook generates visualizations comparing:
* Real Historical Data.
* Manual Projections (based on traditional assumptions).
* LSTM Model Predictions.

Finally, it provides a calculation of the stock's intrinsic value based on the projected cash flows.

---
