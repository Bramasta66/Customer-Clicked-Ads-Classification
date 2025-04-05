# 🧠 Customer-Clicked-Ads-Classification

### Cracking the Ad Click Code for Wanderlust Expeditions  
📍 *Understanding what makes users click — across age groups, usage habits, and online behavior.*

---

## 🚀 Overview

Wanderlust Expeditions recently launched an "Off-the-Beaten-Path" ad campaign targeting Gen Z and Millennials. However, analytics revealed a surprising insight — **older users were clicking on the ads more often**.

This project dives deep into **exploratory data analysis**, **feature engineering**, and **classification modeling** to uncover the behavioral traits that lead users to engage with ads — helping us **refine ad targeting strategies** and boost conversions.

---

## 📊 Key Insights

- 🔍 **Older Users Click More**  
  Experienced travelers with more time and income appear to engage more with curated adventure campaigns.

- 🌐 **Less Internet Usage = Higher Engagement**  
  Those with limited internet time showed higher click-through rates, suggesting a more intentional browsing behavior.

- ⏱️ **Shorter Site Time = Higher Clicks**  
  Users who clicked on ads spent *less* time on the website, highlighting the importance of impactful, fast-loading landing pages.

- 🧬 **Correlations Identified**  
  - Age ↘️ vs. Internet Usage  
  - Internet Usage ↗️ vs. Time on Site

---

## 🧪 Project Workflow

1. **Exploratory Data Analysis**  
   - `ClickedAds_EDA.ipynb`  
     Visualized distributions, correlations, and behavioral trends via boxplots and pair plots.

2. **Preprocessing**  
   - `ClickedAds_PreProc.ipynb`  
     Feature engineering, missing value imputation, time-based feature extraction, and encoding.

3. **Classification Modeling**  
   - `ClickedAds_Classification.ipynb`  
     Trained Logistic Regression, Random Forest, and SVM (with and without normalization).

---

## 🤖 Model Performance

| Model                 | Normalized | Accuracy |
|----------------------|------------|----------|
| Logistic Regression  | ✅          | **96%**  |
| Random Forest        | ✅/❌       | **94%**  |
| SVM                  | ✅          | **95%**  |
| SVM                  | ❌          | 69%      |

✅ Logistic Regression showed dramatic improvement with scaling  
✅ Random Forest remained consistently strong in both versions

---

## 🔍 Feature Importance

### 📊 Random Forest
- **Top Features**:
  - Daily Internet Usage: `0.34`
  - Time Spent on Site: `0.25`
  - Age: `0.11`
  - Area Income: `0.10`

### 📈 Logistic Regression (Scaled)
- **Top Coefficients**:
  - Age: `+1.33`
  - Daily Internet Usage: `-2.98`
  - Time on Site: `-2.58`
  - Area Income: `-1.58`

---

## 📈 Business Impact

| Metric                      | Before AI Targeting | After AI Targeting |
|----------------------------|---------------------|--------------------|
| Conversions                | 200                 | 500                |
| Conversion Rate            | 2%                  | 5%                 |
| Revenue                    | $10,000             | $25,000            |
| Profit                     | $5,000              | **$20,000**        |

By leveraging AI insights and focusing on **key predictors**, the campaign's profit potential increased by **300%**.

---

## 🎯 Recommendations

- 📱 Target platforms frequented by older and less frequent internet users.
- ⚡ Use short, compelling ad formats that appeal to users with low site time.
- 📅 Use time-based targeting (e.g., specific days or hours) for better CTRs.
- 🎯 Tailor ads to specific **income brackets**, **cities**, and **age groups**.
- 🧪 A/B test ad content variations (language, visuals) aligned to audience segments.

---

## 📁 Repository Structure

```
Customer-Clicked-Ads-Classification/
│
├── data/
│   ├── Clicked Ads Dataset.csv           # Original dataset
│   └── preprocessed_untargeted.csv       # Cleaned & processed version
│
├── code/
│   ├── ClickedAds_EDA.ipynb              # Step 1: Exploratory Data Analysis
│   ├── ClickedAds_PreProc.ipynb          # Step 2: Preprocessing
│   └── ClickedAds_Classification.ipynb   # Step 3: Modeling
│
├── Final Presentation.pdf                # Business presentation
└── README.md                             # Project documentation
```

---

## 🛠️ Tech Stack

🧠 **Python**  
📊 **Pandas**, **Seaborn**, **Plotly**, **Matplotlib**  
📈 **Scikit-Learn**, **StandardScaler**, **Logistic Regression**, **Random Forest**, **SVM**

---

## 📌 Author

👨‍💻 **Bramantyo Raka Adi Nugroho**  
🔗 **GitHub:** [Bramasta66](https://github.com/Bramasta66)  
📧 **Email:** brambsns@gmail.com  
🌍 **LinkedIn:** [Bram Raka](https://www.linkedin.com/in/bramraka666/)  
