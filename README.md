# GigShield AI
### AI-Powered Parametric Insurance for India's Gig Delivery Workers

## Team
Team Name: CoreX

Members:
- Pothireddy Akhil Kumar Reddy
- B Manoj Kumar
- Nagam Teja Narayana Reddy
- Yamparala Divyesh
- Maddula Krishna Vamsi

Guidewire DEVTrails Hackathon 2026

---

# 1. Problem Statement

India’s gig economy relies heavily on delivery partners working with platforms like Swiggy, Zomato, Amazon, Zepto and others.

However, external disruptions such as:

- Heavy rain
- Extreme heat
- Severe air pollution
- Traffic congestion
- Curfews or sudden area shutdowns

can prevent delivery workers from completing orders.

This leads to **loss of income**, and currently there is **no insurance protection for such situations**.

Our goal is to build an **AI-powered parametric insurance platform that protects gig workers from income loss caused by these disruptions.**

---

# 2. Persona Scenario

Persona: Food Delivery Partner (Swiggy / Zomato)

Example scenario:

Ravi is a delivery partner working 8 hours per day and earning approximately ₹4000 per week.

During heavy rain or severe pollution days, delivery demand drops or workers are unable to operate safely.

As a result, Ravi loses daily earnings.

GigShield AI provides **weekly income protection insurance** that automatically compensates workers when disruptions occur.

---

# 3. Proposed Solution

GigShield AI is an **AI-enabled parametric insurance system** that continuously monitors environmental conditions and predicts the risk of income loss.

If predefined conditions are triggered, the system automatically initiates a claim and simulates a payout.

Workers do not need to manually file claims.

---

# 4. Application Workflow

1. Worker registers on the platform
2. System collects location and working zone information
3. AI engine monitors environmental data
4. Risk score is calculated
5. If disruption threshold is crossed:
   - Claim is automatically triggered
6. System processes the claim
7. Payment simulation is executed

---

# 5. Parametric Triggers

Claims are triggered automatically when predefined environmental conditions occur.

Example triggers:

| Trigger | Condition | Impact |
|-------|-------|-------|
Heavy Rain | Rainfall > 50 mm | Delivery disruption |
Extreme Heat | Temperature > 45°C | Unsafe working conditions |
Air Pollution | AQI > 300 | Health risk for outdoor work |
Traffic Congestion | Traffic index > threshold | Delivery slowdown |

These triggers ensure **automated claim processing without manual verification**.

---

# 6. Weekly Premium Model

Gig workers operate on a weekly earning cycle, so the insurance premium is also structured weekly.

| Risk Level | Weekly Premium | Coverage |
|-----------|---------------|----------|
Low Risk | ₹35 | ₹1200 |
Medium Risk | ₹60 | ₹2500 |
High Risk | ₹90 | ₹4000 |

Premium is dynamically adjusted using AI risk prediction.

---

# 7. AI / Machine Learning Integration

AI is used for three main tasks:

### 1. Risk Prediction
AI analyzes environmental conditions to estimate the probability of delivery disruptions.

Input parameters:

- rainfall
- temperature
- AQI
- traffic congestion
- historical disruption data

Example risk score formula:

Risk Score =  
0.4 × weather risk  
+ 0.3 × pollution risk  
+ 0.3 × traffic risk

---

### 2. Dynamic Premium Calculation

The system adjusts the weekly premium depending on predicted disruption risk in the worker’s area.

Higher risk → slightly higher premium  
Lower risk → reduced premium

---

### 3. Fraud Detection

The system identifies suspicious claims using:

- GPS validation
- anomaly detection
- duplicate claim detection
- abnormal claim frequency

---

# 8. System Architecture

The system consists of the following components:

Worker App  
↓  
Frontend (React)  
↓  
Backend API (Spring Boot)  
↓  
Database (MongoDB)  
↓  
AI Risk Engine  
↓  
External APIs (Weather, AQI, Traffic)  
↓  
Claim Processing  
↓  
Payment Simulation

---

# 9. Technology Stack

Frontend  
React.js

Backend  
Spring Boot (Java)

Database  
MongoDB

AI / ML  
Python (Scikit-learn)

External APIs

- OpenWeather API
- AQI API
- Traffic API (mock data allowed)

---

# 10. Development Roadmap

### Phase 1 – Ideation & Research
- Problem analysis
- System architecture
- AI workflow design
- README documentation

### Phase 2 – Automation & Protection
- Worker registration
- Insurance policy management
- Dynamic premium calculation
- Automated claim triggers

### Phase 3 – Scale & Optimization
- Fraud detection
- Instant payout simulation
- Worker & admin dashboards
- Predictive analytics

---

# 11. Expected Impact

GigShield AI aims to provide financial stability to gig workers by protecting their income against uncontrollable external disruptions.

The platform creates a **simple, automated, and AI-driven insurance system designed specifically for the gig economy.**

---

# Repository Structure
