# Awesome adk agents with stars

<div align="center">
  <h1>
    Awesome ADK Agents
    <a href="https://awesome.re">
      <img src="https://awesome.re/badge.svg" alt="Awesome">
    </a>
  </h1>
</div>

<p align="center"><img src="https://google.github.io/adk-docs/assets/agent-development-kit.png" width="200px" alt="Agent Development Kit">
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/sri-krishna-v/awesome-adk-agents?style=flat-square" alt="Stars">
  <a href="CONTRIBUTING.md"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome"></a>
  <a href="https://github.com/google/adk-python"><img src="https://img.shields.io/badge/Powered%20by-Google%20ADK-yellow" alt="Powered by Google ADK"></a>
  <a href="https://www.reddit.com/r/agentdevelopmentkit/"><img src="https://img.shields.io/badge/Reddit-r%2Fagentdevelopmentkit-FF4500?style=flat&logo=reddit&logoColor=white" alt="Reddit: r/agentdevelopmentkit"></a>
  <a href="https://deepwiki.com/google/adk-python"><img src="https://deepwiki.com/badge.svg" alt="Ask DeepWiki"></a>
  <a href="https://mseep.ai/app/sri-krishna-v-awesome-adk-agents"><img src="https://mseep.net/pr/sri-krishna-v-awesome-adk-agents-badge.png" alt="MseeP.ai Security Assessment Badge" height="20"></a>
</p>

*The most comprehensive curated collection for Google's Agent Development Kit (ADK) - featuring **90+ production-ready agents, learning resources, and deployment templates** from hackathon winners ($50K prize pool, 476 submissions), Google's official samples (70+ examples), and a growing community of 20K+ GitHub stars. From beginner tutorials to enterprise-grade multi-agent systems, discover battle-tested solutions for research, business automation, education, and specialized domains.*

## 📖 Table of Contents

