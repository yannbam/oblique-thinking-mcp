# Documentation Plan for README.md

Based on my analysis of the project, I'll create comprehensive documentation covering:

## 1. Project Overview
- Description of the Oblique Strategies MCP server
- Brief explanation of what "Oblique Strategies" are (Brian Eno's creative thinking cards)
- What the `start_oblique_thinking` tool provides

## 2. Installation & Requirements
- Python 3.10+ requirement
- UV package manager setup
- Dependency installation via `uv sync` or `pip install -e .`

## 3. Command Line Usage Options
Document all methods to run the server:
- **Direct Python**: `python server.py [mode]`
- **UV run**: `uv run server.py [mode]`
- **FastMCP**: `fastmcp run server.py -- [mode]`
- **UV + FastMCP**: `uv run --with fastmcp fastmcp run server.py -- [mode]`

## 4. Output Modes Explained
Detailed explanation of the three modes with examples:
- **Mode 0** (no argument): Both thinking text + card → `*Thinking text*—Card`
- **Mode 1** (argument "1"): Card only → `Card`
- **Mode 2** (argument "2"): Thinking text only → `*Thinking text*`

## 5. Claude Desktop Integration
Complete JSON configurations for `claude_desktop_config.json`:
- Direct UV method configuration
- FastMCP method configuration  
- UV + FastMCP method configuration
- Guidance on which method to choose

## 6. Usage Examples
- Local testing instructions
- Sample outputs for each mode
- Troubleshooting tips

## 7. Development Notes
- Project structure overview
- How to modify the card lists or thinking texts

This will transform the empty README into a comprehensive guide covering all usage scenarios you requested.