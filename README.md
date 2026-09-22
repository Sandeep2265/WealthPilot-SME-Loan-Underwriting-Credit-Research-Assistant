# WealthPilot – SME Loan Underwriting & Credit Research Assistant

## Overview

WealthPilot is a multi-agent AI assistant designed to support SME loan
underwriting and credit research. It uses financial-document analysis,
risk-analysis tools, policy-aware RAG, and LLM-based agents to assist
with credit assessment and loan recommendations.

## Key Features

- Multi-agent AI for loan underwriting and credit research
- Financial document parsing and information extraction
- Risk-analysis tools for financial assessment
- Policy-aware RAG using vector search
- LangGraph-based agent orchestration
- MCP-based tool integration
- Persistent memory for applicant information
- Observability and reliability monitoring
- Bias and compliance evaluation
- Human-in-the-loop approval

## System Workflow

Application
    ↓
Document Processing
    ↓
Financial Analysis
    ↓
Policy RAG
    ↓
Risk Assessment
    ↓
Loan Recommendation
    ↓
Human Approval

## Tech Stack

- Python
- LLM APIs
- LangGraph
- MCP
- RAG
- Vector Database
- FastAPI
- PostgreSQL
- Docker

## Project Structure

```text
WealthPilot/
├── backend/
├── agents/
├── tools/
├── rag/
├── memory/
├── evaluation/
├── frontend/
├── tests/
├── docker/
└── README.md
