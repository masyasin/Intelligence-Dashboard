# AI-Powered IT Vendor Intelligence Dashboard (PoC)

## 📌 Overview
This repository contains the **Proof-of-Concept (PoC)** frontend interface for the AI-Powered IT Vendor Intelligence Dashboard. It is designed specifically for enterprise banking and IT procurement teams to monitor third-party vendor performance, SLA compliance, and security risks in real-time.

This prototype demonstrates a high-end, modern SaaS architecture focused on predictive AI capabilities and zero-latency visualization.

## ✨ Core Features
- **Executive Dashboard:** Live KPI tracking, network health monitoring, and interactive SLA/Risk charts.
- **Vendor Directory:** A searchable and filterable database of all integrated IT vendors (e.g., AWS, Azure, Oracle).
- **Risk & Compliance Center:** Visualized "Continuous Audit" engine demonstrating how AI scans SOC2 and HIPAA compliance certificates.
- **AI Predictions Engine:** Predictive alerts forecasting SLA breaches based on anomalous latency data and historical outage patterns.

## 🚀 How to Run
This PoC was engineered to be completely standalone and lightweight. **No build tools, package managers, or server setups are required.**

1. Clone or download this folder.
2. Double-click the `index.html` file to open it in any modern web browser (Chrome, Edge, Firefox, Safari).

*Alternatively, this folder can be directly dragged and dropped into Vercel, Netlify, or GitHub Pages for instant live deployment.*

## 🛠️ Technology Stack
- **Structure:** Pure HTML5
- **Styling:** Custom Vanilla CSS3 (utilizing modern CSS variables, glassmorphism, flex/grid layouts, and native animations)
- **Logic:** Vanilla JavaScript (ES6+)
- **Visualization:** [Chart.js](https://www.chartjs.org/) (via CDN)
- **Typography:** Inter (Google Fonts)
- **Icons:** Inline SVG vectors (Zero external image dependencies for maximum performance)

## 🔒 Security & Privacy (PoC Note)
All data shown in this prototype is **dummy data** generated for demonstration purposes. In a production environment, this frontend is designed to be connected to live APIs (via Python/Node.js backend) to stream real-time JSON payloads from your internal vendor management systems.
