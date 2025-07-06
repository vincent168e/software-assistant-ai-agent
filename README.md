# Software Assistant AI Agent

## Overview

Software Assistant AI Agent is a Python-based tool designed to assist with software development tasks using OpenAI's language models. The agent leverages the LangChain framework to provide suggestions on coding tools for development. It's particularly useful for developers looking to integrate AI-powered assistance into their coding process.

Key features include:
- Structured workflows using LangGraph for workflow handling
- Integration with OpenAI's models for intelligent code suggestions

## Installation

1. Ensure you have Python 3.12 or later installed
2. Install [uv](https://github.com/astral-sh/uv), a fast Python package installer:
   ```bash
   pip install uv
   ```
3. Create and activate a virtual environment:
   ```bash
   uv venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
4. Install dependencies:
   ```bash
   uv pip install -e .
   ```

## Configuration

1. Create a `.env` file in the project root
2. Add your Firecrawl and OpenAI API key:
   ```
   FIRECRAWL_API_KEY=your_api_key_here
   OPENAI_API_KEY=your_api_key_here
   ```

## Dependencies

The project uses modern Python libraries including:
- LangChain (v0.3.26+) for AI workflow orchestration
- OpenAI integration via langchain-openai
- Pydantic v2 for data validation
- Firecrawl for web content processing
