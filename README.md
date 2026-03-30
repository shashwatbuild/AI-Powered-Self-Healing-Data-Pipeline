# AI-Powered-Self-Healing-Data-Pipeline
> 🧠 An intelligent, production-ready data pipeline that **automatically detects, fixes, and processes bad data** using LLMs — without human intervention.

![Python](https://img.shields.io/badge/Python-3.12+-blue?logo=python)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-3.0+-017CEE?logo=apache-airflow)
![Ollama](https://img.shields.io/badge/Ollama-LLaMA%203.2-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🌟 Why This Project is Special

Traditional pipelines ❌ break on bad data.  
This pipeline **thinks, diagnoses, and heals itself** ✅

👉 Built with an **Agentic AI approach**, this system:
- Detects corrupted or invalid data 🕵️‍♂️  
- Automatically fixes it 🔧  
- Continues processing without failure 🚀  

💡 Result: A **resilient, fault-tolerant, production-grade pipeline**

---

## 📌 Table of Contents
- [Overview](#overview)
- [Architecture](#architecture)
- [How It Works](#how-it-works)
- [Core Features](#core-features)
- [Self-Healing Engine](#self-healing-engine)
- [Tech Stack](#tech-stack)
- [Setup & Installation](#setup--installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Pipeline Flow](#pipeline-flow)
- [Health Monitoring](#health-monitoring)
- [Output](#output)
- [Project Structure](#project-structure)
- [Contributing](#contributing)

---

## 🔍 Overview

This project demonstrates a **next-generation data engineering pattern** —  
a pipeline that is not just automated, but **self-correcting**.

It processes **Yelp review data** and performs **sentiment analysis** using a **local LLM (Ollama)**.

### ⚙️ Key Capabilities:
1. 🧠 **Diagnose** data quality issues in real-time  
2. 🔧 **Heal** corrupted records automatically  
3. 📊 **Analyze sentiment** using LLM  
4. 📈 **Track health metrics** of the pipeline  

---

## 🏗️ Architecture

![Architecture](assets/Self%20healing%20pipeline.jpeg)

### 🔄 Flow:

---

## ⚡ How It Works

1. Ingest Data  
2. Inspect Data Quality  
3. Fix Issues Automatically  
4. Run LLM Sentiment Analysis  
5. Track Health + Metrics  

💡 Even if data is broken → pipeline **does NOT fail**

---

## 🚀 Core Features

| Feature | Description |
|--------|------------|
| 🧠 Self-Healing | Automatically fixes bad/missing data |
| 🤖 Local LLM | Uses Ollama (LLaMA 3.2) – no API cost |
| ⚡ Batch Processing | Handles large-scale datasets efficiently |
| 🔄 Parallel Execution | Multiple DAG runs supported |
| 📊 Health Monitoring | Real-time pipeline status |
| 🛡️ Fault Tolerance | Never crashes on bad data |
| 📈 Detailed Metrics | Sentiment + healing analytics |

---

## 🛠️ Self-Healing Engine

| Issue | Detection | Fix |
|------|----------|-----|
| Missing Text | `None` values | Replace with placeholder |
| Empty Text | Blank input | Auto-fill |
| Wrong Type | Not string | Convert |
| Noise Data | Special chars only | Replace |
| Too Long | >2000 chars | Truncate |

💡 Ensures **zero pipeline failure**

---

## 🧰 Tech Stack

- Apache Airflow  
- Python  
- Ollama (LLaMA 3.2)  
- Docker (optional)  
- Yelp Dataset  

---

## ⚙️ Setup & Installation

### 1️⃣ Clone Repository
```bash
git clone https://github.com/airscholar/SelfHealingPipeline.git
cd SelfHealingPipeline
