# Multi-Agent AI Chatbot

A multi-agent AI chatbot built with n8n that uses multiple LLMs to generate independent responses and a separate Judge model to review them and produce one final answer.

## Features

- Multi-agent AI architecture
- Multiple LLM models
- Google Gemini integration
- OpenRouter integration
- Independent AI responses
- LLM-as-a-Judge
- MongoDB conversation memory
- Calculator tool
- HTTP GET request tool
- n8n workflow orchestration

## Workflow

```text
User Query
    ↓
First Opinion Agent
    +
Second Opinion Agent
    ↓
Merge
    ↓
Judge Model
    ↓
Final Response