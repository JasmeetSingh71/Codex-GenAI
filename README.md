Codex-GenAI

An experimental GenAI-powered autonomous software engineering system built using LangGraph
 that simulates a complete software development team.

Codex-GenAI is designed to understand user requirements, plan system architecture, generate production-ready code, debug issues, test applications, and iterate based on feedback — with minimal human intervention.

Inspired by autonomous AI systems like Devin, this project focuses on building a scalable multi-agent AI workflow for real-world software development.
Currently under active development and research. ⚡

✨ Features
🤖 Multi-Agent Architecture (PM, Architect, Planner, Coder, Reviewer, Debugger, Deployer)
🧠 Autonomous project planning & task breakdown
🏗️ AI-generated backend + frontend architecture
💻 Automatic code generation using LLMs
🐳 Docker sandbox execution environment
🔄 Self-debugging & rollback system
📦 Git snapshot/version control per task
🧩 Context-aware coding using file interface registry
💾 Persistent state management with Redis checkpoints
📊 Token tracking & cost monitoring
⚡ Parallel task execution support
🔍 Blueprint validation before development starts
🛠️ Tech Stack
LangGraph — Agent orchestration
Google Gemini API — LLM reasoning & generation
React + Vite — Frontend
Node.js + Express — Backend
PostgreSQL / MongoDB — Database
Redis — State persistence
Docker — Sandbox execution
Git — Snapshots & rollback
Pinecone — Long-term vector memory
🧠 System Workflow
User Requirement
      ↓
PM Agent → Architect Agent → Planner Agent
      ↓
Coder Agent → Reviewer → Executor → Debugger
      ↓
Feedback Loop → Deployment

The system continuously improves code quality using:

validation loops
rollback recovery
project pattern extraction
real execution testing
iterative feedback cycles
⚠️ Current Status

This project is currently under development and not production-ready yet.

The goal is to build a highly reliable autonomous AI engineering system capable of handling real-world software projects with minimal human intervention.

📌 Future Goals
Support multiple tech stacks
Auto deployment pipelines
Advanced RAG integration
Cloud sandbox execution
AI-generated testing suite
Multi-user collaboration
⭐ Vision

“Replacing repetitive software engineering workflows using autonomous AI agents.”

Built with passion for GenAI, autonomous systems, and AI-powered software engineering.