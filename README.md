# ❤️ Heart Disease AI Diagnostic Tool

ระบบวิเคราะห์ความเสี่ยงโรคหัวใจด้วย Machine Learning และ Dashboard แบบ Interactive  
พัฒนาโดยใช้ AutoML เพื่อเลือกโมเดลที่ดีที่สุด และแสดงผลผ่าน Web Dashboard

---

## 🔍 Overview
โปรเจกต์นี้มีวัตถุประสงค์เพื่อพยากรณ์ความเสี่ยงของโรคหัวใจจากข้อมูลสุขภาพของผู้ป่วย  
โดยใช้เทคนิค Machine Learning และ AutoML (AutoGluon)  
พร้อมแสดงผลผ่าน Dashboard ที่ใช้งานง่าย

---

## 🚀 Features
- วิเคราะห์ความเสี่ยงโรคหัวใจแบบ Real-time  
- ใช้ AutoML เพื่อเลือกโมเดลอัตโนมัติ  
- ใช้ Ensemble เพิ่มความแม่นยำ  
- รองรับการเลือก Country เพื่อปรับผลลัพธ์  
- แสดงผลเป็นเปอร์เซ็นต์ความเสี่ยง  
- มีกราฟ Feature Importance และ EDA  

---

## 🧠 Machine Learning
โปรเจกต์นี้ใช้ AutoML (AutoGluon) เพื่อทดลองหลายโมเดล เช่น:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Neural Network  

และใช้เทคนิค Ensemble เพื่อรวมผลลัพธ์จากหลายโมเดล  
ทำให้ได้ผลลัพธ์ที่แม่นยำและเสถียรมากขึ้น

---

## 📊 Important Features
โมเดลให้ความสำคัญกับตัวแปรหลัก ได้แก่:
- CP (Chest Pain) – ประเภทอาการเจ็บหน้าอก  
- Thalach (Max Heart Rate) – อัตราการเต้นหัวใจสูงสุด  
- Oldpeak (ST Depression) – ความผิดปกติของคลื่นหัวใจ  

---

## 🗂 Dataset
- ใช้ชุดข้อมูล Heart Disease Dataset  
- จำนวนข้อมูล: 303 แถว  
- จำนวนตัวแปร: 14 คอลัมน์  
- ตัวแปรสำคัญ เช่น Age, Sex, Cholesterol, Blood Pressure, Target  

---

## 🖥️ Dashboard
พัฒนาโดยใช้:
- Python  
- Dash  
- Plotly  

ความสามารถ:
- กรอกข้อมูลสุขภาพ  
- วิเคราะห์ผลทันที  
- แสดงผลเป็นเปอร์เซ็นต์  
- แสดงกราฟช่วยวิเคราะห์  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- Plotly  
- Dash  
- AutoGluon (AutoML)

---

## ⚙️ Installation
```bash
git clone https://github.com/your-username/heart-disease-ai.git
cd heart-disease-ai
pip install -r requirements.txt