* [🎯 What This List Solves](#-what-this-list-solves)
* [What is Google's Agent Development Kit (ADK)?](#what-is-googles-agent-development-kit-adk)
* [🏆 Featured Projects](#-featured-projects)
* [🏆 ADK Hackathon Winners](#-adk-hackathon-winners)
* [🚀 Templates & Starters](#-templates--starters)
* [🌟 Community Excellence](#-community-excellence)
* [📚 Learning Resources](#-learning-resources)
* [🎯 Official Examples](#-official-examples)
* [🚀 Getting Started](#-getting-started)
* [🤝 Contributing](#-contributing)
* [🙏 Acknowledgements](#-acknowledgements)

##

> Welcome to **Awesome ADK Agents**👋👋

A comprehensive ecosystem resource for Google's Agent Development Kit - one of the fastest-growing agentic AI frameworks, with 20K+ stars, 3.6K+ forks, and thousands of dependent projects. Whether you're exploring AI agents for the first time or deploying production multi-agent systems, this collection provides vetted implementations, learning paths, and deployment patterns from Google's official team and a vibrant global community.

## 🎯 What This List Solves

Building production-ready AI agents with Google's ADK shouldn't require starting from scratch or piecing together fragmented tutorials. This curated collection addresses three critical challenges that slow down agent development:

### 1. **Template Discovery & Quality Gap**

* **Problem**: Most developers waste weeks searching for reliable starting points and end up with toy examples that don't scale
* **Solution**: Curated, battle-tested templates and real-world implementations you can actually build upon

### 2. **Production Readiness Barrier**

* **Problem**: Tutorials teach basics, but deploying robust, scalable agents requires understanding integration patterns, error handling, and deployment strategies
* **Solution**: Production-ready examples with complete implementation details, from development to deployment

### 3. **Implementation Learning Curve**

* **Problem**: The jump from "Hello World" tutorials to building meaningful solutions feels overwhelming
* **Solution**: Progressive examples that bridge theory and practice, showing how real developers solve actual problems

**Whether you're a beginner looking for solid foundations or an experienced developer seeking proven patterns, this repository eliminates the trial-and-error phase and accelerates your path to production-ready agents.**

## What is Google's Agent Development Kit (ADK)?

**Google's Agent Development Kit (ADK)** is Google's open-source, code-first Python framework for building production AI agents - backed by Google Cloud with tight Gemini integration while remaining fully model-agnostic (supports Claude, Ollama, LiteLLM). Launched in 2025, ADK has rapidly gained traction with 20K+ GitHub stars, frequent releases (currently v2.x, with the major ADK 2.0 milestone shipped), and adoption by thousands of projects, positioning itself as a serious alternative to established frameworks like LangChain and CrewAI. ADK is now available in Python, Go, Java, and TypeScript.

**Why ADK Matters:**

* **Google's Strategic Bet**: Deep integration with Vertex AI, Cloud Run, BigQuery, and Google's AI ecosystem
* **Production-First Design**: Built for enterprise deployment from day one, not research experiments
* **Model Flexibility**: While optimized for the latest Gemini models, supports Anthropic Claude, Ollama, and any LLM via adapters
* **Active Innovation**: 200+ contributors, community hackathons with $50K prizes, and rapid feature development
* **Growing Ecosystem**: Official samples, third-party integrations (MongoDB, MCP, A2A protocol), and strong community momentum

### 🗝️ Key Features

* **🛠️ Rich Tool Ecosystem**: Pre-built tools, custom functions, OpenAPI specs, and Google ecosystem integration
* **💻 Code-First Development**: Define agents in Python with full testability and version control
* **🔗 Multi-Agent Orchestration**: Compose specialized agents into scalable hierarchies
* **🚀 Deploy Anywhere**: Cloud Run, Vertex AI Agent Engine, or any containerized environment

## 🏆 Featured Projects

*My showcase agents demonstrating production-ready ADK implementations*

| Agent Name                                                                  | Category/Domain           | Short Description                                                                                                                               | Badges |
| --------------------------------------------------------------------------- | ------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| [Job Interview Agent](./my-adk-agents/job-interview-agent/)                 | HR/Recruitment            | AI-powered interview assistant with calendar integration and real-time feedback                                                                 | ⭐🏭🟡  |
| [Education Path Advisor for India](./my-adk-agents/education-path-advisor/) | Education/Career Guidance | Multi-agent AI advisor for Indian students/parents: personalized pathways, stepwise plans, risk analysis, and region/reservation-aware guidance | ⭐🟡    |
| [Academic Research Assistant](./my-adk-agents/academic-research-assistant/) | Research/Academia         | Multi-agent literature review assistant with profile analysis, robust paper search (with SerpAPI fallback), and personalized research synthesis | 🟡     |
| [Project Manager Agent](./my-adk-agents/project-manager-agent/)             | Productivity/Management   | Automated project management with task tracking and progress monitoring                                                                         | 🟡     |
| [Learning Content System (WIP)](./my-adk-agents/local-rag-agent/)           | Information Retrieval     | Enhanced RAG implementation with vector search and context optimization using pgvector and PostgreSQL                                           | 🚧🟡   |

**Badge Legend:**

* ⭐ **My Showcase** - Featured portfolio projects
* 🏭 **Production-Ready** - Has deployment code and infrastructure
* 🔥 **Community Pick** - Outstanding community contributions
* 🚧 **In Development** - Work in progress
* 📚 **Learning Resource** - Educational/tutorial content (official examples are demo/educational only)
* 🟢🟡🔴 **Difficulty**: Beginner, Intermediate, Advanced

***

## 🏆 ADK Hackathon Winners

*Outstanding projects from the Agent Development Kit Hackathon with Google Cloud (May 12 - June 23, 2025)*

> **🎉 $50,000 in prizes awarded** | **476 submissions** | **10,432 participants worldwide**
>
> [View all submissions](https://googlecloudmultiagents.devpost.com/project-gallery) | [Hackathon details](https://googlecloudmultiagents.devpost.com/)

### 🥇 Grand Prize Winner ($15,000)

* 🏆 **[TradeSage AI](https://devpost.com/software/tradesage-ai)** 🏭🔴🔥 - Intelligent multi-agent financial analysis platform that revolutionizes trading hypothesis evaluation using ADK, Agent Engine, Cloud Run and Vertex AI

### 🌍 Regional Winners ($8,000 each)

* 🌎 **North America**: [Energy Agent AI](https://devpost.com/software/energy-agent-ai) 🏭🟡🔥 - Multi-agent AI transforming energy customer management through Google ADK orchestration
* 🌍 **Europe/Middle East/Africa**: [Bleach](https://devpost.com/software/bleach-7tqdmo) 🟡🔥 - Visual AI agent builder for Google ADK with plain English descriptions, visual design, and instant testing
* 🌏 **Asia Pacific**: [Edu.AI](https://devpost.com/software/edu-ai-multi-agent-educational-system-for-brazil) 🟡🔥 - Multi-agent educational system democratizing Brazil's education with autonomous AI agents
* 🌎 **Latin America**: [SalesShortcut](https://devpost.com/software/salesshortcut) 🏭🟡🔥 - Comprehensive AI-powered Sales Development Representative system with multi-agent architecture

### 🎖️ Honorable Mentions ($1,000 each)

* 🧪 [Particle Physics Agent](https://devpost.com/software/particle-physics-agent) 🔴🔥 - Physics AI agent converting natural language into validated Feynman diagrams using real physical laws
* ♻️ [GreenOps](https://devpost.com/software/greenops-gzp4aj) 🟡🔥 - Multi-agent system optimizing operational costs while reducing carbon emissions
* 🎓 [Nexora-AI](https://devpost.com/software/teachai-upzofa) 🟡🔥 - Next-gen personalized education with interactive lessons, visuals, and smart AI support

### 🌟 Notable Submissions

* 🎮 [Lucilla AI Agent Game Studio](https://devpost.com/software/lucilla-ai-agent-game-studio) 🔴🔥 - World's most comprehensive AI game agent platform with fully functional microservices
* 🛡️ [GuardianOS](https://devpost.com/software/guardianos) 🔴🔥 - Multi-agent compliance and monitoring system for privacy-preserving blockchain transactions
* 🌾 [AgriFlow Nexus](https://devpost.com/software/agriflow-nexus) 🟡🔥 - AI-powered platform slashing SADC farm-to-market costs with price prediction and sustainability grading
* 🛠️ [DA-Forge](https://devpost.com/software/da-forge-autonomous-developer-agent) 🔴🔥 - Autonomous developer agent turning text instructions into working automation workflows
* 🚗 [Let's ON:DRIVE](https://devpost.com/software/let-s-on-drive) 🟡🔥 - Emotion-aware AI assistant preventing drowsy driving accidents
* 📊 [Vendo AI](https://devpost.com/software/vendo-ai) 🏭🟡🔥 - Analytics co-pilot connecting to data and helping teams make faster, smarter decisions

**Hackathon Highlights:**

* **476 total submissions** from global developers
* **Multi-agent focus**: All projects showcase collaborative AI systems
* **Categories**: Automation, Data Analysis, Customer Service, Content Creation
* **Google Cloud Integration**: Heavy use of ADK, Vertex AI, Cloud Run, BigQuery
* **Innovation**: Novel applications across physics, education, finance, sustainability, and gaming

***

## 🚀 Templates & Starters

*Ready-to-use templates to kickstart your ADK projects*

* 🔥 [Deep Search ADK Quickstart](https://github.com/google/adk-samples/tree/main/python/agents/deep-search) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🏭🔴⭐ - **The gold standard**: Complete fullstack research agent (formerly Gemini Fullstack) with React frontend, human-in-the-loop workflows, autonomous research pipelines, and Cloud Run deployment
* 🚀 [GoogleCloudPlatform/agent-starter-pack](https://github.com/GoogleCloudPlatform/agent-starter-pack) ⭐ 6,543 | 🐛 49 | 🌐 Python | 📅 2026-07-21 🏭🟢 - Production-ready Generative AI Agent templates for Google Cloud with ADK samples, comprehensive deployment infrastructure
* 📱 [kkdai/linebot-adk](https://github.com/kkdai/linebot-adk) ⭐ 33 | 🐛 0 | 🌐 Python | 📅 2026-08-17 🏭🟢 - LINE Bot template with Docker, Cloud Run deployment, and security configurations
* 🌐 [phamvuhoang/google-adk-nextjs-starter](https://github.com/phamvuhoang/google-adk-nextjs-starter) ⭐ 24 | 🐛 0 | 🌐 TypeScript | 📅 2025-04-17 🟢 - Next.js starter template for Google ADK projects with Angular frontend
* 🎨 [abhishekkumar35/google-adk-nocode](https://github.com/abhishekkumar35/google-adk-nocode) ⭐ 24 | 🐛 2 | 🌐 Python | 📅 2025-04-10 🟢 - Visual, no-code interface for creating AI agents (supports cloud and local Ollama models)
* 🧪 [Yash-Kavaiya/google-adk-test-automation](https://github.com/Yash-Kavaiya/google-adk-test-automation) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-07-27 🏭🟡 - Comprehensive ADK testing framework with automated conversation flows, session management, and detailed CSV reporting

***

## 🌟 Community Excellence

*Outstanding community projects showcasing ADK capabilities*

### Multi-Agent Systems

* 🚀 [kweinmeister/agentic-trading](https://github.com/kweinmeister/agentic-trading) ⭐ 251 | 🐛 4 | 🌐 Python | 📅 2026-08-24 🏭🔴 - Multi-agent trading system with risk management, featuring AlphaBot and RiskGuard agents with complete A2A protocol implementation and production deployment
* 📊 [vladkol/CRM Data Q\&A Agent](https://github.com/vladkol/crm-data-agent) ⭐ 145 | 🐛 2 | 🌐 Python | 📅 2025-06-20 🏭🔴 - Multi-agentic system with Advanced RAG and NL2SQL over Salesforce Data, "Run on Google Cloud" deployment
* 🌐 [seehiong/adk-web-multi-agent](https://github.com/seehiong/adk-web-multi-agent) ⭐ 37 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-11-03 🟡 - Multi-agent system with Google ADK and OpenRouter models coordinating specialist agents to query PostgreSQL (via MCP Toolbox) and Data Commons
* 🏛️ [intent-solutions-io/iam-bobs-brain](https://github.com/intent-solutions-io/iam-bobs-brain) ⭐ 22 | 🐛 1 | 🌐 Python | 📅 2026-07-15 🏭🔴 - General-purpose enterprise orchestrator on Google ADK + Vertex AI Agent Engine with risk tiers (R0-R4), policy gates, evidence bundles, and Mission Spec v1 workflows
* 🤖 [derailed-dash/rickbot-adk](https://github.com/derailed-dash/rickbot-adk) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2026-06-30 🏭🟡 - Multi-personality chatbot with FastAPI backend, Next.js UI, OAuth, and multi-agent RAG/search architecture
* 🔥 [Parth0248/Forkcast](https://github.com/Parth0248/Forkcast) ⭐ 7 | 🐛 1 | 🌐 Python | 📅 2025-06-25 🏭🟡 - Multi-agent AI system for collaborative dining decisions with deployed webapp, technical reports, and Cloud Run deployment

### Integration & Advanced Patterns

* 🛡️ [microsoft/agent-governance-toolkit](https://github.com/microsoft/agent-governance-toolkit) ⭐ 6,109 | 🐛 222 | 🌐 Python | 📅 2026-08-21 🏭🔴🔥 - Governance toolkit for AI agents (now maintained by Microsoft, formerly `agent-os`) with policy enforcement, zero-trust identity, execution sandboxing, and full OWASP Agentic Top 10 coverage — works with Google ADK, LangChain, CrewAI, AutoGen, and more
* ⚡ [lemony-ai/cascadeflow](https://github.com/lemony-ai/cascadeflow) ⭐ 3,984 | 🐛 8 | 🌐 Python | 📅 2026-08-06 🏭🔴🔥 - Cascading runtime that optimizes cost, latency, quality, and policy decisions inside the agent loop, with support for Google ADK and 20+ model providers
* 🔐 [Idun-Group/idun-agent-platform](https://github.com/Idun-Group/idun-agent-platform) ⭐ 198 | 🐛 110 | 🌐 Python | 📅 2026-08-06 🏭🔴🔥 - Open-source Agent Governance Platform that turns any LangGraph or ADK agent into a production-ready service with AG-UI, OpenTelemetry, MCP, memory, guardrails, SSO, and RBAC
* 🎤 [bhancockio/Voice-Enabled-Agent](https://github.com/bhancockio/adk-voice-agent) ⭐ 89 | 🐛 1 | 🌐 Python | 📅 2025-05-14 🟡 - Speech-to-text and voice interaction capabilities with G-Calendar integration and comprehensive setup documentation
* 🚦 [ThreeMoonsLab/agents-shipgate](https://github.com/ThreeMoonsLab/agents-shipgate) ⭐ 87 | 🐛 29 | 🌐 Python | 📅 2026-08-25 🏭🟡 - Deterministic merge gate performing local-first, static Tool-Use Readiness review for MCP, OpenAPI, and SDK tool surfaces (CLI + GitHub Action)
* 🔌 [RubensZimbres/A2A\_ADK\_MCP](https://github.com/RubensZimbres/A2A_ADK_MCP) ⭐ 58 | 🐛 3 | 🌐 Python | 📅 2025-04-21 🔴 - Multi-Agent Systems using Google's ADK + A2A + MCP
* 🖥️ [trendmicro/adk-agui-middleware](https://github.com/trendmicro/adk-agui-middleware) ⭐ 40 | 🐛 9 | 🌐 Python | 📅 2026-03-02 🏭🟡 - Python middleware bridging Google ADK agents with the AG-UI protocol via Server-Sent Events for real-time agent interactions in frontend applications
* 🔗 [serkanyasr/mcp-agent-tool-adapter](https://github.com/serkanyasr/mcp-agent-tool-adapter) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-04-14 🟡 - Converts MCP tools into Google ADK or LangGraph agents with streaming FastAPI/CLI
* ✅ [ceodaradigu/proofline-agent](https://github.com/ceodaradigu/proofline-agent) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-24 🏭🟡 - Evidence-first Google ADK agent that blocks external action until fresh authoritative evidence passes a deterministic four-state gate and explicit human approval, with Cloud Run deployment and unit tests
* 🔧 [codeninja/Mongoose Migration Agent System](https://gist.github.com/codeninja/a6e117a3480de8d32dd9ef01b519cdae) 🔴🔥 - Multi-agent system for automated Mongoose database migration (v6→v8) with specialized agents and MCP integration

### Agent Development & Engineering Platforms

* 🦀 [vllora/vllora](https://github.com/vllora/vllora) ⭐ 812 | 🐛 29 | 🌐 Rust | 📅 2026-06-30 🟡 - Rust-based AI gateway and debugger for agents with tracing and routing across Google ADK, LangChain, and 20+ providers
* 🏗️ [antiv/mate](https://github.com/antiv/mate) ⭐ 87 | 🐛 1 | 🌐 Python | 📅 2026-08-22 🏭🔴🔥 - Production-ready multi-agent orchestration engine built on Google ADK with database-driven agent config, 50+ LLM providers, MCP protocol, persistent memory, web dashboard, and RBAC
* 🗄️ [edu010101/adk-extra-services](https://github.com/edu010101/adk-extra-services) ⭐ 18 | 🐛 1 | 🌐 Python | 📅 2025-10-22 🏭🟡 - Python package providing additional service backends for Google ADK (S3, Redis, MongoDB, Azure, Supabase) to replace default in-memory storage
* 🧠 [serkanh/adk-with-memorybank](https://github.com/serkanh/adk-with-memorybank) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2025-07-10 🏭🟡 - ADK agents integrated with Vertex AI Memory Bank for persistent cross-session memory and context management
* 🛠️ [VidyutChakrabarti/AgentFlux](https://github.com/VidyutChakrabarti/AgentFlux) ⭐ 10 | 🐛 0 | 🌐 TypeScript | 📅 2025-07-20 🏭🔴🔥 - Agent engineering platform with interactive playgrounds, graph visualization, automated refinement loops, and fine-tuned models for prompt optimization

### Domain-Specific Applications

* 🔬 [K-Dense-AI/k-dense-byok](https://github.com/K-Dense-AI/k-dense-byok) ⭐ 1,040 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-24 🔴🔥 - Desktop AI co-scientist powered by scientific agent skills for bioinformatics and drug discovery (BYOK, local-first, runs on Google ADK)
* 📚 [Beever-AI/beever-atlas](https://github.com/Beever-AI/beever-atlas) ⭐ 442 | 🐛 56 | 🌐 Python | 📅 2026-08-12 🟡 - Conversational wiki knowledge base with Slack/Teams/Discord bots, RAG, and MCP integration built on Google ADK
* 🌐 [anxuanzi/bua](https://github.com/anxuanzi/bua) ⭐ 86 | 🐛 1 | 🌐 Go | 📅 2026-01-04 🟡 - AI-powered browser automation for Go — describe tasks in plain English and let the ADK-powered agent handle the clicks via vision-language models
* ✈️ [AashiDutt/Google-Agent-Development-Kit-Demo](https://github.com/AashiDutt/Google-Agent-Development-Kit-Demo) ⭐ 65 | 🐛 3 | 🌐 Python | 📅 2025-05-25 🟢 - ADK-powered travel planner
* 🔍 [sreekar2858/JobSearch-Agent](https://github.com/sreekar2858/JobSearch-Agent) ⭐ 50 | 🐛 0 | 🌐 Python | 📅 2026-01-19 🟡 - Automated job search agent using ADK that scrapes listings from LinkedIn, Indeed, and Glassdoor, filters by preferences, and manages applications
* 📊 [AI Trends Analysis Pipeline](https://github.com/Astrodevil/ADK-Agent-Examples/tree/main/analyzer_agent) ⭐ 47 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2025-11-08 🟡🔥 - Comprehensive AI analysis pipeline using Exa Search, Tavily Search, Firecrawl and Nebius AI
* 📁 [Job Finder Agent](https://github.com/Astrodevil/ADK-Agent-Examples/tree/main/jobfinder_agent) ⭐ 47 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2025-11-08 🟡 - Sequential Agent using Mistral OCR, Linkup API and Nebius AI
* 📧 [Email ADK Agent](https://github.com/Astrodevil/ADK-Agent-Examples/tree/main/email_adk_agent) ⭐ 47 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2025-11-08 🟢 - Email management and automation agent using Resend API
* 🔧 [serkanh/sre-bot](https://github.com/serkanh/sre-bot) ⭐ 44 | 🐛 3 | 🌐 Python | 📅 2025-10-13 🏭🟡 - SRE/DevOps bot built on Google ADK for intelligent infrastructure management and incident response
* 📈 [sudsk/tradesage-mvp](https://github.com/sudsk/tradesage-mvp) ⭐ 42 | 🐛 1 | 🌐 Python | 📅 2025-06-23 🏭🟡 - Multi-agent trading hypothesis analysis system with 6 specialized agents and Cloud Run deployment
* 🎨 [bhancockio/YouTube-Thumbnail-Agent](https://github.com/bhancockio/adk-youtube-thumbnail-agent) ⭐ 33 | 🐛 1 | 🌐 Python | 📅 2025-05-08 🟢 - Automated thumbnail generation and optimization
* 💰 [mtwn105/zerodha-mcp](https://github.com/mtwn105/zerodha-mcp) ⭐ 32 | 🐛 2 | 🌐 Python | 📅 2025-04-17 🟡 - Zerodha MCP Server & Client integrating Google ADK for financial applications
* 📦 [arjunprabhulal/MCP-Gemma-3-Agent](https://github.com/arjunprabhulal/adk-mcp-gemma3) ⭐ 27 | 🐛 3 | 🌐 Python | 📅 2025-04-23 🟡 - Gemma 3 leveraged by Ollama, MCP Youtube Search
* 🔬 [emansarahafi/Research-Assistant-Agent](https://github.com/emansarahafi/Research-Assistant-Agent) ⭐ 23 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-12-06 🟡 - Multi-agent research assistant with Researcher, Analyst, and Formatter sub-agents using ArXiv search, deployable locally (Flask) or on Vertex AI
* 🏭 [ntg2208/production-ai-customer-support](https://github.com/ntg2208/production-ai-customer-support) ⭐ 21 | 🐛 1 | 🌐 Python | 📅 2025-12-06 🔴🏭 - Enterprise-grade multi-agent system with Policy Agent, Ticket Agent, and Master orchestrator featuring location intelligence, RAG knowledge base, and comprehensive tutorials
* 📚 [Anubhob435/Ai-Agents-EditorHouse](https://github.com/Anubhob435/Ai-Agents-EditorHouse) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2026-04-22 🟡 - Multi-agent book creation system using Google ADK that plans, writes, edits, illustrates, and compiles complete books from a single topic prompt with MongoDB metadata tracking
* 🧠 [IhateCreatingUserNames2/Cognisphere](https://github.com/IhateCreatingUserNames2/Cognisphere) ⭐ 17 | 🐛 1 | 🌐 Python | 📅 2025-06-06 🔴 - AI agent development framework built on Google's ADK
* 👔 [akajammythakkar/adk\_hiring\_agent](https://github.com/akajammythakkar/adk_hiring_agent) ⭐ 12 | 🐛 2 | 🌐 Python | 📅 2025-12-21 🟡 - AI-powered hiring agent using Google ADK and Gemini to analyze resumes, assess skills, and match candidates via multi-agent collaboration
* 💬 [B4K2/WhatsApp-agent](https://github.com/B4K2/WhatsApp-agent) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2026-03-07 🟡 - Intelligent WhatsApp agent built with MCP + Google ADK for conversational automation
* 💹 [RubensZimbres/Financial\_ADK\_Agent\_Graph\_Database](https://github.com/RubensZimbres/Financial_ADK_Agent_Graph_Database) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-01-23 🏭🔴 - Multi-agent financial analytics with Neo4j graph database, SEC filings RAG, and ML stock predictions
* 📊 [jenyss/google-adk-data-visualization-agent](https://github.com/jenyss/google-adk-data-visualization-agent) ⭐ 4 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-04-27 🟡 - Data visualization agent built with Google ADK
* 🏥 [Ahsan462aggk/Medical\_Search\_Pro\_Agent](https://github.com/Ahsan462aggk/Medical_Search_Pro_Agent) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2025-06-22 🟡🏭 - Multi-agent biomedical research system with PubMed search, analysis, and email delivery

***

## 📚 Learning Resources

*Comprehensive guides, tutorials, and educational content*

### ⭐ Featured Training Platform

* 🏆 **[Google ADK Training Hub](https://raphaelmansuy.github.io/adk_training/)** 🟢🟡🔴📚🔥 - **The most comprehensive ADK training platform**: 35+ hands-on tutorials, production deployment patterns, multi-agent architectures, Cloud Run/Vertex AI deployment, React/Next.js integration, and enterprise-grade best practices. Progressive learning paths from beginner to advanced with copy-paste ready code and working implementations.

### 🚀 Quickstart Courses

* 📚 [ADK Crash Course by Brandon Hancock](https://github.com/bhancockio/agent-development-kit-crash-course) ⭐ 897 | 🐛 22 | 🌐 Python | 📅 2025-05-02 🟢📚 - Fundamentals of ADK, from basics to advanced workflows and multi-agent systems with [Youtube](https://www.youtube.com/watch?v=P4VFL9nIaIA\&t=2659s) tutorial
* 📚 [chongdashu/adk-made-simple](https://github.com/chongdashu/adk-made-simple) ⭐ 135 | 🐛 4 | 🌐 Python | 📅 2025-05-23 🟢📚 - From basics to A2A integration with real world applications and projects
* 📚 [A2A Crash Course by Brandon Hancock](https://github.com/bhancockio/agent2agent) ⭐ 131 | 🐛 0 | 🌐 Python | 📅 2025-08-27 🟡📚 - Comprehensive guide to building agent-to-agent (A2A) communication using ADK with [Youtube](https://www.youtube.com/watch?v=mFkw3p5qSuA\&t=172s) tutorial
* 📚 [omerbsezer/Fast-LLM-Agent-MCP](https://github.com/omerbsezer/Fast-LLM-Agent-MCP) ⭐ 87 | 🐛 0 | 🌐 Python | 📅 2026-08-24 🟡📚 - Comprehensive resource covering LLMs, RAG, fine-tuning, agents, MCP, and Google ADK both theoretically and practically with reference documents
* 📚 [theailifestyle/google-adk-demos](https://github.com/theailifestyle/google-adk-demos) ⭐ 52 | 🐛 2 | 🌐 Python | 📅 2025-05-17 🟢📚 - Collection of practical demos showcasing various ADK features
* 📚 [arjunprabhulal/google-adk-masterclass](https://github.com/arjunprabhulal/google-adk-masterclass) ⭐ 44 | 🐛 0 | 🌐 Python | 📅 2025-12-08 🟡📚 - 20-module masterclass covering ADK basics through advanced topics including MCP, Vertex AI, and production deployment
* 📚 [proflead/how-to-build-ai-agent](https://github.com/proflead/how-to-build-ai-agent) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2025-04-29 🟢📚 - Beginner-friendly tutorial for building AI agents with Google ADK, covering install, tools, and first agent creation

### 🧪 Official Hands-on Learning

* 🧪 [Google ADK Codelabs](https://codelabs.developers.google.com/?text=ADK) ⭐📚 - Interactive, guided tutorials with hands-on coding exercises from Google
* 🧪 [Build Your First ADK Agent Workforce](https://cloud.google.com/blog/topics/developers-practitioners/build-your-first-adk-agent-workforce) ⭐🟢📚 - Complete learning path with 3 official codelabs: building autonomous agents, empowering agents with tools, and orchestrating multi-agent systems
* 🧪 [Building GraphRAG Agents with ADK and Neo4j](https://codelabs.developers.google.com/neo4j-adk-graphrag-agents) ⭐🟡📚💡 - Official 65-minute codelab building multi-agent investment research system with Neo4j graph database, MCP Toolbox integration, and GraphRAG patterns for complex relationship traversal and multi-hop reasoning
* 🎓 [5-Day Agents Course on Kaggle](https://www.kaggle.com/learn-guide/5-day-agents) ⭐📚 - Comprehensive 5-day online course crafted by Google's ML researchers and engineers exploring foundations and practical applications of AI agents, covering core components (models, tools, orchestration, memory, and evaluation) and production-ready systems
* 📖 [Introduction to Agents Whitepaper](https://www.kaggle.com/whitepaper-introduction-to-agents) ⭐📚 - Comprehensive whitepaper by Google's AI researchers explaining the paradigm shift from passive AI models to autonomous problem-solving agents, covering agent architecture, capabilities, and real-world applications

### 📖 Tutorials & Walkthroughs

* 📖 [bhancockio/RAG-Agent-Tutorial](https://github.com/bhancockio/adk-rag-agent) ⭐ 136 | 🐛 3 | 🌐 Python | 📅 2025-05-11 🟡📖 - Complete RAG implementation with ADK and Vertex AI with [YouTube](https://www.youtube.com/watch?v=TvW4A0a75mw\&t=14s) tutorial
* 📖 [bhancockio/MCP Integration Tutorial](https://github.com/bhancockio/adk-mcp-tutorial) ⭐ 91 | 🐛 2 | 🌐 Python | 📅 2025-05-29 🟡📖 - Model Context Protocol (both local and remote) with ADK with [Youtube](https://www.youtube.com/watch?v=HkzOrj2qeXI\&t=2362s) tutorial
* 📖 [sokart/adk-walkthrough](https://github.com/sokart/adk-walkthrough) ⭐ 86 | 🐛 1 | 🌐 Python | 📅 2025-06-17 🟡📖 - Step-by-step guides and examples using the open-source Python ADK framework
* 📖 [chongdashu/adk-mcp-a2a-crash-course](https://github.com/chongdashu/adk-mcp-a2a-crash-course) ⭐ 53 | 🐛 3 | 🌐 Python | 📅 2025-06-14 🟡📖🔥 - Complete multi-agent system with ADK + A2A + MCP integration, featuring Notion and ElevenLabs with full architecture, testing, and [YouTube](https://www.youtube.com/watch?v=s6-Ofu-uu2k) tutorial
* 📖 [mongodb-developer/MongoDB-ADK-Agents](https://github.com/mongodb-developer/MongoDB-ADK-Agents) ⭐ 47 | 🐛 1 | 🌐 Python | 📅 2025-10-05 🟡📖💡 - Official MongoDB grocery shopping agent implementation with Vector Search, complete dataset, and step-by-step setup - companion repository  for the MongoDB Atlas tutorial
* 📖 [lavinigam-gcp/build-with-adk](https://github.com/lavinigam-gcp/build-with-adk) ⭐ 44 | 🐛 2 | 🌐 HTML | 📅 2026-04-29 🏭🟡📖 - Design patterns and production-ready architectures for building multi-agent AI systems with Google ADK on Cloud Run, Vertex AI, and AI Studio
* 📖 [meteatamel/adk-demos](https://github.com/meteatamel/adk-demos/) ⭐ 41 | 🐛 1 | 🌐 Python | 📅 2025-10-29 🟢📖 - Collection of demos and tutorials for Google's Agent Development Kit
* 📖 [thomas-chong/google-adk-visual-agent-builder-demo](https://github.com/thomas-chong/google-adk-visual-agent-builder-demo) ⭐ 32 | 🐛 0 | 📅 2025-11-10 🟡📖 - Complete demo of Google ADK Visual Agent Builder with a multi-agent research system walkthrough
* 📖 [datascalehq/datascale](https://github.com/datascalehq/datascale/tree/main/cookbook/tutorials/agent_docs) ⭐ 10 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-06-19 🟡📖🔥 - Multi-agent documentation builder with planner and writer agents that automatically analyze codebases and generate structured knowledge bases - companion repository for the codebase documentation article
* 📝 [Add Live Web Search to a Google ADK Agent](https://superhighway.walls.sh/guides/web-search-google-adk) 🟢📝 - Step-by-step guide for adding live web search to ADK agents: MCPToolset with StdioConnectionParams for autonomous x402 per-call payments (USDC on Base, no signup), or plain Python function tools with a free API key. Covers both patterns with complete runnable code.

#### 🎓 Google ADK Tutorial Examples

*Comprehensive tutorial examples from [awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 demonstrating ADK patterns and capabilities*

**Fundamentals:**

* 📖 [Starter Agent](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/1_starter_agent) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟢📖 - Your first ADK agent: basic agent creation, the ADK workflow, and simple text processing
* 📖 [Model-Agnostic Agent](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/2_model_agnostic_agent) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟢📖 - Running ADK with non-Gemini models, with OpenAI and Anthropic Claude integration sub-examples
* 📖 [Memory Agent](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/5_memory_agent) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟢📖 - Memory and session management with in-memory conversation handling and persistent SQLite storage
* 📖 [Simple Multi-Agent](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/8_simple_multi_agent) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟢📖 - Multi-agent orchestration via a researcher pipeline of specialized agents in a sequential workflow
* 📖 [ADK YAML Examples](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/adk_yaml_examples) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟢📖 - Config-driven agent definitions using ADK's YAML format

**Structured Output Agents:**

* 📖 [Customer Support Ticket Agent](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/3_structured_output_agent/3_1_customer_support_ticket_agent) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟢📖 - Generates structured support tickets with Pydantic schemas
* 📖 [Email Generator Agent](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/3_structured_output_agent/3_2_email_agent) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟢📖 - Creates formatted emails with structured output

**Tool-Using Agents:**

* 📖 [Code Execution Agent](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/4_tool_using_agent/4_1_builtin_tools/code_exec_agent) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟢📖 - Built-in code execution tools
* 📖 [Google Search Agent](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/4_tool_using_agent/4_1_builtin_tools/search_agent) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟢📖 - Web search capabilities
* 📖 [Filesystem Agent](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/4_tool_using_agent/4_4_mcp_tools/filesystem_agent) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟢📖 - MCP filesystem tools integration
* 📖 [LangChain Integration Agent](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/4_tool_using_agent/4_3_thirdparty_tools/langchain_agent) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟢📖 - Third-party tool integration with LangChain
* 📖 [CrewAI Integration Agent](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/4_tool_using_agent/4_3_thirdparty_tools/crewai_agent) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟢📖 - Third-party tool integration with CrewAI

**Callback Agents:**

* 📖 [Agent Lifecycle Callbacks](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/6_callbacks/6_1_agent_lifecycle_callbacks) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟢📖 - Monitoring agent execution lifecycle
* 📖 [LLM Interaction Callbacks](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/6_callbacks/6_2_llm_interaction_callbacks) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟢📖 - Tracking LLM calls and responses
* 📖 [Tool Execution Callbacks](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/6_callbacks/6_3_tool_execution_callbacks) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟢📖 - Monitoring tool usage and execution

**Plugin Agents:**

* 📖 [Plugin-based Agent](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/7_plugins) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟢📖 - Extensible plugin architecture for modular agent design

**Multi-Agent Systems:**

* 📖 [Sequential Multi-Agent Pattern](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/9_multi_agent_patterns/9_1_sequential_agent) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟢📖 - Step-by-step multi-agent coordination
* 📖 [Loop Multi-Agent Pattern](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/9_multi_agent_patterns/9_2_loop_agent) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟢📖 - Iterative multi-agent workflows
* 📖 [Parallel Multi-Agent Pattern](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/ai_agent_framework_crash_course/google_adk_crash_course/9_multi_agent_patterns/9_3_parallel_agent) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟢📖 - Concurrent multi-agent execution

**Multi-Agent Applications:**

* 📖 [AI Financial Coach Agent](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/ai_financial_coach_agent) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟡📖 - Financial advisory system with specialized agent teams
* 📖 [AI Home Renovation Agent](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/ai_home_renovation_agent) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟡📖 - Home improvement planning with multi-agent coordination
* 📖 [AI SEO Audit Team](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/ai_seo_audit_team) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟡📖 - Website SEO analysis with specialized agent teams
* 📖 [Multimodal UI/UX Feedback Agent Team](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/multimodal_uiux_feedback_agent_team) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟡📖 - Design review system with multimodal capabilities
* 📖 [AI Negotiation Battle Simulator](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/ai_negotiation_battle_simulator) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟡📖 - Buyer, seller, and orchestrator agents simulate negotiations with an AG-UI frontend (ag\_ui\_adk)
* 📖 [AI Sales Intelligence Agent Team](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/ai_sales_intelligence_agent_team) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟡📖 - Sequential research agents that generate competitive battle cards and comparison charts
* 📖 [AI VC Due Diligence Agent Team](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/multi_agent_apps/agent_teams/ai_vc_due_diligence_agent_team) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟡📖 - Sequential agents producing HTML reports, infographics, and financial charts for VC due diligence

**Single-Agent Applications:**

* 📖 [Earnings Call Analyst Agent](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/single_agent_apps/earnings_call_analyst_agent) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟡📖 - Ingests and analyzes earnings calls with transcription, research, and analyst agents
* 📖 [AI Consultant Agent](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents/single_agent_apps/ai_consultant_agent) ⭐ 133,972 | 🐛 15 | 🌐 Python | 📅 2026-08-22 🟡📖 - Business consulting agent using Google Search grounding and session management

### 📝 Articles & Best Practices

* 📝 [Ralph Loop with Google ADK: AI Agents That Verify, Not Guess](https://medium.com/google-cloud/ralph-loop-with-google-adk-ai-agents-that-verify-not-guess-b41f71c0f30f) 🔴📝🔥 - Advanced guide to implementing Ralph Loop pattern for external verification-driven workflows, featuring multi-agent Dockerfile generation with Docker-based validation and iterative refinement until objective success criteria are met. Check the repo [here.](https://github.com/thomas-chong/google-adk-ralph-loop-demo) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-01-10
* 📝 [Introducing the File Search Tool in Gemini API](https://blog.google/technology/developers/file-search-gemini-api/) ⭐🟢📝💡 - Official launch of fully managed RAG system in Gemini API with free storage/embeddings, automatic chunking, vector search, and built-in citations - essential for building knowledge-grounded agents
* 📝 [More Ways to Build, Scale, and Govern AI Agents with Vertex AI Agent Builder](https://cloud.google.com/blog/products/ai-machine-learning/more-ways-to-build-and-scale-ai-agents-with-vertex-ai-agent-builder) ⭐🟡📝🏭 - Official Google Cloud announcement of ADK updates including observability, evaluation, agent identities, and production scaling features with real customer case studies
* 📝 [ADK Architecture: When to Use Sub-Agents versus Agents as Tools](https://cloud.google.com/blog/topics/developers-practitioners/where-to-use-sub-agents-versus-agents-as-tools) ⭐🟡📝 - Essential architectural guide with decision matrix for choosing between sub-agents and agent tools, featuring real-world use cases (data agents, travel planners) and best practices for multi-agent systems
* 📝 [From Zero to Multi-Agents: A Beginner's Guide to Google ADK](https://medium.com/@sokratis.kartakis/from-zero-to-multi-agents-a-beginners-guide-to-google-agent-development-kit-adk-b56e9b5f7861) 🟢📝 - Step-by-step beginner guide by Dr Sokratis Kartakis
* 📝 [Choosing the Right Deployment Path for Your Google ADK Agents](https://medium.com/google-cloud/choosing-the-right-deployment-path-for-your-google-adk-agents-86c89c251ab5) 🟡📝🏭 - Official Google Cloud guide comparing deployment strategies (Cloud Run vs Vertex AI vs GKE) for production ADK agents
* 📝 [Announcing a Datastore-Backed Session Service for the ADK](https://medium.com/google-cloud/announcing-a-new-datastore-backed-session-service-for-the-adk-d14596ae28df) 🟡📝🏭 - Google Cloud solution for persistent agent sessions in serverless environments using Cloud Datastore instead of SQLite
* 📝 [Drawing Charts in Your AI Agent Frontend with Google ADK](https://medium.com/@dconsonni/drawing-charts-in-your-ai-agent-frontend-with-google-adk-9c74a4a98931) 🟡📝🏭 - Production-ready guide to agent-generated visualizations using ADK Artifacts with Apache ECharts/vis-network, featuring FastAPI integration, session-scoped artifact management, and complete working examples for rendering charts from agent outputs
* 📝 [Build a Python AI Agent in 15 Minutes with Google ADK and MongoDB Atlas Vector Search](https://medium.com/google-cloud/build-a-python-ai-agent-in-15-minutes-with-google-adk-and-mongodb-atlas-vector-search-groceries-b6c4af017629) 🟡📝💡 - Practical tutorial building a grocery shopping agent with ADK, MongoDB Vector Search, and Gemini 2.0 Flash
* 📝 [Building Next-Gen AI Agents with Google ADK, MCP, RAG and Ollama](https://medium.com/@tam.tamanna18/building-next-gen-ai-agents-with-google-adk-mcp-rag-and-ollama-ca3c1e5002da) 🟡📝💡 - Comprehensive tutorial on building multi-agent chatbots integrating ADK + MCP + RAG + Ollama with step-by-step code and architecture diagrams
* 📝 [Google ADK + LM Studio: The Power Couple of Local Agent Development](https://medium.com/@c-damien/google-adk-lm-studio-the-power-couple-of-local-agent-development-2dd225bae36f) 🟡📝💡 - Complete guide to running ADK agents locally with LM Studio, featuring setup instructions, model configuration, and privacy-focused development without cloud dependencies
* 📝 [Building a Knowledge Base from Your Codebase using Google ADK](https://medium.com/gitconnected/building-a-knowledge-base-from-your-codebase-using-google-adk-7508e845bdc1) 🟡📝🔥 - Complete guide to building multi-agent documentation systems that automatically analyze codebases and generate structured knowledge bases using ADK's planner and writer agents
* 📝 [Optimize Your Google ADK Agent's SOP with GEPA](https://raphaelmansuy.github.io/adk_training/blog/gepa-optimization-tutorial/) 🔴📝🔥 - Advanced guide to systematic prompt optimization using GEPA (Genetic Evolutionary Prompt Augmentation) with LLM-based reflection, automated SOP evolution, and production-ready implementation achieving 0% to 100% success rates

### 🎥 Video Content

* 🎥 [Introducing Agent Development Kit (ADK)](https://www.youtube.com/watch?v=zgrOwow_uTQ) 🟢🎥 - 3-minute product overview shown at launch
* 🎥 [Getting started with ADK](https://www.youtube.com/watch?v=44C8u0CDtSo) 🟢🎥 - 12-minute "hello-world" coding session from pip install to first agent
* 🎥 [Google Launches an Agent SDK – ADK Deep Dive](https://www.youtube.com/watch?v=G9wnpfW6lZY) 🟡🎥 - Independent review comparing ADK to other agent SDKs
* 🎥 [Agent Factory: AI Agents for Data Engineering and Data Science](https://cloud.google.com/blog/topics/developers-practitioners/agent-factory-recap-ai-agents-for-data-engineering-and-data-science) 🟡🎥 - Episode recap featuring BigQuery Data Engineering Agent, Data Science Agent in Colab Enterprise, and creative ADK application with Spanner graph database
* 🎥 [ADK Tutorial Playlist](https://www.youtube.com/playlist?list=PL6tW9BrhiPTAZts0W5nQS9dbW6VMnLKab) 🟢🎥 - Comprehensive video tutorial series covering ADK fundamentals and advanced topics

***

## 🎯 Official Examples

*Google ADK samples repository - educational and demonstration purposes only*

> **⚠️ Important:** These are official Google examples for learning and demonstration purposes only. They are not intended for production use without significant modification. See the [ADK samples disclaimer](https://github.com/google/adk-samples) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25.

### 🔬 Research & Analysis

* 📚 [Academic Research Agent](https://github.com/google/adk-samples/tree/main/python/agents/academic-research) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Assists researchers in identifying recent publications and discovering emerging research areas
* 📊 [Data Science Agent](https://github.com/google/adk-samples/tree/main/python/agents/data-science) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Multi-agent system for sophisticated data analysis with NL2SQL and structured data processing
* 🏛️ [FOMC Research Agent](https://github.com/google/adk-samples/tree/main/python/agents/fomc-research) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Federal Reserve meeting analysis and market event insights
* 🔍 [LLM Auditor](https://github.com/google/adk-samples/tree/main/python/agents/llm-auditor) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟢📚 - Chatbot response verification and content auditing with Google Search integration
* 📺 [YouTube Analyst](https://github.com/google/adk-samples/tree/main/python/agents/youtube-analyst) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - YouTube channel performance and audience engagement analysis using YouTube Data API with interactive Plotly visualizations via a dedicated visualization sub-agent
* 🧠 [Economic Research Agent](https://github.com/google/adk-samples/tree/main/python/agents/economic-research-agent) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Multi-agent regional economic analysis and site selection grounded in live public APIs (FRED, BLS, Census, HUD, EIA) with an auditor judge for zero-hallucination verification (ADK 2.0)

### 💼 Business & Customer Service

* 🛡️ [Auto Insurance Agent](https://github.com/google/adk-samples/tree/main/python/agents/auto-insurance-agent) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Auto insurance management for members, claims, rewards and roadside assistance with Apigee integration
* 🎯 [Brand Search Optimization](https://github.com/google/adk-samples/tree/main/python/agents/brand-search-optimization) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - E-commerce product data enrichment analyzing top search results with BigQuery integration
* 🎨 [Brand Aligner Agent](https://github.com/google/adk-samples/tree/main/python/agents/brand-aligner) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - End-to-end visual asset (images/videos) evaluation against brand guidelines using Gecko on Vertex AI Eval Service, with sequential multi-agent orchestration and GCS artifact storage
* 🏠 [Customer Service Agent](https://github.com/google/adk-samples/tree/main/python/agents/customer-service) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟢📚 - Home & garden customer service with product selection, order management, and live streaming support
* 💰 [Financial Advisor](https://github.com/google/adk-samples/tree/main/python/agents/financial-advisor) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Educational content assistant for financial advisors covering finance and investment topics
* 🚨 [Incident Management](https://github.com/google/adk-samples/tree/main/python/agents/incident-management) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟢📚 - ServiceNow integration with Application Integration Connectors and dynamic identity propagation
* 📦 [Order Processing](https://github.com/google/adk-samples/tree/main/python/agents/order-processing) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟢📚 - Automated order workflows with human-in-the-loop using Application Integration Connectors
* 🪪 [Global KYC / Compliance Agent](https://github.com/google/adk-samples/tree/main/python/agents/global-kyc-agent) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Conversational agent handling KYC and compliance queries for both UK and US companies
* 🧾 [Invoice Processing](https://github.com/google/adk-samples/tree/main/python/agents/invoice-processing) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Document-processing agent combining an end-to-end inference pipeline with an interactive learning loop for continuous improvement
* 🏥 [Health Claim Adjudication Agent](https://github.com/google/adk-samples/tree/main/python/agents/claim-adjudication-agent) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Multi-agent cashless health-insurance claim workflow: GCS document discovery, admissibility checks, financial adjudication, and report synthesis
* 🔗 [Supply Chain Agent](https://github.com/google/adk-samples/tree/main/python/agents/supply-chain) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Multi-agent system analyzing real-time market dynamics and weather conditions for supply-chain decisions
* 💸 [Ambient Expense Agent](https://github.com/google/adk-samples/tree/main/python/agents/ambient-expense-agent) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Ambient agent processing expense reports via Pub/Sub through an ADK 2.0 graph workflow — auto-approving low-value items and routing high-value ones through LLM risk review
* 🏦 [Small Business Loan Agent](https://github.com/google/adk-samples/tree/main/python/agents/small-business-loan-agent) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Multi-agent loan processing with sequential orchestration, human-in-the-loop approval, LLM-as-Judge validation, and Firestore-backed repair & resume

### 🛍️ E-commerce & Marketing

* 🛒 [Personalized Shopping](https://github.com/google/adk-samples/tree/main/python/agents/personalized-shopping) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - AI-driven product recommendations and shopping assistance
* 📱 [Marketing Agency](https://github.com/google/adk-samples/tree/main/python/agents/marketing-agency) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Website and product launch automation with domain optimization, content generation, and brand asset design
* ✈️ [Travel Concierge](https://github.com/google/adk-samples/tree/main/python/agents/travel-concierge) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Multi-agent travel planning and digital task assistance with dynamic instructions
* 📈 [Google Trends Agent](https://github.com/google/adk-samples/tree/main/python/agents/google-trends-agent) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - BigQuery-powered trending search terms analysis by region and time period
* 📺 [Product Catalog Ad Generation](https://github.com/google/adk-samples/tree/main/python/agents/product-catalog-ad-generation) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Automated advertising content generation from product catalogs
* 🛍️ [GenMedia for Commerce](https://github.com/google/adk-samples/tree/main/python/agents/genmedia-for-commerce) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Full-stack agent for commerce media generation including virtual try-on (image & video)
* 🗺️ [Grounded Travel Agent (Maps MCP)](https://github.com/google/adk-samples/tree/main/python/agents/travel-planner-google-maps-mcp) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Travel planner grounded in the Google Maps Platform MCP server for real-time places, weather, and routes, with a modular SKILL.md architecture
* 📑 [Brand-Aligned Presentations](https://github.com/google/adk-samples/tree/main/python/agents/brand-aligned-presentations) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Multi-agent system on Vertex AI that generates presentations aligned to brand guidelines

### 🔧 Development & Technical

* 🐛 [Software Bug Assistant](https://github.com/google/adk-samples/tree/main/python/agents/software-bug-assistant) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Bug resolution assistant with RAG, MCP, and external knowledge sources (GitHub, StackOverflow)
* 🤖 [Machine Learning Engineering](https://github.com/google/adk-samples/tree/main/python/agents/machine-learning-engineering) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Autonomous ML model building and training for state-of-the-art performance on diverse ML tasks
* 🧩 [RAG Systems](https://github.com/google/adk-samples/tree/main/python/agents/RAG) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Vertex AI RAG Engine powered document Q\&A with citations
* 📊 [Data Engineering Agent](https://github.com/google/adk-samples/tree/main/python/agents/data-engineering) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - BigQuery and Dataform pipeline builder for ELT workflows and analytics engineering
* 🔧 [Plumber Data Engineering Assistant](https://github.com/google/adk-samples/tree/main/python/agents/plumber-data-engineering-assistant) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Big data pipeline creator for Apache Spark, Apache Beam, and dBT on GCP
* 🧪 [SWE Benchmark Agent](https://github.com/google/adk-samples/tree/main/python/agents/swe-benchmark-agent) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Software engineering benchmark testing and evaluation agent
* 🧪 [Tau2 Benchmark Agent](https://github.com/google/adk-samples/tree/main/python/agents/tau2-benchmark-agent) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Tau2 benchmark agent for advanced evaluation tasks
* 🎓 [Agent Skills Tutorial](https://github.com/google/adk-samples/tree/main/python/agents/agent-skills-tutorial) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟢📚 - Demonstrates four ADK skill patterns: inline, file-based, external, and meta
* 🧠 [Memory Bank Agent](https://github.com/google/adk-samples/tree/main/python/agents/memory-bank) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - ADK agent with Vertex AI Memory Bank integration that remembers user preferences and facts across sessions, deployable to Agent Runtime or Cloud Run
* 🧩 [Multi-format Hybrid RAG](https://github.com/google/adk-samples/tree/main/python/agents/multiformat-hybrid-rag) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Production RAG on GCP with contextual chunking, Vector Search 2.0 hybrid search, a REST API, and an MCP server from a single Cloud Run service
* 📊 [Agent Observability (BigQuery)](https://github.com/google/adk-samples/tree/main/python/agents/agent-observability-bq) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - BigQuery-connected agent demonstrating the BigQueryAgentAnalyticsPlugin for centralized logging, debugging, and auditing
* 🛡️ [Cyber Guardian Agent](https://github.com/google/adk-samples/tree/main/python/agents/cyber-guardian-agent) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Hierarchical multi-agent security workflow with conditional routing and four specialized sub-agents
* 🔑 [Agent Runtime + OAuth (Drive Reader)](https://github.com/google/adk-samples/tree/main/python/agents/adk-ae-oauth) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Production ADK agent on Agent Runtime with OAuth 2.0 to read Google Drive files on behalf of authenticated users, locally via ADK Web UI and in production via Gemini Enterprise
* 🌀 [Airflow Version Upgrade Agent](https://github.com/google/adk-samples/tree/main/python/agents/airflow_version_upgrade_agent) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Two-stage agentic system that migrates Apache Airflow DAGs across versions using Gemini, Vertex AI Search RAG, and a BigQuery knowledge base
* 📄 [High-Volume Document Analyzer](https://github.com/google/adk-samples/tree/main/python/agents/high-volume-document-analyzer) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Reads, summarizes, and answers questions over massive collections of unstructured documents in a chunked, iterative manner with Vertex AI and Gemini
* 📋 [SDLC: Task Planner](https://github.com/google/adk-samples/tree/main/python/agents/sdlc-task-planner) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Software Development Life Cycle agent that breaks work into actionable tasks (part of the SDLC agent workflow)
* 🏛️ [SDLC: Technical Designer](https://github.com/google/adk-samples/tree/main/python/agents/sdlc-technical-designer) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - SDLC agent that produces technical designs from requirements (part of the SDLC agent workflow)
* 📝 [SDLC: User Story Refiner](https://github.com/google/adk-samples/tree/main/python/agents/sdlc-user-story-refiner) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - SDLC agent that refines and structures user stories (part of the SDLC agent workflow)
* 🔀 [Workflow: Concurrent Research Writer](https://github.com/google/adk-samples/tree/main/python/agents/workflow-concurrent_research_writer) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Nested WorkflowAgents that research a topic, generate a blog post, and publish it to the most appropriate platform
* ⏰ [Workflow: Morning Email Debrief](https://github.com/google/adk-samples/tree/main/python/agents/workflow-morning_email_debrief) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Timed-trigger WorkflowAgent that retrieves and summarizes emails on a daily schedule
* 🙋 [Workflow: HITL Concierge](https://github.com/google/adk-samples/tree/main/python/agents/workflows-HITL_concierge) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Human-in-the-loop WorkflowAgent that pauses for user input while building an itinerary
* ➡️ [Workflow: Sequential](https://github.com/google/adk-samples/tree/main/python/agents/workflows-sequential) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟢📚 - Minimal sequential WorkflowAgent demonstrating a linear, non-branching execution path

### 🎨 Specialized Applications

* 🎨 [Image Scoring Agent](https://github.com/google/adk-samples/tree/main/python/agents/image-scoring) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟢📚 - Image generation and policy compliance scoring with Imagen integration
* 🐪 [CAMEL Integration](https://github.com/google/adk-samples/tree/main/python/agents/camel) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Multi-agent communication framework integration with CAMEL
* 🔥 [Deep Search](https://github.com/google/adk-samples/tree/main/python/agents/deep-search) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚⭐ - **Complete fullstack research agent** (formerly Gemini Fullstack) with React frontend, FastAPI backend, and Human-in-the-Loop workflows
* 🏥 [Medical Pre-Authorization](https://github.com/google/adk-samples/tree/main/python/agents/medical-pre-authorization) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Healthcare pre-authorization automation analyzing medical records and policies for coverage determination
* 🎬 [Short Movie Agents](https://github.com/google/adk-samples/tree/main/python/agents/short-movie-agents) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - End-to-end video construction based on user intent with multi-agent coordination
* 🎙️ [Podcast Transcript Agent](https://github.com/google/adk-samples/tree/main/python/agents/podcast_transcript_agent) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Podcast transcription and analysis agent
* ✍️ [Blog Writer](https://github.com/google/adk-samples/tree/main/python/agents/blog-writer) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Automated blog content generation and writing assistant
* 📖 [Story Teller](https://github.com/google/adk-samples/tree/main/python/agents/story_teller) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Multi-agent collaborative story writer with a PromptEnhancer, Parallel Writers (creative + focused temperature), Critique Agent, and final Editor — showcases Sequential, Parallel, and Loop agent composition
* 🛡️ [Safety Guardrail Plugins](https://github.com/google/adk-samples/tree/main/python/agents/safety-plugins) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Security filters using Gemini-as-judge and Model Armor for jailbreak protection
* 💳 [Antom Payment](https://github.com/google/adk-samples/tree/main/python/agents/antom-payment) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Ant International payment and refund integration via MCP tools
* 💬 [Realtime Conversational Agent](https://github.com/google/adk-samples/tree/main/python/agents/realtime-conversational-agent) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Live streaming conversational agent with real-time interaction capabilities
* ⚡ [ADK Bidi-streaming Demo](https://github.com/google/adk-samples/tree/main/python/agents/bidi-demo) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Real-time bidirectional streaming demo with WebSocket communication, multimodal support (audio/video/text), and concurrent task handling
* 🛡️ [AI Security Agent](https://github.com/google/adk-samples/tree/main/python/agents/ai-security-agent) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - LLM red team agent for comprehensive security testing and vulnerability assessment
* 💰 [Currency Agent](https://github.com/google/adk-samples/tree/main/python/agents/currency-agent) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Currency exchange rate lookups and conversions with A2A and MCP integration
* 🏗️ [Hierarchical Workflow Automation](https://github.com/google/adk-samples/tree/main/python/agents/hierarchical-workflow-automation) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Structured multi-system transaction orchestration with multi-agent architecture
* 🔀 [Parallel Task Decomposition Execution](https://github.com/google/adk-samples/tree/main/python/agents/parallel_task_decomposition_execution) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - Design pattern for parallel task decomposition and execution with ADK agents
* 🔐 [Policy-as-Code Agent](https://github.com/google/adk-samples/tree/main/python/agents/policy-as-code) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Data governance agent implementing policy-as-code patterns for compliance
* 🏪 [Retail AI Location Strategy](https://github.com/google/adk-samples/tree/main/python/agents/retail-ai-location-strategy) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Retail location optimization and market analysis with multi-agent system
* 🌍 [Earth Engine Geospatial Agent](https://github.com/google/adk-samples/tree/main/python/agents/earth-engine-geospatial) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Geospatial chatbot using Google Earth Engine and the AlphaEarth Satellite Embeddings dataset to compute land-change area for user-supplied GeoJSON geometries
* 🍽️ [Gemma Food Tour Guide](https://github.com/google/adk-samples/tree/main/python/agents/gemma-food-tour-guide) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Personalized culinary tour builder using Gemma 4 31B and the Google Maps MCP server
* 🎉 [Fun Facts Agent](https://github.com/google/adk-samples/tree/main/python/agents/fun-facts) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟢📚 - Minimal starter agent using Gemini and Google Search grounding to serve fun facts — a gentle intro to ADK tools, Agent Runtime, and Gemini Enterprise
* 🩺 [NexShift](https://github.com/google/adk-samples/tree/main/python/agents/nexshift-agent) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - AI nurse rostering agent that generates, validates, and manages optimal schedules, balancing regulatory constraints and fairness via OR-Tools constraint programming
* 🏥 [Nurse Handover Agent](https://github.com/google/adk-samples/tree/main/python/agents/nurse-handover) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Generates concise, structured shift-handover summaries from raw medical logs in the standardized ISBAR format
* 🎨 [On-Brand GenMedia Agent](https://github.com/google/adk-samples/tree/main/python/agents/on-brand-genmedia) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Generates and evaluates images against brand guidelines, iteratively improving them until policy and quality requirements are met

### 🌐 Other Language Samples

*Official ADK samples in TypeScript, Java, and Go*

**TypeScript**

* 🏠 [Customer Service Agent (TypeScript)](https://github.com/google/adk-samples/tree/main/typescript/agents/customer_service) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟢📚 - TypeScript port of the customer service agent for home & garden retail with product selection and order management

**Java**

* 🐛 [Software Bug Assistant (Java)](https://github.com/google/adk-samples/tree/main/java/agents/software-bug-assistant) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Java port of the bug resolution assistant using ADK Java with RAG and external knowledge integration
* 📈 [Time Series Forecasting (Java)](https://github.com/google/adk-samples/tree/main/java/agents/time-series-forecasting) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🔴📚 - ADK Java agent using MCP Toolbox + BigQuery `AI.FORECAST` for natural language time series forecasting over public datasets, deployable to Cloud Run

**Go**

* 🔍 [LLM Auditor (Go)](https://github.com/google/adk-samples/tree/main/go/agents/llm-auditor) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟢📚 - Go port of the LLM response auditor for chatbot verification and content auditing
* ⛵ [Boat Agent (Go)](https://github.com/google/adk-samples/tree/main/go/agents/boat-agent) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟢📚 - Go ADK sample agent for sailing/boating assistance
* 📋 [Naval List (Go)](https://github.com/google/adk-samples/tree/main/go/agents/navallist) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟢📚 - Go ADK sample demonstrating list management with a naval theme
* 🔭 [Sail Researcher (Go)](https://github.com/google/adk-samples/tree/main/go/agents/sail-researcher) ⭐ 10,231 | 🐛 74 | 🌐 Python | 📅 2026-08-25 🟡📚 - Go ADK research agent for sailing-domain information retrieval

***

## 🚀 Getting Started

### Quick Start with Google ADK

```bash
# Install ADK framework
pip install google-adk

# Create your first agent
adk create my-agent
cd my-agent

# Run with web interface
adk web
```

### Using This Repository

This is a **hybrid awesome list** - combining curated resources with featured implementations:

* **Browse & Learn**: Explore categorized projects for inspiration and best practices
* **Clone & Build**: Featured projects in `/my-adk-agents/` are production-ready starting points
* **Contribute**: Add your own projects or improve existing ones via [CONTRIBUTING.md](./CONTRIBUTING.md)

### Essential ADK Commands

```bash
adk web         # Launch web UI (recommended)
adk run         # Interactive CLI
adk create      # Generate new agent template
adk deploy      # Deploy to cloud platforms
```

### Resources

* 💬 [Community Discussions](https://github.com/google/adk-python/discussions) ⭐ 21,269 | 🐛 544 | 🌐 Python | 📅 2026-08-25
* 📖 [Official ADK Documentation](https://google.github.io/adk-docs/)
* 🛠️ [Third-Party Tools for ADK](https://google.github.io/adk-docs/tools/third-party/) - Official catalog of integrated third-party tools including Browserbase, Exa, Firecrawl, GitHub, Hugging Face, Notion, Tavily, and more
* 🎓 [Learning Path](#-learning-resources)

***

## 🤝 Contributing

We welcome high-quality contributions that advance the ADK ecosystem. See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

**Quality Standards**: Production-ready code, comprehensive documentation, and adherence to ADK best practices.

## 📞 Support

* 🐛 **Issues**: Report bugs or request features via GitHub Issues
* 💡 **Discussions**: Join the community for questions and ideas
* 📧 **Maintainer**: Contact repository owner for collaboration opportunities

***

## 🙏 Acknowledgements

**Core Contributors:**

* Google ADK Team - Framework development
* Brandon Hancock - Educational content and tutorials
* Community Contributors - Featured projects and improvements

**Related Lists:**

* [tsubasakong/awesome-google-adk](https://github.com/tsubasakong/awesome-google-adk) ⭐ 78 | 🐛 2 | 📅 2025-05-05 - Another community-curated list of Google ADK resources

## ⭐ Impact

This repository is trusted by a growing community of developers building production AI agents. Help us grow:

* ⭐ **Star** if this helps your development
* 🔗 **Share** with your network
* 🤝 **Contribute** your expertise

## 💚 Sponsors

* [MeterCall](https://metercall.ai/?v=a\&src=github) — One metered API gateway. 21M+ endpoints (payments, SMS, AI, CRMs, gov data). Free tier; pay per call.

***

<div align="center">
<strong>Building the future of AI agents, one contribution at a time.</strong><br>
<em>Powered by Google ADK • Curated by the community</em>
</div>

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._
