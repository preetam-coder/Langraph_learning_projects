# LangGraph Learning Projects

This repository contains a collection of beginner-friendly LangGraph examples focused on building AI workflows using state graphs, routing, RAG, and human-in-the-loop patterns.

## Overview

These projects are part of my LangGraph learning journey and demonstrate how to build intelligent applications using:

- LangGraph for workflow orchestration
- LangChain for LLM integration
- Groq models for generation
- Streamlit for interactive UI
- Retrieval-Augmented Generation (RAG) for document-based Q&A

## Project Files

- `sequential_base.py`  
  A basic sequential workflow with three nodes:
  - editor
  - scriptwriter
  - translator

- `conditional_RAG.py`  
  A college assistant application that classifies user queries into:
  - academic
  - fee
  - general

  It then routes the query to the appropriate RAG pipeline.

- `app.py`  
  A Streamlit-based web app version of the college assistant.

- `states.py`  
  Demonstrates different ways to define state in LangGraph, including:
  - TypedDict
  - Pydantic
  - Dataclass
  - MessagesState

- `parallel_reducers.py`  
  Example of parallel node execution using reducers to merge state safely.

- `iterative_tools.py`  
  Shows an iterative workflow where the model can use tools and improve drafts over multiple attempts.

- `humanintheloop.py`  
  Demonstrates human-in-the-loop interaction where a user reviews and approves or edits the generated output.

## Tech Stack

- Python
- LangGraph
- LangChain
- Groq
- Streamlit
- FAISS
- Hugging Face Embeddings
- PyPDF
- python-dotenv

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
