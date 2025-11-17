![Banner](/img/Banner.png)

---

# Docker MCP & n8n agent workshop 🚀 

## Workshop Overview  
This hands-on workshop will teach you how to give Large Language Models (LLMs) the ability to manage and interact with other applications using the Docker MCP toolkit, and build practical AI agents using n8n workflow automation.

## What You’ll Need 
- Docker Desktop
- Claude Code Desktop
- Node.js version 18.10 or newer
- npm (comes with Node.js) or pnpm

## Docker MCP
1. Load up Docker Desktop navigate over to the `MCP Toolkit` option on the left panel.
2. Once in the MCP Toolkit area, go over to the `Clients` tab.
3. Look down in the list until you find the client for the Claude Desktop app, and click the blue 'connect' button next to it.
4. Go to the `Catalogue` page and install MCP servers for the tools you want to use (Each server has its own slightly different config).

---

## n8n Agents

### Installing and Running n8n Locally

n8n is a powerful workflow automation tool that can be run locally on your machine. This guide covers installation using npm or pnpm.

### Installation

**Using npm**

```bash
npm install -g n8n
```

**Using pnpm**

```bash
pnpm install -g n8n
```

**Running n8n**

After installation, start n8n with:

```bash
n8n
```

**Accessing n8n**

Once n8n is running, open your browser and navigate to:

```
http://localhost:5678
```

The first time you access n8n, you'll be prompted to create an account.

**Stopping n8n**

Press `Ctrl+C` in the terminal where n8n is running to stop it.

**Data Storage**

By default, n8n stores workflow data in:
- **Linux/macOS**: `~/.n8n`
- **Windows**: `%USERPROFILE%\.n8n`

**Additional Resources**

- [n8n Documentation](https://docs.n8n.io/)
- [n8n GitHub Repository](https://github.com/n8n-io/n8n)
