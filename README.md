# Model Context Protocol (MCP)

## Core MCP Concepts
MCP servers can provide three main types of capabilities:  
**Resources:** File-like data that can be read by clients (like API responses or file contents)  
**Tools:** Functions that can be called by the LLM (with user approval)  
**Prompts:** Pre-written templates that help users accomplish specific tasks  


## Install
1. NodeJS: https://nodejs.org/en/download  
1. Claude Desktop: https://claude.ai/download  
1. UV: An extremely fast Python package and project manager, written in Rust. https://docs.astral.sh/uv/ & https://pypi.org/project/uv/  
3.1. `pip install uv`  
3.2. `powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"` for Windows OS  
3.3- `curl -LsSf https://astral.sh/uv/install.sh | sh` for Linux Base OS  

## Configuration
> Claude Desktop  
**Path:** C:\Users\uslum\AppData\Roaming\Claude  
**Setting Path:** C:\Users\uslum\AppData\Roaming\Claude\claude_desktop_config.json  
**Logs Path:** C:\Users\uslum\AppData\Roaming\Claude\logs  


## References
> Introducing the Model Context Protocol - https://www.anthropic.com/news/model-context-protocol  
> Model Context Protocol (MCP) - https://docs.anthropic.com/en/docs/agents-and-tools/mcp
> MCP Specification - https://modelcontextprotocol.io/specification/2025-03-26
> EP154: What is MCP? https://blog.bytebytego.com/p/ep154-what-is-mcp
> EP165: AI Agent versus MCP - https://blog.bytebytego.com/p/ep165-ai-agent-versus-mcp
> EP163: 12 MCP Servers You Can Use in 2025 - https://blog.bytebytego.com/p/ep163-12-mcp-servers-you-can-use
> https://www.philschmid.de/mcp-introduction 