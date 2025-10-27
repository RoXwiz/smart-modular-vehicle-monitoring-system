# 🚘 Smart Modular Vehicle Monitoring System (SMVMS)

### 🎓 Final Year Research Project - SLIIT  
**Module Code:** IT4010 - Research Project - 25 July Batch  
**📚 Research Group ID:** 25-26J-308  

---

## 📖 Overview
The **Smart Modular Vehicle Monitoring System (SMVMS)** is an intelligent vehicle monitoring and analytics platform that integrates **OBD-II data**, **multiple sensors**, and **AI-driven analysis** to enhance vehicle safety, efficiency, and sustainability.  

This project aims to modernize the way vehicle diagnostics and driving analytics are performed by combining IoT-based data collection with cloud computing and AI models. The modular design allows the system to be easily extended with new sensors or features without major reconfiguration.

---

## ⚙️ Core Features

- **📡 OBD-II Data Integration:**  
  Captures real-time engine and vehicle parameters such as RPM, temperature, and fuel efficiency.

- **🌡️ Multi-Sensor Module:**  
  Integrates **thermal**, **ultrasonic**, and **microphone** sensors to detect overheating, obstacles, and abnormal sounds.

- **👤 Driver Recognition:**  
  Uses a camera module for facial recognition to identify the driver and create personalized driving profiles.

- **☁️ Cloud Data Storage:**  
  Uploads real-time data to a secure cloud platform for storage, visualization, and analytics.

- **🧠 AI & ML Analytics:**  
  Analyzes driver behavior and predicts potential issues, offering eco-driving recommendations and vehicle health predictions.

- **🔧 Modular Design:**  
  Each hardware and software module functions independently, ensuring easy upgrades and scalability.

---

## 🧩 System Architecture

```
[OBD-II]      [Thermal]      [Ultrasonic]      [Microphone]      [Camera]
    │               │               │               │               │
    └──────────────→ [Raspberry Pi Processing Unit] ────────────────┘
                              │
                        [Cloud Database + API]
                              │
                        [Web Dashboard / Mobile App]
```

---

## 💻 Tech Stack

| Component | Technology |
|------------|-------------|
| **Hardware** | Raspberry Pi, OBD-II Adapter, Thermal / Ultrasonic / Microphone / Camera Sensors |
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
