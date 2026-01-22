# Agentic AI Pathway (Hands-on Portfolio)

This repository is my hands-on learning portfolio for **Agentic AI systems** using Python notebooks.
The focus is on understanding how modern LLM applications are built end-to-end (prompting → chains → RAG → agents).

## What this repo demonstrates
- Using multiple LLM providers (OpenAI / Gemini / Anthropic / Grok etc.)
- Building reusable prompt + chain patterns (LCEL style)
- Core foundations for agent workflows:
  - prompt templates
  - tool calling patterns (later)
  - retrieval-augmented generation (RAG) foundations (later)
  - debugging + evaluation mindset

## Projects / Notebooks
### 1) Multi-provider LLM basics
**Notebook:** `Using_ChatGPT_or_Google_Gemini.ipynb`
- API key handling (secure, no hardcoding)
- Basic model calls
- Simple helper functions for switching providers

### 2) LangChain LCEL chain (Prompt → LLM)
(coming next)
- `ChatPromptTemplate`
- LCEL pipe syntax: `prompt | llm`
- `.invoke()` calls with structured inputs

## Tech stack (current + planned)
- Python (Jupyter / Colab / local)
- LangChain (LCEL)
- Provider SDKs (OpenAI / Gemini / Anthropic / Grok)

## Notes
- Keys are never committed to GitHub.
- This repo is designed as a learning + portfolio artifact (not a production library).

## Roadmap
- RAG mini-project: ingest → chunk → embed → retrieve → answer
- Tool-using agent: planner → tool calls → final answer
- Evaluation: relevance checks + hallucination reduction

