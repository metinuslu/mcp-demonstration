# Weather MCP Server

## Commands
- Create a new directory for our project  
uv init weather  
cd weather

- Create virtual environment and activate it  
uv venv  
.venv\Scripts\activate  

- Install dependencies  
uv add mcp[cli] httpx  

- Create our server file  
touch weather.py  

## MCP Inspection  
mcp dev weather.py  

## Running the server
uv run weather.py

## Prompts
    Prompt-1: What’s the weather in Sacramento and DC?
    Prompt-2: What are the active weather alerts in Texas?

## What’s happening under the hood
When you ask a question:  

1. The client sends your question to Claude  
1. Claude analyzes the available tools and decides which one(s) to use  
1. The client executes the chosen tool(s) through the MCP server  
1. The results are sent back to Claude  
1. Claude formulates a natural language response  
1. The response is displayed to you!  

## Source:
    [-] https://modelcontextprotocol.io/quickstart/server
    [-] https://modelcontextprotocol.io/quickstart/server#implementing-tool-execution