# Agentic AI Prescription Writer: Doctor's Assistant Agent

> A Agentic AI agentic framework developed during the Google 5-Day Agentic AI Course, simulates designing patients' prescription for doctor.

**Winner of the Completion Certificate in the associated Kaggle competition.**

---

## Table of Contents
* [Problem Statement](#problem-statement)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Setup and Usage](#setup-and-usage)
* [Demo](#demo)
* [Lessons Learned](#lessons-learned)

---

## Problem Statement
Exploring the capabilities of modern AI Agents to create specialized orchestration of agents. This project aimed to build a proof-of-concept Agentic AI, "Agentic AI Prescription Writer" that can understand components and prescription in natural language and design doctor's prescrption based on a knowledge base, Agentic tools(google_search), simulating an prescription given to patient.

## Features
This Project includes usage of the following concepts:
 * 1. Parallel Agents - reaserching and formulating prescription
 * 2. Loop Agents - Refining prescription
 * 3. Sequential Agents - execute the aggregated prescription
 * 4. Building the Workflow - How the Agents pause - take Doctor's input - resume.
 * 5. Agent powered by an LLM - Prescriber Agents powered by gemini-2.5-flash-lite.
 * 6. Built-in tools, such as Google Search - Google search for citations
 * 7. Observability: Logging, Tracing, Metrics - Tracing Logs.
 * 8. Long Running Operations (Human In The Loop) - Taking Doctor's approval to prescription.
 * 9. Custom tool for confirmation - confirm_prescription for resuming after Doctor's approva

## Technologies Used
*   Python 3
*   Google AI Generative Language (Gemini API)
*   Pandas for data handling
*   Kaggle Notebooks for development and experimentation
*   Google ADK
*   Logging plugin
*   Agent Tools: google_search(Search Grounding) 
*   Few shot prompting

## Setup and Usage
1.  **Clone the repository:**
    ```bash
    git clone https://github.com/AakashDeshpande-GenAI/PrescriberAgent.git
    cd PrescriberAgent
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Open and run the notebook:**
    *   The main logic is contained within `agent-doc-1.ipynb`. Open this in Jupyter Notebook or VS Code or Kaggle.

## Demo
!Agentic AI Prescription Writer : (httpshttps://github.com/AakashDeshpande-GenAI/PrescriberAgent/blob/main/Images/logging_plugin.png?raw=true://raw.githubusercontent.com/AakashDeshpande-GenAI/PrescriberAgent/refs/heads/main/Images/final_prescription.png)
!Logging Plugin : (https://github.com/AakashDeshpande-GenAI/PrescriberAgent/blob/main/Images/logging_plugin.png?raw=true)
!Human In The Loop : (https://github.com/AakashDeshpande-GenAI/PrescriberAgent/blob/main/Images/Human_in_the_loop.png?raw=true)
## Lessons Learned
This project was a deep dive into Agentic AI and the practical application of Agents and their Tools. A key challenge was ensuring the Agentic responses were constrained to the provided knowledge base and google_search tool with logging traces to prevent hallucination. This project solidified my understanding of building real-world applications with Agentic AI.
