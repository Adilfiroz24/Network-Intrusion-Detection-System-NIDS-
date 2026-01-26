# 🛡️ NIDS Pro – Network Intrusion Detection System

**NIDS Pro** is a modular, high-performance **Network Intrusion Detection System (NIDS)** capable of real-time packet sniffing, threat detection, anomaly analysis, and visualization through a modern security dashboard.

This project combines **signature-based detection**, **anomaly detection**, and **machine learning classification** to identify suspicious network activity.

---

## 📌 Table of Contents
- [Features](#-features)
- [Dashboard Screenshots](#-dashboard-screenshots)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [Running the System](#-running-the-system)
- [Testing Tools](#-testing-tools)
- [Modules Overview](#-modules-overview)
- [Tech Stack](#-tech-stack)
- [Disclaimer](#️-disclaimer)
- [Support](#-support)

---

## 🚀 Features

### 🔍 Real-Time Packet Monitoring
- Custom packet sniffer  
- Live traffic inspection  
- Port scan, SYN flood, brute-force detection  

### 🧠 Detection Engine
- Signature-based rule matching  
- Statistical anomaly detection  
- Machine Learning threat classifier  
- Modular design for easy extension  

### 📊 Interactive Security Dashboard
- Real-time alert counters  
- Protocol distribution  
- Attack categories  
- Alerts timeline  
- Top attackers  
- System online status  

### 🛢️ Logging & Storage
- Structured logs  
- Database-ready models for attack records  

### 🧩 Clean Architecture
- Sniffing → Detection → Storage → Dashboard  
- Highly maintainable & extensible  

---

## 📸 Dashboard Screenshots
![Screenshot 1 (1)](https://github.com/user-attachments/assets/77e1c12b-f8c0-4be6-8c33-c999572b09e0)
![Screenshot 2](https://github.com/user-attachments/assets/12d29186-26d5-474b-90ba-34b485769bbe)



---

## 📁 Project Structure

```
advanced-nids/
├── src/
│   ├── sniffing/
│   ├── detection/
│   ├── storage/
│   ├── dashboard/
│   ├── utils/
│   └── main.py
│
├── signature_rules.json
├── requirements.txt
├── test_traffic.py
├── quick_test.py
│
├── Dockerfile
├── docker-compose.yml
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Adilfiroz24/Network-Intrusion-Detection-System-NIDS-.git
cd Network-Intrusion-Detection-System-NIDS-
```

### 2️⃣ Create Virtual Environment
```bash
python -m venv venv
source venv/bin/activate     # Linux / Mac
venv\Scripts\activate        # Windows
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

---

## ▶️ Running the System

### Start Packet Sniffer + Detection Engine
```bash
python src/main.py
```

### Start the Dashboard
```bash
python src/dashboard/app.py
```

### Using Docker
```bash
docker-compose up --build
```

---

## 🧪 Testing Tools

### Traffic Simulator
```bash
python test_traffic.py
```

### System Health Validator
```bash
python quick_test.py
```

---

## 🧱 Modules Overview

| Module | Description |
|--------|-------------|
| sniffing/packet_sniffer.py | Packet capture engine |
| detection/rule_engine.py | Signature-based threat detection |
| detection/anomaly_detection.py | Statistical anomaly detection |
| detection/ml_detector.py | Machine learning detection |
| storage/models.py | Database models |
| dashboard/templates/ | Dashboard HTML |
| dashboard/static/ | CSS, JS, charts |
| utils/logger.py | Logging utilities |
| utils/geoip_lookup.py | IP geo-location |

---

## 🧰 Tech Stack

- Python 3  
- Scapy (Packet Sniffing)  
- Flask (Dashboard)  
- SQLite / JSON Storage  
- Docker / Docker Compose  
- Chart.js (Visualizations)  

---

## ⚠️ Disclaimer

This project is intended **only for educational and authorized cybersecurity testing**.  
Do **not** use it on networks without proper permission.

---

## ⭐ Support

If this project helped you, please consider giving it a **⭐ star on GitHub** — it motivates future updates!



