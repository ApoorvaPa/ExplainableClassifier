# Transaction Risk Classifier with LangChain

An AI-powered system to classify transaction risks and generate natural language explanations using LangChain. Designed for compliance-ready auditability, real-time decisioning, and seamless API integration.

## Features

- Risk Classification: Classifies transactions into low, medium, or high risk using a custom ML model.
- LangChain Explanations: Uses LLMs to generate human-readable justifications for high-risk classifications.
- FastAPI Backend: Provides RESTful APIs for classification and explanation.
- Audit-Ready Logging: Centralized structured logging for traceability.
- CI/CD Ready: GitHub Actions integration for testing and deployment workflows.

## Project Structure

transaction-risk-classifier/ ├── app/ # FastAPI application │ ├── api/ # API routes │ ├── core/ # Config and logging │ ├── services/ # Classifier and LangChain logic │ ├── models/ # Pydantic models │ └── main.py # Entry point ├── langchain_modules/ # LangChain templates and chain setup ├── tests/ # Unit and integration tests ├── .github/workflows/ # CI workflows ├── Dockerfile ├── docker-compose.yml ├── requirements.txt └── README.md

## Quickstart

### 1. Clone the Repo
```bash
git clone https://github.com/yourusername/transaction-risk-classifier.git
cd transaction-risk-classifier
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
