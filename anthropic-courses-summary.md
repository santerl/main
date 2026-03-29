# Anthropic Academy — Course Summaries
> Source: [anthropic.skilljar.com](https://anthropic.skilljar.com) | Launched: March 2, 2026 | 15 courses, all free with certificate

All courses are self-paced, free, and issue official Anthropic certificates. No Claude/Anthropic account required — only a Skilljar account. Many are also cross-listed on Coursera.

---

## Developer Track (Most Relevant)

### 1. Building with the Claude API
**URL:** https://anthropic.skilljar.com/claude-with-the-anthropic-api
**Also on Coursera:** https://www.coursera.org/learn/building-with-the-claude-api
**Size:** 84 lectures · 8+ hours · 10 quizzes

The flagship developer course. Full syllabus:
- API setup, authentication, model selection, first API call
- Single and multi-turn conversations, message formatting, context handling
- System prompts, temperature control, streaming responses, structured output
- **Tool use and function calling** with JSON Schema
- **RAG pipeline architecture** — text chunking, vector embeddings, hybrid search (semantic + BM25), reranking, contextual retrieval
- **Model Context Protocol (MCP)** overview
- **Agentic workflows** — orchestration, parallelization, chaining, routing
- Claude Code for automated development tasks
- Computer Use for UI automation
- Error handling, inference optimization
- **Evaluation frameworks** — model-based and code-based grading

---

### 2. Claude Code in Action
**URL:** https://anthropic.skilljar.com/claude-code-in-action
**Also on Coursera:** https://www.coursera.org/learn/claude-code-in-action
**Size:** 15 lessons · ~6 hours · 4 modules

Full syllabus:
1. Setting Up Claude Code
2. Adding Context with CLAUDE.md
3. Making Changes with Planning and Thinking Modes
4. Controlling Conversation Context
5. Building Custom Commands
6. Extending Claude Code with MCP Servers
7. GitHub Integration for Automated Workflows
8. Introduction to Claude Code Hooks
9. Defining and Configuring Hooks
10. Implementing a Security Hook
11. Useful Hook Patterns for Real Projects
12. The Claude Code SDK

Key concepts:
- **CLAUDE.md** — project context files Claude reads automatically
- **Hooks** — user-defined shell commands that run at points in Claude Code's lifecycle (pre/post tool execution), defined in `settings.json` at global, project, or local scope
- **Claude Code SDK** — programmatic access to the agent loop
- Context management with `/init` and `@` mentions
- MCP server integration

**Prerequisites:** CLI familiarity and basic Git.

---

### 3. Introduction to Agent Skills
**URL:** https://anthropic.skilljar.com/introduction-to-agent-skills
**Size:** 6 lectures · ~30 minutes of video

Skills = SKILL.md files (YAML frontmatter + markdown instructions) that Claude Code applies automatically. Covers:
- Skill structure and YAML frontmatter configuration
- Invocation control: user-invoked vs. Claude-invoked
- Distributing Skills via plugins
- Deploying Skills organisation-wide
- Wiring Skills into custom subagents
- Skills vs. other Claude Code extension mechanisms

**Note:** Claude Code Skills follow the open **Agent Skills standard**, which works across multiple AI tools.

---

### 4. Introduction to Subagents
**URL:** https://anthropic.skilljar.com/introduction-to-subagents

Sub-agents operate in **separate context windows** and return only relevant information back to the main conversation. Covers:
- Managing context by isolating tasks into dedicated agents
- Delegating specialised work (research, refactoring, testing)
- Building multi-agent workflows
- Parallelising independent tasks

**Prerequisites:** Claude Code in Action recommended.

---

### 5. Introduction to Model Context Protocol
**URL:** https://anthropic.skilljar.com/introduction-to-model-context-protocol
**Also on Coursera:** https://www.coursera.org/learn/introduction-to-model-context-protocol

Build MCP servers and clients from scratch in Python. Full syllabus:
- MCP architecture — how it shifts tool-definition to specialised servers
- Three core primitives:
  - **Tools** (model-controlled) — callable functions
  - **Resources** (app-controlled) — data/content Claude can read
  - **Prompts** (user-controlled) — reusable prompt templates
- Transport-agnostic communication and message types
- Building servers with Python SDK decorators (no manual JSON Schema)
- Document management patterns
- **MCP Inspector** for testing and debugging
- Autocomplete and context injection patterns

**Prerequisites:** Working Python knowledge. Follow-up: Advanced MCP.

---

### 6. Model Context Protocol: Advanced Topics
**URL:** https://anthropic.skilljar.com/model-context-protocol-advanced-topics
**Also on Coursera:** https://www.coursera.org/learn/model-context-protocol-advanced-topics

Production-grade MCP patterns:
- **Sampling** — letting the MCP server make LLM calls back through the client
- Real-time notification systems
- File system access control
- Advanced transport mechanisms (stdio, SSE, HTTP)
- Stateless scaling patterns
- Context window efficiency
- Production-ready server design

**Prerequisites:** Introduction to Model Context Protocol.

---

### 7. Claude with Amazon Bedrock
**URL:** https://anthropic.skilljar.com/claude-in-amazon-bedrock

Originally a first-of-its-kind accreditation for AWS employees, now public. Uses the boto3 SDK. Full syllabus:
- Multi-turn conversations, system prompt configuration, structured prompt building
- Tool use and function calling via Bedrock
- RAG pipelines — chunking, embeddings, hybrid search, reranking, contextual retrieval
- **Extended thinking** — Claude's reasoning phase for complex problems
- Vision capabilities, prompt caching
- Claude Code for automated debugging
- MCP tools, resources, and prompts in client applications
- Streaming, temperature control, structured data extraction
- Evaluation frameworks (model-based and code-based grading)

~70% overlaps with Building with the Claude API; differences are AWS-SDK-specific.
**Prerequisites:** Python + basic AWS/Bedrock familiarity.

---

### 8. Claude with Google Cloud's Vertex AI
**URL:** https://anthropic.skilljar.com/claude-with-google-vertex

Full spectrum of Claude on GCP. Covers:
- API access via Vertex AI SDK
- Prompt design, RAG, system evaluation
- AI architecture patterns for production
- Streaming and tool use via Vertex AI

~70% overlaps with Building with the Claude API; differences are GCP-SDK-specific.
**Prerequisites:** Python + Google Cloud Platform experience.

---

### 9. Introduction to Claude Cowork
**URL:** https://anthropic.skilljar.com/introduction-to-claude-cowork

Claude acting as a **computer-use agent on your machine** — working directly with your real files and projects. Covers:
- The Cowork task loop and how context shapes Claude's planning
- Setting up plugins and Skills for your specific work
- File and research workflows
- Steering multi-step work responsibly
- Running end-to-end tasks from first launch through daily use

**Prerequisites:** None.

---

## AI Fluency Track

Non-technical but useful if you're building products for end users — helps you understand how people actually interact with Claude.

| Course | Audience | Key Concept |
|--------|----------|-------------|
| **[Claude 101](https://anthropic.skilljar.com/claude-101)** | Everyone | Core features: Projects, Artifacts, Skills, Research Mode; practical workflows |
| **[AI Fluency: Framework & Foundations](https://anthropic.skilljar.com/ai-fluency-framework-foundations)** | General professionals | **4D Framework**: Delegation, Description, Discernment, Diligence. CC BY-NC-SA licensed. |
| **[AI Fluency for Educators](https://anthropic.skilljar.com/ai-fluency-for-educators)** | Faculty / instructional designers | Applying AI Fluency to teaching practice and institutional strategy |
| **[AI Fluency for Students](https://anthropic.skilljar.com/ai-fluency-for-students)** | University students | Responsible AI for learning, productivity, academic success |
| **[AI Fluency for Nonprofits](https://anthropic.skilljar.com/ai-fluency-for-nonprofits)** | Nonprofit staff | Mission-aligned AI adoption |
| **[Teaching AI Fluency](https://anthropic.skilljar.com/teaching-ai-fluency)** | Instructors | Formally teaching and assessing AI Fluency; ~5–6 hrs, 7 lessons, CC BY-NC-SA |

---

## Enterprise Track

| Course | Link | Summary |
|--------|------|---------|
| **Driving Enterprise Adoption of Claude** | [link](https://anthropic.skilljar.com/driving-enterprise-adoption-of-claude) | Scaling Claude across an org: workflows, change management, literacy programs |
| **Enterprise Train-the-Trainer** | [link](https://anthropic.skilljar.com/enterprise-train-the-trainer) | Equip internal champions to run Claude training at scale |

---

## Certification

- **Claude Certified Architect Foundations** — Anthropic's first official technical cert, launched March 12, 2026. Available through the [Claude Partner Network](https://www.anthropic.com/learn) (free to join). Claude 101 is listed as a preparation course.
- All 15 courses offer a **certificate of completion** after passing the final assessment.

---

## Recommended Learning Path (Developer)

```
Claude 101 (~30 min)
  └─► Building with the Claude API (8+ hrs)  ← core foundation
         ├─► Introduction to MCP
         │     └─► Advanced MCP
         └─► Claude Code in Action (~6 hrs)
               ├─► Introduction to Agent Skills (~30 min)
               └─► Introduction to Subagents

Cloud integrations (pick one if applicable):
  ├─► Claude with Amazon Bedrock  (AWS)
  ├─► Claude with Google Cloud Vertex AI  (GCP)
  └─► Introduction to Claude Cowork  (local computer-use)
```

---

## Platform Summary

| | |
|---|---|
| URL | https://anthropic.skilljar.com |
| Launch | March 2, 2026 |
| Courses | 15 |
| Cost | Free |
| Certificate | Yes, official Anthropic certificate |
| Account needed | Skilljar only (no Claude subscription) |
| Also on Coursera | Yes (several courses) |
| AI Fluency license | CC BY-NC-SA (institutions can adapt) |

---

*Sources: [anthropic.skilljar.com](https://anthropic.skilljar.com) · [analyticsvidhya.com](https://www.analyticsvidhya.com/blog/2026/03/free-anthropic-ai-courses-with-certificates/) · [aitoolsclub.com](https://aitoolsclub.com/10-free-anthropic-academy-ai-courses-to-master-claude-claude-code-and-mcp/) · [kingy.ai](https://kingy.ai/ai/anthropic-academys-new-claude-courses-2026-the-web-developers-guide-to-claude-101-ai-fluency-claude-code-mcp-and-the-claude-api/) · [pasqualepillitteri.it](https://pasqualepillitteri.it/en/news/371/anthropic-academy-free-courses-claude) · [blog.stackademic.com](https://blog.stackademic.com/ia-anthropic-skilljar-sum-up-claude-code-in-action-part-1-context-756e5119ea5f) · [xataka.com](https://www.xataka.com/basics/cursos-gratis-claude-creados-anthropic-15-cursos-oficiales-certificacion-para-aprender-exprimir-su-ia)*
