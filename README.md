# 🩺 EasySwasth
### Health Explainer System

EasySwasth is a Django + React based healthcare assistance system designed especially for **rural users**.  
It explains medical reports and health conditions in **simple Hindi / Hinglish** and provides affordable food, yoga, and lifestyle guidance.

---

## 🌾 Problem Statement
In rural areas:
- People do not understand medical reports  
- Many avoid medical tests due to lack of money  
- Access to doctors and labs is limited  

This results in late diagnosis and serious health problems.

---

## 💡 Solution
EasySwasth helps users by:
- Explaining medical reports in **easy language**  
- Providing **symptom-based health checks** when reports are not available  
- Suggesting **Indian diet, yoga, and lifestyle changes**  
- Helping users find **free or low-cost diagnostic labs**

---

## 🎯 Target Audience
- Rural population  
- Users with low medical awareness  
- Hindi / Hinglish speaking users  

---

## ✨ Core Features

### 📄 1. Medical Report Upload
- Upload PDF or image reports  
- Supported tests:
  - Blood Test / CBC  
  - Thyroid  
  - Sugar (FBS, PP, HbA1c)  
  - Lipid Profile  

The system extracts values and identifies:
- Normal  
- Borderline  
- Abnormal  

---

### 🩺 2. Symptom-Based Health Check (No Report Required)
- Users can select symptoms  
- Manual entry of test values (single or multiple)  
- Risk score generation  
- Minimal test recommendations  

---

### 🧠 3. Easy Language Explanation (Core Feature)
Medical results are explained in simple language.

**Example:**  
“Aapka Hemoglobin thoda kam hai. Is wajah se thakaan aur chakkar aa sakta hai.”

- Rule-based  
- Explainable  
- Safe for medical use  

---

### 🍎 4. Food Recommendation Engine
- Indian diet focused  
- Veg / Non-veg options  
- Condition-based suggestions  

| Condition | Suggested Food |
|---------|----------------|
| Low Hemoglobin | Palak, chana, gur |
| High Sugar | Lauki, oats |
| High Cholesterol | Fruits, nuts |

---

### 🧘 5. Yoga & Lifestyle Advisor
- Disease-specific yoga  
- Time duration  
- Precautions  

**Example:**  
“Diabetes ke liye Kapalbhati – 10 minute roz subah”

---

### 🏥 6. Free / Low-Cost Lab Finder 
- Government hospitals  
- NGO diagnostic centers  
- Free medical camps  
- Location-based suggestions  

---

## 🗣️ Language Support
- Hindi  
- Hinglish  
- English 

---

## 🧠 AI & Logic Approach
- Rule-based medical analysis  
- Template-based natural language explanation  
- No black-box machine learning models  

---

## 🛠️ Tech Stack

### Backend
- Django  
- Django REST Framework  

### Frontend
- React  

### OCR & Processing
- Tesseract OCR / EasyOCR  
- Rule-based medical logic  

### Database
- SQLite (development)  
- PostgreSQL 

---

## 🏗️ High-Level Architecture

User → React Frontend → Django REST API
→ OCR & Data Extraction
→ Medical Rule Engine
→ Easy Language Explanation
→ Food & Yoga Recommendations


---

## 🚀 Future Scope
- Voice-based explanations for rural users  
- Mobile application  
- Doctor verification system  
- Advanced chatbot integration  

---

## 🏆 Key Highlights
- Social impact focused project  
- Rural healthcare solution  
- Explainable AI approach  
- Full-stack development  
- Zero-cost implementation  

---

## 👩‍💻 Author
**Shristi Kumari**  
B.Tech CSE Student  
AI & Full Stack Enthusiast



