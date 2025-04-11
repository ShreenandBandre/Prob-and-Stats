# 🛒 Market Basket Analysis & Recommendation System

This project is a comprehensive implementation of **Market Basket Analysis** using the **Apriori algorithm**, designed to derive useful insights from transaction data and build a simple recommendation system. It is divided into four logical parts for clarity and deeper exploration of association rules.

---

## 📁 Project Structure

### 1. **Main Code**
- Implements the core logic of **Market Basket Analysis** using the **Apriori Algorithm**.
- Utilizes a transactional dataset to generate association rules.
- Computes essential metrics: **Support**, **Confidence**, and **Lift**.
- Provides a **comparative visualization** to understand algorithmic performance and rule generation effectiveness.

### 2. **Comparison**
- Displays a **heatmap-based comparison** between all the metrics.
- Helps identify strong associations visually for better insight into the dataset.
- Useful for quick exploratory analysis before deep-diving.

### 3. **Advanced Analysis**
- Extends the basic analysis by including **more refined metrics** and deeper statistical insights.
- Focuses on user-driven trends and business-critical patterns.
- Aims to enhance both **user experience** and **business decision-making** through smarter analysis.

### 4. **Recommendation System**
- A simple, terminal-based **recommendation system**.
- Allows the user to input new transactional data manually.
- Processes the input through the trained Apriori model and returns relevant item recommendations.
- Designed for ease of use and quick evaluation of product associations.

---

## ⚙️ Technologies & Libraries Used

- **Python**
- **Pandas**
- **mlxtend** (for Apriori algorithm & rule extraction)
- **Matplotlib / Seaborn** (for data visualization)
- **NumPy**

---
--------------------------------------------------------------------------------------------------------------------------------------------
## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/market-basket-analysis.git
   cd market-basket-analysis
2.**Install Required Libraries**
```bash
  pip install pandas mlxtend matplotlib seaborn
```
-------------------------------------------------------------------------------------------------------------------------------------------
### **Sample Outputs**
- **Bar charts comparing support, confidence, and lift.**
- **Heatmaps showing strong association rules.**
- **Rule tables with sorted metrics.**
- **Terminal-based recommendations from user-entered data.**

-------------------------------------------------------------------------------------------------------------------------------------------
### **Insights & Applications**
- **Identify frequently bought itemsets to boost cross-selling.**
- **Understand consumer behavior and optimize shelf layouts or product bundles.**
- **Enhance personalized marketing using user-specific recommendation outputs.**
-------------------------------------------------------------------------------------------------------------------------------------------
### **Future Scope**
- **Integration with a GUI or web app for user-friendly interaction.**
- **Real-time transactional data integration.**
- **Improved algorithms like FP-Growth for larger datasets.**
-------------------------------------------------------------------------------------------------------------------------------------------
### **Contributors**
- **1. Shreenand Bandre.**
- **2. Rushikesh Shinde.**
- **3. Yash Gaikwad.**
-------------------------------------------------------------------------------------------------------------------------------------------
### **Feedback**
- **Feel free to open issues or pull requests. We appreciate any kind of feedback to improve our project!**

