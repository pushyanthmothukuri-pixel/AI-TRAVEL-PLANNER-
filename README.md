# AI-TRAVEL-PLANNER-
A multi-stage prompt engineering pipeline that utilizes Chain-of-Thought reasoning, few-shot prompting, and structured outputs to generate highly optimized, budget-constrained AI travel itineraries.
# ✈️ Enterprise Prompt Portfolio: AI Travel Planner

An advanced prompt engineering mini-project demonstrating how to build a robust, production-ready pipeline for an AI-powered travel planner. This repository moves beyond basic prompting by implementing a structured, multi-stage architecture to ensure predictable, high-quality, and machine-readable outputs from Large Language Models (LLMs).

## 🧠 Overview

This project showcases a fundamental agentic workflow using a declarative JSON configuration (`app.json`) and an execution script (`app.py`). It is designed to take raw user constraints (destination, budget, interests) and process them through a rigorous reasoning pipeline to generate logically routed travel itineraries.

## ⚙️ Pipeline Architecture

The prompt pipeline is divided into five specialized engineering stages:

1. **Role & Context Initialization:** Establishes the core persona of an "expert AI Travel Planner," setting strict boundaries for geographic routing and budget adherence.
2. **Few-Shot Pattern Matching:** Injects input/output examples to establish the desired tone, pacing, and format.
3. **Structured Outputs:** Enforces a rigid JSON schema constraint to ensure the LLM's final response is machine-readable and easily parsed by downstream applications.
4. **Chain-of-Thought (CoT) Reasoning:** Forces the model to expose its step-by-step logic (`<thinking>` tags) to analyze budgets, group geographical locations, and optimize transit times *before* generating the final itinerary.
5. **Multi-Step Chaining:** The conceptual framework that links extraction, reasoning, and formatting nodes into a continuous automated pipeline.

## 🛠️ Tech Stack

* **Language:** Python
* **Configuration:** JSON
* **LLM Integration:** Google GenAI SDK (Gemini API) *[Can be adapted for OpenAI or Anthropic]*

## 🚀 Getting Started

### Prerequisites
* Python 3.8+
* A valid Gemini API Key (or alternative LLM API key)
* VS Code or any preferred IDE

### Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/ai-travel-planner-pipeline.git](https://github.com/your-username/ai-travel-planner-pipeline.git)
   cd ai-travel-planner-pipeline
