<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0f3460,100:16213e&height=180&section=header&text=Awesome%20AI%20Agents&fontSize=52&fontColor=58a6ff&animation=fadeIn&fontAlignY=40&desc=The%20most%20comprehensive%20curated%20list%20of%20AI%20agent%20resources%20on%20the%20internet&descSize=16&descColor=8b949e&descAlignY=62" />

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)](CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/aredwan-xyz/awesome-ai-agents?style=flat-square&color=58a6ff)](https://github.com/aredwan-xyz/awesome-ai-agents/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/aredwan-xyz/awesome-ai-agents?style=flat-square&color=58a6ff)](https://github.com/aredwan-xyz/awesome-ai-agents)
[![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey?style=flat-square)](LICENSE)

**🤖 115 curated resources · 17 categories**

*If this saves you 10 hours of research — give it a ⭐. That's the deal.*

</div>

---

## 📖 Table of Contents

- [🧠 What Are AI Agents?](#-what-are-ai-agents)
- [🔥 Why This List Exists](#-why-this-list-exists)
- [⚡ Quick Start](#-quick-start)
- [🏗️ Frameworks & Platforms](#️-frameworks--platforms)
- [🧩 Core Components](#-core-components)
- [📐 Architecture Patterns](#-architecture-patterns)
- [🛠️ Tools & Utilities](#️-tools--utilities)
- [📚 Papers & Research](#-papers--research)
- [🎓 Learning Resources](#-learning-resources)
- [🎥 Video Courses & Talks](#-video-courses--talks)
- [🏭 Production & Deployment](#-production--deployment)
- [🔐 Safety & Alignment](#-safety--alignment)
- [💼 Real-World Use Cases](#-real-world-use-cases)
- [🌍 Communities](#-communities)
- [🗞️ Newsletters & Blogs](#️-newsletters--blogs)
- [🤝 Contributing](#-contributing)

---

## 🧠 What Are AI Agents?

An **AI agent** is a system that perceives its environment, reasons about it, and takes actions to achieve goals — often autonomously over multiple steps. Unlike a chatbot that answers a single question, an agent can:

- 📋 **Plan** multi-step tasks
- 🛠️ **Use tools** (APIs, browsers, code interpreters, databases)
- 🧠 **Remember** across interactions (short-term + long-term memory)
- 🤝 **Collaborate** with other agents
- 🔁 **Reflect** and self-correct

---

## 🔥 Why This List Exists

The AI agent space exploded in 2024–2026. GitHub now hosts **4.3 million+** AI repositories. Finding the signal in the noise is a full-time job.

This list does the curation work for you — so you can spend time building, not searching.

---

## ⚡ Quick Start

> New to AI agents? Start here.

| Resource | Type | What You'll Learn |
|---|---|---|
| [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) | Framework | The simplest multi-agent starting point |
| [LangGraph Quickstart](https://langchain-ai.github.io/langgraph/) | Tutorial | Graph-based agent orchestration |
| [CrewAI Docs](https://docs.crewai.com/) | Framework | Role-based multi-agent teams |
| [Building Your First Agent](https://www.deeplearning.ai/short-courses/) | Course | DeepLearning.ai — free, ~2 hours |
| [Anthropic Agent Patterns](https://docs.anthropic.com/en/docs/build-with-claude/tool-use) | Guide | Tool use + agentic loop fundamentals |

---

## 🏗️ Frameworks & Platforms

### 🥇 Tier 1 — Production Ready

| Project | Stars | Description | Language |
|---|---|---|---|
| [LangChain](https://github.com/langchain-ai/langchain) | 100k+ ⭐ | The foundational LLM application framework | Python / JS |
| [LangGraph](https://github.com/langchain-ai/langgraph) | 15k+ ⭐ | Stateful, multi-actor agent graphs | Python |
| [OpenAI Agents Python](https://github.com/openai/openai-agents-python) | 20k+ ⭐ | Official OpenAI multi-agent framework | Python |
| [AutoGen](https://github.com/microsoft/autogen) | 40k+ ⭐ | Microsoft's multi-agent conversation framework | Python |
| [CrewAI](https://github.com/crewAIInc/crewAI) | 30k+ ⭐ | Role-based collaborative AI agent teams | Python |
| [Dify](https://github.com/langgenius/dify) | 130k+ ⭐ | Open-source LLM app development platform | Python / TS |
| [Langflow](https://github.com/langflow-ai/langflow) | 140k+ ⭐ | Visual agent builder | Python |

### 🥈 Tier 2 — Specialist / Emerging

| Project | Stars | Description | Language |
|---|---|---|---|
| [MetaGPT](https://github.com/geekan/MetaGPT) | 45k+ ⭐ | Multi-agent framework for software companies | Python |
| [AgentGPT](https://github.com/reworkd/AgentGPT) | 32k+ ⭐ | Browser-based autonomous agent | TypeScript |
| [BabyAGI](https://github.com/yoheinakajima/babyagi) | 20k+ ⭐ | The original task-driven autonomous agent | Python |
| [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) | 15k+ ⭐ | Open-source autonomous AI agent framework | Python |
| [Haystack](https://github.com/deepset-ai/haystack) | 18k+ ⭐ | NLP + RAG + agent pipelines | Python |
| [LightAgent](https://github.com/wanxingai/LightAgent) | ~1.2k ⭐ | Tools, memory, MCP, checkpointed workflows, and verified dynamic DAGs | Python |
| [Flowise](https://github.com/FlowiseAI/Flowise) | 30k+ ⭐ | Drag-and-drop LLM flow builder | JavaScript |
| [n8n](https://github.com/n8n-io/n8n) | 50k+ ⭐ | Workflow automation with native AI | TypeScript |

### 🧪 Experimental / Research

| Project | Stars | Description |
|---|---|---|
| [Voyager](https://github.com/MineDreamer/Voyager) | 6k+ ⭐ | LLM-powered lifelong learning agent in Minecraft |
| [SWE-agent](https://github.com/princeton-nlp/SWE-agent) | 14k+ ⭐ | Agent that resolves real GitHub issues |
| [OpenDevin](https://github.com/OpenDevin/OpenDevin) | 30k+ ⭐ | Open-source Devin software engineering agent |
| [GPT-Engineer](https://github.com/AntonOsika/gpt-engineer) | 52k+ ⭐ | One prompt → entire codebase |
| [Aider](https://github.com/paul-gauthier/aider) | 20k+ ⭐ | AI pair programming in your terminal |

---

## 🧩 Core Components

### 🧠 Memory Systems

| Tool | Stars | What It Does |
|---|---|---|
| [Mem0](https://github.com/mem0ai/mem0) | 25k+ ⭐ | Persistent memory layer for AI agents |
| [Zep](https://github.com/getzep/zep) | 3k+ ⭐ | Long-term memory store for LLM apps |
| [MemGPT](https://github.com/cpacker/MemGPT) | 12k+ ⭐ | OS-inspired memory management for LLMs |
| [ChromaDB](https://github.com/chroma-core/chroma) | 15k+ ⭐ | The open-source embedding database |
| [Pinecone](https://pinecone.io) | — | Managed vector DB, free tier available |
| [Weaviate](https://github.com/weaviate/weaviate) | 12k+ ⭐ | Vector search engine with hybrid search |
| [Qdrant](https://github.com/qdrant/qdrant) | 20k+ ⭐ | High-performance vector database |

### 🛠️ Tool Use & Function Calling

| Resource | Type | Description |
|---|---|---|
| [OpenAI Function Calling](https://platform.openai.com/docs/guides/function-calling) | Docs | The standard for tool use |
| [Anthropic Tool Use](https://docs.anthropic.com/en/docs/build-with-claude/tool-use) | Docs | Claude's tool use API |
| [LangChain Tools](https://python.langchain.com/docs/modules/agents/tools/) | Docs | 100+ pre-built tools |
| [Composio](https://github.com/ComposioHQ/composio) | Framework | 250+ managed tool integrations for agents |
| [Browser Use](https://github.com/browser-use/browser-use) | Tool | Give your agent a real browser |

### 🔁 Orchestration & Planning

| Tool | Description |
|---|---|
| [LangGraph](https://langchain-ai.github.io/langgraph/) | Graph-based stateful orchestration |
| [Prefect](https://github.com/PrefectHQ/prefect) | Workflow orchestration with AI support |
| [Temporal](https://github.com/temporalio/temporal) | Durable execution for long-running agents |
| [Ray](https://github.com/ray-project/ray) | Distributed computing for agent fleets |

---

## 📐 Architecture Patterns

### The Core Loop
```
Observe → Think → Act → Observe → ...
```

### ReAct (Reason + Act)
The most common and reliable agent pattern:
```
User Input
    ↓
Thought: What do I need to do?
    ↓
Action: call_tool("search", query="...")
    ↓
Observation: <search results>
    ↓
Thought: Now I have enough information...
    ↓
Final Answer
```
📄 **Paper:** [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629)

### Plan-and-Execute
Good for long-horizon tasks:
```
Goal → Planner Agent → [Step 1, Step 2, Step 3, ...]
                             ↓
                       Executor Agent → Tool calls
                             ↓
                       Evaluator Agent → Done? Replan?
```

### Multi-Agent Supervisor
```
                    Supervisor Agent
                   /        |        \
           Agent A      Agent B      Agent C
         (Research)    (Writing)    (Review)
```

### Reflection / Self-Critique Loop
```
Draft Response → Critic Agent → Revised Response → Critic → Final
```

### RAG Agent Pattern
```
User Query → Query Rewriter → Vector Search → Context Assembly → LLM → Response
                                                    ↑
                                              Document Store
```

---

## 🛠️ Tools & Utilities

### LLM Providers

| Provider | Models | Best For |
|---|---|---|
| [Anthropic](https://anthropic.com) | Claude 3.5/3.7 Sonnet, Opus | Complex reasoning, long context |
| [OpenAI](https://openai.com) | GPT-4o, o1, o3 | General purpose, tool use |
| [Google](https://ai.google.dev) | Gemini 2.0 Flash/Pro | Multimodal, speed |
| [Ollama](https://github.com/ollama/ollama) | Llama, Mistral, Phi, etc. | Local, private, free |
| [Groq](https://groq.com) | Llama 3, Mixtral | Blazing fast inference |
| [Together AI](https://together.ai) | 100+ open models | Fine-tuning + inference |

### Observability & Debugging

| Tool | Stars | Description |
|---|---|---|
| [LangSmith](https://smith.langchain.com) | — | Tracing, evaluation, monitoring for LLM apps |
| [Arize Phoenix](https://github.com/Arize-ai/phoenix) | 4k+ ⭐ | Open-source LLM observability |
| [Helicone](https://github.com/Helicone/helicone) | 2k+ ⭐ | Open-source LLM observability proxy |
| [Weights & Biases](https://wandb.ai) | — | Experiment tracking with LLM support |
| [PromptLayer](https://github.com/MagnivOrg/prompt-layer-library) | 1k+ ⭐ | Prompt versioning and tracking |

### Evaluation

| Tool | Description |
|---|---|
| [RAGAS](https://github.com/explodinggradients/ragas) | RAG pipeline evaluation framework |
| [DeepEval](https://github.com/confident-ai/deepeval) | LLM evaluation with 50+ metrics |
| [LangChain Evals](https://python.langchain.com/docs/guides/evaluation/) | Built-in evaluation chains |
| [OpenAI Evals](https://github.com/openai/evals) | Framework for evaluating LLMs |
| [Promptfoo](https://github.com/promptfoo/promptfoo) | Red team and test your prompts |

---

## 📚 Papers & Research

### Must-Read Foundation Papers

| Paper | Year | Why It Matters |
|---|---|---|
| [ReAct](https://arxiv.org/abs/2210.03629) | 2022 | The reason+act loop that powers most agents |
| [Chain-of-Thought Prompting](https://arxiv.org/abs/2201.11903) | 2022 | Step-by-step reasoning for LLMs |
| [Toolformer](https://arxiv.org/abs/2302.04761) | 2023 | Teaching LLMs to use tools |
| [HuggingGPT](https://arxiv.org/abs/2303.17580) | 2023 | Using ChatGPT as a controller for AI models |
| [AutoGPT Analysis](https://arxiv.org/abs/2306.02224) | 2023 | What actually works in autonomous agents |
| [LLM as Agent Survey](https://arxiv.org/abs/2309.07864) | 2023 | Comprehensive survey of agent architectures |
| [Generative Agents](https://arxiv.org/abs/2304.03442) | 2023 | Simulating believable human behaviour |

### 2024–2026 Breakthroughs

| Paper | Year | Contribution |
|---|---|---|
| [Agent Hospital](https://arxiv.org/abs/2405.02957) | 2024 | Multi-agent medical diagnosis simulation |
| [SWE-bench](https://arxiv.org/abs/2310.06770) | 2024 | Benchmark for software engineering agents |
| [OpenAI o1 System Card](https://openai.com/index/openai-o1-system-card/) | 2024 | Reasoning chains at inference time |
| [Claude's Extended Thinking](https://docs.anthropic.com/en/docs/build-with-claude/extended-thinking) | 2025 | Deep reasoning in production |

---

## 🎓 Learning Resources

### Free Courses

| Course | Provider | Level | Hours |
|---|---|---|---|
| [AI Agents in LangGraph](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/) | DeepLearning.ai | Beginner | 2h |
| [Multi AI Agent Systems](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/) | DeepLearning.ai | Intermediate | 2h |
| [AI Agentic Design Patterns](https://www.deeplearning.ai/short-courses/agentic-rag-research-assistant/) | DeepLearning.ai | Intermediate | 1.5h |
| [Building Production RAG](https://www.deeplearning.ai/short-courses/building-evaluating-advanced-rag/) | DeepLearning.ai | Advanced | 2h |
| [LangChain Academy](https://academy.langchain.com/) | LangChain | All | Self-paced |
| [Anthropic Courses](https://github.com/anthropics/courses) | Anthropic | All | Self-paced |
| [Fast.ai Practical Deep Learning](https://course.fast.ai/) | fast.ai | Intermediate | 40h |

### Books

| Book | Author | Best For |
|---|---|---|
| [AI Engineering](https://www.oreilly.com/library/view/ai-engineering/9781098166298/) | Chip Huyen | End-to-end AI systems |
| [Building LLMs for Production](https://www.amazon.com/Building-LLMs-Production-Reliability-Fine-Tuning/dp/B0D3P8GCFQ) | Bouchard & Peters | Production-grade LLM apps |
| [Designing Machine Learning Systems](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/) | Chip Huyen | ML systems at scale |

---

## 🎥 Video Courses & Talks

| Resource | Creator | Description |
|---|---|---|
| [Andrej Karpathy — Intro to LLMs](https://www.youtube.com/watch?v=zjkBMFhNj_g) | Andrej Karpathy | 1hr masterclass on how LLMs work |
| [LangChain YouTube](https://www.youtube.com/@LangChain) | LangChain | Weekly tutorials on agents + LLMs |
| [AI Jason](https://www.youtube.com/@AIJasonZ) | AI Jason | Practical agent-building walkthroughs |
| [Sam Witteveen](https://www.youtube.com/@samwitteveenai) | Sam Witteveen | Deep dives into agent architectures |
| [David Shapiro](https://www.youtube.com/@DavidShapiroAutomator) | David Shapiro | Autonomous AI and cognitive architecture |

---

## 🏭 Production & Deployment

### Checklist Before You Ship an Agent

```
✅ Observability   — Are you logging every LLM call, tool use, and decision?
✅ Rate limiting   — Can a single user's bad input loop your agent forever?
✅ Fallbacks       — What happens when the LLM returns garbage?
✅ Cost guardrails — Have you capped max tokens per session?
✅ Human-in-loop  — Can a human override or stop the agent?
✅ Prompt testing  — Did you red-team your system prompt?
✅ Latency SLAs    — What's your P95 response time?
✅ Memory hygiene  — Are you clearing stale context between sessions?
```

### Deployment Patterns

| Pattern | When to Use |
|---|---|
| **Serverless Functions** | Stateless, single-turn agents (Lambda, Cloud Functions) |
| **Container + Queue** | Stateful, long-running agents (Docker + Redis/SQS) |
| **Streaming API** | Real-time UX where users see intermediate steps |
| **Batch Processing** | Offline analysis, document processing, data enrichment |
| **Hybrid** | Synchronous for planning, async for execution |

---

## 🔐 Safety & Alignment

| Resource | Type | Description |
|---|---|---|
| [Anthropic's Agent Safety Guide](https://docs.anthropic.com/en/docs/build-with-claude/agent-design) | Guide | Best practices for safe agents |
| [OWASP LLM Top 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/) | Security | The 10 biggest LLM security risks |
| [Prompt Injection Explained](https://simonwillison.net/2023/Apr/14/prompt-injection/) | Blog | Simon Willison on prompt injection |
| [Guardrails AI](https://github.com/guardrails-ai/guardrails) | Tool | Open-source guardrails for LLM outputs |
| [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | Tool | NVIDIA's guardrail toolkit |
| [Rebuff](https://github.com/protectai/rebuff) | Tool | Prompt injection detector |

---

## 💼 Real-World Use Cases

### By Industry

| Industry | Agent Use Cases |
|---|---|
| **Software Engineering** | Code review, bug detection, PR generation, test writing |
| **Customer Support** | Ticket triage, resolution drafts, escalation routing |
| **Finance** | Document analysis, compliance checking, report generation |
| **Healthcare** | Clinical notes, drug interaction checks, scheduling |
| **Legal** | Contract review, case research, document drafting |
| **Marketing** | Content generation, SEO analysis, campaign optimization |
| **Sales** | Lead research, email personalization, CRM enrichment |
| **Operations** | Process automation, anomaly detection, incident response |

### Open-Source Agent Applications

| Project | Stars | Use Case |
|---|---|---|
| [GPT Researcher](https://github.com/assafelovic/gpt-researcher) | 15k+ ⭐ | Autonomous web research agent |
| [Danswer](https://github.com/danswer-ai/danswer) | 12k+ ⭐ | AI assistant connected to your knowledge base |
| [Perplexica](https://github.com/ItzCrazyKns/Perplexica) | 14k+ ⭐ | Open-source Perplexity AI clone |
| [Open Interpreter](https://github.com/KillianLucas/open-interpreter) | 55k+ ⭐ | Run code locally with a natural language interface |
| [Khoj](https://github.com/khoj-ai/khoj) | 14k+ ⭐ | Personal AI with web + document memory |

---

## 🌍 Communities

| Community | Platform | Members |
|---|---|---|
| [r/LocalLLaMA](https://reddit.com/r/LocalLLaMA) | Reddit | 200k+ |
| [Hugging Face Discord](https://discord.gg/huggingface) | Discord | 100k+ |
| [LangChain Discord](https://discord.gg/langchain) | Discord | 50k+ |
| [AI Engineer Foundation](https://www.aiengineer.foundation/) | Web | — |
| [ODSC Community](https://odsc.com/community/) | Web | — |
| [Latent Space Discord](https://discord.gg/latent-space) | Discord | 20k+ |

---

## 🗞️ Newsletters & Blogs

| Newsletter | Focus | Frequency |
|---|---|---|
| [The Batch (DeepLearning.ai)](https://www.deeplearning.ai/the-batch/) | AI news + research | Weekly |
| [Ahead of AI](https://magazine.sebastianraschka.com/) | LLM research | Monthly |
| [The Rundown AI](https://therundown.ai/) | Daily AI news | Daily |
| [Latent Space](https://www.latent.space/) | AI engineering deep dives | Weekly |
| [Simon Willison's Blog](https://simonwillison.net/) | LLMs + tools | Daily |
| [Chip Huyen's Blog](https://huyenchip.com/blog/) | ML systems | Occasional |
| [Eugene Yan's Blog](https://eugeneyan.com/) | Applied ML | Occasional |

---

## 🤝 Contributing

This list only stays valuable if the community keeps it sharp.

**To add a resource:**
1. Fork this repo
2. Add your resource in the correct category with the format: `| [Name](URL) | Stars | Description |`
3. Open a PR with the title: `Add: [Resource Name]`

**Standards for inclusion:**
- ✅ Open source OR free to use
- ✅ Actively maintained (commit in last 6 months)
- ✅ Clear, demonstrable value
- ❌ No affiliate links
- ❌ No paywalled content without a free tier

---

<div align="center">

**Maintained by [Abid Redwan](https://github.com/aredwan-xyz) · [CodeBeez Technology](http://aredwan.com)**

*If this list saved you time, a ⭐ star is the best thank you.*

[![Star History Chart](https://api.star-history.com/svg?repos=aredwan-xyz/awesome-ai-agents&type=Date)](https://star-history.com/#aredwan-xyz/awesome-ai-agents&Date)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,100:0d1117&height=100&section=footer" />

</div>
