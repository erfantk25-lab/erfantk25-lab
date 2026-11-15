<p align="center">
  <img src="banner.svg" alt="Erfan Tahmasebi — Elite Midnight navy and cyan MLOps banner" width="100%">
</p>

<p align="center">
  <img src="elite-midnight-profile-panel.svg" alt="Elite Midnight profile panel" width="100%">
</p>

<h1 align="center">Erfan Tahmasebi</h1>

<p align="center">
  <strong>MLOps Engineering Student · Stockholm, Sweden</strong><br>
  Engineering reliable ML systems — from validated data and model training to APIs, containers and deployment.
</p>

<p align="center">
  <a href="https://erfantk25-lab.github.io/">PORTFOLIO</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/erfan-tahmasbikondroodi/">LINKEDIN</a> &nbsp;·&nbsp;
  <a href="mailto:erfan.tahmasebi@gmail.com">EMAIL</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/FOCUS-MLOps-42D9F5?style=for-the-badge&labelColor=071426" alt="Focus: MLOps">
  <img src="https://img.shields.io/badge/BUILD-ML%20Systems-42D9F5?style=for-the-badge&labelColor=071426" alt="Building ML systems">
  <img src="https://img.shields.io/badge/BASED-Stockholm-42D9F5?style=for-the-badge&labelColor=071426" alt="Based in Stockholm">
</p>

---

## Profile

I'm studying **MLOps Engineering at Nackademin**, focusing on the engineering practices that make machine learning applications reproducible, deployable and maintainable.

I enjoy connecting model development with practical software engineering: data validation, experiment workflows, model APIs, containerization, CI/CD and monitoring. The projects below show how I approach those problems through hands-on individual and collaborative work.

| Focus | What I'm building |
|---|---|
| **ML engineering** | Reproducible training, evaluation, model serving |
| **Platform & delivery** | Docker, CI/CD, GitHub Actions, container registries |
| **Data & reliability** | Schema validation, drift checks, tests and monitoring |
| **Edge & connected systems** | Device telemetry, MQTT pipelines and observability |

<p align="center">
  <img src="elite-midnight-toolkit-panel.svg" alt="Elite Midnight technical toolkit panel" width="100%">
</p>

## Technical toolkit

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,docker,githubactions,git,linux,kubernetes,sklearn,postgres,grafana&theme=dark" alt="Python, FastAPI, Docker, GitHub Actions, Git, Linux, Kubernetes, scikit-learn, PostgreSQL and Grafana">
</p>
<p align="center">
  <img src="https://img.shields.io/badge/MLflow-Experiment%20Tracking-42D9F5?style=flat-square&labelColor=071426" alt="MLflow">
  <img src="https://img.shields.io/badge/Streamlit-Data%20Apps-42D9F5?style=flat-square&labelColor=071426" alt="Streamlit">
  <img src="https://img.shields.io/badge/Folium-Geospatial-42D9F5?style=flat-square&labelColor=071426" alt="Folium">
  <img src="https://img.shields.io/badge/MQTT-Device%20Telemetry-42D9F5?style=flat-square&labelColor=071426" alt="MQTT">
  <img src="https://img.shields.io/badge/TimescaleDB-Time%20Series-42D9F5?style=flat-square&labelColor=071426" alt="TimescaleDB">
</p>

---

<p align="center">
  <img src="elite-midnight-work-panel.svg" alt="Elite Midnight selected work panel" width="100%">
</p>

## Selected work

Three projects, one engineering direction: build systems that move data reliably from source to useful outcomes.

### 01 / Customer Churn MLOps · Model serving & delivery

<p align="center">
  <img src="fastapi-ml-serving-banner.svg" alt="FastAPI, Docker and ML serving project banner" width="100%">
</p>

