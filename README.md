# Seasonal-Agriculture-Performance-Analysis

An exploratory and statistical data analysis project evaluating agricultural productivity, profitability, and resource efficiency across India's primary cropping seasons: **Kharif**, **Rabi**, and **Zaid**.

## 📌 Project Overview

Agricultural profitability and yield depend heavily on seasonal dynamics, environmental parameters, and resource management. This project analyzes multi-seasonal farming datasets to uncover key patterns in crop performance, input costs, irrigation methods, and climate variables, providing data-driven recommendations for optimized resource allocation.

### Core Objectives
* **Seasonal Yield Comparison:** Quantify yield variations across Kharif, Rabi, and Zaid seasons.
* **Profitability Drivers:** Identify which input factors (fertilizers, irrigation, labor) have the highest correlation with net margin.
* **Resource & Environmental Impact:** Assess how variations in rainfall, temperature, and water access affect crop failure risk.
* **Statistical Validation:** Test hypotheses regarding yield variance across seasons and regional zones.

---

## 🛠️ Tech Stack & Libraries

* **Language:** Python
* **Data Manipulation:** `pandas`, `numpy`
* **Statistical Analysis:** `scipy` 
* **Data Visualization:** `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebook/ Goggle colab/ VS Code

---

## 📊 Dataset & Key Variables

The dataset includes records across multiple seasons, regions, and crop types with the following primary features:

| Feature | Description |
| `Season` | Cropping cycle (Kharif, Rabi, Zaid) |
| `Crop_Type` | Specific crop cultivated |
| `Region` / `Zone` | Geographic farming location |
| `Irrigation_Type` | Irrigation source (Canal, Borewell, Drip, Rainfed) |
| `Rainfall_mm` | Total seasonal rainfall received in millimeters |
| `Temperature_Avg`| Average seasonal temperature in Celsius |
| `Fertilizer_Used`| Total chemical/organic fertilizer inputs (kg/hectare) |
| `Production_Yield`| Output measured per unit area (tonnes/hectare) |
| `Cost_of_Cultivation` | Total operating expenditure per hectare |
| `Net_Profit` | Final economic return after input costs |

## 🔍 Key Insights & Analysis

1. **Seasonal Productivity:** Rabi season exhibits the most stable yields due to controlled irrigation reliance, whereas Kharif shows higher variance driven by monsoon fluctuations.
2. **Cost-to-Yield Tradeoff:** Increasing fertilizer application shows diminishing marginal returns on net profit past threshold levels.
3. **Irrigation Efficiency:** Drip-irrigated zones maintained significantly higher profit margins during Zaid compared to rainfed setups.

⚡ Getting Started

1. Clone the repository

   git clone [https://github.com/anusha2403/Seasonal-Agriculture-Performance-Analysis.git](https://github.com/anusha2403/Seasonal-Agriculture-Performance-Analysis.git)
cd Seasonal-Agriculture-Performance-Analysis

3. Create a virtual environment & install dependencies

   python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt

3. Run the notebook
   
   jupyter notebook notebooks/seasonal_analysis.ipynb

