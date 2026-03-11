<p align="center">
  <img src="https://img.shields.io/badge/MCP-Servers Hub-00B4D8?style=for-the-badge" alt="MCP Servers" />
  <img src="https://img.shields.io/badge/Protocol-Model_Context_Protocol-blueviolet?style=for-the-badge" alt="MCP" />
  <img src="https://img.shields.io/badge/Maintained-Active-brightgreen?style=for-the-badge" alt="Maintained" />
  <img src="https://img.shields.io/badge/PRs-Welcome-orange?style=for-the-badge" alt="PRs Welcome" />
  <img src="https://img.shields.io/badge/License-CC0%201.0-lightgrey?style=for-the-badge" alt="License" />
</p>

<h1 align="center">🔌 MCP Servers Hub</h1>

<p align="center">
  <strong>The community-curated directory of Model Context Protocol (MCP) servers</strong>
  <br />
  <em>Connect your AI agents to databases, APIs, tools & services</em>
</p>

<p align="center">
  <a href="https://aiagentbase.app/skills">🌐 Deploy MCP Servers on AiAgentBase</a> •
  <a href="#-how-to-contribute">🤝 Contribute</a> •
  <a href="#-catalog">📂 Catalog</a> •
  <a href="https://modelcontextprotocol.io">📋 MCP Spec</a>
</p>

---

