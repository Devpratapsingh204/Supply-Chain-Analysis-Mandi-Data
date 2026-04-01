# 📦 Agricultural Mandi Price Intelligence Framework

## 📌 Project Overview
This project presents a **research-grade analytical framework** for evaluating price behavior, market efficiency, and supply chain fragmentation in Indian agricultural mandis using Government of India data.

It goes beyond basic analysis by introducing **novel economic indices** and a **data-driven risk taxonomy**, enabling actionable insights for farmers, policymakers, and financial institutions.

---

## 📊 Dataset
- **Source**: data.gov.in (AGMARKNET Mandi Data)  
- **Records**: 7,100+  
- **Coverage**: 19 States, 327 Markets  
- **Attributes**: State, District, Market, Commodity, Grade, Min/Max/Modal Prices  

---

## ⚙️ Methodology & Features
- 📌 Data Cleaning & Preprocessing  
- 📌 Feature Engineering:
  - Price Spread  
  - Price Spread Ratio (PSR)  
  - Coefficient of Variation (CV)  
- 📌 Novel Index Design:
  - **PSR (Price Spread Ratio)** → Market Efficiency  
  - **GPI (Grade Premium Index)** → Quality-based Pricing  
  - **SCFI (Supply Chain Fragmentation Index)** → Inter-state price dispersion  
  - **MEC Score** → Composite market efficiency score  
- 📌 Commodity Risk Classification using **K-Means Clustering**  
- 📌 Machine Learning Validation using **Random Forest**  
- 📌 Statistical Validation:
  - Silhouette Score  
  - Bootstrap Stability  
  - Correlation Analysis  

---

## 📈 Key Insights
- 📊 **National PSR = ~15.8%** → Significant intra-mandi price dispersion  
- 🧩 Supply chains are moderately fragmented (Mean SCFI ≈ 35%)  
- 💰 Quality upgrade can yield up to **500%+ price increase** (GPI analysis)  
- ⚠️ Certain states exhibit consistently inefficient markets (PSR > 0.20)  
- 🧠 SCFI and PSR emerge as the **strongest predictors of market risk**

---

## 📊 Outputs
All visual outputs are available in the `outputs/` folder:
- Price Distribution Analysis  
- Commodity & Grade Distribution  
- PSR Efficiency Analysis  
- GPI Visualization  
- SCFI Fragmentation Analysis  
- Clustering & Risk Taxonomy  
- ML Validation & Feature Importance  
- MEC Score by State  

---

## 🛠 Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🚀 Future Scope
- Real-time mandi price integration (API-based)  
- Predictive price modeling (Time Series / ML)  
- Power BI / Dashboard deployment  
- Farmer decision-support system  

---

## 👨‍💻 Author
**Dev Pratap Singh**  
B.Tech CSE (Data Science)  
