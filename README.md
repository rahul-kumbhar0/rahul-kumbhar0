<div align="center">

# Rahul Kumbhar

### AI Engineer · LLM Applications · MCP Servers · Agent Tooling

I build tools that let LLMs do real work: MCP servers, tool-use integrations and AI-assisted code migration.<br>
By day I automate finance workflows in NetSuite, so I care about AI that holds up inside real business systems.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rahul%20Kumbhar-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/rahul-kumbhar-a05a31235/)
[![Email](https://img.shields.io/badge/Email-rahulanilkumbhar09%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:rahulanilkumbhar09@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-rahulkumbhar09-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/u/rahulkumbhar09/)

</div>

---

## What I build

- **MCP servers and agent tools**: giving Claude real capabilities (media generation, browser automation) with safe, well-scoped tools
- **LLM-powered developer tools**: AI-assisted SuiteScript migration with confidence scoring and human review
- **Enterprise automation**: SuiteScript 2.x, Suitelets and token-secured approval flows in production NetSuite accounts

---

## Featured projects

### SuiteMigrate · AI-powered SuiteScript migration
Migrates legacy NetSuite SuiteScript 1.0/2.0 code to 2.1 by combining rule-based preprocessing with LLM-assisted conversion.
- Confidence scoring and review flags, so developers check low-certainty output instead of trusting the model blindly
- Web app plus Chrome extension, with auth and usage limits; launched to the NetSuite developer community

`TypeScript` `Next.js` `Supabase` `LLM API` `Chrome Extension` · **[suitemigrate.in](https://suitemigrate.in)**

### FlowCast MCP · Generative media MCP server for Claude
A Python MCP server that gives Claude 7 tools for image generation and editing, text/image-to-video, extending clips and joining them into reels.
- Async job handling for long-running video generation (background jobs + a polling tool)
- Pluggable provider layer: Gemini or free open-source models (FLUX, Wan 2.2 on Hugging Face) with one env var
- Deployed on Render with secret-scoped endpoints

`Python` `MCP (FastMCP)` `Gemini API` `Hugging Face` `Render` · **[Repo](https://github.com/rahul-kumbhar0/instagram-claude-agent)**

### PullRows · AI web scraper with a Claude MCP connector
Chrome extension with 10 extraction tools, an AI Extract feature (plain English → structured table) and an MCP connector so Claude can drive the browser.
- MCP relay + OAuth, because Claude's cloud can't reach a local browser
- Agent guardrails: read-only by default, blocked sensitive sites, rate limits, per-call logging
- Playwright end-to-end tests for the relay, OAuth and MCP flows

`JavaScript (MV3)` `Node.js` `MCP` `OAuth` `Claude API` `Playwright` · **[Repo](https://github.com/rahul-kumbhar0/web-scrapper-extension)**

---

## Currently building

- **JobFit AI**: RAG job matcher that ranks live job posts against a resume (Python, embeddings, pgvector)
- **NetSuite AI Copilot**: an agent that turns plain-English finance questions into validated SuiteQL (LangGraph)

---

## Tech stack

**AI:** Claude API · Gemini API · Model Context Protocol · tool use / function calling · prompt engineering · Hugging Face<br>
**Languages:** Python · TypeScript · JavaScript · SQL · SuiteScript 2.x<br>
**Backend:** Node.js · Express · REST APIs · OAuth / JWT · webhooks<br>
**Frontend:** React · Next.js · Tailwind CSS · Chrome Extensions (MV3)<br>
**Data & Cloud:** Supabase / Postgres · MongoDB · Docker · Vercel · Render · Playwright<br>
**ERP:** NetSuite (SuiteScript, Suitelets, SuiteQL, workflows)

---

## Experience

**Associate ERP Developer, NetSuite** · VNMT Solutions · Jan 2026 – present<br>
SuiteScript 2.x customizations and finance automation, including email-based vendor bill approvals with secure one-click, token-verified actions.
