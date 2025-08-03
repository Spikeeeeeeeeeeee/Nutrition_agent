# Nutrition_agent
# 🧠 Nutrition Agent – Personalized Meal Planning using IBM Cloud & AI

## 👤 Presented By
**Abtahi Sayed**  
S G Balekundri Institute of Technology  


## 📘 Project Overview

This capstone project introduces an AI-powered **Nutrition Agent** designed to deliver **real-time, explainable, and highly personalized meal plans** to users. Leveraging **IBM Cloud**, **Watson AI**, and **Granite LLM**, the system simulates the experience of interacting with a professional dietician—providing diet suggestions that adapt to the user’s goals, allergies, medical conditions, and preferences.

---

## ❓ Problem Statement

While health awareness continues to grow, most nutritional tools in the market suffer from:

- Generic diet plans that don't personalize effectively
- Lack of real-time adaptability and contextual intelligence
- No support for allergies, health conditions, or cultural preferences
- Inability for human dieticians to scale one-on-one consultations

Thus, there's a clear need for a **scalable, adaptive, and intelligent nutrition recommendation system**.

---

## 💡 Proposed Solution

The proposed Nutrition Agent uses a combination of **AI**, **machine learning**, and **cloud deployment** to provide users with personalized dietary recommendations. The system includes:

### 🔍 Data Collection
- User profile (age, gender, height, weight, goals)
- Health conditions (e.g., diabetes, hypertension)
- Allergies, food preferences
- Voice and image inputs using IBM Watson services

### 🧹 Data Preprocessing
- NLP to extract relevant information from inputs
- Voice-to-text using IBM Watson Speech-to-Text
- Structured data formatting for model input

### 🤖 AI/ML Integration
- Uses **IBM Granite LLM** for dynamic meal generation
- Custom prompts based on health and dietary constraints
- Feedback loop incorporated for continuous adaptation

### ☁️ Deployment
- Chatbot interface built with **IBM Watson Assistant**
- Backend logic using **IBM Cloud Functions (Serverless)**
- Hosted on **IBM Cloud Lite tier**

### 📊 Evaluation
- User feedback analysis for personalization
- Meal plan performance monitoring and improvements

---

## ⚙️ System Requirements

### 💻 Hardware
- Intel i5 Processor or above
- Minimum 8 GB RAM
- Stable internet connection
- Webcam and Microphone

### 🛠️ Software & Libraries
- **Python 3.8+**
- Libraries: `pandas`, `opencv-python`, `flask`, `ibm-watson`, `requests`

---

## 🧠 Algorithm Details

### 📈 Model & Logic
- **Granite LLM** used for natural language understanding and generation
- Rule-based filtering ensures medical safety and precision
- Prompts are dynamically crafted per user (e.g., "no sugar" for diabetics)

### 🧾 Input Data
- Demographics and health parameters
- Specific goals (e.g., weight loss, muscle gain)
- Constraints (e.g., allergies, vegetarianism)

### 📤 Output
- Fully structured meal plans
- Explanation for each recommendation (e.g., “Low sodium due to hypertension”)

---

## 🚀 Deployment Workflow

```bash
1. Collect user data through chatbot/voice
2. Preprocess data and generate prompt
3. Call Granite LLM for meal plan generation
4. Present results via chatbot
5. Store user feedback and refine prompts