**[FastAPI Docker ML Serving](https://github.com/erfantk25-lab/fastapi-docker-ml-serving)**

An MLOps pipeline for customer churn prediction, combining data quality checks, model training and evaluation, artifact integrity, an inference API and Docker delivery.

- **Data quality:** Pandera schema validation and statistical drift checks.
- **Model lifecycle:** training, threshold evaluation, regression gate and optional MLflow tracking/registry.
- **Delivery:** FastAPI inference service, Docker image build, smoke tests and GitHub Actions CI/CD.
- **Reliability:** artifact checksum verification and automated tests.

<p>
  <img src="https://img.shields.io/badge/Python-071426?style=flat-square&logo=python&logoColor=42D9F5" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-071426?style=flat-square&logo=fastapi&logoColor=42D9F5" alt="FastAPI">
  <img src="https://img.shields.io/badge/Docker-071426?style=flat-square&logo=docker&logoColor=42D9F5" alt="Docker">
  <img src="https://img.shields.io/badge/MLflow-071426?style=flat-square&logo=mlflow&logoColor=42D9F5" alt="MLflow">
  <img src="https://img.shields.io/badge/GitHub_Actions-071426?style=flat-square&logo=githubactions&logoColor=42D9F5" alt="GitHub Actions">
</p>

<details>
<summary><strong>Explore the system architecture</strong></summary>

<p align="center">
  <img src="fastapi-mlops-architecture.svg" alt="Customer churn MLOps architecture: data validation, model training, evaluation, artifact verification, FastAPI and Docker delivery" width="100%">
</p>

</details>

<p align="right"><a href="https://github.com/erfantk25-lab/fastapi-docker-ml-serving">VIEW PROJECT REPOSITORY →</a></p>

---

### 02 / Taxi Prediction · Full-stack machine learning

<p align="center">
  <img src="taxi-prediction-banner.svg" alt="Taxi prediction full-stack project banner" width="100%">
</p>

**[Taxi Prediction — Full Stack](https://github.com/erfantk25-lab/taxi-prediction-fullstack-ERFAN)**

An individual application that combines a regression model, a prediction API and an interactive geographic interface to estimate taxi fares from trip details.

- **Frontend:** Streamlit collects trip inputs and presents the prediction.
- **Route context:** OpenRouteService provides geocoding and driving-route information; Folium displays the route.
- **Inference:** FastAPI serves a scikit-learn regression pipeline and returns the predicted fare.
- **Model workflow:** candidate models are compared using RMSE; the selected pipeline and metadata are exported.
- **Quality:** GitHub Actions trains the model and runs API tests.

<p>
  <img src="https://img.shields.io/badge/Python-071426?style=flat-square&logo=python&logoColor=42D9F5" alt="Python">
  <img src="https://img.shields.io/badge/scikit--learn-071426?style=flat-square&logo=scikitlearn&logoColor=42D9F5" alt="scikit-learn">
  <img src="https://img.shields.io/badge/FastAPI-071426?style=flat-square&logo=fastapi&logoColor=42D9F5" alt="FastAPI">
  <img src="https://img.shields.io/badge/Streamlit-071426?style=flat-square&logo=streamlit&logoColor=42D9F5" alt="Streamlit">
  <img src="https://img.shields.io/badge/Folium-071426?style=flat-square&logo=python&logoColor=42D9F5" alt="Folium">
</p>

<details>
<summary><strong>Explore the system architecture</strong></summary>

<p align="center">
  <img src="taxi-fullstack-architecture.svg" alt="Taxi prediction architecture: Streamlit, OpenRouteService, FastAPI, scikit-learn model and Folium map" width="100%">
</p>

</details>

<p align="right"><a href="https://github.com/erfantk25-lab/taxi-prediction-fullstack-ERFAN">VIEW PROJECT REPOSITORY →</a></p>

---

### 03 / Edge Computing · Smart Grow environmental monitor

<p align="center">
  <img src="edge-computing-banner.svg" alt="Edge computing project banner" width="100%">
</p>

**[Edge Computing Project](https://github.com/erfantk25-lab/Edge-computing-project-)**

A collaborative edge-IoT project using a Raspberry Pi Pico W to monitor environmental conditions, trigger local alerts and stream telemetry to a containerized monitoring stack.

- **At the edge:** temperature, humidity and light readings are checked locally; threshold breaches trigger a buzzer and LED.
- **Messaging:** the device publishes telemetry over Wi-Fi using MQTT through Mosquitto.
- **Data pipeline:** a Python consumer writes readings to TimescaleDB.
- **Observability:** Grafana visualizes time-series data; Discord webhooks deliver remote alerts.
- **Simulation:** a Wokwi digital twin complements the physical setup.

<p>
  <img src="https://img.shields.io/badge/EDGE-Computing-071426?style=flat-square&logo=cloudflare&logoColor=42D9F5" alt="Edge Computing">
  <img src="https://img.shields.io/badge/Raspberry_Pi-Pico_W-071426?style=flat-square&logo=raspberrypi&logoColor=42D9F5" alt="Raspberry Pi Pico W">
  <img src="https://img.shields.io/badge/MQTT-Mosquitto-071426?style=flat-square&logo=eclipsemosquitto&logoColor=42D9F5" alt="MQTT Mosquitto">
  <img src="https://img.shields.io/badge/TimescaleDB-071426?style=flat-square&logo=postgresql&logoColor=42D9F5" alt="TimescaleDB">
  <img src="https://img.shields.io/badge/Grafana-071426?style=flat-square&logo=grafana&logoColor=42D9F5" alt="Grafana">
</p>

<details>
<summary><strong>Explore the system architecture</strong></summary>

<p align="center">
  <img src="edge-iot-architecture.svg" alt="Edge IoT architecture: Pico W sensors, MQTT broker, Python consumer, TimescaleDB, Grafana and Discord alerts" width="100%">
</p>

</details>

<p align="right"><a href="https://github.com/erfantk25-lab/Edge-computing-project-">VIEW PROJECT REPOSITORY →</a></p>

---

<p align="center">
  <img src="elite-midnight-lia-panel.svg" alt="Elite Midnight LIA internship panel" width="100%">
</p>

## LIA 1 · Internship

<p align="center">
  <img src="https://img.shields.io/badge/AVAILABLE-FROM%2008%20FEB%202027-42D9F5?style=for-the-badge&labelColor=071426" alt="Available from 8 February 2027">
</p>

I'm looking for an **LIA 1 placement** starting **8 February 2027**, preferably within **MLOps, ML Engineering or a closely related field**.

Based in Stockholm and open to on-site or hybrid opportunities. I'm eager to contribute to a team, learn from experienced engineers and help build reliable machine learning systems.

---

<p align="center">
  <img src="elite-midnight-profile-panel.svg" alt="Elite Midnight contact section visual" width="100%">
</p>

## Let's connect

<p align="center">
  <a href="mailto:erfan.tahmasebi@gmail.com"><img src="https://img.shields.io/badge/EMAIL-Contact%20me-42D9F5?style=for-the-badge&logo=gmail&logoColor=071426&labelColor=071426" alt="Email"></a>
  <a href="https://www.linkedin.com/in/erfan-tahmasbikondroodi/"><img src="https://img.shields.io/badge/LINKEDIN-Connect-42D9F5?style=for-the-badge&logo=linkedin&logoColor=071426&labelColor=071426" alt="LinkedIn"></a>
  <a href="https://erfantk25-lab.github.io/"><img src="https://img.shields.io/badge/PORTFOLIO-Visit%20website-42D9F5?style=for-the-badge&logo=githubpages&logoColor=071426&labelColor=071426" alt="Portfolio"></a>
</p>

<p align="center"><sub>BUILD WITH PURPOSE · AUTOMATE WITH CARE · IMPROVE CONTINUOUSLY</sub></p>
