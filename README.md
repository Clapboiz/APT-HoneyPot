# Proactive Hybrid Honeypot-Based Detection of Advanced Persistent Threats
## Project Overview
This project focuses on developing a proactive security framework that integrates hybrid honeypot technology to detect and mitigate Advanced Persistent Threats (APT). By leveraging multiple layers of honeypots and integrating with firewall systems, the framework enhances early threat detection and improves network security resilience.

## Key Features
- **Hybrid Honeypot Deployment:** Combines low, medium, and high-interaction honeypots to gather detailed attack information.
- **Firewall Integration:** Uses Pfsense and Web Application Firewall (ModSecurity) to isolate threats.
- **Kubernetes & ELK Stack:** Manages honeypots efficiently and visualizes attack logs.
- **APT Detection & Analysis:** Implements deception techniques and game theory to optimize defense strategies.

## System Components
- **External Honeypots:** (Cowrie, Dionaea) Captures brute force attacks and malware samples.
- **Internal Honeypots:** (Django Admin Honeypot, Kfsensor) Detects lateral movements and unauthorized access.
- **Log Management:** Uses ELK Stack (Elasticsearch, Logstash, Kibana) for real-time monitoring.
- **Automation & Machine Learning (Future Work):** Plans to enhance attack detection using AI-based anomaly detection.

## Architecture
![image](https://github.com/user-attachments/assets/84d7bbc5-2240-49ad-9735-88eab0169555)

## Experiment & Evaluation
- Simulated APT attack scenarios, including SSH brute force, ICMP exfiltration, and web-based attacks.
- Analyzed logs to classify attack patterns and improve system response.
- Validated system effectiveness through controlled penetration testing.

## Future Improvements
- Automating interaction levels in honeypots based on real-time traffic.
- Enhancing deception techniques to evade attacker detection.
- Implementing machine learning models for predictive attack analysis.
