# ⚡ AI & Data Science for Renewable Energy
### Research Portfolio | André Luis Ferreira Marques
**PhD Candidate (USP) | Data Scientist | Professor**

Welcome to my research lab. I specialize in developing **Hybrid Deep Learning** and **Statistical Models** to solve complex energy challenges in the Amazon Basin. My work focuses on overcoming data scarcity in remote regions using Satellite Data (NASA), Advanced Algorithms (CNN-LSTM, Transformers), and Cloud Computing (AWS).

---

## 🏆 Selected Publications (2023–2025)

### 1. 🧠 Hybrid AI: SARIMAX + CNN-Transformer (2025)
**Title:** *Artificial Intelligence in Data Science: Evaluating Forecasting Models for Solar Energy in the Amazon Basin*
**Published in:** IEEE Access, Vol. [cite_start]13 [cite: 2450]

> **The Challenge:** Predicting solar irradiance in the Amazon is difficult due to high cloud variability and "noise" in the data.
> **My Solution:** I developed a novel **Hybrid Model** that decomposes the signal. I used **SARIMAX** for the trend/seasonality and **Deep Learning (CNN-LSTM & Transformers)** to predict the residual noise.
> [cite_start]**Key Results:** Achieved a **MAPE of ~18-26%** for 3-day horizons, significantly outperforming traditional Holt-Winters baselines[cite: 2471].

* **Tech Stack:** Python, PyTorch, Kriging Metamodels, Seasonal-Trend Decomposition (STL).
* **View Paper:** [📄 Download PDF](./Artificial_Intelligence_in_Data_Science_Evaluating_Forecasting_Models.pdf)

![Hybrid Model Workflow](./image-of-your-hybrid-workflow.png)
*(Fig: The Data Science workflow integrating Statistical and Neural Network models)*

---

### 2. 📉 Deep Learning Comparison: LSTM vs. GRU vs. MLP (2024)
**Title:** *Neural Networks Forecast Models Comparison for the Solar Energy Generation in Amazon Basin*
**Published in:** IEEE Access, Vol. [cite_start]12 [cite: 3140]

> [cite_start]**The Scope:** A massive comparative study covering **12 cities** in the Amazon over a **10-year period** (2013-2023)[cite: 3207].
> **The Analysis:** I benchmarked three Neural Network architectures: **Multi-Layer Perceptron (MLP)**, **Long Short-Term Memory (LSTM)**, and **Gated Recurrent Units (GRU)**.
> [cite_start]**Key Results:** The **LSTM-GRU** model proved most efficient, achieving the lowest error (MAPE 19.2%) in the city of Labrea[cite: 3702].

* **Tech Stack:** AWS SageMaker, Python, GridSearch Optimization.
* **View Paper:** [📄 Download PDF](./Neural_Networks_Forecast_Models_Comparison.pdf)

---

### 3. 🛰️ Applied Data Science: Satellite Data & Decision Trees (2023)
**Title:** *Application of data science in the prediction of solar energy for the Amazon basin*
**Published in:** Oxford Clean Energy, Vol. [cite_start]7 [cite: 1927]

> **The Innovation:** Addressed the lack of ground stations in the Amazon by engineering a pipeline that processes **NASA Satellite Data** (CERES/MERRA2 models).
> **The Algo:** Compared Time Series (VAR) against **Ensemble Machine Learning** (Adaptive Boosting & Light Gradient Boosting).
> [cite_start]**Key Results:** Proved that Decision Tree Ensembles could achieve a Mean Absolute Error (MAE) as low as **0.20 kW.h/m²**[cite: 1941].

* **Tech Stack:** Python, Pandas, Scikit-Learn, NASA POWER API.
* **View Paper:** [📄 Download PDF](./Application_of_data_science_solar_energy.pdf)

---

## 🎓 PhD Thesis Focus (Universidade de São Paulo)
**Topic:** *Energy Transition & Data Science*
[cite_start]My ongoing doctoral research focuses on the **application of Data Science in the energy matrix transition**, specifically developing robust algorithms to integrate renewable sources into the grid in data-scarce environments[cite: 3833].

### 🛠️ Tools & Frameworks Used
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_SageMaker-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![IEEE](https://img.shields.io/badge/IEEE_Xplore-00629B?style=for-the-badge&logo=ieee&logoColor=white)

---
*“Ideally, the code we write should be as sustainable as the energy we seek to generate.”*
