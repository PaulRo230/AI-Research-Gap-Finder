# AI Research Gap Finder

This project leverages autonomous AI agents to identify research gaps in academic fields. It uses CrewAI and language models to simulate a researcher that discovers unexplored or underrepresented research areas based on user input.

## Notebook

- `AI_Research_Gap_Finder.ipynb`: Runs a multi-agent system that accepts a research topic and returns a summary of possible unexplored areas using language models like LLaMA via Ollama.

## Features

- Agent-based research planning
- Autonomous querying and summarization
- Uses local LLM (`ollama/llama3.2`) with CrewAI framework
- Asynchronous task execution with agent memory

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/PaulRo230/AI-Research-Gap-Finder.git
   cd AI-Research-Gap-Finder
