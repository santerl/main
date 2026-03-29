# Anthropic Academy — Course Summaries
> Source: [anthropic.skilljar.com](https://anthropic.skilljar.com) | Launched: March 2026 | All courses free with certificate

13 self-paced courses across 3 tracks. Total time: ~15–20 hours. No Anthropic account required.

---

## Most Relevant: Developer Track

### 1. Building with the Claude API
**Link:** [anthropic.skilljar.com/claude-with-the-anthropic-api](https://anthropic.skilljar.com/claude-with-the-anthropic-api)
**Size:** 84 lectures · 8+ hours · 10 quizzes — the largest course on the platform

The comprehensive course for integrating Claude into production applications. Covers:
- Basic API calls → advanced features (tool use, streaming, error handling)
- Conversational AI, retrieval-augmented generation (RAG), automated workflows
- Multimodal capabilities (vision, documents)
- Architectural patterns for production AI apps

**Why it matters:** The end-to-end reference for anyone building on Claude. Covers the full Anthropic SDK surface area with hands-on exercises.

---

### 2. Claude Code in Action
**Link:** [anthropic.skilljar.com/claude-code-in-action](https://anthropic.skilljar.com/claude-code-in-action)
**Size:** ~1 hour

Learn to integrate Claude Code (the CLI AI assistant) into your development workflow:
- Reading files, running commands, editing code within the agent loop
- Extending functionality with MCP servers
- GitHub workflow integration
- Using thinking/planning modes for complex programming tasks
- Managing context across sessions

**Why it matters:** Practical workflows for using Claude Code as a day-to-day coding assistant.

---

### 3. Introduction to Agent Skills
**Link:** [anthropic.skilljar.com/introduction-to-agent-skills](https://anthropic.skilljar.com/introduction-to-agent-skills)

Build, configure, and share **Skills** in Claude Code — reusable markdown instruction sets that Claude applies automatically to the right tasks:
- Creating your first Skill from scratch
- Configuring triggers and scope
- Distributing Skills across a team
- Troubleshooting common issues

**Why it matters:** Skills are how you encode repeatable workflows (code review, PR summaries, test generation) so Claude applies them consistently without re-prompting.

---

### 4. Sub-Agents in Claude Code
**Link:** [anthropic.skilljar.com](https://anthropic.skilljar.com)

Use and create sub-agents in Claude Code to:
- Manage context by isolating tasks into separate agents
- Delegate specialized work (research, refactoring, testing) to focused sub-agents
- Build multi-agent workflows that keep the main conversation clean
- Parallelize independent tasks

**Why it matters:** Essential for complex, long-running tasks where a single agent context would become unwieldy.

---

### 5. Introduction to Model Context Protocol (MCP)
**Link:** [anthropic.skilljar.com](https://anthropic.skilljar.com)

Build MCP servers and clients from scratch in Python. Covers MCP's three core primitives:
- **Tools** — callable functions Claude can invoke
- **Resources** — data/content Claude can read
- **Prompts** — reusable prompt templates

Connect Claude to external APIs, databases, file systems, and services.

**Why it matters:** MCP is the standard protocol for extending Claude with external capabilities. Understanding it is required for any serious integration work.

---

### 6. Advanced MCP
**Link:** [anthropic.skilljar.com](https://anthropic.skilljar.com)

Production-grade MCP patterns beyond the basics:
- Sampling (letting the server make LLM calls back through the client)
- Notifications and server-sent events
- File system access patterns
- Transport mechanisms (stdio, SSE, HTTP)
- Production deployment considerations

**Why it matters:** Required reading before shipping an MCP server to users.

---

### 7. Claude with Google Cloud Vertex AI
**Link:** [anthropic.skilljar.com](https://anthropic.skilljar.com)

Full spectrum of working with Anthropic models via Google Cloud's Vertex AI:
- Authentication and API access via Vertex
- Model versioning and deployment
- GCP-native integrations

**Why it matters:** Relevant if your infrastructure runs on GCP or if you need enterprise compliance/data residency controls.

---

## Supplementary: AI Fluency Track

Less technical but useful for understanding how non-developer users interact with Claude — relevant if you're building products for end users.

| Course | Audience | Key Concept |
|--------|----------|-------------|
| **Claude 101** | Everyone | Core Claude usage patterns and practical workflows |
| **AI Fluency: Framework & Foundations** | General professionals | The "4D Framework": Delegation, Description, Discernment, Diligence |
| **AI Fluency for Educators** | Faculty/instructional designers | Applying AI to teaching and institutional strategy |
| **AI Fluency for Students** | Students | AI for learning, career planning, academic success |
| **AI Fluency for Nonprofits** | Nonprofit staff | Mission-aligned AI adoption |
| **Teaching AI Fluency** | Instructors | Formally teaching and assessing AI Fluency in classrooms |

---

## Enterprise Track

| Course | Link | Summary |
|--------|------|---------|
| **Driving Enterprise Adoption of Claude** | [link](https://anthropic.skilljar.com/driving-enterprise-adoption-of-claude) | Scaling Claude across an organization: workflows, change management, literacy programs |
| **Enterprise Train-the-Trainer** | [link](https://anthropic.skilljar.com/enterprise-train-the-trainer) | Equip internal champions to run Claude training at scale |

---

## Certification

- **Claude Certified Architect Foundations** — Anthropic's first official technical certification, launched March 12, 2026. Available through the [Claude Partner Network](https://www.anthropic.com/learn) (free to join).
- All 13 courses offer a **certificate of completion** after passing the final assessment.

---

## Recommended Learning Path (Developer)

```
Claude 101 (30 min)
  → Building with the Claude API (8+ hrs) ← core
  → Claude Code in Action (1 hr)
      → Introduction to Agent Skills
      → Sub-Agents in Claude Code
  → Introduction to MCP
      → Advanced MCP
```

---

*Sources: [anthropic.skilljar.com](https://anthropic.skilljar.com) · [anthropic.com/learn](https://www.anthropic.com/learn) · [aitoolsclub.com](https://aitoolsclub.com/10-free-anthropic-academy-ai-courses-to-master-claude-claude-code-and-mcp/) · [analyticsvidhya.com](https://www.analyticsvidhya.com/blog/2026/03/free-anthropic-ai-courses-with-certificates/) · [kingy.ai](https://kingy.ai/ai/anthropic-academys-new-claude-courses-2026-the-web-developers-guide-to-claude-101-ai-fluency-claude-code-mcp-and-the-claude-api/)*
