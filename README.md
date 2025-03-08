# 🚀 E-Commerce Shipping Prediction  

## 📌 Business Problem  
E-commerce companies struggle with **on-time deliveries**, leading to **customer dissatisfaction** and **revenue loss**.  
The goal of this project is to **predict whether an order will be delivered on time** based on key factors such as:  
- **Shipping Mode** (Flight, Ship, Road)  
- **Warehouse Block** (Location of product storage)  
- **Product Importance** (High, Medium, Low)  
- **Customer Calls** (Complaints & inquiries)  

By leveraging **machine learning**, this project helps businesses **optimize logistics, reduce delays, and improve customer satisfaction**.  

---

## 📊 Dataset  
- **Source:** Kaggle  
- **Size:** 10,999 entries, 12 features  
- **Key Features:**  
  - `Customer ID`, `Warehouse Block`, `Shipping Mode`, `Customer Calls`, `Ratings`, `Product Cost`, `Discounts`, `Delivery Status`  
  - **Target Variable:** `On-Time Delivery` (Yes/No)  

---

## 🔍 Steps Followed  

### **1️⃣ Data Collection & Understanding**  
- Collected **10,999 orders** with **12 features** from an e-commerce dataset.  
- Identified key variables affecting **shipping delays**.  

### **2️⃣ Data Preprocessing & Cleaning**  
✔ Checked for **missing values** – No missing data.  
✔ Checked for **duplicate rows** – No duplicate records.  
✔ Converted **categorical variables** into numerical format.  
✔ Performed **statistical analysis** to understand data distribution.  

### **3️⃣ Exploratory Data Analysis (EDA) & Key Insights**  
- **Warehouse Block F had the highest number of delays** 🚧
  
  ![image](https://github.com/user-attachments/assets/ae464de0-01fc-48ba-b30f-648cb9f44961)
 
- **Low-importance products were delayed more often** 📦
  
- **Ship mode contributed to higher delays** ⏳
  
#### ![image](https://github.com/user-attachments/assets/6921d603-ed25-4db5-a42f-7f32c64b3ab9)

    
- **Increased customer calls correlated with late deliveries** 📞  

#### ![image](https://github.com/user-attachments/assets/c68817e7-6f52-4422-b978-5f0c332da77c)


## 🧠 Machine Learning Models  
I tested **four ML algorithms** to find the most accurate model:  

| **Model**               | **Accuracy (%)** |
|-------------------------|------------------|
| **Regression Tree**     | **68.45** ✅ (Best) |
| Naïve Bayes            | 66.05            |
| Logistic Regression    | 63.50            |
| K-Nearest Neighbors    | 63.00            |

✅ **Regression Tree had the highest accuracy (68.45%)**, making it the best model for predicting late deliveries.  

---

## 🔬 Model Insights  
✔ **K-Nearest Neighbors (KNN):** Identified **Warehouse & Shipping Mode** as key factors.  
✔ **Naïve Bayes:** Provided a **probabilistic approach** but slightly lower accuracy.  
✔ **Regression Tree:** Found **Warehouse Block F & Shipping Mode as top delay predictors**.  
✔ **Logistic Regression:** Less accurate but **highly interpretable**.  

---

## 🖥️ How to Run This Project  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/your-username/ecommerce-shipping-prediction.git
cd ecommerce-shipping-prediction

