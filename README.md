# Kickstart for GitHub MCP Server

## Requirements
- Docker
- `.env` fail järgmise sisuga: GITHUB_TOKEN=your_pat_token
  
## Start
chmod +x start-github-mcp.sh   # ühekordne

./start-github-mcp.sh Skript peatab vana konteineri (kui on) ja käivitab uue `ghcr.io/github/github-mcp-server:latest` pildi. Token loetakse `.env` failist ning konteineri nimi on `github-mcp-server`.