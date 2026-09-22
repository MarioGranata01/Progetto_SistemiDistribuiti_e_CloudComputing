# Serverless ML Pipeline – Car Evaluation

> An automated, containerized Machine Learning pipeline built with a serverless architecture for real-time car evaluation and classification.

---

## Overview

This project implements an automated **Machine Learning pipeline** leveraging a **serverless architecture**. 

Using the well-known **Car Evaluation Dataset**, the system classifies vehicle quality based on multiple input features. The pipeline automates the entire lifecycle of a typical ML workflow:

- Dataset upload (automatic trigger)
- Data preprocessing & cleaning
- Model training & optimization
- Real-time inference exposed via an HTTP endpoint

---

## Architecture & Workflow

The pipeline consists of the following key stages:

- **Dataset Upload** – Uploading the dataset file automatically triggers the execution flow.
- **Preprocessing** – Cleans and transforms raw data into a structured format for the training phase.
- **Training** – Trains a machine learning classifier using `scikit-learn` on the processed data.
- **Inference** – Exposes a live HTTP endpoint for clients to send new data points and receive instant predictions.

---

## Technologies & Tools

- **Language:** Python
- **Machine Learning:** scikit-learn
- **Containerization:** Docker
- **Architecture:** Serverless

---

## Quick Start (How to Run)

To run or test this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone [https://github.com/MarioGranata01/nome-repo.git](https://github.com/MarioGranata01/nome-repo.git)
