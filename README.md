# GigShield AI
AI-Powered Parametric Insurance for India's Gig Delivery Workers

Guidewire DEVTrails Hackathon 2026

Team Name: CoreX

Team Members
- Pothireddy Akhil Kumar Reddy
- B Manoj Kumar
- Nagam Teja Narayana Reddy
- Yamparala Divyesh
- Maddula Krishna Vamsi

---

# 1. Problem Statement

India’s gig economy relies heavily on delivery partners working with platforms such as Swiggy, Zomato, Amazon, and Zepto.

However, these workers frequently face external disruptions such as:

- Heavy rain
- Extreme heat
- Severe air pollution
- Traffic congestion
- Local curfews or zone closures

These disruptions reduce working hours and cause **loss of income**.

Currently, gig workers do not have insurance protection specifically designed for such income loss.

GigShield AI aims to solve this problem by providing an **AI-powered parametric insurance platform that automatically compensates gig workers when disruptions occur.**

---

# 2. Persona Scenario

Persona: Food Delivery Partner (Swiggy / Zomato)

Example:

Ravi is a delivery partner working in Hyderabad.  
He typically works 8 hours per day and earns around ₹4000 per week.

During heavy rainfall days or severe pollution conditions, delivery demand drops significantly and Ravi cannot complete enough orders.

This results in loss of income.

GigShield AI provides **weekly income protection insurance** that automatically compensates workers like Ravi when such disruptions occur.

---

# 3. Proposed Solution

GigShield AI is an AI-enabled parametric insurance platform designed for gig delivery workers.

The platform continuously monitors environmental conditions affecting delivery operations.

Using AI models, the system predicts disruption risk and automatically triggers claims when predefined conditions are met.

Workers do not need to manually submit claims.

The system automates:

- disruption detection
- risk prediction
- claim triggering
- payout simulation

---

# 4. Application Workflow

1. Worker registers on the platform
2. Worker selects operating delivery zone
3. System monitors environmental conditions using APIs
4. AI model calculates disruption risk score
5. If disruption thresholds are crossed
6. Insurance claim is automatically triggered
7. Claim is processed
8. Payment simulation is executed

---

# 5. Hyper-Local Risk Zones (Innovation Feature)

GigShield AI introduces **Hyper-Local Risk Zones**.

Instead of applying a single risk level to an entire city, the system divides cities into multiple operational zones.

Example:

Hyderabad

- Zone A – High Flood Risk
- Zone B – Medium Risk
- Zone C – Low Risk

Each zone has different disruption probabilities based on environmental and traffic conditions.

Workers operating in safer zones receive lower premiums, while workers in high-risk zones receive higher coverage.

This improves risk prediction accuracy and enables fair pricing.

---

# 6. Parametric Triggers

Parametric insurance uses predefined triggers to automatically initiate claims.

Example triggers used in GigShield AI:

| Trigger | Condition | Impact |
|-------|-------|-------|
Heavy Rain | Rainfall > 50 mm | Deliveries halted |
Extreme Heat | Temperature > 45°C | Unsafe working conditions |
Air Pollution | AQI > 300 | Outdoor work unsafe |
Traffic Congestion | Traffic index above threshold | Delivery delays |

When these triggers occur, the system automatically processes insurance claims.

---

# 7. Weekly Premium Model

Gig workers operate on a weekly earning cycle.

Therefore the insurance premium is structured using a **weekly pricing model**.

| Risk Level | Weekly Premium | Coverage |
|------|------|------|
Low Risk | ₹35 | ₹1200 |
Medium Risk | ₹60 | ₹2500 |
High Risk | ₹90 | ₹4000 |

Premium values are dynamically adjusted using AI risk analysis.

---

# 8. AI / Machine Learning Integration

Machine learning is used in three major components.

### 1. Risk Prediction

The AI model analyzes environmental conditions to predict disruption probability.

Input parameters:

- rainfall
- temperature
- AQI
- traffic congestion
- simulated delivery demand

Example simplified formula:

Risk Score =
0.4 × weather risk +
0.3 × pollution risk +
0.2 × traffic risk +
0.1 × delivery demand drop

---

### 2. Dynamic Premium Calculation

Weekly premiums are adjusted based on predicted disruption risk in the worker's operating zone.

Low risk zones → lower premiums  
High risk zones → higher premiums

---

### 3. Fraud Detection

The system detects suspicious claims using:

- GPS location verification
- duplicate claim detection
- anomaly detection
- abnormal claim patterns

---

# 9. External Data Sources

GigShield AI uses a combination of real-time APIs and simulated data.

### Weather API

Used to monitor rainfall and temperature conditions.

Example parameters:

- rainfall
- temperature
- humidity
- weather alerts

---

### Air Quality API (AQI)

Used to detect pollution levels affecting outdoor work.

Example parameters:

- AQI
- PM2.5 levels

---

### Mock Delivery Data

Since delivery platform data is not publicly available, the system uses simulated delivery activity data.

Example data:

- delivery demand
- orders per hour
- delivery success rate

---

# 10. System Architecture

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

# 11. Technology Stack

Frontend  
React.js

Backend  
Python (FastAPI or Flask)

Database  
MongoDB

AI / Machine Learning  
Python (Scikit-learn)

External APIs

- OpenWeather API
- AQI API
- Mock traffic data

---

# 12. Repository Structure

guidewire-hackathon-CoreX

GigShield-AI  
│  
├── frontend  
├── backend  
│  
├── README.md  
├── architecture.png  
└── ai_workflow.png

Frontend folder will contain:

- worker registration UI
- insurance dashboard
- claim status interface

Backend folder will contain:

- API endpoints
- AI risk model
- claim processing logic
- database integration

---

# 13. Development Roadmap

Phase 1 – Ideation & Planning

- problem research
- system architecture design
- AI workflow design
- documentation

Phase 2 – Automation & Protection

- worker registration
- insurance policy management
- dynamic premium calculation
- automated claim triggers

Phase 3 – Scale & Optimization

- fraud detection
- instant payout simulation
- analytics dashboard
- predictive disruption insights

---

# 14. Expected Impact

GigShield AI provides financial protection for gig workers by protecting their income from sudden disruptions.

The platform introduces an automated and AI-driven insurance system specifically designed for the gig economy.

---

# Demo Video

Phase-1 demo video link will be added here.
