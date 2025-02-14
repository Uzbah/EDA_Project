# AeroFit Treadmill Customer Analysis - EDA Project

## 🎯 Project Overview
This project performs Exploratory Data Analysis (EDA) on AeroFit's treadmill customer data to identify target audience characteristics for different treadmill models. The analysis aims to provide better product recommendations to new customers based on their profiles.

## Product Portfolio
- **KP281**: Entry-level treadmill ($1,500)
- **KP481**: Mid-level treadmill ($1,750)
- **KP781**: Advanced features treadmill ($2,500)

## Tech Stack
- Python 3.2
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset Features
- Product (KP281, KP481, or KP781)
- Age (in years)
- Gender (male/female)
- Education (in years)
- MaritalStatus (single/partnered)
- Usage (average weekly usage)
- Fitness (self-rated 1-5 scale)
- Income (annual income in USD)
- Miles (expected weekly miles)

## 📈 Analysis Components

### 1. Data Exploration and Processing
- Data import and initial examination
- DataFrame shape analysis
- Datatype verification
- Missing value detection
- Duplicate value checking

### 2. Statistical Analysis
- Descriptive statistics for numerical features
- Category distribution analysis
- Feature correlation analysis

### 3. Visualization
- Univariate Analysis
  - Distribution plots
  - Count plots
  - Box plots
- Bivariate Analysis
  - Product vs. demographic features
  - Feature relationship analysis
- Multivariate Analysis
  - Pair plots
  - Correlation heatmaps

### 4. Advanced Analysis
- Outlier detection using IQR method
- Conditional probability analysis
- Customer segment profiling

##  Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Installation
1. Clone the repository
```bash
git clone https://github.com/yourusername/aerofit-treadmill-analysis.git
cd aerofit-treadmill-analysis
```

2. Install required packages
```bash
pip install -r requirements.txt
```

## 🔍 Key Findings & Recommendations

### 1. Gender and Product Preference
- KP781 shows stronger appeal among male customers
- Female customers demonstrate lower interest in high-end models
- **Recommendation**: Target KP781 marketing towards male demographics while developing female-oriented features

### 2. Age and Product Preference
- KP281 is popular in the 20-30 age bracket
- KP781 attracts customers in the 30-50 age range
- **Recommendation**: Implement age-specific marketing campaigns emphasizing affordability for younger buyers and advanced features for older customers

### 3. Income and Product Preference
- Lower-income segments gravitate towards KP281
- Higher-income customers prefer KP781
- **Recommendation**: 
  - Offer strategic discounts for KP281
  - Implement premium positioning for KP781 in affluent markets

### 4. Fitness Level and Product Preference
- Customers with fitness level 5 strongly prefer KP781
- **Recommendation**: Position KP781 as the ideal choice for advanced users with premium fitness goals

### 5. Marital Status Impact
- Partnered customers represent the majority of treadmill users
- **Recommendation**: Frame treadmills as essential tools for couples' and family fitness

### Overall Strategic Recommendations
1. Implement segmented marketing strategies based on:
   - Age demographics
   - Income levels
   - Fitness experience
2. Develop tailored promotions:
   - Installment plans for KP281
   - Premium add-ons for KP781
3. Clear product positioning:
   - KP281: Entry-level, budget-friendly option
   - KP481: Balanced performance and value
   - KP781: Premium choice for serious users
4. Consider developing a product below KP281's price point to:
   - Diversify product portfolio
   - Expand customer base
   - Drive revenue in budget segment

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## 👤 Author
[Uzbah Naseem]
- GitHub: [https://github.com/Uzbah]
- LinkedIn: [www.linkedin.com/in/uzbah-naseem]

---
⭐️ If you found this project helpful, please consider giving it a star!
