<h1 align="center">Vyacheslav Koksharov</h1>

<p align="center">
  <strong>DevOps Engineer</strong> · Infrastructure as Code · CI/CD · Kubernetes · Observability
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open_to-Remote_%26_Relocation-2ea44f?style=flat-square" alt="Open to remote and relocation" />
  <img src="https://img.shields.io/badge/Timezone-UTC%2B3-555555?style=flat-square" alt="Timezone UTC+3" />
</p>

---

## About me

I'm a DevOps engineer who came to the field through Linux administration, and I still think like one:
reliability first, then automation, then speed.

I build infrastructure that is reproducible, observable and boring in production — the good kind of boring.
My daily work is turning manual operations into code: provisioning servers with Ansible and Terraform,
shipping services through CI/CD pipelines, running them on Kubernetes and making sure we know
something is wrong before the users do.

I also have hands-on experience bringing modern infrastructure to traditional industries:
IoT monitoring systems in the agricultural sector, where uptime is measured in tonnes of grain, not page views.

**What I care about**

- 🔁 **Everything as code** — servers, pipelines, dashboards and alerts live in Git and go through review
- 🛡️ **Secure by default** — hardened baselines, secrets in vaults, least privilege
- 📈 **Observability over guesswork** — metrics, logs and alerts that lead to a fix, not to noise
- 🧱 **Same setup for every environment** — dev, stage and prod differ in variables, not in code

---

## 🛠️ Tech stack

| Area | Tools |
| --- | --- |
| **OS & Virtualization** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white) ![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white) ![VMware](https://img.shields.io/badge/VMware-607078?style=flat-square&logo=vmware&logoColor=white) |
| **IaC & Config** | ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) |
| **Containers & Orchestration** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1626?style=flat-square&logo=helm&logoColor=white) ![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white) |
| **CI/CD** | ![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |
| **Observability** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white) ![Kibana](https://img.shields.io/badge/Kibana-005571?style=flat-square&logo=kibana&logoColor=white) |
| **Networking & Messaging** | ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![HAProxy](https://img.shields.io/badge/HAProxy-01A4CA?style=flat-square&logo=haproxy&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white) |
| **Languages & Data** | ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) |

---

## 🚀 Featured projects

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

## 🌾 Domain experience

**IoT monitoring in agriculture** — backend and infrastructure for real-time temperature and humidity
monitoring of grain storage: sensor data over MQTT, processing in Go, storage in PostgreSQL,
dashboards and alerting. *Commercial project, source code is private.*

---

## 🔭 Currently working on

- CI for the Ansible baseline: GitHub Actions lint pipeline and Molecule tests for every role
- A public IoT monitoring platform demo: Terraform, Kubernetes, GitOps with Argo CD, Prometheus and Grafana
- Improving my Go for internal tooling and automation

---

## 📸 Beyond the code

When I'm not writing pipelines, I do street photography — city geometry, light and mood.
Have a look at my channel: [Немного не отсюда](https://t.me/nemnogoneotsuda) *(Telegram, photos speak any language)*.

---

## 📬 Contact

<p>
  <a href="mailto:koksharovyacheslav@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://t.me/Slava_koksh">
    <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
  </a>
  <!-- LinkedIn: uncomment and put your profile link here when it exists
  <a href="https://www.linkedin.com/in/your-profile">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  -->
</p>
