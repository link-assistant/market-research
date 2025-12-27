# Agentic CLI Tools for Coding: A Comprehensive Guide

This guide provides a clear and concise comparison of agentic CLI tools for coding, tailored to help you choose the best tool for your needs. These tools allow you to write, edit, and manage code directly from the terminal using AI-powered assistance. Below, we evaluate leading tools—Claude Code, Gemini CLI, OpenAI Codex CLI, Cline, Aider, Goose, OpenCode, Warp, Kiro CLI, Amazon Q Developer CLI, Qwen Code, Droid, Roo Code, and OpenHands—focusing on their support for advanced AI models, pricing, and key features. The analysis prioritizes fair pricing and open-source options where possible, ensuring you have the information needed to make an informed decision.

### Key Points (Updated December 2025)
- **Claude Code** is Anthropic's terminal-based agentic coding tool with 49K GitHub stars, excelling in complex multi-file projects with deep codebase understanding, available via Pro ($20/month) and Max ($100-$200/month) plans.
- **Gemini CLI** from Google is the most starred CLI tool (88.5K stars) with an industry-leading free tier (1,000 requests/day) and access to Gemini 3 Flash with 1M token context.
- **OpenAI Codex CLI** is open-source (54.7K stars) with GPT-5.2-Codex as the default model, featuring new agent skills and GitHub/Linear integrations.
- **Cline** is GitHub's fastest-growing AI open source project (50K+ stars), offering Plan/Act modes and IDE integration.
- **Aider** is the pioneer open-source AI pair programmer with Git integration and support for virtually any LLM.
- **Goose** from Block (24.8K stars) is now part of the Linux Foundation's Agentic AI Foundation, offering fully local execution with any LLM.
- **OpenCode** (41K stars) is a truly open-source alternative to Claude Code with multi-session support and LSP-enabled architecture.
- **Warp** is an AI-native terminal with new Build plan ($20/month) and bring-your-own-key support.
- **Kiro CLI** from AWS reached general availability in November 2025 with spec-driven development and team features.
- **Amazon Q Developer CLI** integrates well with AWS, offering a free tier and a $19/month Pro plan.
- **Qwen Code** is Alibaba's open-source CLI optimized for Qwen3-Coder with 2,000 free requests/day via OAuth.
- **Droid by Factory** is #1 on Terminal-Bench with 58.75% score, offering multi-model orchestration.
- **Roo Code** (21.4K stars) provides multiple AI modes (Code, Architect, Debug, Ask) in VS Code.
- **OpenHands** is an open-source platform for autonomous AI software development with SDK, CLI, and GUI interfaces.

### Why Choose an Agentic CLI Tool?
Agentic CLI tools are designed for developers who prefer working in the terminal, offering AI-driven assistance to generate code, fix bugs, and automate tasks. These tools understand your codebase, execute commands, and integrate with version control, making them ideal for efficient, hands-on coding workflows. Unlike passive autocomplete tools, an agentic CLI actively plans and executes multi-step tasks: reading your repository, generating or editing files, running tests, resolving Git history, and orchestrating shell commands through natural-language prompts.

### Top Tools at a Glance
- **Claude Code**: Ideal for complex, multi-file projects requiring deep codebase understanding. Best terminal UX for rapid prototyping.
- **Gemini CLI**: Excellent for developers wanting generous free usage with massive context window (1M tokens) and Google Search integration. Best for large-context refactors.
- **OpenAI Codex CLI**: Great for cost-conscious users with GPT-5.2-Codex, agent skills, and deep GitHub/Linear integration.
- **Cline**: Suited for autonomous coding with IDE integration, Plan/Act modes, and strong community (fastest-growing on GitHub).
- **Aider**: Perfect for open-source enthusiasts who value Git integration and model flexibility.
- **Goose**: Ideal for developers wanting local execution with extensible agent capabilities and enterprise privacy.
- **OpenCode**: Best open-source alternative to Claude Code with multi-session support.
- **Warp**: Best for developers wanting an AI-native terminal experience with BYOK support.
- **Kiro CLI**: Great for teams using AWS services with spec-driven development and structured workflows.
- **Amazon Q Developer CLI**: Optimal for AWS users needing cloud-integrated tools.
- **Qwen Code**: Excellent for users wanting a free, open-source CLI with Qwen3-Coder's 256K context.
- **Droid**: Best for enterprise users needing top benchmark performance and multi-model orchestration.

