# 🌿 AgriAdvisor AI

**Smart Pest Detection & Fertilizer Recommendation System**  
*Final Year Project — Phase 2 (Software Demo)*

---

## 🚀 Live Demo
Open `index.html` in any browser — no server or installation needed.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔍 Pest & Disease Detection | 3-tap symptom-based diagnosis for 12 crops with offline rule engine |
| 🌱 Fertilizer Advisor | NPK/pH/moisture input → AI prescription + shopping list with INR pricing |
| ⛅ Weather Advisor | Live weather via Open-Meteo API + farm advisory (spray/fertilizer/irrigation) |
| 📋 Scan History | Session-based log of all diagnoses with sensor snapshots |
| 🏪 Nearby Agri Shops | GPS-based Google Maps search for local agricultural suppliers |
| 🌐 Multi-language | Full EN / ಕನ್ನಡ / हिन्दी support |

---

## 🛠️ Tech Stack

- **Frontend:** Vanilla HTML, CSS, JavaScript — single file, zero dependencies
- **Disease Engine:** Rule-based offline diagnosis (38 disease rules across 5 crops)
- **Fertilizer AI:** Claude Sonnet via Anthropic API (falls back to rule-based offline)
- **Weather:** Open-Meteo API (free, no key required)
- **Sensor Bar:** Simulates Raspberry Pi 4 microclimate sensor data (Phase 3: real Pi integration)

---

## 📱 Offline Support

The app is designed for rural use with poor connectivity:
- Disease diagnosis works **100% offline** (rule-based engine)
- Weather falls back to rule-based farm advice when offline
- Fonts use system fallbacks — UI never breaks on slow networks
- Offline banner alerts user when connectivity is lost

---

## 🗺️ Roadmap

| Phase | Status | Description |
|---|---|---|
| Phase 1 | ✅ Complete | System architecture, literature review, Review 1 |
| Phase 2 | ✅ Complete | Full software demo — this repository |
| Phase 3 | 🔜 Upcoming | Raspberry Pi 4 integration — Pi Camera replaces manual upload, NPK/pH/moisture sensors replace sliders |

---

## 📂 Project Structure

```
agri-advisor/
├── index.html        ← entire app (single file)
└── README.md
```

---
