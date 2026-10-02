# 🧠 Historian — Enterprise Memory Intelligence Platform

> An AI-powered enterprise memory and intelligence platform that transforms organizational data into meaningful insights, evidence, predictions, and actionable intelligence.

---

## 📌 Overview

**Historian** is an enterprise intelligence platform designed to help organizations understand, analyze, and interact with their organizational data.

The platform combines a modern **React + Vite frontend**, a **Python FastAPI backend**, machine-learning capabilities, and an AI-powered assistant called **Harvey**.

Historian provides a unified interface for exploring employee information, organizational insights, evidence, predictions, timelines, knowledge graphs, and analytical results.

---

## ✨ Features

### 📊 Intelligent Dashboard

- Enterprise KPI dashboard
- Organizational overview
- Data-driven insights
- Evidence visualization
- Causal timeline visualization
- Graph-based intelligence
- Real-time-style dashboard experience

### 🤖 Harvey AI Assistant

**Harvey** is the intelligent assistant integrated into Historian.

It provides a conversational interface for interacting with enterprise intelligence and helps users explore:

- Organizational information
- Employee intelligence
- Insights
- Evidence
- Recommendations
- Analytical results
- Enterprise knowledge

### 👨‍💼 Employee Intelligence

- Employee search
- Employee profiles
- Employee badge search
- Badge OCR support
- Employee-related analytics
- Employee data visualization

### 🔍 Advanced Analytics

Historian includes multiple machine-learning and analytical capabilities:

- Anomaly Detection
- Classification
- Regression
- Clustering
- Feature Engineering
- Data Preprocessing
- Explainability
- Model Evaluation
- Recommendation Generation

### 📈 Forecasting & Predictions

- Predictive analytics
- Forecasting
- Trend analysis
- Prediction dashboards
- Data-driven recommendations

### 🧠 Knowledge Graph

- Relationship visualization
- Organizational knowledge mapping
- Connected data exploration
- Graph-based intelligence

### 📜 Timeline & Causal Analysis

- Organizational timelines
- Causal relationships
- Event visualization
- Evidence-based analysis

### 🚨 Alerts & Reports

- Important organizational alerts
- Analytical reports
- Evidence-based reporting
- Insight summaries

### 🔐 Authentication

- Login
- Signup
- Protected routes
- Public-only routes
- Password strength validation
- Authentication context
- Secure route handling

---

# 🛠️ Tech Stack

## Frontend

- React.js
- Vite
- JavaScript
- Tailwind CSS
- React Router
- CSS

## Backend

- Python
- FastAPI
- Pydantic
- SQLAlchemy
- REST APIs

## Machine Learning

- Python
- Scikit-learn
- Pandas
- NumPy
- Anomaly Detection
- Classification
- Regression
- Clustering
- Feature Engineering
- Explainability
- Model Evaluation

## Development Tools

- Git
- GitHub
- VS Code
- npm
- Python
- Virtual Environment

---

# 🏗️ System Architecture

```text
                    ┌─────────────────────────┐
                    │       User / Admin      │
                    └────────────┬────────────┘
                                 │
                                 ▼
                    ┌─────────────────────────┐
                    │     React Frontend      │
                    │       + Vite            │
                    │     + Tailwind CSS      │
                    └────────────┬────────────┘
                                 │
                                 │ REST API
                                 ▼
                    ┌─────────────────────────┐
                    │     FastAPI Backend     │
                    │       Python            │
                    └────────────┬────────────┘
                                 │
             ┌───────────────────┼───────────────────┐
             │                   │                   │
             ▼                   ▼                   ▼
      ┌─────────────┐    ┌──────────────┐    ┌──────────────┐
      │   Database  │    │ Machine      │    │   Services   │
      │             │    │ Learning     │    │              │
      │   SQL/ORM   │    │ Pipeline     │    │ Analytics    │
      └─────────────┘    └──────────────┘    └──────────────┘
                                 │
                                 ▼
                    ┌─────────────────────────┐
                    │     Harvey Assistant    │
                    │     AI Intelligence     │
                    └─────────────────────────┘
