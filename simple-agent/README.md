# Simple Research Agent

A lightweight research agent with web crawling capabilities using Firecrawl MCP tools.

## Features

- Web scraping and crawling
- Data extraction from websites
- Interactive chat interface
- Tool-based architecture

## Setup

1. Install dependencies:
   ```bash
   uv sync
   ```

2. Install Firecrawl MCP:
   ```bash
   npm install -g firecrawl-mcp
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env
   # Add your API keys to .env
   ```

4. Run the agent:
   ```bash
   python main.py
   ```

## Environment Variables

- `OPENAI_API_KEY`: OpenAI API key for language model
- `FIRECRAWL_API_KEY`: Firecrawl API key for web scraping

## Usage

1. Start the application
2. Available tools will be displayed
3. Enter requests for web scraping or data extraction
4. Type 'quit' or 'exit' to stop

## Requirements

- Python 3.11+
- Node.js (for Firecrawl MCP)
- OpenAI API access
- Firecrawl API access
