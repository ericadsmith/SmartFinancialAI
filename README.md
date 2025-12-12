[![Docker Pulls](https://img.shields.io/docker/pulls/nubiandev/smartfinancial-ai.svg)](https://hub.docker.com/r/nubiandev/smartfinancial-ai)


# Smart Financial Insights AI Assistant

**Smart Financial Insights AI Assistant** is an AI-powered financial transaction classifier built with Python, Streamlit, and machine learning. It helps users **automatically categorize business expenses and income** using natural language processing (NLP).

---

## Overview

Manually categorizing financial data is tedious and error-prone. This assistant streamlines bookkeeping by automatically assigning the correct category.(e.g., Travel, Meals, Housing) based on transaction descriptions. It supports CSV uploads and is ideal for freelancers, small businesses, or financial analysts.

---

## Features

- Predicts transaction categories using machine learning
- CSV file upload for batch classification
- Interactive Streamlit dashboard
- NLP-powered classification with scikit-learn
- Dockerized for easy deployment

---

## Run with Docker

```bash
docker pull nubiandev/smartfinancial-ai:latest
docker run -p 8501:8501 nubiandev/smartfinancial-ai
