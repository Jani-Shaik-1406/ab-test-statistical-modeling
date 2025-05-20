# 🔬 Statistical Analysis: A/B Testing and Machine Learning  
**Author**: Jani Shariff Shaik  
📧 Email: shaikjanishariff@gmail.com  
🔗 LinkedIn: [jani-shariff-shaik](https://www.linkedin.com/in/jani-shariff-shaik-374998292/)  
🌐 Portfolio: [janishariffshaik.wixstudio.com/portfolio](https://janishariffshaik.wixstudio.com/portfolio)  
💻 GitHub: [github.com/janishariffshaik](https://github.com/janishariffshaik)

---

## 🎯 Project Objective

To apply A/B testing and machine learning methodologies to determine the better-performing version of a webpage, and understand key variable relationships using statistical and predictive techniques.

---

## ⚙️ Methods Used

- Inferential Statistics  
- Data Visualization  
- Probability Calculation  
- A/B Testing  
- Logistic Regression

---

## 🤖 Model Used

- **A/B Testing** using statsmodels and p-values  
- **Logistic Regression** for classification analysis

---

## 🛠️ Technologies and Libraries

- Python, Jupyter Notebook  
- NumPy, Pandas  
- Matplotlib, Statsmodels

---

## 📁 Project Description

### 🔍 Motivation  
A/B testing is widely used by data professionals to evaluate website performance. In this project, I analyzed data from an e-commerce site’s A/B test to determine whether the company should implement a new webpage or retain the old one.  

### 📊 Dataset  
- ~300,000 user entries  
- Clean and pre-processed  
- Treatment/control groups, timestamps, user interaction

---

## 📌 Methodology

### 📐 Calculated Probability  
- Calculate proportion of users converted  
- Group data by control/treatment  
- Check for duplicates  
- Compute probabilities for each condition

### 🧪 A/B Testing  
- Histogram visualization  
- Hypothesis testing  
- p-value calculation  
- Interpretation in business context

### 📈 Modeling with Logistic Regression  
- Categorical response variable analysis  
- Added interaction terms (e.g., country, timestamp)  
- Enhanced model with weekday/weekend and time-of-day features  
- Checked for multicollinearity and added higher-order terms

---

## ✅ Conclusion

- **Probability results**: Over 50% of users preferred the new page, yet actual conversion was ~12%.  
- **A/B Testing**: With a p-value > 0.05, the result is not statistically significant → **retain the old version**.  
- **Modeling Results**: Logistic regression confirms categorical behavior, with improved accuracy by adding engineered time-based variables.  

The overall design is robust, the data is unbiased, and the experiment provides clear business insights for product strategy.

---