> 🚀 **Deploy MCP Servers in 1-Click!** Visit [AiAgentBase.app/skills](https://aiagentbase.app/skills) — The Community-Driven AI Skills & Tools Marketplace

---

## 📖 What is MCP?

**Model Context Protocol (MCP)** is an open standard by Anthropic that enables AI agents to connect with external tools, databases, and APIs. Think of MCP servers as the **hands and feet** of your AI — while [Agent Skills](https://agentskills.io) are the **brain**.

```
Skills (SKILL.md) = AI's BRAIN  (knowledge, rules, expertise)
MCP Servers       = AI's HANDS  (actions, tools, integrations)
```

### How MCP + Skills Work Together

```
User asks: "Analyze our sales data and write a report"
    │
    ├── MCP Server: Postgres → Fetches data from database
    ├── MCP Server: Google Sheets → Pulls additional spreadsheet data
    │
    ├── Agent Skill: Data Analyst → Analyzes patterns & trends
    └── Agent Skill: Technical Writer → Writes the report
```

---

## 📂 Catalog

### 🗄️ Databases

| Server | Description | Language | Links |
|---|---|---|---|
| **Postgres MCP** | Query & manage PostgreSQL databases | TypeScript | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) |
| **SQLite MCP** | Local SQLite database operations | TypeScript | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) |
| **MongoDB MCP** | MongoDB database queries & collections | TypeScript | [GitHub](https://github.com/mongodb-js/mongodb-mcp-server) |
| **MySQL MCP** | MySQL database queries & management | Python | [GitHub](https://github.com/designcomputer/mysql_mcp_server) |
| **Supabase MCP** | Full Supabase — auth, storage, database, edge functions | TypeScript | [GitHub](https://github.com/supabase/mcp) |
| **Redis MCP** | Redis cache and data store operations | Python | [GitHub](https://github.com/redis/mcp-redis) |
| **Neon MCP** | Serverless Postgres with branching | TypeScript | [GitHub](https://github.com/neondatabase/mcp-server-neon) |

### 🌐 Web & Scraping

| Server | Description | Language | Links |
|---|---|---|---|
| **Firecrawl MCP** | Advanced web scraping & crawling | TypeScript | [GitHub](https://github.com/mendableai/firecrawl-mcp-server) |
| **Puppeteer MCP** | Browser automation & web scraping | TypeScript | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) |
| **Playwright MCP** | Cross-browser automation & testing | TypeScript | [GitHub](https://github.com/microsoft/playwright-mcp) |
| **Brave Search MCP** | Web search via Brave Search API | TypeScript | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) |
| **Browserbase MCP** | Cloud browser automation | TypeScript | [GitHub](https://github.com/browserbase/mcp-server-browserbase) |

### 🛠️ Developer Tools

| Server | Description | Language | Links |
|---|---|---|---|
| **GitHub MCP** | Repos, issues, PRs, actions management | Go | [GitHub](https://github.com/github/github-mcp-server) |
| **GitLab MCP** | GitLab projects & CI/CD integration | TypeScript | [GitLab](https://gitlab.com/gitlab-org/editor-extensions/gitlab-mcp-server) |
| **Docker MCP** | Container management & orchestration | Go | [GitHub](https://github.com/docker/docker-mcp) |
| **Figma MCP** | Design file access & context | TypeScript | [GitHub](https://github.com/nickarora/figma-context-mcp) |
| **Sentry MCP** | Error tracking & monitoring | TypeScript | [GitHub](https://github.com/getsentry/sentry-mcp) |
| **Linear MCP** | Issue tracking & project management | TypeScript | [GitHub](https://github.com/linearapp/linear-mcp-server) |

### 📈 Business & Productivity

| Server | Description | Language | Links |
|---|---|---|---|
| **Slack MCP** | Messages, channels & workspace mgmt | TypeScript | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) |
| **Notion MCP** | Pages, databases & blocks | TypeScript | [GitHub](https://github.com/makenotion/notion-mcp-server) |
| **Google Drive MCP** | File access, search & management | TypeScript | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) |
| **Google Maps MCP** | Geocoding, directions & places API | TypeScript | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/google-maps) |

### 💰 Finance & Payments

| Server | Description | Language | Links |
|---|---|---|---|
| **Stripe MCP** | Payment processing & subscriptions | TypeScript | [GitHub](https://github.com/stripe/agent-toolkit) |
| **Dodo Payments MCP** | Global payments, licenses & billing | TypeScript | [npm](https://www.npmjs.com/package/@dodopayments/mcp-server) |

### 📁 File Systems & Storage

| Server | Description | Language | Links |
|---|---|---|---|
| **Filesystem MCP** | Local file read/write operations | TypeScript | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) |
| **S3 MCP** | AWS S3 bucket management | Python | [GitHub](https://github.com/awslabs/mcp) |
| **Memory MCP** | Persistent knowledge graph storage | TypeScript | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) |

### 🧠 AI & ML

| Server | Description | Language | Links |
|---|---|---|---|
| **EXA MCP** | AI-powered web search | TypeScript | [GitHub](https://github.com/exa-labs/exa-mcp-server) |
| **Sequential Thinking MCP** | Step-by-step reasoning engine | TypeScript | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/sequentialthinking) |
| **Everart MCP** | AI image generation | TypeScript | [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/everart) |

---

## 📈 Stats

| Metric | Count |
|---|---|
| Total MCP Servers | 35+ |
| Categories | 7 |
| Protocol | [Model Context Protocol](https://modelcontextprotocol.io) |
| Maintained | Community-curated |

---

## 🤝 How to Contribute

Know a great MCP server? Add it to the list!

### Quick Steps

1. ⭐ **Star this repo**
2. 🍴 **Fork** this repository
3. ✏️ **Add** your MCP server in the correct category table in README.md
4. 📤 **Submit a Pull Request**

👉 **Full guidelines:** [CONTRIBUTING.md](CONTRIBUTING.md)

### Entry Format
```markdown
| **Server Name** | Short description (under 80 chars) | Language | [GitHub](link) |
```

### Requirements
- ✅ Must implement MCP (Model Context Protocol)
- ✅ Must have a public repository
- ✅ Must have documentation/README
- ✅ Actively maintained (commits within 6 months)

---

## 🔗 Related Projects

| Project | Description |
|---|---|
| [modelcontextprotocol.io](https://modelcontextprotocol.io) | Official MCP specification |
| [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) | Official MCP server implementations |
| [claude-skills](https://github.com/skillsdirectory/claude-skills) | Agent Skills for Claude |
| [awesome-ai-skills](https://github.com/skillsdirectory/awesome-ai-skills) | Agent Skills for all AI tools |
| [agentskills.io](https://agentskills.io) | Agent Skills specification |

---

## 📄 License

[CC0 1.0 Universal](LICENSE) — Free to use, modify, and share.

---

## ⚖️ Disclaimer

> **This is an independent, community-maintained project.**
>
> - This repository is **NOT** affiliated with, endorsed by, sponsored by, or associated with **any** of the companies, organizations, or products referenced herein, including but not limited to:
>   - **Anthropic** (Model Context Protocol, Claude)
>   - **Supabase, Neon, MongoDB, Redis** (Database providers)
>   - **Stripe, Dodo Payments** (Payment providers)
>   - **GitHub / Microsoft, GitLab** (Developer platforms)
>   - **Google / Alphabet** (Google Drive, Google Maps, Gemini)
>   - **Slack / Salesforce, Notion** (Productivity tools)
>   - **Figma, Sentry, Linear, Browserbase** (Developer tools)
>   - **Brave, EXA** (Search providers)
>   - **Amazon / AWS** (Cloud services)
>   - Any other company, tool, service, or MCP server listed in this repository
> - All product names, trademarks, and registered trademarks are the property of their respective owners. Use of these names is solely for **informational and compatibility purposes** and is considered nominative fair use.
> - The **Model Context Protocol (MCP)** is an open standard. This repository curates community-discovered MCP servers independently.
> - Listings of MCP servers are for **informational purposes only**. Inclusion in this list does not constitute an endorsement, guarantee of quality, security, or ongoing maintenance.
> - This repository and its maintainers make **no warranties** regarding the functionality, security, or reliability of any MCP servers listed herein. **Use at your own risk.**
> - **Individual contributors** are responsible for the entries they submit. Maintainers verify basic information but do not audit the code or security of listed servers.
> - Users should **independently verify** the security and trustworthiness of any MCP server before connecting it to their AI agents or systems.

---

<p align="center">
  <strong>🌟 Found this useful? Give us a ⭐ Star!</strong>
  <br /><br />
  <a href="https://aiagentbase.app/skills">
    <img src="https://img.shields.io/badge/🚀_Deploy_MCP_Servers-AiAgentBase.app-FF6B35?style=for-the-badge" alt="AiAgentBase" />
  </a>
</p>