### How to Choose
- **If you're working on large projects**: Claude Code's robust features make it a strong choice.
- **If you want maximum free usage**: Gemini CLI offers 1,000 requests/day free with 1M token context.
- **If you need deep GitHub integration**: OpenAI Codex CLI with @codex mentions and agent skills.
- **If budget is a concern**: Gemini CLI, OpenAI Codex CLI, Aider, Cline, Goose, OpenCode, or Qwen Code offer free usage with API costs.
- **If you prefer local execution**: Goose runs entirely locally with any LLM.
- **If you want an AI-native terminal**: Warp provides a reimagined terminal experience with built-in agents.
- **If you use AWS**: Amazon Q Developer CLI or Kiro CLI provide seamless cloud integration.
- **If you need top benchmark performance**: Droid by Factory leads on Terminal-Bench.

---

# Comprehensive Analysis of Agentic CLI Tools (Updated December 2025)

This comprehensive analysis evaluates agentic CLI tools for coding, focusing on the most popular and capable tools available as of December 2025. These tools enable developers to generate, edit, and refactor code directly in the terminal using advanced AI models. The report assesses their support for the latest AI models, pricing, usage limits, and suitability for autonomous coding tasks. It emphasizes fair pricing and open-source options, providing a detailed guide for developers.

## Background and Context
Agentic CLI tools are conversational, AI-driven tools that operate in the terminal, allowing developers to perform coding tasks such as code generation, debugging, and multi-file refactoring without leaving the command line. These tools leverage advanced AI models to understand codebases, execute commands, and integrate with version control systems like Git. The analysis prioritizes fair pricing and open-source options, ensuring alignment with the latest data as of December 2025.

