# 🚀 CodeFusion: AI-Powered Multi-Agent Coding Assistant using Gemini

CodeFusion is an **AI-driven coding assistant** built using **LangGraph**, **LangChain**, and **Gemini API**.  
It employs an **autonomous multi-agent architecture** — *Planner*, *Architect*, and *Coder* — that collaboratively transforms natural language prompts into **structured, production-ready code**.

---

## 🧠 Key Features

- 🤖 **Gemini-Powered Reasoning:** Uses Google’s Gemini API as the central intelligence engine for understanding and generating code.
- 🧩 **Multi-Agent System:** Implements distinct agents for planning, architecture design, and code generation.
- 💡 **Natural Language to Code:** Converts plain English requirements into syntactically correct and logically consistent code.
- 🔁 **Context-Aware Workflow:** Each agent communicates through LangGraph for iterative refinement and task orchestration.
- ⚙️ **Modular & Extensible:** Easily customizable to integrate with other LLMs or add new agent roles.

---

## 🏗️ Architecture Overview

```text
User Prompt
   ↓
[Planner Agent] → defines overall goal & sub-tasks
   ↓
[Architect Agent] → outlines structure & logic flow
   ↓
[Coder Agent] → writes executable code
   ↓
Output: Final, ready-to-run code
