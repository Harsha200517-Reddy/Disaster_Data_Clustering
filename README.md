<div align="center">

# 🛡️ DisasterGuard AI
### AI-Powered Real-Time Disaster Intelligence & Emergency Monitoring Platform

<p align="center">
<img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Streamlit-Interactive_App-red?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Google-Gemini_AI-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Folium-Geospatial-green?style=for-the-badge"/>
<img src="https://img.shields.io/badge/AI-Incident_Analysis-purple?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge"/>
</p>

<p align="center">

DisasterGuard AI is an intelligent disaster monitoring and emergency response platform that leverages Artificial Intelligence, geospatial mapping, and multi-source incident intelligence to detect, classify, prioritize, and visualize disaster events in real time.

</p>

</div>

---

# 📖 Table of Contents

- Overview
- Problem Statement
- Solution
- Key Features
- System Workflow
- Architecture
- Dashboard Walkthrough
- Technology Stack
- AI Components
- Project Structure
- Installation
- Environment Setup
- Running the Project
- Screenshots
- Future Improvements
- Contribution Guide
- Author

---

# 🌍 Problem Statement

Emergency response systems frequently struggle with:

- Information overload
- Slow incident verification
- Fragmented data sources
- Manual threat assessment
- Delayed decision making
- Lack of real-time situational awareness

Modern disasters generate large amounts of incoming data from:

- News feeds
- Social media
- Sensor systems
- Satellite sources
- Human reports

Manually filtering and analyzing this information becomes difficult.

Critical incidents may remain unnoticed while resources are wasted on low-priority signals.

---

# 💡 Solution

DisasterGuard AI addresses these challenges using an AI-powered monitoring workflow.

The system:

1. Collects incoming incident reports
2. Processes raw incident information
3. Uses AI for contextual understanding
4. Identifies disaster type
5. Estimates severity
6. Filters false positives
7. Displays incidents on an interactive dashboard

This creates an intelligent command center for emergency monitoring.

---

# ✨ Features

## 🚨 AI Incident Detection

Automatically analyzes incoming reports and identifies:

- Fire incidents
- Floods
- Earthquakes
- Medical emergencies
- Vehicle accidents
- Other emergency events

The AI engine determines whether the report represents a genuine threat.

---

## 🧠 AI-Powered Analysis

Uses Google Gemini for:

- Context understanding
- Incident summarization
- Disaster classification
- Relevance filtering
- Priority estimation

AI converts noisy text signals into structured intelligence.

---

## 📍 Interactive Geospatial Monitoring

Visualize incidents through maps.

Features:

- Dynamic markers
- Incident clustering
- Geographic visualization
- Location-based intelligence

Provides immediate situational awareness.

---

## 📊 Command Center Dashboard

Includes:

- Active incident count
- Threat statistics
- AI status indicators
- Priority incident feed
- Real-time monitoring interface

---

## 📡 Multi-Source Intelligence

Designed for integration with:

- Social feeds
- Satellite monitoring
- RSS feeds
- APIs
- Sensor systems

Supports scalable information ingestion.

---

## ⚡ Live Severity Tracking

Each event receives:

- Severity score
- Risk level
- Incident category
- AI confidence estimate

Helps emergency teams prioritize response.

---

# 🧠 System Workflow

```text

Raw Incoming Data
        ↓
Data Collection
        ↓
AI Context Analysis
        ↓
Incident Classification
        ↓
Severity Scoring
        ↓
False Positive Filtering
        ↓
Location Processing
        ↓
Map Rendering
        ↓
Dashboard Visualization

```

---

# 🏗 Architecture

```text

                     +-------------------+
                     | Incoming Sources |
                     |
                     | • Social Media   |
                     | • News Feeds     |
                     | • Sensors        |
                     | • Satellites     |
                     +-------------------+
                               |
                               ↓

               +----------------------------+
               | Incident Processing Layer  |
               +----------------------------+
                               |
                               ↓

               +----------------------------+
               | Google Gemini Intelligence |
               |                            |
               | Classification             |
               | Severity Analysis          |
               | Filtering                  |
               +----------------------------+
                               |
                               ↓

            +----------------------------------+
            | Incident Intelligence Database |
            +----------------------------------+
                               |
                               ↓

               +----------------------------+
               | Streamlit Command Center  |
               +----------------------------+
                               |
                               ↓

                    +----------------+
                    | Emergency Team |
                    +----------------+

```

