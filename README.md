# GigShield AI
AI-Powered Parametric Insurance for India's Gig Delivery Workers

Guidewire DEVTrails Hackathon 2026

Team Name: CoreX

Team Members:
- Pothireddy Akhil Kumar Reddy
- B Manoj Kumar
- Nagam Teja Narayana Reddy
- Yamparala Divyesh
- Maddula Krishna Vamsi

---

# 1. Problem Statement

India’s gig economy relies heavily on delivery workers working with platforms such as Swiggy, Zomato, Amazon, Zepto and Dunzo.

However, these workers often face external disruptions such as:

- Heavy rainfall
- Extreme heat
- Severe air pollution
- Traffic congestion
- Local curfews or zone closures

These disruptions reduce working hours and cause **loss of income**.

Currently, gig workers do not have insurance protection for such income loss.

GigShield AI solves this problem by creating an **AI-powered parametric insurance system** that automatically compensates gig workers when disruptions occur.

---

# 2. Persona Scenario

Persona: Food Delivery Partner (Swiggy / Zomato)

Example scenario:

Ravi is a delivery partner working in Hyderabad.  
He works around 8 hours daily and earns approximately ₹4000 per week.

During extreme rain or severe pollution days, deliveries drop significantly and Ravi cannot complete orders.

This results in income loss.

GigShield AI provides **weekly income protection insurance** that automatically compensates Ravi during such disruptions.

---

# 3. Proposed Solution

GigShield AI is an AI-powered platform that monitors environmental conditions affecting delivery operations.

The platform uses APIs to collect real-time environmental data and applies machine learning models to estimate disruption risk.

If disruption thresholds are exceeded, the system automatically:

1. Detects disruption conditions
2. Triggers an insurance claim
3. Simulates payout for lost income

Workers do not need to manually submit claims.

---

# 4. Application Workflow

1. Worker registers on the platform
2. Worker location and delivery zone are recorded
3. System monitors environmental conditions using APIs
4. AI model calculates disruption risk score
5. If disruption threshold is crossed
6. Claim is automatically triggered
7. Claim is processed
8. Payment simulation is executed

---

# 5. Parametric Triggers

Parametric insurance uses predefined triggers to automate claims.

Example triggers used in GigShield AI:

| Trigger | Condition | Impact |
|------|------|------|
Heavy Rain | Rainfall > 50 mm | Deliveries halted |
Extreme Heat | Temperature > 45°C | Unsafe working conditions |
Air Pollution | AQI > 300 | Outdoor work unsafe |
Traffic Congestion | Traffic index above threshold | Delivery delays |

When these triggers occur, the system automatically initiates claims.

---

# 6. Weekly Premium Model

Gig workers operate on a weekly earning cycle.

Therefore the insurance premium is structured as a **weekly pricing model**.

| Risk Level | Weekly Premium | Coverage |
|------|------|------|
Low Risk | ₹35 | ₹1200 |
Medium Risk | ₹60 | ₹2500 |
High Risk | ₹90 | ₹4000 |

Premium values are dynamically adjusted using AI risk prediction.

---

# 7. AI / Machine Learning Integration

Machine learning is used for the following tasks.

### Risk Prediction

The system analyzes environmental conditions to estimate disruption probability.

Input parameters include:

- rainfall
- temperature
- AQI
- traffic congestion
- historical disruption patterns

Example risk score formula:

Risk Score =
0.4 × weather risk +
0.3 × pollution risk +
0.3 × traffic risk

---

### Dynamic Premium Calculation

The system adjusts weekly premiums based on predicted disruption risk in the worker’s area.

Low risk areas → lower premiums  
High risk areas → higher premiums

---

### Fraud Detection

The platform detects suspicious claims using:

- GPS location verification
- duplicate claim detection
- anomaly detection
- abnormal claim patterns

---

# 8. System Architecture

The system architecture includes the following components:

Worker Application  
↓  
Frontend Interface  
↓  
Backend API  
↓  
Database  
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
Python (FastAPI / Flask)

Database  
MongoDB

AI / Machine Learning  
Python (Scikit-learn)

External APIs

- OpenWeather API
- AQI API
- Traffic API (mock data allowed)

---

# 10. Repository Structure
