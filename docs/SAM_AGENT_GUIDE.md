# SAM Specialist Agent Guide

Welcome to the expanded SAM (Smart Agent Manager) ecosystem. This guide explains how to leverage the 27+ specialized agents now available in the framework to accelerate your development across various domains.

## 🤖 The Core Team
These agents manage the foundational TDD (RED-GREEN-REFACTOR) pipeline:
- **`sam-orchestrator`**: Coordinates the entire TDD loop.
- **`sam-atlas`**: Architect for PRD validation and technical design.
- **`sam-titan`**: Test Architect for the **RED** phase (writing failing tests).
- **`sam-dyna`**: Developer for the **GREEN** phase (implementing code).
- **`sam-argus`**: Reviewer for the **REFACTOR** phase (quality and patterns).

## 🌟 The Specialists (Domain Experts)
You can now summon experts for specific technologies and concerns:

### Frontend & UI
- **`sam-react`**: React.js Expert (Hooks, Context, Performance).
- **`sam-next`**: Next.js Architect (App Router, Server Components).
- **`sam-styling`**: CSS Virtuoso (Tailwind, Framer Motion, Animations).
- **`sam-i18n`**: Localization Specialist (RTL, Multi-language support).
- **`sam-a11y`**: Accessibility Lead (WCAG 2.1+, ARIA).
- **`sam-iris`**: UX Designer (Interface feedback and layout).
- **`sam-cosmo`**: CSS Consistency Reviewer.

### Backend & Languages
- **`sam-python`**: Python Expert (FastAPI, Django, Pydantic).
- **`sam-go`**: Go Specialist (Concurrency, gRPC, Microservices).
- **`sam-rust`**: Rust Engineer (Systems programming, Wasm, Performance).
- **`sam-api`**: API Designer (REST, GraphQL, gRPC contracts).
- **`sam-db`**: Database Architect (Schema design, Prisma, Indexing).

### Infrastructure & AI
- **`sam-ops`**: DevOps Engineer (CI/CD, Docker, Terraform).
- **`sam-cloud`**: Cloud Architect (AWS, Azure, GCP infrastructure).
- **`sam-serverless`**: Serverless Specialist (Lambda, Edge Runtimes).
- **`sam-ai`**: AI/LLM Engineer (RAG, Prompt Engineering, Vector DBs).

### Quality & Performance
- **`sam-sec`**: Security Auditor (OWASP, Vulnerability assessment).
- **`sam-perf`**: Performance Analyst (Web Vitals, Bundle optimization).
- **`sam-e2e`**: E2E Testing Specialist (Playwright, Cypress).
- **`sam-sage`**: Technical Writer (Documentation and READMEs).

---

## 🚀 How to Use

### 1. Installation (Interactive TUI)
Run the new interactive installer to choose your platform:
```bash
npx sam-agents
```
Use the **arrow keys** to select your IDE (Gemini CLI, Cursor, Claude Code, etc.) and press **Enter**.

### 2. The `/sam` Dashboard (Gemini CLI)
In the Gemini CLI, type:
```bash
/sam
```
This launches an interactive menu where you can:
- Start the full TDD pipeline.
- Call specific core agents.
- **Call a Specialist**: Select from the expanded roster to handle domain-specific tasks.

### 3. Direct Activation
You can activate any specialist directly at any time:
- **Gemini CLI:** `activate_skill('sam-react')`
- **Cursor:** Mention `@sam-react`
- **Antigravity:** `/sam-react`

---

## 💡 Best Practices
- **Summon Specialists Early**: If you're building a Next.js app, call `sam-next` during the architectural phase with `sam-atlas`.
- **Layered Reviews**: After `sam-dyna` implements a feature, have `sam-argus` do a general review and then `sam-sec` do a security-specific audit.
- **Visual TDD**: Use `sam-iris` and `sam-styling` together to ensure the final implementation matches the intended design and motion.
