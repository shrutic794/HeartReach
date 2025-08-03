#  HeartReach: AI-Powered Cardiovascular Triage & Support for Women in Remote Areas

##  Overview
**HeartReach** is a multilingual, voice-enabled triage assistant designed to detect early signs of cardiovascular disease (CVD) in women, especially in **rural and underserved communities**. Built for **offline**, **low-literacy**, and **low-connectivity** environments, it combines **edge AI**, **context-aware logic**, and **empathetic health dialogue** to empower users with timely, personalized health insights.

---

##  Problem Statement
Cardiovascular disease is the leading cause of death among women globally, yet it remains **underdiagnosed** due to:
- Gender-biased symptom recognition
- Limited access to screening in rural areas
- Lack of culturally-tailored health tools

**HeartReach** addresses these gaps by thinking *female-first*, *offline-first*, and *community-first*.

---

##  Key Features
-  **Voice-Driven Interface**: Users answer simple, spoken questions in their native language.
-  **Multilingual Support**: English, Hindi, and Spanish with future support for Tamil and Bengali.
-  **AI Risk Prediction**: Calculates cardiovascular risk using parameters like age, BMI, lifestyle, hypertension, anxiety, and family history.
-  **Offline Functionality**: Fully operational without internet — ideal for field deployment.
-  **Care Guidance**: Based on WHO/AHA guidelines, users receive tailored next-step suggestions (e.g., visit clinic, rest, monitor again).
-  **Risk Visualization**: Intuitive, color-coded progress bar with optional text-to-speech.

---

##  Technologies Used
- **Android Studio**, **Java**, **Jetpack Compose**
- **ML Model**: Logistic regression / ensemble models trained offline
- **Text-to-Speech (TTS)** API – for audio guidance
- **Room DB / SharedPreferences** – offline storage
- **Multilingual JSON templates** – for question flow and responses

---


## 🩺 Sample Risk Factors Considered
- Age, Height, Weight
- Family history of CVD
- Hypertension
- Anxiety or chronic stress
- Physical inactivity
- Menopause status

---