### Model Availability Summary (December 2025)
- **GPT-5 Series**: GPT-5 released August 7, 2025; GPT-5.1 released November 2025; GPT-5.2-Codex released December 2025. [Source](https://openai.com/index/introducing-gpt-5-2-codex/)
- **Claude 4 Series**: Claude Opus 4/Sonnet 4 released May 22, 2025; Opus 4.1 released August 2025; Sonnet 4.5 released September 2025; Opus 4.5 released November 24, 2025. [Source](https://www.anthropic.com/news/claude-opus-4-5)
- **Gemini 3 Series**: Gemini 3 Flash available in Gemini CLI since December 17, 2025, with 78% SWE-bench score. [Source](https://developers.googleblog.com/gemini-3-flash-is-now-available-in-gemini-cli/)
- **Grok 4**: Released July 9, 2025 via xAI API. [Source](https://x.ai/news/grok-4/)
- **Qwen3-Coder**: Alibaba's 480B parameter open-source coding model with 256K native context. [Source](https://qwenlm.github.io/blog/qwen3-coder/)

## Methodology
The research involved extensive web searches to verify the features, supported models, pricing, and usage limits of each agentic CLI tool. Official documentation, blogs, GitHub repositories, and community discussions were cross-referenced to ensure accuracy. GitHub star counts and recent releases were verified directly from source repositories.

## Detailed Analysis of Agentic CLI Tools

### Claude Code
- **Description**: Claude Code is Anthropic's terminal-based agentic coding tool with 49K GitHub stars, designed for complex software engineering tasks like code generation, debugging, and multi-file refactoring. It understands your entire codebase and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows. [Source](https://github.com/anthropics/claude-code)
- **Agent Mode**: Maps entire codebases for deep understanding, executes tests, and integrates with GitHub Actions for automated workflows.
- **AI Model Support**: Directly supports Claude Sonnet 4, Sonnet 4.5, Opus 4, Opus 4.5, and older Claude models. Supports other providers via API configuration.
- **Key Features**:
  - Automatic codebase context gathering for precise edits.
  - Multi-file edits and test execution with high accuracy.
  - CLAUDE.md files for project-specific instructions.
  - WebSearch, WebFetch, and MultiEdit tools for enhanced functionality.
  - LSP (Language Server Protocol) tool for code intelligence (v2.0.74+).
  - Available in terminal, VS Code, JetBrains, and Slack.
- **Pricing**: Pro plan at $20/month (light usage, shared limits with Claude web/desktop); Max plans at $100/month (5x more than Pro) or $200/month (20x more than Pro) with access to Opus 4.5; API pricing at $3/$15 per million tokens (input/output) for Sonnet 4.5, $5/$25 for Opus 4.5 (67% reduction from Opus 4.1). [Source](https://www.anthropic.com/pricing)
- **Usage Limits**: Usage limits reset every five hours and are shared across Claude (web, desktop, mobile) and Claude Code. Weekly rate limits added August 2025 for heavy users.
- **Why It Fits**: Excels in complex, multi-file projects with deep codebase comprehension. Best for rapid prototypes and productive terminal UX.

### Gemini CLI
- **Description**: Gemini CLI is Google's open-source (Apache 2.0) AI agent with 88.5K GitHub stars that brings the power of Gemini directly into your terminal. It uses a Reason and Act (ReAct) loop to complete complex use cases like fixing bugs, creating new features, and improving test coverage. [Source](https://github.com/google-gemini/gemini-cli)
- **Agent Mode**: Uses ReAct loop with built-in tools and MCP server support to complete complex tasks autonomously.
- **AI Model Support**: Uses Gemini 2.5 Pro by default; Gemini 3 Flash available since December 17, 2025 (78% SWE-bench Verified score). Gemini 3 Pro available for AI Ultra subscribers. [Source](https://developers.googleblog.com/gemini-3-flash-is-now-available-in-gemini-cli/)
- **Key Features**:
  - Industry-leading free tier: 60 requests/minute, 1,000 requests/day.
  - 1 million token context window for large codebase analysis.
  - Built-in tools: Google Search grounding, file operations, shell commands, web fetching.
  - Model Context Protocol (MCP) support for custom integrations.
  - Multimodal: supports PDFs, images, and sketches.
  - GitHub Actions integration for CI/CD workflows.
  - Fully open-source (Apache 2.0).
- **Pricing**: Free tier with 1,000 requests/day. Google AI Pro at $19.99/month (5x limits). Google AI Ultra for intensive, multi-agent workflows (20x limits). Pay-as-you-go via Gemini API. Gemini 3 Flash at $0.50/$3 per million input/output tokens. [Source](https://geminicli.com/docs/quota-and-pricing/)
- **Usage Limits**: Free tier: 60 requests/minute, 1,000 requests/day. Paid tiers offer higher limits.
- **Why It Fits**: Best for large-context refactors with generous free tier and Google Search integration.

### OpenAI Codex CLI
- **Description**: An open-source (Apache 2.0) command-line tool from OpenAI with 54.7K GitHub stars that brings reasoning models to the terminal, enabling local code reading, modification, and execution. Latest version 0.78.0. [Source](https://github.com/openai/codex)
- **Agent Mode**: Offers Suggest, Auto Edit, and Full Auto modes for task automation, including code generation, bug fixing, and test execution with sandboxed execution and approval workflows.
- **AI Model Support**: Default model is GPT-5.2-Codex (December 2025), the most advanced agentic coding model. Also supports GPT-5, GPT-5.1, o3, o4-mini. [Source](https://openai.com/index/introducing-gpt-5-2-codex/)
- **Key Features**:
  - Agent Skills: reusable bundles of instructions ($skill-installer, $create-plan, etc.).
  - Slash commands (/review, /plan) for specialized workflows.
  - Multimodal inputs (text, screenshots, diagrams).
  - AGENTS.md files for codebase navigation and standards.
  - Sandboxed execution with approval workflows.
  - GitHub integration: @codex mentions in PRs and Issues.
  - Linear integration for task management.
  - Model Context Protocol (MCP) support.
  - Open-source (Apache 2.0 license) for customization.
- **Pricing**: Free to use; pay-as-you-go API pricing. [Source](https://openai.com/api/pricing/)
- **Usage Limits**: API usage-based.
- **Why It Fits**: Best for developers needing deep GitHub/Linear integration with GPT-5.2-Codex capabilities.

### Cline
- **Description**: An open-source AI coding assistant with 50K+ GitHub stars, recognized as GitHub's fastest-growing AI open source project (4,704% YoY growth). Acts as an autonomous coding agent with Plan/Act modes. [Source](https://cline.bot/)
- **Agent Mode**: Supports planning and executing complex tasks, including multi-file edits and command execution with human-in-the-loop approval.
- **AI Model Support**: Model-agnostic, supporting Claude Sonnet 4/4.5, Opus 4/4.5, GPT-5, o3, o4-mini, Grok 4, and any API-compatible model. [Source](https://github.com/cline/cline)
- **Key Features**:
  - Deep context understanding for accurate code changes.
  - Permission-based file edits and command execution.
  - Model Context Protocol (MCP) support for tool integration.
  - Plan/Act modes for structured task execution.
  - Browser capabilities for debugging and UI fixes.
  - CLI extension (Beta) for scripts, cron jobs, and CI pipelines.
  - Available for VS Code, JetBrains, and Cursor.
  - Enterprise features: SSO, audit trails, private networking, self-hosted deployments.
- **Pricing**: Free to use; pay-as-you-go API pricing for chosen model. [Source](https://cline.bot/)
- **Usage Limits**: API usage-based.
- **Why It Fits**: Fastest-growing community with Plan/Act modes and enterprise-ready features.

### Aider
- **Description**: An open-source CLI tool for AI pair programming in your terminal, supporting conversational prompting, multi-file edits, and Git-integrated workflows. One of the first open-source AI coding assistants. [Source](https://aider.chat/)
- **Agent Mode**: Features inline editing, multi-turn refinement, and task automation for collaborative coding. Architect/Editor mode for SOTA benchmark results.
- **AI Model Support**: Works best with Claude 4.1 Opus, DeepSeek V3, OpenAI GPT-5 and -4.1. Supports Grok-4, Gemini models. Can connect to almost any LLM, including local models. [Source](https://github.com/Aider-AI/aider)
- **Key Features**:
  - Multi-file and multi-language support (Python, JavaScript, C++, etc.).
  - Git-based code tracking with automatic commits and sensible messages.
  - Conversational prompting for iterative refinements.
  - Repository map for better context understanding.
  - Image and web page support for visual context.
  - Voice input support for hands-free coding.
  - Automatic lint and test execution after changes.
  - Shell completions for bash, zsh, etc.
  - Optional web UI and VS Code extensions.
- **Pricing**: Free to use; pay-as-you-go API pricing for chosen model. [Source](https://aider.chat/)
- **Usage Limits**: API usage-based.
- **Why It Fits**: Best value CLI tool with optimized context fetching and pioneering Git integration.

### Goose
- **Description**: An open-source (Apache 2.0), extensible AI agent from Block with 24.8K GitHub stars, now part of the Linux Foundation's Agentic AI Foundation (AAIF). Goes beyond code suggestions—can install, execute, edit, and test with any LLM. Runs entirely locally. [Source](https://github.com/block/goose)
- **Agent Mode**: Full autonomous agent capable of building entire projects from scratch, writing and executing code, debugging failures, orchestrating workflows, and interacting with external APIs.
- **AI Model Support**: Works with any language model that has tool calling capabilities, including DeepSeek, OpenAI models (GPT-5), Anthropic models (Claude Opus 4, Sonnet 4), Google models, and XAI models. [Source](https://block.github.io/goose/)
- **Key Features**:
  - Fully local execution for privacy and control.
  - Modular design with Model Context Protocol (MCP) support.
  - Desktop app and CLI interfaces available.
  - Extensible with custom tools and integrations (Jira, GitHub, etc.).
  - Transparent operation—see exactly what the agent is doing.
  - Permission modes: Autonomous or Manual Approval.
  - Agent Client Protocol (ACP) support for editor integration.
  - Slash commands: /prompts, /prompt, /compact, /clear (December 2025).
  - OpenRouter & XAI streaming support.
- **Pricing**: Free and open-source (Apache 2.0). API costs depend on chosen model provider. [Source](https://github.com/block/goose)
- **Usage Limits**: API usage-based depending on chosen model.
- **Why It Fits**: Ideal for developers wanting local execution, privacy, and extensible agent capabilities. Part of Linux Foundation AAIF.

### OpenCode
- **Description**: An open-source AI coding agent with 41K GitHub stars, truly open-source alternative to Claude Code. Built by neovim users and creators of terminal.shop. [Source](https://github.com/sst/opencode)
- **Agent Mode**: Full agentic capabilities for multi-file editing, refactoring, and complex development tasks.
- **AI Model Support**: Supports any model via OpenAI, Anthropic, or local models like Ollama. [Source](https://opencode.ai/)
- **Key Features**:
  - Multi-session support: multiple AI agents on same project without conflict.
  - LSP-enabled architecture: auto-detects best tools for each language.
  - Shareable sessions for debugging and collaboration.
  - Deep project context: scans project files for dependencies.
  - GitHub integration: /opencode or /oc mentions in comments.
  - Desktop app and CLI interfaces.
  - Haskell LSP support (December 2025).
- **Pricing**: Free and open-source. API costs depend on chosen model provider. [Source](https://opencode.ai/)
- **Usage Limits**: API usage-based.
- **Why It Fits**: Best open-source alternative to Claude Code with unique multi-session and LSP features.

### Warp
- **Description**: Warp is an agentic development environment—a reimagined terminal with AI agents built-in. Features Agent Mode, Warp Pair, and Dispatch Mode for different levels of autonomy. [Source](https://www.warp.dev/)
- **Agent Mode**: Agent Mode tackles multi-step tasks by executing commands with permission. Dispatch Mode operates fully autonomously. Warp Pair enables collaborative AI coding.
- **AI Model Support**: Access to Claude 3.5 Sonnet (default), Claude 3.5 Haiku, and GPT-4o. Enterprise controls for custom models. BYOK support for OpenAI, Anthropic, or Google models on Build plan. [Source](https://www.warp.dev/warp-ai)
- **Key Features**:
  - Native terminal with AI agents built-in.
  - Agent steering with code review and file editing support.
  - WARP.md files (compatible with AGENTS.md, CLAUDE.md, cursor rules).
  - MCP support and codebase embeddings.
  - Privacy: No data used for model training, Zero Data Retention policies.
  - Available on macOS, Linux, and Windows.
  - Works with Zsh, Bash, fish, PowerShell, WSL, Git Bash.
- **Pricing**: Free tier with 75-150 credits/month. Build plan at $20/month with 1,500 credits and BYOK support. Business at $50/month with SSO and SOC 2 compliance. [Source](https://www.warp.dev/pricing)
- **Usage Limits**: Free: 75-150 credits/month. Build: 1,500 credits/month with rollover.
- **Why It Fits**: Best for developers wanting an AI-native terminal experience with BYOK flexibility.

### Kiro CLI
- **Description**: Kiro CLI from AWS brings AI-powered development tools directly to the terminal. Generally available since November 2025 with 250,000+ developers. [Source](https://kiro.dev/cli/)
- **Agent Mode**: Full agentic capabilities for building features, automating workflows, analyzing errors, and suggesting fixes in an interactive loop. Spec-driven development framework.
- **AI Model Support**: Uses Claude Haiku 4.5, and Auto mode which balances performance, efficiency, and output quality. [Source](https://kiro.dev/blog/introducing-kiro-cli/)
- **Key Features**:
  - Spec-driven development: plan, generate, and validate code through AI agents.
  - Property-Based Testing (PBT) and Checkpointing.
  - Custom agents for specialized tasks with pre-approved tool permissions.
  - Seamless transfer of IDE configurations (MCP servers, steering rules).
  - Native MCP support.
  - Multi-root workspace support.
  - Works with macOS and Linux.
  - Available in US East (N. Virginia) and Europe (Frankfurt) regions.
- **Pricing**: Free tier with 500 bonus credits. Kiro Pro at $20/month, Kiro Pro+ at $40/month, Kiro Power at $200/month with increasing AI generation credits. Startup Credits Program available until December 31, 2025. [Source](https://kiro.dev/pricing/)
- **Usage Limits**: Credit-based; varies by tier and model selection.
- **Why It Fits**: Great for teams using AWS services with structured, spec-driven AI coding workflows.

### Amazon Q Developer CLI
- **Description**: A CLI tool that enhances terminal workflows with AI-powered features like command autocompletion and natural language chat, integrated with AWS ecosystems. [Source](https://aws.amazon.com/q/developer/)
- **Agent Mode**: Supports multi-step tasks like debugging, code reviews, and structured development with session memory. Can upgrade to Kiro CLI for additional features.
- **AI Model Support**: Uses Claude Sonnet 4 (as of August 2025) for chat sessions. Through Amazon Bedrock, supports additional Claude models. [Source](https://aws.amazon.com/q/developer/)
- **Key Features**:
  - Session-aware responses for multi-step tasks.
  - CLI autocompletions and natural language-to-bash translation.
  - AI chat in terminal (locally and over SSH).
  - Strong AWS service integration for cloud workflows.
  - Autonomous agents for feature implementation, refactoring, dependency upgrades.
  - Cost estimation and optimization recommendations.
  - Available in IDE, CLI, AWS Console, and Slack.
- **Pricing**: Free tier with 1,000 agentic chat interactions/month (from August 2025), 4,000 LOC/month for transformations. Pro tier at $19/month per user with higher limits. [Source](https://aws.amazon.com/q/developer/pricing/)
- **Usage Limits**: Free tier: 1,000 agentic interactions/month, 1,000 generative SQL queries/month. Pro tier offers higher limits.
- **Why It Fits**: Ideal for AWS users needing cloud-integrated CLI tools with generous free tier.

### Qwen Code
- **Description**: An open-source AI agent from Alibaba optimized for Qwen3-Coder, adapted from Gemini CLI. Provides Claude Code-like experience with 2,000 free requests/day via OAuth. [Source](https://github.com/QwenLM/qwen-code)
- **Agent Mode**: Full agentic workflow with Skills, SubAgents, and Plan Mode.
- **AI Model Support**: Optimized for Qwen3-Coder-480B (480B parameters, 35B active with MoE). Supports 256K native context, 1M with extrapolation. State-of-the-art among open models for agentic coding. [Source](https://qwenlm.github.io/blog/qwen3-coder/)
- **Key Features**:
  - Deep code understanding & editing beyond normal context windows.
  - Workflow automation: PR handling, rebases, formatting.
  - Enhanced parser optimized for Qwen-Coder models.
  - Vision model support for multimodal analysis.
  - OpenAI-compatible API.
  - OAuth free tier: 2,000 requests/day.
  - Terminal-first, IDE-friendly (VS Code, Zed integration).
  - Fully open-source (both framework and model).
- **Pricing**: Free to use with OAuth (2,000 requests/day). OpenAI-compatible API available. [Source](https://github.com/QwenLM/qwen-code)
- **Usage Limits**: OAuth free tier: 2,000 requests/day.
- **Why It Fits**: Best free option with powerful open-source model and generous daily limits.

### Droid by Factory
- **Description**: Enterprise-grade AI coding agent from Factory that lives in your terminal and handles end-to-end development workflows. #1 on Terminal-Bench with 58.75% score. [Source](https://factory.ai/news/terminal-bench)
- **Agent Mode**: Full autonomous agent with multi-model orchestration. Extracts more capability from each model than labs' own agents.
- **AI Model Support**: Supports Anthropic (Opus, Sonnet) and OpenAI (GPT-5) models. Droid with Opus (58.8%) beats Claude Code with Opus (43.2%). [Source](https://factory.ai/)
- **Key Features**:
  - Multi-model support: switch between labs without switching tools.
  - Specialized Droids: Knowledge, Reliability, Product agents.
  - IDE integration: VS Code, JetBrains, Vim.
  - Web interface, IDE extension, and CLI.
  - CI/CD integration for migrations and maintenance.
  - Automated code review and self-healing builds.
  - Enterprise-grade with team features.
- **Pricing**: Free trial available. Enterprise pricing. [Source](https://factory.ai/)
- **Usage Limits**: Contact for enterprise limits.
- **Why It Fits**: Best for enterprises needing top benchmark performance and specialized agent types.

### Roo Code
- **Description**: An open-source AI coding agent for VS Code with 21.4K GitHub stars, providing a whole dev team of AI agents in your code editor. Fork/derivation of Cline. [Source](https://github.com/RooCodeInc/Roo-Code)
- **Agent Mode**: Multiple modes (Code, Architect, Ask, Debug, Custom) for different development tasks. Supports multi-file edits, test execution, and browser control.
- **AI Model Support**: Fully customizable, integrating any AI model (OpenAI, Anthropic, local LLMs). [Source](https://roocode.com)
- **Key Features**:
  - Multiple modes: Code, Architect, Ask, Debug, Custom.
  - Sticky models: preserves stateful preferences per mode.
  - Multi-file edits and refactoring.
  - Test execution and browser control.
  - Completely free and open-source.
  - Privacy: code never leaves your machine unless you connect to external API.
  - 901K installs on VS Code Marketplace.
- **Pricing**: Free and open-source. API costs depend on chosen model provider. [Source](https://roocode.com)
- **Usage Limits**: API usage-based.
- **Why It Fits**: Best for developers wanting multiple AI agent modes within VS Code.

### OpenHands (formerly OpenDevin)
- **Description**: An open-source (MIT license) platform for AI-powered software development with SDK, CLI, and GUI interfaces. Creates autonomous AI agents that emulate human software developers. [Source](https://openhands.dev/)
- **Agent Mode**: Full autonomous agent capable of modifying code, executing commands, browsing the web, and interacting with APIs. Solves over 50% of real GitHub issues on SWE-bench.
- **AI Model Support**: Model-agnostic platform supporting Claude, GPT, and any LLM. [Source](https://github.com/OpenHands/OpenHands)
- **Key Features**:
  - SDK: composable Python library for defining agents.
  - CLI: Claude Code/Codex-like experience.
  - Local GUI: React application with REST API.
  - Cloud deployment: scale to 1000s of agents.
  - Sandboxed environment for safe execution.
  - $10 free credit for new users.
  - Task management integrations: Jira, Linear.
- **Pricing**: Free and open-source (MIT license, except enterprise directory). $10 free credit. [Source](https://openhands.dev/)
- **Usage Limits**: API usage-based.
- **Why It Fits**: Best for developers wanting a complete platform for autonomous AI development with multiple interfaces.

## Comparison Table

| **CLI Tool** | **GitHub Stars** | **Open-Source** | **AI Model Support** | **Pricing** | **Free Tier** | **Key Strengths** | **Best For** |
|--------------|------------------|-----------------|----------------------|-------------|---------------|-------------------|--------------|
| **Claude Code** | 49K | No | Sonnet 4/4.5, Opus 4/4.5 | Pro $20/mo, Max $100-200/mo | No (Pro required) | Deep codebase understanding, multi-file edits, LSP support | Complex, multi-file projects |
| **Gemini CLI** | 88.5K | Yes (Apache 2.0) | Gemini 2.5 Pro, Gemini 3 Flash/Pro | Free, AI Pro $19.99/mo | Yes (1000 req/day) | Largest free tier, 1M token context, GitHub Actions | Large-context refactors |
| **OpenAI Codex CLI** | 54.7K | Yes (Apache 2.0) | GPT-5.2-Codex, GPT-5, o3, o4-mini | Free, API pay-as-you-go | Yes | Agent skills, GitHub/Linear integration | Deep GitHub integration |
| **Cline** | 50K+ | Yes | Any LLM (Sonnet 4, Opus 4, GPT-5, Grok 4) | Free, API pay-as-you-go | Yes | Plan/Act modes, fastest-growing, enterprise features | IDE-integrated autonomy |
| **Aider** | ~35K | Yes | Any LLM (Claude 4.1, GPT-5, Grok 4, local) | Free, API pay-as-you-go | Yes | Git integration, multi-language, voice input | Open-source Git workflows |
| **Goose** | 24.8K | Yes (Apache 2.0) | Any LLM with tool calling | Free, API pay-as-you-go | Yes | Local execution, AAIF member, ACP support | Privacy-focused, extensible |
| **OpenCode** | 41K | Yes | Any LLM (OpenAI, Anthropic, Ollama) | Free, API pay-as-you-go | Yes | Multi-session, LSP-enabled, shareable sessions | Claude Code alternative |
| **Warp** | N/A | No | Claude 3.5, GPT-4o, BYOK | Free, Build $20/mo | Yes (75-150 credits/mo) | AI-native terminal, BYOK, multi-platform | AI-native terminal experience |
| **Kiro CLI** | N/A | No | Claude Haiku 4.5, Auto mode | Free, Pro $20-200/mo | Yes (500 bonus) | Spec-driven development, AWS integration | AWS teams, structured workflows |
| **Amazon Q Developer CLI** | N/A | No | Claude Sonnet 4 via Bedrock | Free, Pro $19/mo | Yes (1000 interactions/mo) | AWS integration, cost optimization | AWS users, cloud workflows |
| **Qwen Code** | New | Yes (Apache 2.0) | Qwen3-Coder-480B (256K-1M context) | Free (2000 req/day OAuth) | Yes (2000 req/day) | Open-source model, vision support | Free usage, open models |
| **Droid** | N/A | No | Opus 4, Sonnet 4, GPT-5 | Free trial, Enterprise | Trial | #1 Terminal-Bench, multi-model | Enterprise, top performance |
| **Roo Code** | 21.4K | Yes | Any LLM (OpenAI, Anthropic, local) | Free, API pay-as-you-go | Yes | Multiple modes, VS Code integration | Multi-mode VS Code agent |
| **OpenHands** | N/A | Yes (MIT) | Any LLM (Claude, GPT) | Free ($10 credit), API | Yes ($10 credit) | SDK/CLI/GUI, 50%+ SWE-bench | Platform for AI dev |

## Analysis and Recommendations

Based on the evidence gathered in December 2025, all major tools support or can be configured to support the latest AI models. The market has seen significant consolidation around MCP (Model Context Protocol) and AGENTS.md standards.

**Recommendations**:
- **For complex projects**: Choose **Claude Code** for its precision and deep codebase comprehension, starting at $20/month.
- **For maximum free usage**: Choose **Gemini CLI** for its industry-leading 1,000 requests/day free tier and 1M token context.
- **For open-source with GPT-5**: Choose **OpenAI Codex CLI** for agent skills and GitHub integration.
- **For fastest-growing community**: Choose **Cline** with 50K+ stars and enterprise features.
- **For Git-integrated workflows**: Choose **Aider** for automatic commits and flexible model support.
- **For local execution and privacy**: Choose **Goose** for fully local operation with any LLM.
- **For Claude Code alternative**: Choose **OpenCode** for multi-session support and LSP features.
- **For AI-native terminal**: Choose **Warp** for a reimagined terminal experience with BYOK.
- **For AWS users**: Choose **Amazon Q Developer CLI** or **Kiro CLI** for cloud-integrated coding.
- **For free open-source model**: Choose **Qwen Code** for 2,000 requests/day with Qwen3-Coder.
- **For top benchmark performance**: Choose **Droid by Factory** (#1 on Terminal-Bench).
- **For multi-mode IDE agent**: Choose **Roo Code** for Code/Architect/Debug/Ask modes.
- **For complete AI dev platform**: Choose **OpenHands** for SDK, CLI, and GUI interfaces.

## References

For further details, explore the official documentation:
- [Claude Code](https://github.com/anthropics/claude-code)
- [Gemini CLI](https://github.com/google-gemini/gemini-cli)
- [OpenAI Codex CLI](https://github.com/openai/codex)
- [Cline](https://cline.bot/)
- [Aider](https://aider.chat/)
- [Goose](https://github.com/block/goose)
- [OpenCode](https://opencode.ai/)
- [Warp](https://www.warp.dev/)
- [Kiro CLI](https://kiro.dev/cli/)
- [Amazon Q Developer CLI](https://aws.amazon.com/q/developer/)
- [Qwen Code](https://github.com/QwenLM/qwen-code)
- [Factory Droid](https://factory.ai/)
- [Roo Code](https://roocode.com/)
- [OpenHands](https://openhands.dev/)

### Additional Sources
- [GPT-5.2-Codex Announcement](https://openai.com/index/introducing-gpt-5-2-codex/)
- [Claude Opus 4.5 Announcement](https://www.anthropic.com/news/claude-opus-4-5)
- [Gemini 3 Flash in Gemini CLI](https://developers.googleblog.com/gemini-3-flash-is-now-available-in-gemini-cli/)
- [Grok 4 Announcement](https://x.ai/news/grok-4/)
- [Qwen3-Coder Announcement](https://qwenlm.github.io/blog/qwen3-coder/)
- [Agentic AI Foundation (Linux Foundation)](https://www.linuxfoundation.org/press/linux-foundation-announces-the-formation-of-the-agentic-ai-foundation)
- [Droid Terminal-Bench Results](https://factory.ai/news/terminal-bench)
- [Cline Fastest Growing AI Project](https://cline.bot/blog/cline-the-fastest-growing-ai-open-source-project-on-github-in-2025-thanks-to-you)
- [Claude Pricing](https://www.anthropic.com/pricing)
- [Gemini CLI Pricing](https://geminicli.com/docs/quota-and-pricing/)
- [Amazon Q Developer Pricing](https://aws.amazon.com/q/developer/pricing/)
- [Kiro Pricing](https://kiro.dev/pricing/)
- [Warp Pricing](https://www.warp.dev/pricing)
