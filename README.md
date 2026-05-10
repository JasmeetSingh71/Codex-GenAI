# 🤖 Codex-GenAI — Multi-Agent AI Software Development System

Codex-GenAI is an autonomous multi-agent software engineering platform built using **LangGraph**, **Gemini**, and **Node.js**.

The system accepts a software requirement and intelligently:
- Understands the requirement
- Asks clarifying questions
- Creates technical specifications
- Plans architecture
- Generates code
- Reviews and debugs output
- Tracks token usage
- Streams execution in real time

---

# 🚀 Features

- Multi-Agent Architecture
- LangGraph Workflow Engine
- Gemini-Powered AI Agents
- Real-Time WebSocket Streaming
- Redis Checkpointing & Persistence
- Token Usage Tracking
- Automated Planning Pipeline
- Modular Agent System
- Frontend Dashboard
- REST + WebSocket APIs

---

# 🧠 Current Development Phase

### ✅ Phase 1 — PM Agent
Transforms raw user requirements into structured software specifications.

Current capabilities:
- Requirement analysis
- Clarification question generation
- Structured spec creation
- Token monitoring

---

# 📁 Project Structure

```bash
codex-project/
├── dashboard/                # Frontend dashboard
├── server/                   # Backend server
│   ├── routes/               # REST APIs
│   ├── services/             # Business logic
│   ├── ws/                   # WebSocket streaming
│   └── index.js
├── src/
│   ├── agents/               # AI agents
│   ├── config/               # Graph + state configs
│   ├── nodes/                # LangGraph nodes
│   └── utils/                # Utilities
├── tests/                    # Test suites
├── .env
├── .gitignore
├── package.json
└── README.md