# sentinel-ai
# SentinelAI — AI-Native Security Platform

## Overview

SentinelAI is a class project demonstrating how local large language models can help organizations identify social engineering risks and possible digital impersonation.

The application uses Python, Streamlit, and Ollama to analyze suspicious messages, identify potential warning signs, generate risk assessments, and recommend defensive actions.

## Features

- AI-powered message analysis using a locally hosted LLM.
- Rule-based detection of common social engineering indicators.
- Risk scoring and risk categorization.
- Structured security reports using Pydantic.
- Recommended defensive actions.
- Local inference through Ollama.

## Technology Stack

- Python
- Ollama
- Llama 3.2
- Streamlit
- Pydantic

## Prerequisites

- Python 3.10 or later
- Ollama installed
- Git installed

## Installation

1. Clone the repository.
2. Create and activate a Python virtual environment.
3. Install dependencies using `pip install -r requirements.txt`.
4. Download the model using `ollama pull llama3.2:3b`.
5. Start the application using `python -m streamlit run app.py`.

## Responsible Use

SentinelAI is an educational prototype. Its findings are not proof of fraud or identity compromise. Security decisions require appropriate verification and human review.

## Project Status

Educational prototype under development.
