# AlphaAgents

A prototype multi-agent AI system for equity analysis and portfolio construction using **LangGraph**, **RAG (Retrieval-Augmented Generation)**, and **LLMs**.  
Inspired by BlackRock’s AlphaAgents, this project demonstrates modular agents collaborating to analyze financial data, news sentiment, and valuations.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Folder Structure](#folder-structure)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Backtesting](#backtesting)
- [Dashboard](#dashboard)
- [Contributing](#contributing)
- [License](#license)

---

## Project Overview
AlphaAgents-LangGraph is a multi-agent system that:
- Processes **financial data** and **news sentiment**
- Uses **RAG** to provide evidence-backed reasoning
- Resolves conflicting outputs with a **consensus node**
- Offers a modular architecture for easy addition of new agents

---

## Features
- **Modular Agent Nodes**: Fundamental, Sentiment, Valuation
- **RAG Integration**: Agents retrieve relevant documents before generating outputs
- **Consensus Mechanism**: Handles disagreements between agents
- **Backtesting Support**: Evaluate agent recommendations on historical data
- **Dashboard**: Visualize agent outputs and final recommendations

---
