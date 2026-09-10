# seasonal-agriculture-performance-analysis

Python-based agricultural data analysis project that studies crop performance, seasonal trends, irrigation methods, environmental conditions, resource usage, profitability, and agricultural performance across different states and districts using Pandas, NumPy, Matplotlib, and Seaborn.

# 🌾 Seasonal Agriculture Performance Analysis

A Python-based **Exploratory Data Analysis (EDA)** project that studies agricultural data to understand how crops perform under different seasons, irrigation methods, environmental conditions, farming practices, and regions.

The project uses a dataset containing **4,000 records and 28 variables** to find useful patterns related to crop productivity, resource usage, revenue, and profit.

## 📌 Project Overview

Agricultural performance depends on many factors such as:

* Crop type
* Season
* Irrigation method
* Rainfall and temperature
* Soil and farming conditions
* Fertilizer and seed usage
* Water consumption
* Market price
* Production cost
* Location

This project analyzes these factors to understand:

* Which crops perform better
* Which season gives better results
* Which irrigation method gives higher yield
* How resources affect production
* Which crops and regions are more profitable
* How agricultural performance differs between states and districts

## 🎯 Objectives

* Analyze agricultural performance across different crops and seasons.
* Find high-performing and low-performing crops.
* Compare irrigation methods based on average crop yield.
* Study the relationship between production, yield, revenue, and resource usage.
* Understand the effect of environmental and farming factors.
* Compare agricultural performance across different states and districts.
* Find useful insights that can help in better agricultural decision-making.

## 📊 Dataset

The dataset contains **4,000 agricultural records and 28 variables**.

The variables include information about:

* Farm details
* Crop information
* Season
* State and district
* Rainfall
* Temperature
* Humidity
* Soil and farming conditions
* Irrigation method
* Fertilizer usage
* Seed quality
* Water usage
* Crop yield
* Production
* Market price
* Revenue
* Cost
* Profit
* Disease and pest risk

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## 🔍 Analysis Performed

### 1. Seasonal Analysis

The project compares agricultural performance across three seasons:

* Kharif
* Rabi
* Zaid

**Kharif** showed the highest average revenue and profit among the three seasons.

### 2. Crop-wise Analysis

Different crops were compared using:

* Average yield
* Average production
* Average revenue
* Average profit

**Sugarcane** performed the best in the analyzed dataset.

* Average Yield: **46.64 tonnes/hectare**
* Average Production: **392.41 tonnes**
* Average Profit: **₹817,188**

### 3. Irrigation Analysis

The project compares the average yield of different irrigation methods.

| Irrigation Method | Average Yield |
| ----------------- | -------------: |
| Drip              | 6.58 tonnes/ha |
| Sprinkler         | 5.16 tonnes/ha |
| Flood             | 4.86 tonnes/ha |
| Rainfed           | 4.60 tonnes/ha |

**Drip irrigation** recorded the highest average yield among the irrigation methods analyzed.

### 4. Economic Analysis

The project compares revenue and profit across different seasons.

**Kharif** recorded the highest average revenue:

**₹710,719**

Other seasons:

* Rabi: **₹601,526**
* Zaid: **₹519,172**

This shows that Kharif had the strongest economic performance in the dataset.

### 5. Correlation Analysis

Correlation analysis was used to understand how different agricultural variables are related to each other.

The strongest relationship found was:

**Production vs Yield → 0.883**

Other important relationships include:

* Water Usage vs Production → **0.516**
* Production vs Revenue → **0.564**
* Market Price vs Revenue → **0.182**

Rainfall, temperature, and humidity showed **very weak linear relationships with yield** in this dataset.

### 6. State-wise Analysis

Agricultural performance was compared across different states using:

* Average yield
* Average production
* Average revenue
* Average profit

**Punjab** recorded the highest average yield and production among the analyzed states and also had the highest average profit.

### 7. District-wise Analysis

The project also compares agricultural performance across different districts.

**Rajkot** recorded the highest average yield and production.

**Warangal** recorded the highest average revenue and profit among the analyzed districts.

## 📈 Key Findings

* 🌾 **Sugarcane** was the highest-performing crop in terms of average yield, production, and profit.
* 🌧️ **Kharif** had the best overall economic performance among the three seasons.
* 💧 **Drip irrigation** had the highest average yield among the analyzed irrigation methods.
* 📊 **Production and yield** had a strong positive correlation of approximately **0.883**.
* 💰 **Production and revenue** had a moderate positive relationship.
* 🌦️ **Rainfall, temperature, and humidity** had very weak linear relationships with yield.
* 🗺️ Agricultural performance was different across states and districts.
* ⚠️ Some crops had negative average profit and need further analysis of their costs and revenue.

## 💡 Recommendations

* Consider high-performing crops such as **Sugarcane and Chilli** when suitable for the region and available resources.
* Study the production costs of crops with negative average profit.
* Improve disease and pest management, especially during the Kharif season.
* Consider both water usage and water efficiency when selecting irrigation methods.
* Use state-wise and district-wise results for region-specific agricultural planning.
* Use machine learning and advanced statistical methods to find more complex relationships in the data.

## 🚀 Future Scope

This project can be improved further by:

* Building crop yield prediction models.
* Creating a crop recommendation system.
* Adding real-time weather data.
* Adding real-time market-price data.
* Creating interactive dashboards using Power BI.
* Applying regression and machine learning algorithms.
* Developing region-specific agricultural decision-support systems.

## 📂 Project Structure

```text
seasonal-agriculture-performance-analysis/
│
├── collab/
│   └── Seasonal_Agriculture_Performance_Analysis.ipynb
│
├── dataset/
│   └── agriculture_dataset.csv
│
├── presentation/
│   └── Seasonal_Agriculture_Performance_Analysis.pptx
│
├── images/
│   └── project_visualizations
│
├── requirements.txt
└── README.md

## 👨‍💻 Author

**Shubham Bachkheti** 

Data Analytics | Python | Data Visualization

---

⭐ If you find this project useful, consider giving the repository a star!
