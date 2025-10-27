# 🚘 Smart Modular Vehicle Monitoring System (SMVMS)

### 🎓 Final Year Research Project - SLIIT  
**Module Code:** IT4010 - Research Project - 25 July Batch  
**📚 Research Group ID:** 25-26J-308  

---

## 📖 Overview
The **Smart Modular Vehicle Monitoring System (SMVMS)** is a next-generation vehicle intelligence platform integrating **OBD-II data**, **acoustic, motion, environmental, and emission sensors**, **driver behavior analysis**, and **digital twin simulation** to enhance vehicle safety, efficiency, and sustainability.  

This system combines multiple IoT and AI modules into a modular platform that provides **real-time diagnostics, predictive analytics, eco-driving optimization**, and **driver safety monitoring**. Each module is designed to function independently, allowing for easy upgrades and extension.

---

## ⚙️ Project Components

### 1️⃣ Integrated Acoustic Intelligence and Vehicle Security Analytics System (IAVSAS)  
**Member:** Perera G.S.M (IT22335432)  

- Detects engine faults using sound signatures and AI analysis.  
- Monitors vehicle security while parked using motion sensors.  
- Provides emergency alerts for drivers or passengers in critical situations.  
- Integrates acoustic signal processing, machine learning, IoT sensors, and emergency communication modules in a single edge-device platform.  

---

### 2️⃣ Driver Emotion & Behavior Recognition for Intelligent Safety Assistance  
**Member:** Basnayake B.M.R.V.V (IT22348616)  

- AI-based system that analyzes facial expressions and driving behavior to detect unsafe emotional and physical states in real-time.  
- Uses in-cabin camera and vehicle data interface (OBD-II) or sensors to capture behavioral indicators such as hard braking, rapid acceleration, and phone usage while driving.  
- Sends instant alerts via visual/audio notifications or messages to a connected app when risky conditions (fatigue, distraction, aggressive driving) are detected.  

---

### 3️⃣ Green Driving Optimization using AI  
**Member:** Gurusinghe W.S.H (IT22923042)  

- “Eco-Driving Assistant using Real-Time Data and ML” predicts fuel-efficient driving patterns using OBD-II data and AI.  
- Provides feedback on speed, acceleration, and driving habits to reduce fuel consumption and emissions.  
- Integrates a sensor to monitor **exhaust air quality**, providing **real-time emission reports**, predictions, and **daily summary reports** for the driver.  
- Focuses on sustainable vehicle monitoring with predictive modeling and reinforcement learning for continuous improvement.  

---

### 4️⃣ Digital Twin for Vehicle Health Prediction  
**Member:** Hansamali A.C (IT22343970)  

- “Vehicle Digital Twin for Real-time Fault Simulation” creates a virtual representation of the vehicle to mirror its real-time condition.  
- Uses past OBD data and ML to simulate engine performance and predict faults before they occur.  
- Enables predictive maintenance and advanced IoT analytics through real-time synchronization and simulation.  

---

## 🧩 System Architecture

```
[OBD-II]      [Thermal]      [Ultrasonic]      [Microphone]      [Camera]      [Exhaust Air Quality]
    │               │               │               │               │                   │
    └──────────────→ [Raspberry Pi Processing Unit] ───────────────────────────────────┘
                              │
                        [Cloud Database + API]
                              │
                        [Web Dashboard / Mobile App]
```

---

## 💻 Tech Stack

| Component | Technology |
|------------|-------------|
| **Hardware** | Raspberry Pi, OBD-II Adapter, Thermal / Ultrasonic / Microphone / Camera / Exhaust Air Quality Sensors |
| **Backend** | Python (Flask / FastAPI) or Node.js |
| **Database** | Firebase / MongoDB / PostgreSQL |
| **Frontend** | React.js / Android (Kotlin) |
| **AI & ML** | Python (TensorFlow / Scikit-learn) |
| **Cloud** | Google Cloud / Firebase / AWS IoT |

---

## 📂 Repository Structure

```
smart-modular-vehicle-monitoring-system/
│
├── backend/                 # API & database connections
├── frontend/                # Web or mobile interface
├── ai-models/               # Machine learning models
├── hardware/                # Raspberry Pi & sensor configurations
├── docs/                    # Diagrams, reports, and research documents
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/smart-modular-vehicle-monitoring-system.git
```

### 2. Install dependencies
```bash
cd backend
npm install  # or pip install -r requirements.txt
```

### 3. Run the system
```bash
npm start    # or python app.py
```

---

## 👥 Research Team

| Name | Student ID |
|------|-------------|
| **Perera G.S.M** | IT22335432 |
| **Basnayake B.M.R.V.V** | IT22348616 |
| **Gurusinghe W.S.H** | IT22923042 |
| **Hansamali A.C** | IT22343970 |

---

## 🧑‍🏫 Supervisors

| Role | Name | Position |
|------|------|-----------|
| **Supervisor** | Mr. Nelum Chathuranga | Senior Lecturer |
| **Co-Supervisor** | Ms. Manori Gamage | Lateral Entry Coordinator, Senior Lecturer |

**Institute:** Sri Lanka Institute of Information Technology (SLIIT)

---

## 🌱 Future Enhancements
- Integration with **Electric Vehicle (EV)** systems  
- Advanced **eco-driving optimization** using reinforcement learning  
- **Fleet management dashboard** for organizations  
- **Voice feedback** and **real-time alerts** via mobile app  

---

## 🧾 License
This project is licensed under the **MIT License** — you are free to use, modify, and distribute it with attribution.

---

**© 2025 Smart Modular Vehicle Monitoring System | Final Year Research Project - SLIIT**
