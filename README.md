# Erick Villon Muniz

Computer Science Engineer focused on backend development, cloud infrastructure, and automation.

[![GitHub followers](https://img.shields.io/github/followers/Erick-Zam?style=for-the-badge)](https://github.com/Erick-Zam)
[![Profile views](https://komarev.com/ghpvc/?username=Erick-Zam&style=for-the-badge)](https://github.com/Erick-Zam)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com)

## About me

- Proactive, patient, and fast learner.
- Experience in software development, IoT, Linux server administration, and web/mobile technologies.
- Strong interest in scalable architecture, automation, and clean engineering practices.
- Native Spanish speaker and English B1-B2 (in progress).

## Core skills

### Software development
- Languages: Python, JavaScript, PHP, Java, C++, HTML5, CSS3.
- Frameworks: FastAPI, Flask, Node.js, Vite, Next.js.
- Backend style: SOLID, Clean Code, and test-driven mindset.

### Backend and infrastructure
- Databases: MySQL, SQL Server, MongoDB.
- DevOps and Cloud: Docker, Linux server management, DigitalOcean deployments.
- IoT and automation: Arduino and ESP32 integration for real-time data systems.

### AI and emerging tech
- Chatbot implementation and ML integration into existing workflows.

## Professional experience

### Web Developer Intern
Universidad Agraria del Ecuador (2022)

- Developed a web platform to manage and display university researcher information.
- Improved data administration workflows and access for the academic community.

### Chair of Physics
Universidad Agraria del Ecuador (2023)

- Taught Physics I and II to Computer Science students.
- Structured practical and theoretical sessions with measurable progress.

### Analysis Assistant
Agricultural Consulting Firm (2024)

- Managed weather station systems and data analysis workflows.
- Maintained Davis meteorological station infrastructure and operations.

## Education and certifications

- BSc in Computer Science, Universidad Agraria del Ecuador (2025).
- GNU/Linux Administration, Universidad Agraria del Ecuador (2021).
- Computer Forensics Security, Universidad Agraria del Ecuador (2022).
- Python Development, Self-paced practical training (2025).

## GitHub Status API (professional monitoring)

This section helps monitor GitHub platform health directly from your scripts, dashboards, or automations.

### Base endpoint

- https://www.githubstatus.com/api/v2

### Recommended endpoints

| Purpose | Endpoint |
|---|---|
| Global summary | `https://www.githubstatus.com/api/v2/summary.json` |
| Global status | `https://www.githubstatus.com/api/v2/status.json` |
| Components | `https://www.githubstatus.com/api/v2/components.json` |
| Unresolved incidents | `https://www.githubstatus.com/api/v2/incidents/unresolved.json` |
| Recent incidents | `https://www.githubstatus.com/api/v2/incidents.json` |
| Upcoming maintenance | `https://www.githubstatus.com/api/v2/scheduled-maintenances/upcoming.json` |
| Active maintenance | `https://www.githubstatus.com/api/v2/scheduled-maintenances/active.json` |
| Recent maintenances | `https://www.githubstatus.com/api/v2/scheduled-maintenances.json` |

### Quick check with cURL

```bash
curl -s https://www.githubstatus.com/api/v2/summary.json
```

### Python example for automations

```python
import requests

url = "https://www.githubstatus.com/api/v2/summary.json"
data = requests.get(url, timeout=10).json()

indicator = data["status"]["indicator"]
description = data["status"]["description"]
updated_at = data["page"]["updated_at"]

print(f"GitHub status: {description} ({indicator})")
print(f"Last update: {updated_at}")
```

### Practical use cases

- Alerting in CI/CD pipelines when GitHub has incidents.
- Showing live platform status in internal engineering dashboards.
- Avoiding false alarms when deployment failures are caused by external outage.

> Note: GitHub profile README does not execute JavaScript. Use API calls from scripts or external dashboards.

## GitHub analytics

![Erick's GitHub stats](https://github-readme-stats.vercel.app/api?username=Erick-Zam&show_icons=true&theme=default&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Erick-Zam&layout=compact&hide_border=true)

## Contact

- Email: erick997261@gmail.com
- Website: https://erickvillon.dev
- Phone: +593 0995514638
