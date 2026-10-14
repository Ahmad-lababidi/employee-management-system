# Employee Management System

A full-stack, containerized web application designed for managing employee data and visualizing workforce analytics. This project integrates a RESTful backend with an interactive frontend, fully deployed via Docker[cite: 1, 3].

## Features

**FastAPI Backend**
* Implements a REST API to handle seamless CRUD (Create, Read, Update, Delete) operations[cite: 2].
* Manages direct interactions with a local SQLite database, utilizing automatically generated primary keys[cite: 1].
* Includes comprehensive error handling and system logging across all critical endpoints[cite: 3].

**Streamlit Frontend**
* **Analytics Dashboard:** Visualizes workforce data, including the average salary, a bar chart of employee counts per department, and a salary distribution histogram[cite: 2].
* **Employee Management:** Provides an intuitive form interface to add, update, or delete employee records in real-time[cite: 2, 3].

**Architecture & Deployment**
* Containerized using Docker and `docker-compose` to ensure consistent execution across environments[cite: 3].
* Centralized configuration management and isolated dependency tracking[cite: 3, 4].

## 🛠️ Tech Stack
* **Backend:** FastAPI, Python 3.11.9[cite: 1]
* **Frontend:** Streamlit, Pandas, Matplotlib[cite: 1, 3]
* **Database:** SQLite[cite: 1]
* **Containerization:** Docker[cite: 3]

## 📂 Project Structure
```text
employee-management-system/
├── backend.py           # FastAPI application and CRUD endpoints
├── frontend.py          # Streamlit UI and data visualizations
├── database.py          # SQLite database initialization script
├── config.py            # Centralized application configuration
├── requirements.txt     # Python dependencies
├── Dockerfile           # Image build instructions
└── docker-compose.yml   # Multi-container orchestration
