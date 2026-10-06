<h1 align="center">Vyacheslav Koksharov</h1>

<p align="center">
  <strong>DevOps Engineer</strong> · CI/CD · Kubernetes · Infrastructure as Code · Observability
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Experience-2_years-0969da?style=flat-square" alt="Experience: 2 years" />
  <img src="https://img.shields.io/badge/English-B2-0969da?style=flat-square" alt="English B2" />
  <img src="https://img.shields.io/badge/Open_to-Remote-2ea44f?style=flat-square" alt="Open to remote" />
  <img src="https://img.shields.io/badge/Timezone-UTC%2B3-555555?style=flat-square" alt="Timezone UTC+3" />
</p>

---

## About me

I'm a DevOps engineer with about two years of hands-on experience, currently working at a cybersecurity company.
I came to DevOps through Linux administration, and I still think like an admin:
reliability first, then automation, then speed.

I've built infrastructure **from scratch** for a microservice product in the cloud and now support
deployments in a security-focused environment. My daily work is turning manual operations into code:
CI/CD pipelines, Ansible and Terraform, Helm releases on Kubernetes, and monitoring that tells us
something is wrong before the users do.

**How I work**

-  **Build once, promote everywhere** — one image per commit travels from dev to prod without rebuilding
-  **Everything as code** — infrastructure, configs and pipelines live in Git and go through merge requests
-  **Secure by default** — secrets in Vault and CI variables, never in repositories; hardened Linux baselines
-  **Alert on symptoms, not noise** — 5xx, latency and disk space instead of every CPU spike

---

## 💼 Experience

**DevOps Engineer — Rostelecom Solar** · *Apr 2026 – present*
<br/>Cybersecurity company. Deployment automation and support for internal services.

- Maintain and extend GitLab CI pipelines: Docker builds, tests, publishing to the registry, deployment to environments
- Ansible roles and playbooks for service rollout and Linux host configuration across dev / stage / prod
- Kubernetes deployments with Helm: per-environment values, rollbacks, troubleshooting pods
  (CrashLoopBackOff, Pending, requests/limits, liveness/readiness probes)
- Secrets management with HashiCorp Vault and GitLab CI variables; monitoring and alerting with Prometheus and Grafana

**DevOps Engineer — Ai Lapki** · *Jan 2025 – Apr 2026*
<br/>Built the infrastructure from scratch for Python / FastAPI microservices in Yandex Cloud.

- **CI/CD:** self-hosted GitLab CI with fast checks first, then a single image tagged `version + commit SHA`
  promoted through all environments; faster builds with multi-stage Dockerfiles, layer caching and parallel jobs
- **IaC:** moved the infrastructure to Terraform (VPC, networks, VMs) with remote state and locking,
  changes reviewed as `plan` in merge requests; Ansible roles for hosts, Docker and monitoring agents
- **Observability:** Prometheus + Grafana dashboards for hosts and services, symptom-based alerts to Telegram,
  centralized logging with ELK
- **Networking:** Nginx reverse proxy with TLS, HAProxy load balancing with health checks,
  VPN for the team (WireGuard, OpenVPN), nftables / iptables, fail2ban
- **Kubernetes:** delivering services to existing clusters with Helm and Argo CD
- **Troubleshooting:** OOM killer, disk and inode exhaustion, 502/504 between proxy and app, Docker network routing

---

## Tech stack

| Area | Tools |
| --- | --- |
| **OS & Virtualization** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white) ![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white) ![VMware](https://img.shields.io/badge/VMware-607078?style=flat-square&logo=vmware&logoColor=white) |
| **Cloud & IaC** | ![Yandex Cloud](https://img.shields.io/badge/Yandex_Cloud-5282FF?style=flat-square&logo=yandexcloud&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) |
| **Containers & Orchestration** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1626?style=flat-square&logo=helm&logoColor=white) ![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white) |
| **CI/CD** | ![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |
| **Observability** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white) ![Kibana](https://img.shields.io/badge/Kibana-005571?style=flat-square&logo=kibana&logoColor=white) ![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=flat-square&logo=zabbix&logoColor=white) |
| **Security** | ![Vault](https://img.shields.io/badge/HashiCorp_Vault-FFEC6E?style=flat-square&logo=vault&logoColor=black) ![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white) ![OpenVPN](https://img.shields.io/badge/OpenVPN-EA7E20?style=flat-square&logo=openvpn&logoColor=white) |
| **Networking & Messaging** | ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![HAProxy](https://img.shields.io/badge/HAProxy-01A4CA?style=flat-square&logo=haproxy&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white) |
| **Languages & Data** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) |

---

## Featured projects

### [Ansible Server Baseline](https://github.com/koksharoff/Ansible_templates)
Turns a fresh Debian / Ubuntu server into a hardened, consistently configured host for **dev, stage and prod**
from the same set of roles.
SSH hardening with lock-out protection, UFW, fail2ban, unattended upgrades, kernel `sysctl` hardening,
secrets in `ansible-vault`, typed role arguments and an `ansible-lint` production profile.

`Ansible` · `Linux` · `Security` · `Make`

### [TimeTracker for VS Code](https://github.com/koksharoff/TimeTracker)
A VS Code extension that tracks time spent in the editor and per file.

`TypeScript` · `VS Code API`

---

## Domain experience

**IoT monitoring in agriculture** — backend and infrastructure for real-time temperature and humidity
monitoring of grain storage: sensor data over MQTT, processing in Go, storage in PostgreSQL,
dashboards and alerting. *Commercial project, source code is private.*

---

## Currently working on

- CI for the Ansible baseline: GitHub Actions lint pipeline and Molecule tests for every role
- A public IoT monitoring platform demo: Terraform, Kubernetes, GitOps with Argo CD, Prometheus and Grafana
- Improving my Go for internal tooling and automation

---

## 📸 Beyond the code

When I'm not writing pipelines, I do street photography — city geometry, light and mood.
Have a look at my channel: [Немного не отсюда](https://t.me/nemnogoneotsuda) *(Telegram, photos speak any language)*.

---

## Contact

<p>
  <a href="https://t.me/Slava_koksh">
    <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
  </a>
  <a href="mailto:koksharovyacheslav@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <!-- LinkedIn: uncomment and put your profile link here when it exists
  <a href="https://www.linkedin.com/in/your-profile">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  -->
</p>
