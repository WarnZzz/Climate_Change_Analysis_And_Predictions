# 🌍 Climate Change Analysis & Temperature Prediction

Exploratory Data Analysis and Machine Learning project analyzing 
global temperature trends from the 1750s to 2015 using Python. 
This project uncovers key insights about climate change and builds 
a predictive model for future global temperatures.

---

## 📊 Analyses Performed

| # | Analysis | Key Finding |
|---|----------|-------------|
| 1 | Global Temperature Trend | Temperatures rising steadily since 1850 |
| 2 | Temperature Fluctuation | Min temperatures rising faster than max |
| 3 | Land vs Ocean Temperature | Ocean consistently warmer than land |
| 4 | Monthly Seasonality | July/August hottest, January coldest |
| 5 | Hottest & Coldest Countries | Djibouti hottest, Greenland coldest |
| 6 | Fastest Warming Countries | Central Asia warming fastest globally |
| 7 | Decade-wise Comparison | 2010s is the hottest decade in history |

---

## 🤖 Machine Learning Model

- **Algorithm:** Linear Regression
- **Target:** Global Average Land Temperature
- **Feature:** Year
- **Training Data:** 1950-2015
- **MAE:** 0.12°C
- **R² Score:** 0.87

### 🔮 Future Temperature Predictions
| Year | Predicted Temperature |
|------|----------------------|
| 2025 | 9.75°C |
| 2030 | 9.85°C |
| 2040 | 10.03°C |
| 2050 | 10.22°C |

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository:
```
   git clone https://github.com/WarnZzz/Climate_Change_Analysis_And_Predictions.git
```
2. Install dependencies:
```
   pip install -r requirements.txt
```
3. Open the notebook:
```
   jupyter notebook notebooks/climate_analysis_prediction.ipynb
```

---

## 📁 Project Structure
```
Climate Change Analysis & Temperature Prediction/
│
├── notebooks/               # Jupyter notebooks
│   └── climate_analysis_prediction.ipynb
├── README.md                # Project documentation
└── requirements.txt         # Dependencies
```

---

## 📂 Dataset

- **Source:** [Kaggle — Climate Change: Earth Surface Temperature Data](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data)
- **Files used:** `GlobalTemperatures.csv`, `GlobalLandTemperaturesByCountry.csv`

---

## 💡 Key Takeaways

- Global temperatures have risen significantly since the **Industrial Revolution (1850)**
- **Central Asia** is warming fastest due to landlocked geography and the Aral Sea disaster
- **2010s is the hottest decade** in recorded history
- Model predicts global average land temperature will **cross 10°C by 2040**
- Simple Linear Regression achieves **87% accuracy** on recent temperature data

---

## ⚠️ Model Limitations

This project uses a simple Linear Regression with year as the only 
feature. Real climate models use hundreds of variables like CO2 levels, 
ocean currents, and solar activity. Predictions are indicative, not definitive.

---

## 👤 Author

**Ranjan Paudel**
- GitHub: [@WarnZzz](https://github.com/WarnZzz)