---

# 📊 Dashboard Walkthrough

The application consists of two primary modules:

---

## 🗺️ Command Center

Provides:

### Live Metrics

Displays:

- Active incidents
- Critical threats
- AI model status

---

### Interactive Map

Displays:

- Incident locations
- Disaster markers
- Severity indicators

---

### Priority Feed

Shows:

- Latest incidents
- AI descriptions
- Timestamp
- Severity levels

---

## 🔌 Data Sources

Displays:

- Connected source systems
- Feed availability
- Source reliability
- External integrations

---

# 🧠 AI Components

The system includes multiple AI capabilities.

---

## Incident Understanding

AI analyzes:

- Raw text
- Context
- Keywords
- Event intent

---

## Threat Classification

Categories:

| Incident Type | Example |
|---|---|
| Fire | Building fire |
| Flood | Water overflow |
| Medical | Health emergency |
| Accident | Vehicle collision |
| Earthquake | Seismic activity |
| Other | Uncategorized events |

---

## Severity Prediction

Severity scale:

```text
1–3     Low

4–7     Medium

8–10    Critical
```

---

# ⚙ Technology Stack

## Frontend

- Streamlit

---

## AI

- Google Gemini

---

## Geospatial

- Folium
- Streamlit Folium

---

## Data Processing

- Pandas

---

## Feed Integration

- Feedparser

---

## Programming Language

- Python

---

# 📦 Dependencies

```txt
streamlit
pandas
folium
streamlit-folium
google-generativeai
feedparser
```

---

# 📂 Project Structure

```bash

DisasterGuard-AI/

│
├── app.py
│
├── check_models.py
│
├── requirements.txt
│
├── components/
│   │
│   ├── map_view.py
│   │
│   └── data_feed.py
│
├── data/
│   │
│   └── simulator.py
│
├── utils/
│   │
│   └── gemini_brain.py
│
├── assets/
│   │
│   └── screenshots/
│
├── README.md
│
├── .env
│
└── .gitignore

```

---

# 🔧 Installation

Clone repository:

```bash
git clone https://github.com/yourusername/DisasterGuard-AI.git

cd DisasterGuard-AI
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# 🔑 Environment Setup

Create:

```bash
.env
```

Add:

```env
GEMINI_API_KEY=your_api_key
```

Generate API key:

https://makersuite.google.com/

---

# ▶ Running Project

Launch application:

```bash
streamlit run app.py
```

Application starts at:

```bash
http://localhost:8501
```

---

# 📸 Screenshots

Create folder:

```bash
assets/screenshots/
```

Recommended images:

```bash
dashboard.png

map.png

priority_feed.png

data_sources.png
```

Add preview section:

```md

## Dashboard

![Dashboard](assets/screenshots/dashboard.png)

## Map

![Map](assets/screenshots/map.png)

## Feed

![Feed](assets/screenshots/priority_feed.png)

```

---

# 🚀 Future Improvements

Planned enhancements:

- Real-time Twitter integration
- Satellite image processing
- Computer Vision analysis
- Disaster prediction models
- Historical trend analytics
- Notification systems
- Mobile application
- Reinforcement learning optimization
- Multi-agent emergency systems

---

# 🔒 Security Improvements

Future versions may include:

- API authentication
- Role-based access
- Incident encryption
- Audit logs

---

# 🤝 Contribution Guide

Contributions are welcome.

Steps:

```bash

Fork repository

Create feature branch

git checkout -b feature-name

Commit changes

git commit -m "message"

Push branch

Create Pull Request

```


---

# ⭐ Support

If you found this project useful:

Give it a star ⭐

---

<div align="center">

Built with AI + Geospatial Intelligence + Emergency Response Systems

</div>
