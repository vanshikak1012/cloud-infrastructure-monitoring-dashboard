# 📊 Cloud Infrastructure Monitoring & Business Metrics Dashboard

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker\&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana\&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github\&logoColor=white)

## 📌 Project Overview

The **Cloud Infrastructure Monitoring & Business Metrics Dashboard** is a centralized monitoring solution designed to provide real-time visibility into system performance and operational KPIs. The project combines modern monitoring tools with business analysis practices to transform technical infrastructure metrics into meaningful business insights.

The solution collects system and container metrics using **Node Exporter** and **cAdvisor**, stores them in **Prometheus**, and visualizes them through interactive **Grafana dashboards**. In addition to the technical implementation, the project includes complete Business Analysis documentation such as Business Requirements, Functional Requirements, User Stories, Stakeholder Analysis, KPI Definitions, Gap Analysis, and Risk Assessment.

---

## 🎯 Business Problem

Organizations often monitor servers using multiple tools, making it difficult for technical teams and business stakeholders to obtain a unified view of infrastructure health and operational performance.

Common challenges include:

* Lack of centralized infrastructure monitoring
* Limited visibility into operational KPIs
* Slow identification of infrastructure issues
* Technical metrics that are difficult for business stakeholders to interpret
* Limited executive reporting capabilities

---

## 🎯 Project Objectives

* Build a centralized infrastructure monitoring platform.
* Monitor real-time system and container performance.
* Track operational Key Performance Indicators (KPIs).
* Provide business-friendly dashboards for management.
* Support data-driven decision making through visual reporting.

---

# 🏗️ Solution Architecture

```text
                  Docker Host
                       │
        ┌──────────────┴──────────────┐
        │                             │
 Node Exporter                  cAdvisor
        │                             │
        └──────────────┬──────────────┘
                       │
                  Prometheus
                       │
                  Grafana
                       │
      Business Metrics Dashboard
```

---

# 📊 Key Features

### Infrastructure Monitoring

* CPU Utilization
* Memory Utilization
* Disk Usage
* Network Traffic
* System Availability
* System Uptime
* Resource Utilization

### Container Monitoring

* Running Containers
* Container CPU Usage
* Container Memory Usage
* Container Resource Consumption

### Business Dashboard

* Infrastructure Health
* Executive KPI Dashboard
* Resource Utilization Trends
* Performance Monitoring
* Operational Insights

---

# 💼 Business Analysis Deliverables

This project includes complete Business Analysis documentation:

* Business Requirements Document (BRD)
* Functional Requirements Specification (FRS)
* User Stories
* Stakeholder Analysis
* KPI Definition Document
* Gap Analysis
* Risk Assessment
* Business Process Flow

---

# 🛠️ Technology Stack

| Category             | Technology    |
| -------------------- | ------------- |
| Monitoring           | Prometheus    |
| Visualization        | Grafana       |
| Metrics Collection   | Node Exporter |
| Container Monitoring | cAdvisor      |
| Container Platform   | Docker        |
| Version Control      | Git & GitHub  |
| Documentation        | Markdown      |

---

# 📊 Infrastructure KPIs

| KPI                       | Description                            |
| ------------------------- | -------------------------------------- |
| CPU Utilization           | Measures processor usage               |
| Memory Utilization        | Tracks RAM consumption                 |
| Disk Usage                | Monitors storage usage                 |
| Network Traffic           | Measures incoming and outgoing traffic |
| System Availability       | Indicates system uptime                |
| Active Monitoring Targets | Number of monitored services           |
| Infrastructure Health     | Overall operational status             |

---

# 📁 Project Structure

```text
cloud-infrastructure-monitoring-dashboard/
│
├── docs/
│   ├── BRD.md
│   ├── FRS.md
│   ├── UserStories.md
│   ├── StakeholderAnalysis.md
│   ├── KPIDefinitions.md
│   ├── GapAnalysis.md
│   ├── RiskAssessment.md
│   └── BusinessProcessFlow.md
│
├── grafana/
│   ├── dashboards/
│   │   ├── infrastructure-dashboard.json
│   │   └── business-dashboard.json
│   └── provisioning/
│
├── prometheus/
│   └── prometheus.yml
│
├── monitoring/
├── screenshots/
├── images/
├── docker-compose.yml
├── README.md
├── LICENSE
└── .gitignore
```

---

# 🚀 Getting Started

## Prerequisites

* Docker Desktop
* Docker Compose
* Git
* Visual Studio Code (Recommended)

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/cloud-infrastructure-monitoring-dashboard.git
```

Navigate to the project directory:

```bash
cd cloud-infrastructure-monitoring-dashboard
```

Start all services:

```bash
docker compose up -d
```

Verify running containers:

```bash
docker ps
```

---

# 🌐 Access the Applications

| Service       | URL                   |
| ------------- | --------------------- |
| Grafana       | http://localhost:3000 |
| Prometheus    | http://localhost:9090 |
| Node Exporter | http://localhost:9100 |
| cAdvisor      | http://localhost:8080 |

Default Grafana Credentials:

**Username:** admin

**Password:** admin

---

# 📸 Screenshots

Add screenshots of:

* Docker Desktop
* Prometheus Dashboard
* Prometheus Targets
* Grafana Infrastructure Dashboard
* Business Metrics Dashboard
* Node Exporter Metrics
* cAdvisor Dashboard

---

# 📈 Business Value

This solution enables organizations to:

* Improve infrastructure visibility
* Monitor operational KPIs
* Identify performance issues proactively
* Support informed business decisions
* Simplify infrastructure reporting
* Centralize monitoring into a single dashboard

---

# 🔮 Future Enhancements

* Application Performance Monitoring (APM)
* Email and Slack Alerting
* Kubernetes Monitoring
* Cloud Monitoring Integration
* Cost Optimization Dashboard
* Predictive Analytics
* Automated Incident Reporting

---

# 👩‍💻 Author

**Vanshika Kashyap**

Cloud Business Analyst | Associate Business Analyst | AWS & Cloud Enthusiast

### Skills Demonstrated

* Business Analysis
* Requirement Gathering
* BRD & FRS Documentation
* User Story Creation
* KPI Analysis
* Dashboard Design
* Infrastructure Monitoring
* Docker
* Prometheus
* Grafana
* Node Exporter
* cAdvisor
* Git & GitHub

---

## ⭐ If you found this project useful, consider giving it a star!
