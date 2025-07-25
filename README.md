
# 🚀 Integration of Prometheus, Grafana and Node Exporter on Kubernetes  
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

Welcome to my monitoring project using Prometheus, Grafana and Node Exporter! This setup allows you to effortlessly monitor the health and performance of your Kubernetes environments.

## 📌 Quick Start
``bash
git clone https://github.com/DevLizOps/prometheus-grafana-on-kubernetes.git
cd prometheus-grafana-on-kubernetes
bash scripts/deploy-monitoring-stack.sh
bash scripts/start-tunnel-and-show-urls.sh

🧭 Project Overview
This project simplifies Kubernetes monitoring with:

Prometheus for metrics collection

Grafana for visualization

Node Exporter for host-level metrics

ℹ️ Note: Originally deployed on Minikube. Install Minikube here.

🌟 Why It Matters
Monitoring Kubernetes shouldn't be hard. This stack provides:

✅ Automated setup

✅ Portable configuration

✅ Quick deployment

✅ Perfect for development/testing

🏗️ Architecture
https://assets/monitoring-architecture-diagram.jpg

Data Flow:

Node Exporter collects system metrics

Prometheus scrapes metrics

Grafana visualizes data from Prometheus

Persistent volumes retain data

🛠️ Usage Guide
🔄 Deploying
bash
bash scripts/deploy-monitoring-stack.sh
🌐 Accessing Services
bash
bash scripts/start-tunnel-and-show-urls.sh
Default URLs:

Grafana: http://<EXTERNAL_IP>:3000

Prometheus: http://<EXTERNAL_IP>:9090

Credentials in grafana/grafana-secret.yaml

📊 Sample Dashboard
Go to Dashboard > + New > Import

Use ID 1860 (Node Exporter Full)

Select Prometheus datasource

https://assets/node-exporter-full-dashboard.png

🧹 Cleanup
bash
bash scripts/undeploy-monitoring-stack.sh
⚠️ Warning: The script includes force-delete for stuck resources

📚 Resources
Prometheus Docs

Grafana Docs

Minikube Docs

🤝 Contributing
PRs and issues welcome! Licensed under MIT.

Versión en Español
Click here for English Version

🚀 Integración de Prometheus, Grafana y Node Exporter en Kubernetes
https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white

¡Sistema de monitorización completo para Kubernetes!

📌 Inicio Rápido
bash
git clone https://github.com/DevLizOps/prometheus-grafana-on-kubernetes.git
cd prometheus-grafana-on-kubernetes
bash scripts/deploy-monitoring-stack.sh
bash scripts/start-tunnel-and-show-urls.sh
Ver guía completa...

text

Key improvements:
1. Added colorful badges for technologies
2. Better visual hierarchy with emojis
3. Compact quick-start section
4. Clearer section separation
5. Responsive formatting
6. Consistent heading styles
7. Prominent warning/note boxes
8. Bilingual toggle at top/bottom
