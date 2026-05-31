# 🔐 ELK Stack + VirusTotal SIEM

A real-time security monitoring system built with the ELK Stack and VirusTotal API integration for automated threat detection.

## 🏗️ Architecture
- **Filebeat** — Collects system and network logs
- **Logstash** — Parses logs and enriches with VirusTotal threat intelligence
- **Elasticsearch** — Stores and indexes all security events
- **Kibana** — Live security dashboard and visualization

## ⚡ Features
- Real-time malicious IP detection
- Automatic threat scoring (critical/high/medium/low)
- VirusTotal API integration for 70+ engine scanning
- Geographic attack origin mapping
- Live Kibana dashboard

## 🚀 Setup
1. Install Docker Desktop with WSL2
2. Clone this repository
3. Set VirusTotal API key: `$env:VT_API_KEY="your_key"`
4. Run: `docker compose up -d`
5. Open: `http://localhost:5601`

## 📊 Dashboard
- Threat level distribution chart
- Attacking IPs table with VT scores and countries
- Attack origin donut chart

## 🛠️ Tech Stack
`Elasticsearch` `Logstash` `Kibana` `Filebeat` `Docker` `VirusTotal API` `Windows 11` `WSL2`
