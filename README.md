# 🌐 HAS Gateway

This repository includes the **gateway and data processing services** of the Home Automation System (**HAS**).  
It is responsible for ingesting sensor data, managing rule-based automation, and enabling real-time analysis.

---

## 📦 Included Modules

- `EdgeLink` – Unified external gateway (REST/GraphQL/MQTT)
- `EchoStream` – Sensor data ingestion via MQTT, HTTP, WebSocket
- `SensGuard` – Real-time threshold monitoring and anomaly detection
- `Automata` – Rule engine (If-Then logic, timers, events)
- `DataTrendz` – Time-series analytics and trend visualization

---

## 🚀 Features

- Real-time data ingestion and processing
- Internal routing of sensor events via CoreMesh
- Stream-based anomaly detection
- Automation rules and triggers
- Historical data analysis with InfluxDB & Plotly

---

## 🧱 Tech Stack

- Python, FastAPI
- MQTT, Redis Streams
- InfluxDB, Pandas, Plotly
- Docker, Uvicorn

---

## 🛠️ Getting Started

```bash
git clone https://github.com/<your-username>/has-gateway.git
cd has-gateway
docker-compose up
