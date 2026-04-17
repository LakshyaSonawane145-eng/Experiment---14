# 🧹 Experiment 14 : Data Binning and Data Formatting using Python

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-orange?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Ops-blue?logo=numpy)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-yellow?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 🔰 Introduction

Data preprocessing is an essential step in data analysis, and it includes techniques such as **data binning and data formatting**.

This experiment demonstrates how raw numerical data can be:
- Converted into meaningful categories using binning  
- Cleaned and standardized using formatting techniques  

The implementation is performed using Python libraries such as Pandas and NumPy to ensure efficient and structured data handling. :contentReference[oaicite:0]{index=0}

---

## 🎯 Objectives

- Understand the concept of data binning  
- Convert continuous data into categorical data  
- Perform data formatting operations  
- Improve data readability and consistency  
- Prepare datasets for further analysis  

---

## 📚 Theory

- 🔹 **Data Binning**
  - Process of grouping continuous values into discrete intervals  
  - Helps simplify analysis and detect patterns  

- 🔹 **Types of Binning**
  - Equal-width binning  
  - Custom binning (used in this experiment)  

- 🔹 **Pandas `cut()` Function**
  - Used to divide data into bins  
  - Assigns labels to each category  

- 🔹 **Data Formatting**
  - Process of transforming data into a standard format  

- 🔹 **Data Type Conversion**
  - Changing data types using `astype()`  

- 🔹 **String Operations**
  - Standardizing text using `.str.upper()`  

- 🔹 **Rounding Values**
  - Adjusting numerical precision  

- 🔹 **Sorting**
  - Arranging data using `sort_values()`  

- 🔹 **Categorical Data**
  - Data divided into groups such as Low, Medium, High  

---

## 📊 Dataset Description

### 1️⃣ Product Dataset
- Product Name  
- Price  
- Units Sold  

### 2️⃣ Order Dataset
- Order ID  
- Order Value  
- Delivery Time  
- Distance (km)  

---

## 🔧 Key Operations Performed

### 🟢 Data Binning

- Price categorized into:
  - Low  
  - Medium  
  - High  

- Units Sold categorized into:
  - Low  
  - Medium  
  - High  

- Order Value categorized into:
  - Low  
  - Medium  
  - High  

- Delivery Time categorized into:
  - Fast  
  - Normal  
  - Slow  

- Distance categorized into:
  - Short  
  - Medium  
  - Long  

---

### 🔵 Data Formatting

- ✔️ Conversion of data types (int → float)  
- ✔️ Standardization of text (uppercase conversion)  
- ✔️ Rounding numerical values  
- ✔️ Cleaning and structuring dataset  

---

### 🟣 Data Manipulation

- ✔️ Sorting data (ascending & descending)  
- ✔️ Extracting unique categories  
- ✔️ Counting category frequency using `value_counts()`  

---

## 🚀 Workflow

1. Data Creation and Loading  
2. Data Binning using `pd.cut()`  
3. Data Formatting and Cleaning  
4. Data Sorting and Organization  
5. Category Analysis  
6. Final Structured Dataset  

---

## 📈 Key Highlights

- Efficient conversion of numerical data into categories  
- Improved readability and interpretability of datasets  
- Practical implementation of binning techniques  
- Application of multiple formatting operations  
- Handling real-world structured datasets  

---

## ⚠️ Observations

- Some values fall outside bin ranges (e.g., distance), resulting in `NaN`  
- Proper bin selection is crucial for accurate categorization  
- Data formatting improves consistency and usability  

---

## ✅ Conclusion

This experiment demonstrates the importance of **data binning and formatting in preprocessing**.

Key outcomes:
- 📊 Simplified data representation using categories  
- 📉 Improved data quality and consistency  
- 📌 Better understanding of preprocessing techniques  
- 🚀 Prepared dataset for further analysis and visualization  

Data preprocessing techniques like these are essential for ensuring **accurate and meaningful data analysis**.

---

## 👨‍💻 Author

**Lakshya Sonawane**

---

## ⭐ Support

If you found this useful:
- ⭐ Star the repository  
- 🍴 Fork and explore further  
