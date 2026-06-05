# ResearchPilot AI

An autonomous multi-agent research system built with LangGraph, RAG, ChromaDB, SQLite, Streamlit, and Ollama.



# ResearchPilot v1

## Overview

ResearchPilot v1 is the first working version of an autonomous multi-agent research assistant (now called - Poneglyph) built using LangGraph, ChromaDB, SQLite, and Streamlit.

This version was developed as a learning project to understand:

* Agentic AI workflows
* Retrieval-Augmented Generation (RAG)
* LangGraph state management
* Multi-agent orchestration
* Local LLM integration
* Research report generation

---

## Architecture

### Agents

* Router Agent
* Search Agent
* Reader Agent
* Research Agent
* Critic Agent
* Writer Agent
* RAG Answer Agent
* Chat Agent

### Technologies

* Python
* LangGraph
* ChromaDB
* SQLite
* Streamlit
* Ollama
* Groq API

---

## Features Implemented

### Research Modes

* Web Research
* RAG Retrieval
* Hybrid Research

### Report Generation

* Structured research reports
* Executive summaries
* Key findings
* Emerging trends
* Recommendations
* Source tracking

### Evaluation Layer

* Confidence scoring
* Coverage scoring
* Source quality scoring
* Contradiction detection
* Research gap identification

### User Features

* Research history
* Follow-up chat
* Continue research
* Markdown export
* PDF export

---

## Challenges Solved During Development

### State Management

Resolved multiple session-state synchronization issues in Streamlit.

### UI Flickering

Removed excessive reruns and stabilized the interface.

### PDF Export

Implemented reliable report generation using ReportLab.

### Agent Pipeline

Built and debugged LangGraph routing across:

* WEB
* RAG
* HYBRID

research flows.

### Critic Integration

Added post-processing evaluation metrics and research insights.

---

## Known Limitations

At the time development stopped:

* Streamlit UI had scalability limitations.
* Frontend design was difficult to modernize within Streamlit.
* Citation formatting was basic.
* Academic paper search was not implemented.
* Gemini integration was not implemented.
* Production deployment architecture was not finalized.

---

## Why Development Stopped

Development was intentionally paused to create ResearchPilot v2.

Version 2 migrates toward:

* React + Vite frontend
* API-driven architecture
* Gemini integration
* Academic paper retrieval
* Improved UI/UX
* Production-ready deployment

---

## Lessons Learned

ResearchPilot v1 served as the foundation for understanding:

* Agentic systems
* Retrieval systems
* LLM orchestration
* Research automation workflows

All future work continues in ResearchPilot v2.

---

Created by Tagore Nandan

ResearchPilot v1 Archive


V2 is named Poneglyph which was further deployed into a live project
