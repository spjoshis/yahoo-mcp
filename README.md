# Yahoo-MCP
Yahoo MCP is an MCP server that provides various tools, including retrieving stock prices, viewing stock details, listing available stocks, and more.

### Prerequisite
Make sure you have local LLM or Ollama running

### Installation

Clone the repository:

```bash
git clone https://github.com/spjoshis/yahoo-mcp.git
cd Yahoo-MCP
```

### Setup

```bash
# Create a virtual environment 
uv venv 

# Activate it source .venv/bin/activate

# Install the dependencies
uv sync

# Run the request 
uv run request.py
```
