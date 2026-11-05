# Multi-Agent-Travel-Planner
# Built following Krish Naik’s Trip Agent tutorial, with modifications.

An open-source AI travel planner that turns a natural-language trip request or prompt into a travel plan with flight suggestions, hotel ideas, and a day-by-day itinerary. The project uses a multi-agent workflow built with LangGraph, LangChain, and FastAPI.

Planning a trip usually requires jumping between multiple websites, tools, and spreadsheets. This project brings that flow into one experience by combining a flight-search agent, hotel-research agent, itinerary-planning agent, and a final response agent.

## Features

- Flight research using AviationStack
- Hotel suggestions using Tavily search
- Multi-agent orchestration with LangGraph
- Structured travel itinerary generation
- FastAPI backend with a web interface
- Conversation state persistence using PostgreSQL
- LLM-powered responses with Groq
- Logging using LangSmith

## Tech Stack

- Python 3.10+
- FastAPI
- Jinja2 + HTML/CSS/JavaScript frontend
- LangGraph
- LangChain
- Groq LLMs (openai/gpt-oss-120b)
- PostgreSQL
- Tavily API
- AviationStack API
- PostgreSQL

## Project Setup

1. Create Virtual Environment:
python3 -m venv .venv

2. Active Environment:
source .venv/bin/activate

3. Install the requirements:
pip install -r requirements.txt