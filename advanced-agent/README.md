# Advanced Research Agent

A comprehensive research agent for analyzing developer tools and technologies.

## Features

- Automated web scraping and content analysis
- Structured data extraction for developer tools
- Technology stack analysis
- Pricing model identification
- API availability detection
- Integration capability assessment

## Setup

1. Install dependencies:
   ```bash
   uv sync
   ```

2. Set up environment variables:
   ```bash
   cp .env.example .env
   # Add your API keys to .env
   ```

3. Run the agent:
   ```bash
   python main.py
   ```

## Environment Variables

- `OPENAI_API_KEY`: OpenAI API key for language model
- `FIRECRAWL_API_KEY`: Firecrawl API key for web scraping

## Usage

1. Start the application
2. Enter search queries about developer tools
3. Review the analysis and recommendations
4. Type 'quit' or 'exit' to stop

## Requirements

- Python 3.11+
- OpenAI API access
- Firecrawl API access
