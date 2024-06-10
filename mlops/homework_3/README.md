# MLOps Zoomcamp - Module 3: Orchestration with Mage

This repository contains the project work for Module 3 of the MLOps Zoomcamp by DataTalksClub. This module focuses on orchestration with Mage and includes setting up Docker containers and managing ML models with MLflow.

## Project Overview

In this module, we explored the following:

- Setting up and running Docker containers for ML pipelines.
- Using Mage for orchestrating ML workflows.
- Implementing MLflow for model tracking and versioning.
- Training and exporting a linear regression model.
- Logging artifacts and models using MLflow.

## Repository Structure

```plaintext
.
├── data_prep
│   ├── transformers
│   │   └── train_model.py
│   └── exporters
│       └── export_model.py
├── Dockerfile
├── docker-compose.yml
├── mlflow.dockerfile
└── README.md

