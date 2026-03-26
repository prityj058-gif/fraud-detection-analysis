 # 📊 Fraud Detection Data Analysis

## 📌 Project Overview
This project analyzes financial transaction data to identify patterns, anomalies, and potential fraud indicators. The goal is to uncover hidden insights that can help improve fraud detection systems.

---

## 🎯 Objectives
- Analyze transaction behavior  
- Identify suspicious patterns  
- Detect potential fraud indicators  
- Generate actionable business insights  

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📂 Dataset Features
The dataset includes the following key features:
- Transaction details (amount, time, frequency)  
- Customer information  
- Merchant risk score  
- Device type  
- Payment channel  
- Geographic data  
- Fraud label (`is_fraud`)  

---

## 📥 Data Loading
- Loaded dataset using Pandas  
- Previewed data using `.head()`  
 

---

## 🔍 Data Understanding
- Checked dataset shape and structure  
- Explored dataset using `.info()` and `.describe()`  
- Identified important variables  
- Understood fraud distribution  

---

## 🧹 Data Cleaning
- Handled missing values  
- Converted data types (datetime format)  
- Removed duplicate records  
- Ensured data consistency  

---

## 📊 Exploratory Data Analysis 

### 📊 Transaction Amount Analysis
- Analyzed distribution of transaction amounts  
- Compared fraud vs non-fraud transactions  

**Insight:**  
Higher transaction amounts are more likely to be fraudulent.

---

### 🏪 Merchant Risk Score Analysis
- Examined fraud rate across merchant risk scores  

**Insight:**  
Higher merchant risk scores are strongly associated with fraud.

---

### ⚡ Transaction Frequency Analysis
- Analyzed number of transactions per hour/day  

**Insight:**  
Sudden spikes in transaction frequency indicate suspicious activity.

---

### 🌍 International Transaction Analysis
- Compared domestic vs international transactions  

**Insight:**  
International transactions have a higher probability of fraud.

---

### 📱 Device Type Analysis
- Studied fraud distribution across device types  

**Insight:**  
Certain device types show increased fraud activity.

---

### ❌ Failed Transactions Analysis
- Analyzed failed transaction attempts  

**Insight:**  
Multiple failed transactions are a strong fraud signal.

---

### 📍 Location Distance Analysis
- Measured distance between consecutive transactions  

**Insight:**  
Large location changes in a short time indicate suspicious behavior.

---

### 💰 Spending Deviation Analysis
- Compared transaction amount with user’s average spending  

**Insight:**  
Significant deviation from normal spending is highly suspicious.

---

### 💳 Payment Channel Analysis
- Compared fraud rates across payment methods  

**Insight:**  
Some payment channels are more vulnerable to fraud.

---

## 📌 Conclusion
The analysis reveals clear patterns associated with fraudulent transactions, such as high transaction amounts, unusual frequency, and abnormal user behavior. These insights can help in building effective fraud detection systems.

---

## 🚀 Future Improvements
- Build machine learning models for fraud prediction  
- Implement real-time fraud detection  
- Perform advanced feature engineering  

---

## 👩‍💻 Author
 
Prity Jaiswal

Aspiring Data Analyst passionate about transforming raw data into meaningful insights.

GitHub: https://github.com/prityj058-gif
