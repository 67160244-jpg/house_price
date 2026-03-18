# 🏠 House Price Prediction Web App

## 📌 Overview

โปรเจคนี้เป็นการพัฒนา **Machine Learning Model** เพื่อทำนายราคาบ้าน
และนำโมเดลไป deploy เป็น **Web Application** ด้วย Streamlit

ผู้ใช้งานสามารถกรอกข้อมูลบ้าน เช่น จำนวนห้อง ขนาดพื้นที่ ฯลฯ
และระบบจะทำนายราคาบ้านโดยอัตโนมัติ

---

## 🎯 Objective

* สร้างโมเดลสำหรับทำนายราคาบ้าน (Regression)
* เปรียบเทียบโมเดล Machine Learning
* Deploy โมเดลเป็น Web App ให้ใช้งานได้จริง

---

## 🧠 Machine Learning Model

### 🔹 Models Used

* Random Forest Regressor (โมเดลหลัก)
* Linear Regression (ใช้เปรียบเทียบ)

### 🔹 Features (X)

ตัวอย่างข้อมูลที่ใช้ทำนาย:

* Rooms (จำนวนห้อง)
* Bathroom (จำนวนห้องน้ำ)
* Landsize (ขนาดที่ดิน)
* BuildingArea (พื้นที่ใช้สอย)
* Region (พื้นที่ตั้ง)

### 🔹 Target (y)

* Price (ราคาบ้าน)

---

## ⚙️ Workflow

1. Data Cleaning
2. Feature Engineering
3. Train/Test Split
4. Model Training (Pipeline)
5. Model Evaluation
6. Save Model (joblib)
7. Deploy with Streamlit

---

## 📊 Model Evaluation

* RMSE: ใช้วัดความคลาดเคลื่อนของราคา
* MAE: ค่า error เฉลี่ย
* R² Score: ความสามารถของโมเดลในการอธิบายข้อมูล

---

## 📈 Visualization

โปรเจคนี้มีการใช้กราฟเพื่อวิเคราะห์ข้อมูล เช่น:

* Heatmap (Correlation)
* Distribution ของราคา
* Scatter plot (Price vs Area)
* Feature Importance
* Actual vs Predicted

---

## 🚀 Web Application

สามารถใช้งานได้ผ่านลิงก์ด้านล่าง:

👉 [Live Demo](https://your-app-url.streamlit.app)

---
