# Stock Price-2 MCP Server

## Installations

## Commands
> mcp dev stock_price_server.py  
> mcp install stock_price_server.py --name "Stock Price Server" (Check Config File: C:\Users\uslum\AppData\Roaming\Claude\claude_desktop_config.json)  

## Prompts:
    Prompt-1: Could you please provide the current stock price of Tesla?  
    Prompt-2: Could you please compare the prices of Microsoft and Tesla stocks?  
    Prompt-3: Could you please provide the historical data for Tesla over the past month?  

**Source Code:** Building A Simple MCP Server - https://www.kdnuggets.com/building-a-simple-mcp-server

## Description
This is a simple MCP server that provides stock price information for Microsoft and Tesla. It can compare the prices of the two stocks, provide historical data for Tesla, and give the current stock price of Tesla.

## Usage
To use the Stock Price MCP server, you can send prompts to it that request information about stock prices. The server will respond with the requested data.

## Example
### Example 1: Compare Prices
> Could you please compare the prices of Microsoft and Tesla stocks?
### Example 2: Historical Data
> Could you please provide the historical data for Tesla over the past month?
### Example 3: Current Price
> Could you please provide the current stock price of Tesla?

## Requirements
- Python 3.11
- MCP (Machine Communication Protocol)
- requests library for making HTTP requests to stock price APIs

## References
- **MCP Documentation:** https://mcp.readthedocs.io/en/latest/
- **Requests Library Documentation:** https://docs.python-requests.org/en/latest/