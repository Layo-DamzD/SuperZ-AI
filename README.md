# 🧠 SuperZ AI

Your phone, supercharged. An adaptive AI assistant that learns how you use your Android phone, controls gadgets, locks apps, diagnoses problems, and talks to you in different personalities.

## 🚀 Features

| Feature | Description |
|---------|-------------|
| 🎙️ Wake Word | Say "Hey SuperZ" to activate |
| 🧠 Personalities | Switch between Baby, Boss, Worker, Friend modes |
| 📱 Screen Sharing | Share your screen with SuperZ for help |
| 🎮 Phone Control | SuperZ can navigate and control your phone |
| 🔒 App Locking | Lock apps until next day with emergency override |
| 🌐 IoT Control | Add gadgets by IP address and control them |
| 🔧 Diagnostics | Auto-detect and fix phone problems |
| 📊 Adaptive Learning | Learns your habits and gets smarter over time |

## 🏗️ Architecture

- **Platform:** Android (Kotlin)
- **AI Brain:** Custom-trained ML models
- **Wake Word:** Porcupine + custom "Hey SuperZ" model
- **Vision:** MobileSAM + custom screen classifier
- **IoT:** MQTT + HTTP REST protocols
- **Backend:** Python (FastAPI)

## 📋 Development Phases

- [x] Phase 0: Project Setup
- [ ] Phase 1: Talk to Me (Voice + AI + Personality)
- [ ] Phase 2: Control My World (IoT + App Locking)
- [ ] Phase 3: See & Fix (Screen + Phone Control + Diagnostics)
- [ ] Phase 4: Know Me (Adaptive Learning)

## 🛠️ Tech Stack

- Android (Kotlin) — Main app
- TensorFlow Lite — On-device ML
- Python + FastAPI — Backend services
- PostgreSQL — Data storage
- MQTT — IoT protocol

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.
