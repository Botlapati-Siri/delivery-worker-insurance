
## 1. Problem Definition

Delivery workers face high risks on roads while delivering orders. 
Most gig workers cannot afford traditional insurance plans.

Our system provides an affordable weekly insurance model with automated claim detection.

---

## 2. Delivery Worker Personas

### Persona 1 – Ravi
Age: 28  
Platform: Swiggy  
Vehicle: Bike  
Income: ₹900/day

Pain Points
- No accident protection
- Medical costs
- Income loss

---

### Persona 2 – Aisha
Age: 22  
Platform: Zomato  
Part time delivery worker

Pain Points
- Irregular income
- Cannot afford monthly insurance

---

## 3. User Scenario

Ravi starts his delivery shift.

1. Opens the app
2. Pays ₹25 weekly premium
3. Starts deliveries
4. Accident detected through phone sensors
5. Automatic claim generated
6. Insurance payout processed

---

## 4. Application Workflow

Signup → Worker Verification → Premium Calculation → Weekly Payment → Delivery Monitoring → Accident Detection → Claim Processing → Payout

---

## 5. Weekly Premium Model

Base Premium = ₹20/week

Factors affecting premium:
- Working hours
- Distance travelled
- Delivery count
- Risk zone
- Past accident history

Example:

Base premium = ₹20  
High traffic zone = ₹5  
Long distance = ₹3  

Final Premium = ₹28/week

---

## 6. Parametric Triggers

Accident detection using:

- Phone accelerometer
- GPS sudden stop
- Delivery app activity

Triggers:
- High impact motion
- Sudden speed drop
- No movement after accident

System automatically starts claim verification.

---

## 7. AI/ML Integration

AI will be used for:

1. Premium Calculation
AI predicts accident risk.

2. Fraud Detection
Checks fake claims using GPS data and motion patterns.

3. Risk Prediction
Identifies unsafe driving behaviour.

---

## 8. Platform Choice

Mobile Application

Reasons:
- Delivery workers use smartphones
- Access to sensors
- GPS tracking possible

---

## 9. Tech Stack

Frontend
- React Native / Flutter

Backend
- Node.js
- Express.js

Database
- MongoDB

AI/ML
- Python
- TensorFlow

Cloud
- Firebase / AWS

---

## 10. Development Plan

Week 1
Research and planning

Week 2
UI prototype

Week 3
Backend setup

Week 4
Premium model

Week 5
AI integration

Week 6
Testing
